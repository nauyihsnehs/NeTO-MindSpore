

# NeTO: NeTO:Neural Reconstruction of Transparent Objects with Self-Occlusion Aware Refraction-Tracing

## [Project Page](https://www.xxlong.site/NeTO/) | [Paper](./doc/NeTO_ARXIV.pdf) 

we will release the code soon.

![](./docs/images/teaser.png)

## Introduction
   We present a novel method, called NeTO, for capturing 3D geometry of solid transparent objects from 2D images via volume rendering. 
    Reconstructing transparent objects is a very challenging task, which is ill-suited for general-purpose reconstruction techniques due to the specular light transport phenomena.
    Although existing refraction-tracing based methods, designed specially for this task, achieve impressive results, they still suffer from unstable optimization and loss of fine details, since the explicit surface representation they adopted is difficult to be optimized, and the self-occlusion problem is ignored for refraction-tracing.
    In this paper, we propose to leverage implicit Signed Distance Function (SDF) as surface representation, and optimize the SDF field via volume rendering with a self-occlusion aware refractive ray tracing. 
    The implicit representation enables our method to be capable of reconstructing high-quality reconstruction even with a limited set of images, and the self-occlusion aware strategy makes it possible for our method to accurately reconstruct the self-occluded regions. 
    Experiments show that our method achieves faithful reconstruction results and outperforms prior works by a large margin.
            

