---
layout: default
title: 4<sup>th</sup> Monocular Depth Estimation Challenge
description: MDEC @ CVPR 2025
---

:wave: Welcome to the **4<sup>th</sup> Monocular Depth Estimation Challenge Workshop** organized at :wave: 
[<img class="rounded-rect" src="assets/imgs/cvpr2025.jpg" width="400px" alt="cvpr2025"/>](https://cvpr2025.thecvf.com)
{: .text-center}

<div class="container">
<img class="img-syns" src="assets/imgs/syns/image_0026.png" alt="image_0026"/>
<img class="img-syns" src="assets/imgs/syns/image_0254.png" alt="image_0254"/>
<img class="img-syns" src="assets/imgs/syns/image_0698.png" alt="image_0698"/>

<img class="img-syns" src="assets/imgs/syns/depth_0026.png" alt="depth_0026"/>
<img class="img-syns" src="assets/imgs/syns/depth_0254.png" alt="depth_0254"/>
<img class="img-syns" src="assets/imgs/syns/depth_0698.png" alt="depth_0698"/>
</div>

Monocular depth estimation (**MDE**) is an important low-level vision task with applications in fields such as augmented reality, robotics, and autonomous vehicles.
In 2024, the field was dominated by generative approaches, with [DepthAnything](https://depth-anything.github.io/) representing the transformer-based solution and [Marigold](https://marigoldmonodepth.github.io/) being a denoising diffusion model based on the popular Text-to-Image LDM Stable Diffusion.
Even before that, there has been an increased interest in self-supervised systems capable of predicting the 3D scene structure without requiring ground-truth LiDAR training data.
The automotive industry accelerated the development of these systems thanks to the vast quantities of data and the ubiquity of stereo camera rigs.
However, the evaluation process has remained focused on in-domain evaluation, relying on simple metrics and sparse LiDAR data.

This workshop seeks to answer the following questions:
1. How well do networks generalize beyond their training distribution relative to humans?
2. What metrics provide the most insight into the model's performance? 
3. How do the predictions made by the models differ from how humans perceive depth? 

The workshop will consist of two parts: 
invited <a href="#speakers" target="_self">keynote talks</a> discussing current developments in MDE 
and a <a href="#challenge" target="_self">challenge</a> organized around a benchmarking procedure 
using the [SYNS dataset](https://www.nature.com/articles/srep35805).

## :newspaper: **News** {#news}
- **01 Feb 2025 ---** 🏆 Submissions to the challenge are now open!
- **30 Jan 2025 ---** :microphone: **Konrad Schindler** confirmed as keynote speaker.
- **07 Jan 2025 ---** :microphone: **Yiyi Liao** confirmed as keynote speaker.
- **06 Jan 2025 ---** :microphone: **Peter Wonka** confirmed as keynote speaker.
- **05 Jan 2025 ---** :tada: Website is live!
                                               
---

## :microphone: **Keynote Speakers** {#speakers}
<div class="container">
<figure>
    <a href="https://peterwonka.net/">
    <img class="img-author" src="https://peterwonka.net/Pics/Peter2020.jpg" alt="Peter Wonka"/></a>
    <b><br><a href="https://peterwonka.net/">Peter Wonka</a>
    <br>Full Professor<br>KAUST</b>
</figure>

<figure>
    <a href="https://yiyiliao.github.io/">
    <img class="img-author" src="https://yiyiliao.github.io/assets/img/prof_pic.jpg" alt="Yiyi Liao"/></a>
    <b><br><a href="https://yiyiliao.github.io/">Yiyi Liao</a>
    <br>Assistant Professor<br>Zhejiang University</b>
</figure>

<figure>
    <a href="https://prs.igp.ethz.ch/group/people/person-detail.schindler.html">
    <img class="img-author" src="https://prs.igp.ethz.ch/group/people/person-detail.person_image.jpeg?persid=MTQzOTg2" alt="Konrad Schindler"/></a>
    <b><br><a href="https://prs.igp.ethz.ch/group/people/person-detail.schindler.html">Konrad Schindler</a>
    <br>Full Professor<br>ETH Zurich</b>
</figure>
</div>

[**Peter Wonka**](https://peterwonka.net/)
is a full professor of computer science at King Abdullah University of Science and Technology (KAUST).
Peter Wonka received his doctorate in computer science from the Technical University of Vienna. Additionally, he received a Master of Science in Urban Planning from the same institution. After his PhD, Dr. Wonka worked as a postdoctoral researcher at the Georgia Institute of Technology and as faculty at Arizona State University. His research publications tackle various computer vision, computer graphics, and machine learning topics. The current research focuses on deep learning, generative models, and 3D shape analysis and reconstruction.

[**Yiyi Liao**](https://yiyiliao.github.io/)
is an assistant professor at Zhejiang University. Prior to that, she received her Ph.D. degree from Zhejiang University and subsequently worked as a Postdoc at MPI for Intelligent Systems. Her research interest lies in 3D computer vision and immersive media, including reconstruction, generation, and compression. She received the Best Robot Vision Paper award at ICRA 2024. She serves as a program chair for 3DV 2025 and an area chair for CVPR and NeurIPS. 

[**Konrad Schindler**](https://prs.igp.ethz.ch/group/people/person-detail.schindler.html)
received the Diplomingenieur (M.Tech.) degree in photogrammetry from the Vienna University of Technology, Vienna, Austria, in 1999 and the Ph.D. degree from the Graz University of Technology, Graz, Austria, in 2003. He was a Photogrammetric Engineer in the private industry and held researcher positions at the Computer Graphics and Vision Department, Graz University of Technology, the Digital Perception Laboratory, Monash University, Melbourne, VIC, Australia, and the Computer Vision Laboratory, ETH Zürich, Zürich, Switzerland. He was an Assistant Professor of Image Understanding with TU Darmstadt, Darmstadt, Germany, in 2009. Since 2010, he has been a Tenured Professor of Photogrammetry and Remote Sensing with ETH Zürich. His research interests include computer vision, photogrammetry, and remote sensing, with a focus on image understanding and information extraction reconstruction. Dr. Schindler has been serving as an Associate Editor of the Journal of Photogrammetry and Remote Sensing of the International Society for Photogrammetry and Remote Sensing (ISPRS) since 2011, and previously served as an Associate Editor of the Image and Vision Computing Journal from 2011 to 2016. He was the TC President of the ISPRS from 2012 to 2016.

---

## :trophy: **Challenge Winners** {#winners}

Congratulations to the challenge winners -- **HRI**!

|                |      | F&nbsp;(↑)                                                                | F&nbsp;(↑)<br/>(Edges)                                                    | MAE&nbsp;(↓)                                                             | RMSE&nbsp;(↓)                                                            | AbsRel&nbsp;(↓)                                                              | Acc&nbsp;(↑)<br/>(Edges)                                                 | Comp&nbsp;(↓)<br/>(Edges)                                                | δ<1.25&nbsp;(↑)                                                | δ<1.25^2&nbsp;(↑)                                                | δ<1.25^3&nbsp;(↑)                                                | 
|----------------|------|------------------------------------------------------------------|------------------------------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------|------------------------------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------|
| **HRI** | A |   <span style="background-color: #BDE6CD; color: black;"><strong>23.05</strong></span>  |  <span style="background-color: #E2EEBC; color: black;"><strong>9.37</strong></span>  |  <span style="background-color: #BDE6CD; color: black;"><strong>3.19</strong></span>  |  <span style="background-color: #BDE6CD; color: black;"><strong>5.64</strong></span>  |  <span style="background-color: #E2EEBC; color: black;"><strong>21.17</strong></span>  | 3.30 |  <span style="background-color: #E2EEBC; color: black;"><strong>6.77</strong></span> |  <span style="background-color: #E2EEBC; color: black;"><strong>77.54</strong></span>  |  <span style="background-color: #E2EEBC; color: black;"><strong>91.79</strong></span>  |  <span style="background-color: #FFF8C5; color: black;"><strong>95.78</strong></span>   |
| **Anonymous** | | <span style="background-color: #E2EEBC; color: black;"><strong>22.95</strong></span>  | 9.21  | 3.44  | 6.48  | 24.65 | 3.27 |  <span style="background-color: #BDE6CD; color: black;"><strong>6.59</strong></span>  |  <span style="background-color: #FFF8C5; color: black;"><strong>76.17</strong></span>  | 90.33  | 94.73    | 
| <span style="background-color: rgb(255, 200, 200); color: black;"><strong>PICO-MR</strong></span> | <span style="background-color: rgb(255, 200, 200); color: black;"> </span> | <span style="background-color: rgb(255, 200, 200); color: black;">22.58</span>  | <span style="background-color: rgb(255, 200, 200); color: black;">8.26</span>  | <span style="background-color: rgb(255, 200, 200); color: black;">3.41</span>  | <span style="background-color: rgb(255, 200, 200); color: black;">5.89</span>  | <span style="background-color: rgb(255, 200, 200); color: black;">22.02</span>  | <span style="background-color: rgb(255, 200, 200); color: black;">4.02</span>  | <span style="background-color: rgb(255, 200, 200); color: black;">11.28</span>  | <span style="background-color: rgb(255, 200, 200); color: black;">76.18</span>  | <span style="background-color: rgb(255, 200, 200); color: black;">90.95</span>  | <span style="background-color: rgb(255, 200, 200); color: black;">95.44</span> |
| **Lavreniuk** | A | <span style="background-color: #FFF8C5; color: black;"><strong>20.81</strong></span>  | 9.12  |  <span style="background-color: #FFF8C5; color: black;"><strong>3.40</strong></span>  |  <span style="background-color: #FFF8C5; color: black;"><strong>5.77</strong></span>  |  <span style="background-color: #BDE6CD; color: black;"><strong>20.48</strong></span>  | 3.20  |  <span style="background-color: #FFF8C5; color: black;"><strong>7.27</strong></span>  | 75.33  |  <span style="background-color: #FFF8C5; color: black;"><strong>91.33</strong></span>  |  <span style="background-color: #BDE6CD; color: black;"><strong>95.97</strong></span>    |
| **Mach-Calib** | A |20.69  | 8.75  | 3.63  | 6.78  | 23.36  | 3.22  | 13.96  | 74.31  | 90.44  | 95.12     |
| **Anonymous** | | 20.50  | 8.63  | 3.68  | 7.07  | 23.96  | 3.17  | 13.66  | 74.00  | 90.32  | 95.01    |
| **EasyMono** | A | 20.24  | 7.30  | 3.43  | 5.91  | 22.47  | 3.91  | 20.98  | 74.73  | 90.55  | 95.24    |
| **Insta360-Percep** | A | 19.41  | 8.98  |  <span style="background-color: #E2EEBC; color: black;"><strong>3.25</strong></span> |  <span style="background-color: #E2EEBC; color: black;"><strong>5.73</strong></span>  |  <span style="background-color: #FFF8C5; color: black;"><strong>21.29</strong></span>  |  <span style="background-color: #BDE6CD; color: black;"><strong>2.75</strong></span>  | 15.54  |  <span style="background-color: #BDE6CD; color: black;"><strong>77.91</strong></span>  |  <span style="background-color: #BDE6CD; color: black;"><strong>92.03</strong></span>  |  <span style="background-color: #E2EEBC; color: black;"><strong>95.91</strong></span>     |
| **Anonymous** | | 18.85  | 8.27  | 4.06  | 7.06  | 26.35  | 3.11  | 13.75  | 67.57  | 87.98  | 94.18     |
| **HIT-AIIA** | A |18.53  |  <span style="background-color: #BDE6CD; color: black;"><strong>9.74</strong></span>  | 3.83  | 6.29  | 23.96  |  <span style="background-color: #FFF8C5; color: black;"><strong>3.06</strong></span> | 9.90  | 69.12  | 88.49  | 94.31     |
| **Anonymous** | | 18.16  | 6.32  | 3.57  | 6.13  | 24.07  | 4.51  | 15.75  | 71.62  | 89.12  | 94.74     |
| **Anonymous** | | 17.46  |  <span style="background-color: #FFF8C5; color: black;"><strong>9.35</strong></span> | 4.43  | 7.30  | 29.19  | 3.27  | 17.69 | 65.64  | 86.45  | 93.09     |
| **Anonymous** | | 17.46  |  <span style="background-color: #FFF8C5; color: black;"><strong>9.35</strong></span> | 4.43  | 7.30  | 29.19  | 3.27  | 17.69  | 65.64  | 86.45  | 93.09    |
| **Anonymous** | | 17.45  |  <span style="background-color: #FFF8C5; color: black;"><strong>9.35</strong></span>  | 4.43  | 7.30  | 29.20  | 3.27  | 17.69  | 65.64  | 86.46  | 93.10     |
| **Robot02-vRobotit** | A |17.25  | 8.27  | 3.90  | 6.54  | 23.64  | 3.07  | 22.85  | 71.07  | 89.38  | 94.80     |
| **Anonymous** | | 17.01  | 9.20  | 4.44  | 7.34  | 29.42  | 3.25  | 18.55  | 65.72  | 86.67  | 93.35     |
| **Anonymous** | | 17.01  | 9.20  | 4.44  | 7.34  | 29.42  | 3.25 | 18.55  | 65.72  | 86.67  | 93.35     |
| <span style="background-color: rgb(235, 235, 255); color: black;">Marigold</span> | <span style="background-color: rgb(235, 235, 255); color: black;">A</span> | <span style="background-color: rgb(235, 235, 255); color: black;">17.01</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">9.19</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">4.44</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">7.34</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">29.42</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">3.25</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">18.56</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">65.72</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">86.67</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">93.35</span> |
| **Anonymous** | | 16.79  | 9.10  | 4.51  | 7.44  | 30.10  | 3.32  | 17.65  | 65.24  | 86.22  | 93.05     |
| **Anonymous** | | 16.67  | 7.49  | 4.01  | 6.92  | 26.34  | 3.07  | 26.32  | 68.17  | 88.47  | 94.42     |
| **Anonymous** | | 16.47  | 8.99  | 4.74  | 7.71  | 30.93  | 3.26  | 18.75  | 62.26  | 84.27  | 91.90    |
| **ViGIR LAB** | | 16.25  | 8.54  | 5.37  | 9.00 | 43.72  | 3.29  | 14.15  | 61.99  | 82.89  | 90.46     |
| **Anonymous** | A |15.31  | 8.46  | 4.62  | 7.46  | 30.63  | 3.42  | 15.59  | 62.41  | 84.89  | 92.43     |
| **Anonymous** | | 15.03  | 7.64  | 5.48  | 9.29  | 38.59  | 3.70  | 20.33  | 58.82  | 81.79  | 90.85    |
| <span style="background-color: rgb(235, 235, 255); color: black;">Depth Anything v2</span>  | <span style="background-color: rgb(235, 235, 255); color: black;"> </span> | <span style="background-color: rgb(235, 235, 255); color: black;">14.34</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">6.72</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">4.84</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">9.13</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">33.57</span>  | <span style="background-color: #E2EEBC; color: black;">2.99</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">35.54</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">66.34</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">86.02</span>  | <span style="background-color: rgb(235, 235, 255); color: black;">92.44</span> |
| **HCMUS-DepthFusion** | A | 14.20  | 7.81  | 4.90  | 7.96  | 33.55  | 3.32  | 17.66  | 61.09  | 83.90  | 92.21     |
| **ReadingLS** | | 13.52  | 6.60  | 4.56  | 7.90 | 30.15  | 3.14  | 35.94  | 65.34  | 86.55  | 93.46    |
_Legend: <span style="background-color: rgb(235, 235, 255); color: black;">**Baselines**</span>; <span style="background-color: rgb(235, 235, 255); color: black;">**Baselines**</span>; A -- affine-invariant predictions_

---

## :checkered_flag: **Challenge** {#challenge}

The challenge focuses on evaluating novel MDE techniques on the [SYNS-Patches dataset](https://arxiv.org/abs/2208.01489).
This dataset provides a challenging variety of urban and natural scenes, including forests, agricultural settings, residential streets, industrial estates, lecture theatres, offices, and more.
Furthermore, the high-quality, dense ground-truth LiDAR allows for the computation of more informative evaluation metrics, such as those focused on [depth discontinuities](https://arxiv.org/abs/1805.01328v1).

**[[GitHub Starter Pack](https://github.com/toshas/mdec_benchmark)] --- [[CodaLab Challenge](https://codalab.lisn.upsaclay.fr/competitions/21305)]**
{: .text-center}

<div class="container">
<img class="img-syns" src="assets/imgs/syns/image_0551.png" alt="image_0551"/>
<img class="img-syns" src="assets/imgs/syns/image_0893.png" alt="image_0893"/>
<img class="img-syns" src="assets/imgs/syns/image_1114.png" alt="image_1114"/>

<img class="img-syns" src="assets/imgs/syns/depth_0551.png" alt="depth_0551"/>
<img class="img-syns" src="assets/imgs/syns/depth_0893.png" alt="depth_0893"/>
<img class="img-syns" src="assets/imgs/syns/depth_1114.png" alt="depth_1114"/>
</div>

### ⚡ What’s new in MDEC 2025? {#news}

- 📐 New prediction types: The challenge became more accessible thanks to the added support of `affine-invariant` predictions. `metric` and `scale-invariant` predictions are also automatically supported. `disparity` predictions, which were supported in previous challenges, are also accepted.
- 🤗 Pre-trained Model Support: We provide ready-to-use scripts for off-the-shelf methods: Depth Anything V2 (`disparity`) and Marigold (`affine-invariant`). These will serve as a competitive baseline for the challenge and a starting point for participants.
- 📊 Updated Evaluation Pipeline: The CodaLab grader code has been updated to accommodate the newly supported prediction types.

### 🚀 How to participate? {#participate}

1. Check out the new starter pack [GitHub](https://github.com/toshas/mdec_benchmark). The [mdec_2025](https://github.com/toshas/mdec_benchmark/tree/main/mdec_2025) folder contains scripts generating valid submissions for [Marigold](https://github.com/toshas/mdec_benchmark/blob/main/mdec_2025/marigold_v1-0/generate.py) (`affine-invariant`) and [Depth Anything v2](https://github.com/toshas/mdec_benchmark/blob/main/mdec_2025/depth_anything_v2/generate.py) (`disparity`).
2. Identify the prediction type of your method and generate a valid submission: `val` split for the "Development" phase and `test` split for the "Final" phase.
3. Register at the [CodaLab Challenge](https://codalab.lisn.upsaclay.fr/competitions/21305) site, check the submission constraints and extra conditions, and submit to the leaderboard.

The phases are open according to the following schedule:
- "Development": Feb 01 - Mar 01
- "Final": Mar 01 - Mar 21

### 📊 Evaluation {#evaluation}

Submissions will be evaluated on a variety of metrics:
- [Pointcloud reconstruction](https://arxiv.org/abs/2203.08122): F-Score
- [Image-based depth](https://arxiv.org/abs/1708.06500): MAE, RMSE, AbsRel
- [Depth discontinuities](https://arxiv.org/abs/1805.01328v1): F-Score, Accuracy, Completeness

The **leading metric** is **F-Score** (based on the point cloud), denoted as **F&nbsp;(↑)** in the leaderboard.
Challenge winners will be determined based on the performance ranked by the leading metric on the withheld validation ("Development" phase) and the test ("Final" phase) sets of the SYNS-Patches dataset.

To measure the performance locally with other datasets or troubleshoot scoring issues within the challenge, refer to the [evaluation code](https://github.com/toshas/mdec_benchmark/blob/main/src/core/evaluator.py).

### 📈 Baselines {#baselines}

This year, we switched to LSE-based alignment between predictions and ground truth maps to accept various types of predictions. 
In addition to previously accepted `disparity` prediction methods, we welcome `affine-invariant`, `scale-invariant`, and `metric` types.

Accordingly, we updated the benchmark with more recent baselines, such as Marigold (`affine-invariant`), Depth Anything v2 (`disparity`), and the winners of the 3rd edition of the MDEC challenge, whose performances are reported below.

|                |      F&nbsp;(↑)                                                                | F&nbsp;(↑)<br/>(Edges)                                                    | MAE&nbsp;(↓)                                                             | RMSE&nbsp;(↓)                                                            | AbsRel&nbsp;(↓)                                                              | Acc&nbsp;(↑)<br/>(Edges)                                                 | Comp&nbsp;(↓)<br/>(Edges)                                                | δ<1.25&nbsp;(↑)                                                | δ<1.25^2&nbsp;(↑)                                                | δ<1.25^3&nbsp;(↑)                                                | 
|----------------|------|------------------------------------------------------------------|------------------------------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------|------------------------------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------|
| **PICO-MR**    | 21.07          | 8.77 | 3.22 | 5.60 | 20.33                                                            | 3.69                                                            | 15.41                                                            | 0.7559                                                            | 0.9125                                                            | 0.9590                                                   
| **EVP++**    | 19.66          | 9.02 | 3.20 | 5.49 | 19.03                                                            | 2.66                                                            | 9.28                                                            | 0.7553                                                            | 0.9182                                                            | 0.9661                                                  
| **Marigold**    | 18.64          | 9.26 | 3.87 | 6.49 | 24.37                                                            | 2.90                                                            | 20.09                                                            | 0.6903                                                            | 0.8860                                                            | 0.9453                                                  
| **Depth Anything v2**    | 14.34          | 7.94 | 4.16 | 7.94 | 25.48                                                            | 2.64                                                            | 30.05                                                            | 0.6907                                                            | 0.8849                                                            | 0.9469                                                  
| **Garg's Baseline**    | 11.38          | 6.03 | 4.62 | 7.58 | 31.15                                                            | 4.01                                                            | 41.24                                                            | 0.5842                                                            | 0.8354                                                            | 0.9251

### 📚 Workshop proceedings {#proceedings}

As part of the CVPR Workshop Proceedings, we will publish a paper summarizing the results of the challenge. The following conditions must be met to have the method included in the paper:

- The method surpasses the performance of the baselines in the leading metric (F-Score);
- The method should not be trivial;
- Each prediction is made using a single corresponding input image;

Once the challenge has finished, we will contact the participants meeting the criteria above to request information about their affiliation, a short description of their method, and the method's source code. Participants not providing this information will not be added to the publication; their submission will stay anonymous in the leaderboard.

Selected top performers will also be invited to present their methods at the workshop. The presentation can be held either in person or virtually. This is mandatory; refusal to do so will result in an invalidated submission and removal from the paper.

## Feedback {#feedback}

Please feel free to reach out with any questions, concerns, or feedback using the address below — this is the quickest way to contact us. If your topic relates to the challenge, in addition to emailing us, consider opening a discussion on the [CodaLab forum](https://codalab.lisn.upsaclay.fr/forums/21249/).

<img src="assets/imgs/feedback.png" height=32px alt="Feedback address"/>

---

## 🤵 **Organizers** {#organizers}
<div class="container">
<figure>
    <a href="https://www.obukhov.ai/">
    <img class="img-author" src="assets/imgs/authors/anthon.png" alt="Anton Obukhov"/></a>
    <b><br><a href="https://www.obukhov.ai/">Anton Obukhov</a>
    <br>Principal Research Scientist<br>Huawei Research Center Zürich</b>
</figure>
    
<figure>
    <a href="https://www.linkedin.com/in/rsarora/">
    <img class="img-author" src="assets/imgs/authors/ripudaman_arora.jpeg" alt="Ripudaman Singh Arora"/></a>
    <b><br><a href="https://www.linkedin.com/in/rsarora/">Ripudaman Singh Arora</a>
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
