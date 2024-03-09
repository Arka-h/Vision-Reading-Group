
# Vision-Reading-Group

## Mission
 -  Foster collaboration and knowledge exchange in various sub-fields of [your field].
 -  Explore and discuss cutting-edge research (SOTA) across different areas.
 -  Provide a platform for brainstorming, peer review, and constructive criticism.
 -  Develop reading papers as a habit/hobby.
## Format
 -  **Online Sessions** : Convenient for everyone.
 -  **Semi-Formal** : Develop reading and discussion skills in a relaxed atmosphere.
 -  **Frequency** : Weekly (optional for members to present every week).
## Paper Selection
 -  **Two Papers per Session** : Focus on foundational or influential papers relevant to different sub-fields.
 -  **Open Selection** : Members can add interesting papers to a shared list (presenter not required to be the recommender).
## Presentation
 -  **Collaborative Exploration** : Brief on-the-spot reading and group discussion encouraged.
 -  **Active Participation** : Attendees should guide the presenter and contribute to understanding, not just ask questions.
 -  **Optional Presentation** : Members can present their own ideas for feedback and discussion.
## Additional Points
 -  **Minimal Commitment** : While regular participation is encouraged, a minimum of two volunteers per week for paper presentations is preferred.
 -  **Constructive Environment** : Promote open discussion, respectful debate, and supportive feedback.


Purpose: 
    * Stay updated/relevant with papers in the contributor's respective interests, and encourage exploratory research & collaboration.
    * Discuss, debate and develop an overview/moderate understanding of SOTA across different verticals (& their own).
    * Provide a platform to discuss interesting concepts, inspiring members to ideate and open perspectives across sub-fields.
    * Provide a inclusive environment to bounce ideas with peer reviews, discussion and constructive criticism.

Rules:
    * Sessions will be held online, as it's the most convenient for all members of the group.
    * It will be semi-formal in nature as it's a practice for developing reading interesting papers and ideating as a hobby & not as merely a voluntary event.
    * Each session we will discuss atleast two interesting papers(think about central papers that are cited in many downstream applications and that need understanding/explaining. ex. Diffusion) presented by two contributors in their respective domains, discuss and explain the papers to the group.
    * Optionally each member can also present their own ideas to receive feedback & ideate online via discussion.
    * Brief reading of papers on the spot by presenter, without preparation is not only allowed but encouraged. Members are expected to help guide the presenter & participate in understanding together, not just ask questions.
    * It is optional for members to prepare and present every week, although it's expected that atleast 2 volunteers will take responsibility every week.
    * Any member is free to pick/add interesting papers to the list to present. However, it's not necessary for the person adding the paper to present themselves. If someone else is interested in presenting the paper, they may do so as well.

