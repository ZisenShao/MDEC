---
layout: default
title: 4<sup>th</sup> Monocular Depth Estimation Challenge
description: MDEC @ CVPR 2025
---

:wave: Welcome to the **4<sup>th</sup> Monocular Depth Estimation Challenge Workshop** organized at :wave: 
[<img class="rounded-rect" src="assets/imgs/cvpr2025.png" width="400px" alt="cvpr2025"/>](https://cvpr2025.thecvf.com)
{: .text-center}

<div class="container">
<img class="img-syns" src="assets/imgs/syns/image_0026.png" alt="image_0026"/>
<img class="img-syns" src="assets/imgs/syns/image_0254.png" alt="image_0254"/>
<img class="img-syns" src="assets/imgs/syns/image_0698.png" alt="image_0698"/>

<img class="img-syns" src="assets/imgs/syns/depth_0026.png" alt="depth_0026"/>
<img class="img-syns" src="assets/imgs/syns/depth_0254.png" alt="depth_0254"/>
<img class="img-syns" src="assets/imgs/syns/depth_0698.png" alt="depth_0698"/>
</div>

Monocular depth estimation (**MDE**) is an important low-level vision task, with application in fields such as augmented reality, robotics and autonomous vehicles.
Recently, there has been an increased interest in **self-supervised systems** capable of predicting the **3D scene structure** without requiring ground-truth LiDAR training data.
Automotive data has accelerated the development of these systems, thanks to the vast quantities of data, the ubiquity of stereo camera rigs and the mostly-static world.
However, the evaluation process has also remained focused on only the automotive domain and has been largely unchanged since its inception, relying on simple metrics and sparse LiDAR data.

This workshop seeks to answer the following questions:
1. How well do networks generalize beyond their training distribution relative to humans?
2. What metrics provide the most insight into the model's performance? 
What is the relative weight of simple cues, e.g. height in the image, in networks and humans?
3. How do the predictions made by the models differ from how humans perceive depth? 
Are the failure modes the same?

The workshop will therefore consist of two parts: 
invited <a href="#speakers" target="_self">keynote talks</a> discussing current developments in MDE 
and a <a href="#challenge" target="_self">challenge</a> organized around a novel [**benchmarking procedure**](https://arxiv.org/abs/2208.01489) 
using the [**SYNS dataset**](https://www.nature.com/articles/srep35805).

## :page_facing_up: **Paper**
[![paper](assets/imgs/paper_cvpr2024.jpeg)](https://arxiv.org/abs/2404.16831)

## :tv: **Videos**

#### Introduction
{% include youtubePlayer.html id="7yP_iX-P2V0" %}

#### Keynote #1 -- Matteo Poggi
{% include youtubePlayer.html id="7yP_iX-P2V0?start=267" %}

#### Keynote #2 -- Vitor Guizilini
{% include youtubePlayer.html id="7yP_iX-P2V0?start=3336" %}

#### The MDEC Challenge
{% include youtubePlayer.html id="7yP_iX-P2V0?start=7553" %}

#### Challenge Participant #1 -- Mykola Lavreniuk
{% include youtubePlayer.html id="7yP_iX-P2V0?start=8960" %}

#### Challenge Participant #1 -- Guangyuan Zhou 
{% include youtubePlayer.html id="7yP_iX-P2V0?start=9782" %}

#### Challenge Participant #1 -- Aradhye Agarwal 
{% include youtubePlayer.html id="7yP_iX-P2V0?start=10480" %}

#### Challenge Participant #1 -- James H. Elder
{% include youtubePlayer.html id="7yP_iX-P2V0?start=11415" %}

#### Keynote #3 -- Eric Brachmann
{% include youtubePlayer.html id="7yP_iX-P2V0?start=12177" %}


## :newspaper: **News** {#news}
- **05 Aug 2024 ---** :tv: Added workshop videos
- **28 May 2024 ---** :page_facing_up: Added publication
- **28 May 2024 ---** :trophy: Announced challenge winners and workshop schedule
- **05 Feb 2024 ---** :microphone: **Vitor Guizilini** confirmed as keynote speaker.
- **25 Jan 2024 ---** :microphone: **Eric Brachmann** confirmed as keynote speaker.
- **25 Jan 2024 ---** :microphone: **Fatma Güney** confirmed as keynote speaker.
- **25 Jan 2024 ---** :tada: Website is live!

---

## :hourglass_flowing_sand: **Important Dates** {#dates}
- **01 Feb 2024 (00:00 UTC) ---** Challenge Development Phase **Opens** (Val)
- **01 Mar 2024 (00:00 UTC) ---** Challenge Final Phase **Opens** (Test)
- **25 Mar 2024 (23:59 UTC) ---** Challenge Submission **Closes**
- **01 Apr 2024 ---** Method Description Submission
- **12 Apr 2024 ---** Invited Talk Notification
- **17-21 Jun 2024 ---** MDEC Workshop @ CVPR 2024

---

## :calendar: **Schedule** {#schedule}

The workshop will take place on **18 Jun 2024** from **08:30AM -- 12:00PM PDT**.

> **NOTE**: Times are shown in **Pacific Daylight Time**. 
> Please take this into account if joining the workshop virtually.

| Time (PDT)    | Event                                                        |
|---------------|--------------------------------------------------------------|
| 13:30 - 13:45 | Introduction                                                 |
| 13:45 - 14:30 | **Matteo Poggi** *                                           |
| 14:30 - 15:15 | **Vitor Guizilini**                                          |
| 15:15 - 15:30 | _Break_                                                      |
| 15:30 - 15:50 | **Matteo Poggi** -- The Monocular Depth Estimation Challenge |
| 15:50 - 16:00 | **Mykola Lavreniuk** -- EVP++ _(Challenge Participant)_      |
| 16:00 - 16:10 | **Guangyuan Zhou** -- PICO-MR _(Challenge Winner!)_          |
| 16:10 - 16:20 | **Aradhye Agarwal** -- visioniitd _(Challenge Participant)_  |
| 16:20 - 16:30 | **James H. Elder** -- Elder Lab _(Challenge Participant)_    |
| 16:30 - 17:15 | **Eric Brachmann**                                           |
| 17:15 - 17:30 | Closing Notes                                                |

\* Fatma was unable to attend the workshop

--- 

## :microphone: **Keynote Speakers** {#speakers}
<div class="container">
<figure>
    <a href="https://mysite.ku.edu.tr/fguney/">
    <img class="img-author" src="assets/imgs/authors/fatma_guney.jpeg" alt="Fatma Güney"/></a>
    <b><br><a href="https://mysite.ku.edu.tr/fguney/">Fatma Güney</a>
    <br>Assistant Professor<br>Koç University</b>
</figure>

<figure>
    <a href="https://scholar.google.com.br/citations?user=UH9tP6QAAAAJ&hl=en">
    <img class="img-author" src="assets/imgs/authors/vitor_guizilini.jpeg" alt="Vitor Guizilini"/></a>
    <b><br><a href="https://scholar.google.com.br/citations?user=UH9tP6QAAAAJ&hl=en">Vitor Guizilini</a>
    <br>Staff Research Scientist<br>Toyota Research Institute</b>
</figure>

<figure>
    <a href="https://ebrach.github.io/">
    <img class="img-author" src="assets/imgs/authors/eric_brachmann.jpeg" alt="Eric Brachmann"/></a>
    <b><br><a href="https://ebrach.github.io/">Eric Brachmann</a>
    <br>Staff Scientist<br>Niantic</b>
</figure>
</div>

[**Fatma Güney**](https://mysite.ku.edu.tr/fguney/)
is an Assistant Professor at Koc University in Istanbul. 
She received her PhD from the Max Planck Institute in Germany. 
Her research focuses on computer vision problems related to autonomous driving. 
In the last few years, she published papers on monocular depth estimation, unsupervised object segmentation, and future prediction in different representations. 
She is a recipient of the ERC Starting Grant as well as prestigious fellowships including the Newton Fund Advanced Fellowship and the Marie Curie Individual Fellowship. 
She regularly serves as a reviewer with multiple outstanding reviewer awards and more recently as an Area Chair in top-tier Computer Vision conferences.

[**Vitor Guizilini**](https://scholar.google.com.br/citations?user=UH9tP6QAAAAJ&hl=en) 
is currently a staff research scientist at the Toyota Research Institute (TRI) in Los Altos, California. 
His interests include self-supervised learning, monocular depth estimation, unsupervised domain adaptation, implicit visual representations, camera calibration, and vision-based machine learning in general. 
He has close to 100 publications in related areas, in addition to a large number of patents in different stages of filing and application to various products. 
He is the creator and currently maintains the `packnet-sfm` and `vidar` repositories, two of the most widely used depth estimation codebases in the scientific community. 
He co-organized the first three editions of the "Frontiers of Monocular 3D Perception" workshop and has also given several talks in top tier conferences.

[**Eric Brachmann**](https://ebrach.github.io/) 
is a staff scientist at Niantic, working on the Lightship Visual Positioning System (VPS). 
He works at the intersection of machine learning and computer vision, 3D vision in particular. 
His research revolves around topics such as visual relocalisation, pose estimation, end-to-end learning, robust optimization and feature matching.
He publishes his research in the top conferences in computer vision where he is also an active reviewer with several outstanding reviewer mentions. 
He has co-organized several tutorials and workshops on visual relocalisation and object pose estimation.

---

## :trophy: **Challenge Winners** {#winners}

Congratulations to the challenge winners -- **PICO-MR**!

|                |      | F                                                                | F<br/>(Edges)                                                    | MEA                                                             | RMSE                                                            | Rel                                                              | Acc<br/>(Edges)                                                 | Comp<br/>(Edges)                                                | 
|----------------|------|------------------------------------------------------------------|------------------------------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------|------------------------------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------|
| **PICO-MR**    | †D*  | <span style="color:green"><strong>23.72</strong></span>          | <span style="color:blue;text-decoration: underline">11.01</span> | <span style="color:blue;text-decoration: underline">3.78</span> | <span style="color:blue;text-decoration: underline">6.61</span> | 21.24                                                            | 3.90                                                            | 4.45                                                            |
| **Anonymous**  | ?    | <span style="color:blue;text-decoration: underline">23.25</span> | 10.78                                                            | 3.87                                                            | 6.70                                                            | 21.70                                                            | 3.59                                                            | 9.86                                                            |
| **RGA-Robot**  | †S   | 22.79                                                            | <span style="color:green"><strong>11.52</strong></span>          | 5.21                                                            | 9.23                                                            | 28.86                                                            | 4.15                                                            | <span style="color:blue;text-decoration: underline">0.90</span> |
| **EVP++**      | †D   | 20.87                                                            | 10.92                                                            | <span style="color:green"><strong>3.71</strong></span>          | <span style="color:green"><strong>6.53</strong></span>          | <span style="color:green"><strong>19.02</strong></span>          | 2.88                                                            | 6.77                                                            |
| **Anonymous**  | ?    | 20.77                                                            | 9.96                                                             | 4.33                                                            | 7.83                                                            | 27.80                                                            | 3.45                                                            | 13.25                                                           |
| **3DCreators** | †D   | 20.42                                                            | 10.19                                                            | 4.41                                                            | 7.89                                                            | 23.94                                                            | 3.61                                                            | 5.80                                                            |
| **visioniitd** | D    | 19.07                                                            | 9.92                                                             | 4.53                                                            | 7.96                                                            | 23.27                                                            | 3.26                                                            | 8.00                                                            |
| **Anonymous**  | ?    | 18.60                                                            | 9.43                                                             | 3.92                                                            | 7.16                                                            | <span style="color:blue;text-decoration: underline">20.12</span> | 2.89                                                            | 15.65                                                           |
| **HIT-AIIA**   | †D   | 17.83                                                            | 9.14                                                             | 4.11                                                            | 7.73                                                            | 21.23                                                            | 2.95                                                            | 17.81                                                           |
| **FRDC-SH**    | †D   | 17.81                                                            | 9.75                                                             | 5.04                                                            | 8.92                                                            | 24.01                                                            | 3.16                                                            | 14.16                                                           |
| **Anonymous**  | ?    | 17.57                                                            | 9.13                                                             | 4.28                                                            | 8.36                                                            | 23.35                                                            | 3.18                                                            | 20.66                                                           |
| **Anonymous**  | ?    | 16.91                                                            | 9.07                                                             | 4.14                                                            | 7.35                                                            | 22.05                                                            | 3.24                                                            | 18.52                                                           |
| **Anonymous**  | ?    | 16.71                                                            | 9.25                                                             | 5.48                                                            | 11.05                                                           | 34.20                                                            | <span style="color:green"><strong>2.57</strong></span>          | 18.04                                                           |
| **Anonymous**  | ?    | 16.45                                                            | 8.89                                                             | 5.29                                                            | 10.53                                                           | 33.67                                                            | <span style="color:blue;text-decoration: underline">2.60</span> | 18.73                                                           |
| **hyc123**     | D    | 15.92                                                            | 9.17                                                             | 8.25                                                            | 13.88                                                           | 43.88                                                            | 4.11                                                            | <span style="color:green"><strong>0.74</strong></span>          |
| **ReadingLS**  | †MD* | 14.81                                                            | 8.14                                                             | 5.01                                                            | 8.94                                                            | 29.39                                                            | 3.28                                                            | 30.28                                                           |
| **Baseline**   | S    | 13.72                                                            | 7.76                                                             | 5.56                                                            | 9.72                                                            | 32.04                                                            | 3.97                                                            | 21.63                                                           |
| **Anonymous**  | ?    | 13.71                                                            | 7.55                                                             | 5.49                                                            | 9.44                                                            | 30.74                                                            | 3.61                                                            | 18.36                                                           |
| **Anonymous**  | ?    | 11.90                                                            | 8.08                                                             | 6.33                                                            | 10.89                                                           | 30.46                                                            | 2.99                                                            | 33.63                                                           |
| **Elder Lab**  | D    | 11.04                                                            | 7.09                                                             | 8.76                                                            | 15.86                                                           | 63.32                                                            | 3.22                                                            | 40.61                                                           |

_**M**: Monocular -- **S**: Stereo -- **D**: Ground-truth Depth -- **D***: Proxy Depth -- **†**: Pre-trained Depth Anything_


### **Teams**
 * **PICO-MR**: GuangYuan Zhou, ZhengXin Li, Qiang Rao, YiPing Bao, Xiao Liu  
 * **RGA-Robot**: Dohyeong Kim, Jinseong Kim, Myunghyun Kim  
 * **EVP++**: Mykola Laverniuk
 * **3DCreators**: Rui Li, Qing Mao, Jiang Wu, Yu Zhu, Jinqiu Sun, Yanning Zhang
 * **visioniitd**: Suraj Patni, Aradhye Agarwal, Chetan Arora 
 * **HIT-AIIA**: Pihai Sun, Kui Jiang, Gang Wu, Jian Liu, Xianming Liu, Junjun Jiang   
 * **FRDC-SH**: Xidan Zhang, Jianing Wei, Fangjun Wang, Zhiming Tan    
 * **hyc123**: Jiabao Wang
 * **ReadingLS**: Albert Luginov, Muhammad Shahzad
 * **Elder Lab**: Seyed Hosseini, Aleksander Trajcevski, James H. Elder

---

## :checkered_flag: **Challenge** {#challenge}
**Teams submitting to the challenge will also be required to submit a description of their method.
As part of the CVPR Workshop Proceedings, we will publish a paper summarizing the results of the challenge, including a description of each method.
All challenge participants surpassing the performance of the Garg baseline (by jspenmar) will be added as authors in this paper.
Top performers will additionally be invited to present their method <a href="#schedule" target="_self">at the workshop</a>.
This presentation can be either in-person or virtually.**

> **IMPORTANT:** We have decided to expand this edition of the challenge beyond self-supervised models.
> This means we are accepting **any** monocular method, e.g. supervised, weakly-supervised, multi-task...
> The only restriction is that the model cannot be trained on any portion of the SYNS(-Patches) dataset and must
> make the final depth map prediction using only a single image.

**[[GitHub](https://github.com/jspenmar/monodepth_benchmark)] --- [[Challenge](https://codalab.lisn.upsaclay.fr/competitions/17161)]**
{: .text-center}

The challenge focuses on evaluating novel MDE techniques on the **SYNS-Patches** dataset proposed in [**this benchmark**](https://arxiv.org/abs/2208.01489).
This dataset provides a challenging variety of urban and natural scenes, including forests, agricultural settings, residential streets, industrial estates, lecture theatres, offices and more.
Furthermore, the high-quality dense ground-truth LiDAR allows for the computation of more informative evaluation metrics, such as those focused on [**depth discontinuities**](https://arxiv.org/abs/1805.01328v1).


<div class="container">
<img class="img-syns" src="assets/imgs/syns/image_0551.png" alt="image_0551"/>
<img class="img-syns" src="assets/imgs/syns/image_0893.png" alt="image_0893"/>
<img class="img-syns" src="assets/imgs/syns/image_1114.png" alt="image_1114"/>

<img class="img-syns" src="assets/imgs/syns/depth_0551.png" alt="depth_0551"/>
<img class="img-syns" src="assets/imgs/syns/depth_0893.png" alt="depth_0893"/>
<img class="img-syns" src="assets/imgs/syns/depth_1114.png" alt="depth_1114"/>
</div>

The challenge is hosted on [**CodaLab**](https://codalab.lisn.upsaclay.fr/competitions/17161). 
We have provided a [**GitHub repository**](https://github.com/jspenmar/monodepth_benchmark) containing training and evaluation code for multiple recent SotA approaches to MDE.
These will serve as a competitive baseline for the challenge and as a starting point for participants.
The challenge leaderboards use the withheld validation and test sets for **SYNS-Patches**.
We additionally encourage evaluation on the public [**Kitti Eigen-Benchmark**](http://www.cvlibs.net/datasets/kitti/eval_depth.php?benchmark=depth_prediction) dataset.

Submissions will be evaluated on a variety of metrics:
1. [**Pointcloud reconstruction**](https://arxiv.org/abs/2203.08122): F-Score
2. [**Image-based depth**](https://arxiv.org/abs/1708.06500): MAE, RMSE, AbsRel
3. [**Depth discontinuities**](https://arxiv.org/abs/1805.01328v1): F-Score, Accuracy, Completeness

Challenge winners will be determined based on the **pointcloud-based F-Score** performance.

---

## :construction_worker: **Organizers** {#organizers}
<div class="container">
<figure>
    <a href="">
    <img class="img-author" src="assets/imgs/authors/ripudaman_arora.jpeg" alt="Ripudaman Singh Arora"/></a>
    <b><br><a href="">Ripudaman Singh Arora</a>
    <br>Principal ML Researcher<br>Blue River Technology</b>
</figure>

<figure>
    <a href="https://www.surrey.ac.uk/people/jaime-spencer-martin">
    <img class="img-author" src="assets/imgs/authors/jaime_spencer.jpg" alt="Jaime Spencer"/></a>
    <b><br><a href="https://www.surrey.ac.uk/people/jaime-spencer-martin">Jaime Spencer</a>
    <br>Data Engineer<br>Oxa</b>
</figure>

<figure>
    <a href="https://fabiotosi92.github.io/">
    <img class="img-author" src="assets/imgs/authors/fabio_tosi.jpeg" alt="Fabio Tosi"/></a>
    <b><br><a href="https://fabiotosi92.github.io/">Fabio Tosi</a>
    <br>Junior Assistant Professor<br>University of Bologna</b>
</figure>

<figure>
    <a href="https://mattpoggi.github.io/">
    <img class="img-author" src="assets/imgs/authors/matteo_poggi.jpeg" alt="Matteo Poggi"/></a>
    <b><br><a href="https://mattpoggi.github.io/">Matteo Poggi</a>
    <br>Tenure-Track Assistant Professor<br>University of Bologna</b>
</figure>

<figure>
    <a href="https://www.oii.ox.ac.uk/people/profiles/chris-russell/">
    <img class="img-author" src="assets/imgs/authors/chris_russell.jpeg" alt="Chris Russell"/></a>
    <b><br><a href="https://www.oii.ox.ac.uk/people/profiles/chris-russell/">Chris Russell</a>
    <br>Associate Professor<br>Oxford Internet Institute</b>
</figure>

<figure>
    <a href="http://personalpages.surrey.ac.uk/s.hadfield/">
    <img class="img-author" src="assets/imgs/authors/simon_hadfield.png" alt="Simon Hadfield"/></a>
    <b><br><a href="http://personalpages.surrey.ac.uk/s.hadfield/">Simon Hadfield</a>
    <br>Associate Professor<br>University of Surrey</b>
</figure>

<figure>
    <a href="https://personalpages.surrey.ac.uk/r.bowden/">
    <img class="img-author" src="assets/imgs/authors/richard_bowden.png" alt="Richard Bowden"/></a>
    <b><br><a href="https://personalpages.surrey.ac.uk/r.bowden/">Richard Bowden</a>
    <br>Professor<br>University of Surrey</b>
</figure>
</div>
