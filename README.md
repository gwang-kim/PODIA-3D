# PODIA-3D: Domain Adaptation of 3D Generative Model Across Large Domain Gap Using Pose-Preserved Text-to-Image Diffusion  

[![arXiv](https://img.shields.io/badge/arXiv-2303.XXXXX-red)](https://arxiv.org/abs/2303.XXXXX) [![project_page](https://img.shields.io/badge/-project%20page-blue)](https://gwang-kim.github.io/podia_3d/)

[//]: # ()
[//]: # ([![arXiv]&#40;https://img.shields.io/badge/paper-cvpr2022-cyan&#41;]&#40;https://openaccess.thecvf.com/content/CVPR2022/html/Kim_DiffusionCLIP_Text-Guided_Diffusion_Models_for_Robust_Image_Manipulation_CVPR_2022_paper.html&#41; [![arXiv]&#40;https://img.shields.io/badge/arXiv-2110.02711-red&#41;]&#40;https://arxiv.org/abs/2110.02711&#41;)

[//]: # ([![video]&#40;https://img.shields.io/badge/video-green&#41;]&#40;https://youtu.be/YVCtaXw6fw8&#41; [![poster]&#40;https://img.shields.io/badge/poster-orange&#41;]&#40;https://drive.google.com/file/d/1QgRFIRba492dCZ6v7BcZB9zqyp91aTjL/view?usp=sharing&#41; )

<p align="center">

  <img src="assets/podia_3d_result.gif" />


</p> 

[comment]: <> (![]&#40;imgs/main1.png&#41;)

[comment]: <> (![]&#40;imgs/main2.png&#41;)

> **PODIA-3D: Domain Adaptation of 3D Generative Model Across Large Domain Gap Using Pose-Preserved Text-to-Image Diffusion**<br>
> [Gwanghyun Kim](https://gwang-kim.github.io/), [Se Young Chun](https://icl.snu.ac.kr/pi) <br>
> 
> 
>**Abstract**: <br>
Recently, significant advancements have been made in 3D generative models, however training these models across diverse domains is challenging and requires an enormous amount of training data and knowledge of pose distribution.
Text-guided domain adaptation methods have allowed the generator to be adapted to the target domains using text prompts, thereby obviating the need for assembling numerous data. Recently, DATID-3D presents impressive quality of view consistent images in text-guided domain, preserving diversity in text by leveraging text-to-image diffusion models. However, adapting 3D generators to domains with significant domain gaps from the source domain still remains challenging due to issues in current text-to-image diffusion models. These issues include: 1) shape-pose trade-off in diffusion-based translation, 2) pose bias, and 3) instance bias in the target domain, resulting in inferior 3D shapes, low text-image correspondence, and low intra-domain diversity in the generated samples.
**To address these issues, we propose a novel pipeline called PODIA-3D, which uses pose-preserved text-to-image diffusion-based domain adaptation for 3D generative models.** We construct a pose-preserved text-to-image diffusion model that allows the use of extremely high-level noise for significant domain changes. We also propose specialized-to-general sampling strategies to improve the details of the generated samples. Moreover, to overcome the instance bias, we introduce a text-guided debiasing method that improves intra-domain diversity. Consequently, our method successfully adapts 3D generators across significant domain gaps, producing excellent text-image correspondence and 3D shapes, while the baselines mostly fail. Our qualitative results and user study demonstrates that our approach outperforms existing 3D text-guided domain adaptation methods in terms of text-image correspondence, realism, diversity of rendered images, and sense of depth of 3D shapes in the generated samples.
# Notice 
- The code is comming soon!