## Table of Contents
- [Vision-Reading-Group](#vision-reading-group)
    - [Table of Contents](#table-of-contents)
- [Research Papers](#research-papers)
    - [3D Vision](#3d-vision)
        - [3D Generation](#3d-generation)
        - [3D Editing](#3d-editing)
        - [3D Grounding](#3d-grounding)
        - [3D Inpainting](#3d-inpainting)
        - [NERFs](#nerfs)
    - [Diffusion](#diffusion)
    - [Distillation](#distillation)
- [Survey Papers](#survey-papers)
    - [Foundation Models](#foundation-models)
    - [3D Vision](#3d-vision-1)
        - [NERFs](#nerfs-1)
        - [Emboidied AI](#emboidied-ai)
    - [Adversarial](#adversarial)
        - [Data Poisoning](#data-poisoning)
- [Explainers](#explainers)
    - [Diffusion](#diffusion-1)

# Research Papers
  
## 3D Vision

### 3D Generation
- [ ] DreamFusion: Text-to-3D using 2D Diffusion [ICLR 23] [[Paper](https://arxiv.org/abs/2209.14988)] [[Demo](https://dreamfusion3d.github.io/)]
- [x] LucidDreaming: Controllable Object-Centric 3D Generation [Submitted 30 Nov 2023 arxiv] [[Paper](https://arxiv.org/abs/2312.00588)] [[Demo](https://www.zhaoningwang.com/LucidDreaming/)] [[Code](https://github.com/EricWang12/LucidDreaming/tree/main)]
  
### 3D Editing
- [Awesome NERF editing](https://github.com/EricLee0224/awesome-nerf-editing)
- [x] GaussianEditor: Swift and Controllable 3D Editing with Gaussian Splatting [Submitted 24 Nov 2023 arxiv] [[Paper](https://arxiv.org/abs/2311.14521)] [[Demo](https://buaacyw.github.io/gaussian-editor/)] [[Code](https://github.com/buaacyw/GaussianEditor)] [[Video](https://www.youtube.com/watch?v=TdZIICSFqsU)]
- [ ] Instruct-NeRF2NeRF: Editing 3D Scenes with Instructions [ICCV 23] [[Paper](https://arxiv.org/abs/2303.12789)] [[Demo](https://instruct-nerf2nerf.github.io/)] [[Code](https://github.com/ayaanzhaque/instruct-nerf2nerf)]
- [x] DreamBooth3D: Subject-Driven Text-to-3D Generation [ICCV 23] [[Paper](https://arxiv.org/abs/2303.13508)] [[Demo](https://dreambooth3d.github.io/)] 
- [ ] DreamEditor: Text-Driven 3D Scene Editing with Neural Fields [SIGGRAPH 23] [[Paper](https://arxiv.org/abs/2306.13455)] [[Demo](https://www.sysu-hcp.net/projects/cv/111.html)] [[Code](https://github.com/zjy526223908/DreamEditor)] 
  
### 3D Grounding
- [ ] Language Conditioned Spatial Relation Reasoning for 3D Object Grounding [NerIPS 22] [[Paper](https://arxiv.org/abs/2211.09646)] [[Demo](https://cshizhe.github.io/projects/vil3dref.html)] [[Code](https://github.com/cshizhe/vil3dref)]
- [ ] 3D Concept Grounding on Neural Fields [NeurIPS 22] [[Paper](https://arxiv.org/abs/2207.06403)] [[Code](https://github.com/evelinehong/3D-Concept-Grounding)]
- [ ] Multi-View Transformer for 3D Visual Grounding [CVPR 22] [[Paper](https://arxiv.org/abs/2204.02174)] [[Code](https://github.com/sega-hsj/MVT-3DVG)]
  
### 3D Inpainting
- [ ] Breathing New Life into 3D Assets with Generative Repainting [ICCV 23] [[Paper](https://arxiv.org/abs/2309.08523)] [[Demo](https://www.obukhov.ai/repainting_3d_assets)] [[Code](https://github.com/kongdai123/repainting_3d_assets)]
- [ ] RePaint: Inpainting using Denoising Diffusion Probabilistic Models [CVPR 22] [[Paper](https://arxiv.org/abs/2201.09865)] [[Code](https://github.com/andreas128/RePaint)]
- [ ] Diffusion Probabilistic Models for Scene-Scale 3D Categorical Data [Submitted 2 Jan 23 arxiv] [[Paper](https://arxiv.org/abs/2301.00527)] [[Code](https://github.com/zoomin-lee/scene-scale-diffusion)]

### NERFs
- [x] NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis [[Paper](https://arxiv.org/abs/2003.08934)] [[Demo](tancik.com/nerf)] [[Code](https://github.com/bmild/nerf)] [[Dataset](https://drive.google.com/drive/folders/128yBriW1IG_3NJ5Rp7APSTZsJqdJdfc1)]
- [x] D-NeRF: Neural Radiance Fields for Dynamic Scenes [CVPR 21] [[Paper](https://arxiv.org/abs/2011.13961)] [[Demo](https://www.albertpumarola.com/research/D-NeRF/index.html)] [[Code](https://github.com/albertpumarola/D-NeRF)]
- [x] Mip-NeRF: A Multiscale Representation for Anti-Aliasing Neural Radiance Fields [ICCV 21] [[Paper](https://arxiv.org/abs/2103.13415)] [[Code](https://github.com/google/mipnerf)]

## Diffusion
- [ ] Understanding Diffusion Models: A Unified Perspective. by Calvin Luo [Explainer, arxiv] [[Paper](https://arxiv.org/abs/2208.11970)]
- [ ] LatentPaint: Image Inpainting in Latent Space with Diffusion Models [WACV 24] [[Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Corneanu_LatentPaint_Image_Inpainting_in_Latent_Space_With_Diffusion_Models_WACV_2024_paper.pdf)] [[Video](https://www.youtube.com/watch?v=mhHc34O2H4o)]
- [ ] DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation [CVPR 23] [[Paper](https://arxiv.org/abs/2208.12242)] [[Demo](https://dreambooth.github.io/)] [[Dataset](https://github.com/google/dreambooth)] [[Tutorial](https://huggingface.co/docs/diffusers/en/training/dreambooth)]

## Distillation
- [ ] Dreaming to Distill: Data-free Knowledge Transfer via DeepInversion [CVPR 20] [[Paper](http://arxiv.org/abs/1912.08795)] [[Code](https://github.com/NVlabs/DeepInversion)]

# Survey Papers

## Foundation Models
- [ ] A Comprehensive Survey on Pretrained Foundation Models: A History from BERT to ChatGPT [Submitted 18 Feb 23 arxiv] [[Paper](http://arxiv.org/abs/2302.09419)]

## 3D Vision
### NERFs
- [ ] NeRF: Neural Radiance Field in 3D Vision, A Comprehensive Review [Submitted 30 Nov 23 arxiv] [[Paper](https://arxiv.org/abs/2210.00379)]
### Emboidied AI
- [ ] A Survey of Embodied AI: From Simulators to Research Tasks [IEEE Txn 22] [[Paper](https://arxiv.org/abs/2103.04918)] 

## Adversarial
### Data Poisoning
- [x] Just How Toxic is Data Poisoning? A Unified Benchmark for Backdoor and
Data Poisoning Attacks [PMLR '21] [[Paper](http://proceedings.mlr.press/v139/schwarzschild21a/schwarzschild21a.pdf)]

# Explainers
## Diffusion
Understanding Diffusion Models: A Unified Perspective [Submitted 25 Aug 23 arxiv] [[Paper](https://arxiv.org/abs/2208.11970)]
