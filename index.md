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
- **30 Jan 2025 ---** :microphone: **Konrad Schindler** confirmed as keynote speaker.
- **7 Jan 2025 ---** :microphone: **Yiyi Liao** confirmed as keynote speaker.
- **6 Jan 2025 ---** :microphone: **Peter Wonka** confirmed as keynote speaker.
- **5 Jan 2025 ---** :tada: Website is live!
                                               
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

## :checkered_flag: **Challenge** {#challenge}

**[[GitHub Starter Pack](https://github.com/toshas/mdec_benchmark)] --- [[CodaLab Challenge](https://codalab.lisn.upsaclay.fr/competitions/21305)]**
{: .text-center}

The challenge focuses on evaluating novel MDE techniques on the [SYNS-Patches dataset](https://arxiv.org/abs/2208.01489).
This dataset provides a challenging variety of urban and natural scenes, including forests, agricultural settings, residential streets, industrial estates, lecture theatres, offices, and more.
Furthermore, the high-quality, dense ground-truth LiDAR allows for the computation of more informative evaluation metrics, such as those focused on [depth discontinuities](https://arxiv.org/abs/1805.01328v1).

<div class="container">
<img class="img-syns" src="assets/imgs/syns/image_0551.png" alt="image_0551"/>
<img class="img-syns" src="assets/imgs/syns/image_0893.png" alt="image_0893"/>
<img class="img-syns" src="assets/imgs/syns/image_1114.png" alt="image_1114"/>

<img class="img-syns" src="assets/imgs/syns/depth_0551.png" alt="depth_0551"/>
<img class="img-syns" src="assets/imgs/syns/depth_0893.png" alt="depth_0893"/>
<img class="img-syns" src="assets/imgs/syns/depth_1114.png" alt="depth_1114"/>
</div>

### ⚡ What’s new in MDEC 2025?

- 📐 New prediction types: The challenge became more accessible thanks to the added support of affine-invariant predictions. Metric and scale-invariant predictions are also automatically supported. Disparity predictions, which were supported in previous challenges, are also accepted.

- 🤗 Pre-trained Model Support: We provide ready-to-use scripts for off-the-shelf methods: Depth Anything V2 (disparity) and Marigold (affine-invariant). These will serve as a competitive baseline for the challenge and a starting point for participants.

- 📊 Updated Evaluation Pipeline: The Codalab grader code has been updated to accommodate the newly supported prediction types.

### How to participate?

- Check out the new starter pack [GitHub](https://github.com/toshas/mdec_benchmark). The [mdec_2025](https://github.com/toshas/mdec_benchmark/tree/main/mdec_2025) folder contains scripts generating valid submissions for [Marigold](https://github.com/toshas/mdec_benchmark/blob/main/mdec_2025/marigold_v1-0/generate.py) (`affine-invariant`) and [Depth Anything v2](https://github.com/toshas/mdec_benchmark/blob/main/mdec_2025/depth_anything_v2/generate.py) (`disparity`).

- Identify the prediction type of your method and generate a valid submission: `val` split for the "Development" phase and `test` split for the "Final" phase.

- Register at the [CodaLab Challenge](https://codalab.lisn.upsaclay.fr/competitions/21305) site, check the submission constraints and extra conditions, and submit to the leaderboard.

### Evaluation

Submissions will be evaluated on a variety of metrics:
1. [Pointcloud reconstruction](https://arxiv.org/abs/2203.08122): F-Score
2. [Image-based depth](https://arxiv.org/abs/1708.06500): MAE, RMSE, AbsRel
3. [Depth discontinuities](https://arxiv.org/abs/1805.01328v1): F-Score, Accuracy, Completeness

The **leading metric** is F-Score (based on point cloud), denoted as **F&nbsp;(↑)** in the leaderboard.
Challenge winners will be determined based on the performance ranked by the leading metric on the withheld validation (Development phase) and the test (Final phase) sets of the SYNS-Patches dataset.

To measure the performance locally with other datasets or troubleshoot scoring issues within the challenge, refer to the [evaluation code](https://github.com/toshas/mdec_benchmark/blob/main/src/core/evaluator.py).

### Workshop proceedings

As part of the CVPR Workshop Proceedings, we will publish a paper summarizing the results of the challenge.
The following conditions must be met to have the method included in the paper:

- A method description is provided as a part of the submission;
- The method surpasses the performance of the baselines in the leading metric;
- The method should not be a trivial extension of any of the baselines;
- All predictions are made using a single input image;
- The source code of the method is provided;

Selected top performers will additionally be invited to present their method at the workshop (<a href="#schedule" target="_self">schedule</a>).
This presentation can be either in-person or virtually.

---

## :rocket: **Baselines** {#baselines}

This year, we switched to LSE-based alignment between predictions and ground truth maps.

Accordingly, we updated the benchmark with more recent baselines, such as Marigold, Depth Anything v2, and with the winners of the 3rd edition,
whose performances are reported below.

Please note that to be invited as authors of the meta-paper describing the challenge, participants are now required to achieve a performance above the Marigold and Depth Anything v2 baselines.

|                |      F&nbsp;(↑)                                                                | F<br/>(Edges,&nbsp;↑)                                                    | MAE&nbsp;(↓)                                                             | RMSE&nbsp;(↓)                                                            | AbsRel&nbsp;(↓)                                                              | Acc<br/>(Edges,&nbsp;↑)                                                 | Comp<br/>(Edges,&nbsp;↓)                                                | δ<1.25&nbsp;(↑)                                                | δ<1.25^2&nbsp;(↑)                                                | δ<1.25^3&nbsp;(↑)                                                | 
|----------------|------|------------------------------------------------------------------|------------------------------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------|------------------------------------------------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------|
| **PICO-MR**    | 21.07          | 8.77 | 3.22 | 5.60 | 20.33                                                            | 3.69                                                            | 15.41                                                            | 0.7559                                                            | 0.9125                                                            | 0.9590                                                   
| **EVP++**    | 19.66          | 9.02 | 3.20 | 5.49 | 19.03                                                            | 2.66                                                            | 9.28                                                            | 0.7553                                                            | 0.9182                                                            | 0.9661                                                  
| **Marigold**    | 18.64          | 9.26 | 3.87 | 6.49 | 24.37                                                            | 2.90                                                            | 20.09                                                            | 0.6903                                                            | 0.8860                                                            | 0.9453                                                  
| **Depth Anything v2**    | 14.34          | 7.94 | 4.16 | 7.94 | 25.48                                                            | 2.64                                                            | 30.05                                                            | 0.6907                                                            | 0.8849                                                            | 0.9469                                                  
| **Garg's Baseline**    | 11.38          | 6.03 | 4.62 | 7.58 | 31.15                                                            | 4.01                                                            | 41.24                                                            | 0.5842                                                            | 0.8354                                                            | 0.9251

---

## :construction_worker: **Organizers** {#organizers}
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
