<p align="center">
  <h1 align="center">Wild3A: Novel View Synthesis from Any Dynamic Images in Seconds</h1>
  <h3 align="center">MM '25</h3>
    <p align="center">Mingrui Li<sup>*</sup>, Dong Li<sup>*</sup>, Sijia Hu, Kangxu Wang, Zhenjun Zhao and Hongyu Wang<sup>†</sup></p>
    <h3 align="center"><a href="https://dl.acm.org/doi/10.1145/3746027.3754971">Paper</a> | <a href="https://github.com/user-attachments/assets/511c5911-9158-425c-a87e-ca107bbe068a">Video</a> </h3>
    <video src="https://github.com/user-attachments/assets/511c5911-9158-425c-a87e-ca107bbe068a" width="100%" controls autoplay > </video>
</p>





## Abstract

Wild3A is an end-to-end framework for novel view synthesis in dynamic scenes. It removes the need for fixed camera parameters, strong semantic priors, or specialized losses by directly predicting 3D points and confidence via MASt3R’s Transformer and integrating a Bayesian fusion module. 

We utilize [TUM RGB-D](https://cvg.cit.tum.de/data/datasets/rgbd-dataset), [BONN RGB-D](https://www.ipb.uni-bonn.de/data/rgbd-dynamic-dataset/index.html), [IMW2020](https://github.com/ubc-vision/image-matching-benchmark) and [NeRF-OTG](https://rwn17.github.io/nerf-on-the-go/) datasets to evaluate the performance of our algorithm, showing that Wild3A jointly optimizes scene representation and camera parameters, delivering artifact-free results, state-of-the-art performance, and real-time rendering at 1000+ FPS.

<img width="1510" height="782" alt="image" src="https://github.com/user-attachments/assets/f529cd65-aa31-47e9-ab05-3c760a03de6d" />

## Build

_**Source code will be released soon.**_

## License
Wild3A is released under the [GNU General Public License v3.0](LICENSE).

## Citation

If you find our work useful, please kindly cite us:

```bibtex
@inproceedings{10.1145/3746027.3754899,
author = {Li, Mingrui and Zhai, Shuhao and Zhao, Zibing and Sun, Luyue and Wang, Xinxiao and Li, Dong and Liu, Shuhong and Wang, Hongyu},
title = {Wild3A: Novel View Synthesis from Any Dynamic Images in Seconds},
year = {2025},
isbn = {9798400720352},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3746027.3754899},
doi = {10.1145/3746027.3754899},
abstract = {The core issue in novel view synthesis lies in how to handle dynamic scenes that are common in the real world, such as dynamic objects, occlusions, and varying luminance. Current 3D Gaussian Splatting-based methods perform excellently in static scenes but often rely on fixed camera parameters, precise semantic prior segmentation, or specially designed rendering loss functions when dealing with dynamic scenes. These additional pieces of information limit the method's generalization ability, real-time performance, and application in AR, VR, and multimedia. To address these issues, we propose Wild3A, a comprehensive end-to-end integrated framework: it directly regresses 3D point positions and initial point confidence via the MASt3R's Transformer and integrates a Bayesian estimation module based on multimodal information fusion. We adopt a self-supervised joint optimization approach for scene representation and camera parameters. Extensive experiments on both public and private datasets show that Wild3A effectively eliminates visual artifacts in various dynamic scenes, achieves state-of-the-art results across multiple tasks, and achieves real-time rendering at 1000+ FPS.},
booktitle = {Proceedings of the 33rd ACM International Conference on Multimedia},
pages = {7472–7480},
numpages = {9},
keywords = {3D reconstruction, dynamic suppression, multi-view geometry, novel view synthesis},
location = {Dublin, Ireland},
series = {MM '25}
}
```
 
