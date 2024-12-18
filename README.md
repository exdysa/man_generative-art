# man_generative-art


### a brain dump for relevant generative art research and datasheets


> This is a reference list for programmers to find articles of interest from ARXIV ~~(pronounced arZIV!!)~~ and pinpoint exact formula and techniques, though it may also be good for winning arguments or persuading people into believing you know something you don't.
>
> Great diffusion learning resources -<br>
[lilianweng.github.io Concentrated information in a single place](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)<br>
[The-GAN-Zoo A very thorough GAN paper collection](https://github.com/hindupuravinash/the-gan-zoo)<br>
[Awesome-Diffusion-Models, A Giant Paper Dump](https://github.com/kyegomez/EXA-1/tree/0e544f47a164548d74d4e986d0c0e6dd6b47cc0d/exa/papers/Awesome-Diffusion-Models)<br>
[huggingface.co Transformers Docs](https://huggingface.co/docs/transformers/index)<br>
[Deep Dive into AI with MLX](https://github.com/neobundy/Deep-Dive-Into-AI-With-MLX-PyTorch/tree/master/deep-dives)<br>

<a name="top"/>

### The linkdump

> - [Diffusion Models](#models)
> - [Attention](#attention)
> - [Guidance](#guidance)
> - [Schedulers/Solvers](#schedulers)
> - [Language-Learning Models](#llm)
> - [Image Restoration & Super Resolution](#resto)
> - [Various Efficiency Optimizations](#opt)
> - [Older and Semi-related Interest](#etc)
> - [Diagram Collection](#infographics)

***

<a name="models"/>

Diffusion Models (& Variational Autoencoders)

> * https://arxiv.org/abs/1312.6114 Variational Autoencoders
> * https://arxiv.org/abs/2112.10752 Latent Diffusion
> * https://arxiv.org/abs/2205.11487v1 Imagen
> * https://arxiv.org/abs/2211.01324 The Ensemble of Expert Denoisers
> * https://arxiv.org/abs/2212.09748 DiT
> * https://arxiv.org/abs/2306.00637 Würstchen
> * https://arxiv.org/abs/2307.01952 SDXL
> * https://arxiv.org/abs/2310.00426 Pixart-α
> * https://arxiv.org/abs/2310.16825 CommonCanvas - Diffusion from Collective Commons images
> * https://arxiv.org/abs/2401.02677 Segmind SSD-1V & Vega
> * https://arxiv.org/abs/2401.05252 Pixart-δ
> * https://arxiv.org/abs/2402.13929 SDXL Lightning
> * https://arxiv.org/abs/2403.03206 Stable Diffusion 3
> * https://arxiv.org/abs/2403.04692 PixArt-Σ
> * https://arxiv.org/abs/2404.13686 Hyper-SD
> * https://arxiv.org/abs/2405.05945 Lumina T2X
> * https://arxiv.org/abs/2405.08748 HunYuan-DiT
> * https://arxiv.org/abs/2406.18583 Lumina-Next (Next-DiT)


> [top](#top)

<a name="attention"/>

Attention

> * https://arxiv.org/abs/1406.2661 Generative Adversarial Networks
> * https://arxiv.org/abs/1505.04597 UNet Model
> * https://arxiv.org/abs/1512.03385 ResNet Model
> * https://arxiv.org/abs/1706.03762 the Transformer & attention
> * https://arxiv.org/abs/1711.10485 Attentional GAN
> * https://arxiv.org/abs/2103.14030 Swin Shifted windows Transformer
> * https://arxiv.org/abs/2108.01073 SDEdit
> * https://arxiv.org/abs/2112.05682v2 Self Attention Memory Efficiency
> * https://arxiv.org/abs/2205.14135 Flash Attention
> * https://arxiv.org/abs/2307.08691 Flash Attention 2: Attention Boogaloo
> * https://arxiv.org/abs/2406.08552 DiTFastAttn: Attention Compression
> * https://arxiv.org/abs/2407.08608 Flash Attention 3: The Flash Crusade
> * https://arxiv.org/abs/2411.06558 Region-Aware Generation Diffusion, improved composition
> [top](#top)

<a name="guidance"/>

Guidance

> * https://arxiv.org/abs/2207.12598 Classifer Free Guidance
> * https://arxiv.org/abs/2210.00939 Self-Attention Guidance
> * https://arxiv.org/abs/2301.12247 Semantic Guidance
> * https://arxiv.org/abs/2301.13826 Attend-and-excite Attention Guidance, Generative Semantic Nursing
> * https://arxiv.org/abs/2404.07724 Interval Guidance

> [top](#top)

<a name="schedulers"/>

Schedulers

> * https://arxiv.org/abs/2006.11239 DDPM Denoising Diffusion Probabilistic Models
> * https://arxiv.org/abs/2010.02502v4 DDIM Denoising Diffusion Implicit Models
> * https://arxiv.org/abs/2011.13456 SDE Stochastic Differential Equations
> * https://arxiv.org/abs/2102.09672 DDPM optimizing
> * https://arxiv.org/abs/2105.14080 adaptive SDE
> * https://arxiv.org/abs/2206.00364 Euler scheduler (Algorithm 2) / Heun / Karras / DPMa SDE
> * https://arxiv.org/abs/2206.00927 DPM Solver
> * https://arxiv.org/abs/2211.01095 DPM Solver ++
> * https://arxiv.org/abs/2202.09778 PNDM Solving Pseudo linear multi-step Numerical Diffusion Models on manifolds
> * https://arxiv.org/abs/2210.02747 Flow Matching
> * https://arxiv.org/abs/2302.04867 UniPC Sampler
> * https://arxiv.org/abs/2305.08891 V Prediction with Zero SNR And CFG Rescale
> * https://arxiv.org/abs/2404.14507 Align Your Steps
> * https://arxiv.org/abs/2406.03293 Rectified Flow

> [top](#top)

<a name="llm"/>

Language-Learning Models

> * https://arxiv.org/abs/1910.10683 T5 Text-to-Text Transfer Transformer
> * https://arxiv.org/abs/2010.11929 ViT Vision Transformer
> * https://arxiv.org/abs/2103.00020 Natural Language Supervision training
> * https://arxiv.org/abs/2106.04560 ViT Scaling
> * https://arxiv.org/abs/2112.10003 CLIPSeg
> * https://arxiv.org/abs/2205.11487 Photorealistic Language models, Imagen & DrawBench benchmark
> * https://arxiv.org/abs/2211.06679 ALTCLIP
> * https://arxiv.org/abs/2403.08857 Evaluating Multi-Modal LLMs

> [top](#top)

<a name="resto"/>

Image Restoration Models

> * https://arxiv.org/abs/1802.05957 GAN Color Normalization
> * https://arxiv.org/abs/2107.10833 RealESRGAN
> * https://arxiv.org/abs/2108.10257 SwinIR
> * https://arxiv.org/abs/2401.13627 SUPIR

> [top](#top)

<a name="opt"/>

Various Optimizations

> * https://arxiv.org/abs/1711.07837 UnFlow unsupervised training
> * https://arxiv.org/abs/2207.04316 Patching diffusion models to increase efficiency
> * https://arxiv.org/abs/2208.01618 Textual Inversion
> * https://arxiv.org/abs/2208.12242 DreamBooth training
> * https://arxiv.org/abs/2110.02861 8 bit optimizers with 32 bit performance
> * https://arxiv.org/abs/2202.00512 Distillation
> * https://arxiv.org/abs/2302.05442 ViT 22b Scaling
> * https://arxiv.org/abs/2302.05543 ControlNET
> * https://arxiv.org/abs/2302.08453 T2i Adapter
> * https://arxiv.org/abs/2303.06555 UniDiffuser
> * https://arxiv.org/abs/2305.08891 ZSNR Zero signal-to-noise
> * https://arxiv.org/abs/2309.11497 FreeU
> * https://arxiv.org/abs/2310.04378 LCM
> * https://arxiv.org/abs/2311.05556 LCM-LoRA
> * https://arxiv.org/abs/2311.17137 Intrinsic LoRA
> * https://arxiv.org/abs/2312.00858v2 DeepCache
> * https://arxiv.org/abs/2312.02238 X-Adapter modular model mapping
> * https://arxiv.org/abs/2312.12491 StreamDiffusion real time generating and modifying
> * https://arxiv.org/abs/2405.18407 PCM Phased Consistency
> * https://arxiv.org/abs/2304.02643 SAM Segment Anything
> * https://arxiv.org/abs/2406.04314 SPO
> * https://arxiv.org/abs/2406.09416 Scaling detail w multiple networks and normalization to prevent distortions
> * https://arxiv.org/abs/2404.10177 Corrupted data training
> * https://arxiv.org/abs/2406.10163 Pd Mesh
> * https://arxiv.org/abs/2407.02158 UltraPixel 4k-6k image generation

> [top](#top)

<a name="etc"/>

older/semi related/non-arxiv/useful and some practical stuff in no particular order

> * https://arxiv.org/abs/1603.09382 stochastic depth training
> * https://arxiv.org/abs/1611.07004 pix2pix
> * https://arxiv.org/abs/1806.02658 Super resolution particulars
> * https://arxiv.org/abs/1810.12890 Managing dropout on layers using DropBlock]
> * https://arxiv.org/abs/1811.11718 Convolution Padding VS Zero Padding
> * https://arxiv.org/abs/1908.04913 Fair face
> * https://arxiv.org/abs/1910.04867 VTAB benchmark
> * https://arxiv.org/abs/2010.14701 Generative Scaling Laws and Relation
> * https://arxiv.org/abs/2105.05233 Comparative study of diffusion and GAN
> * https://arxiv.org/abs/2303.13439 Pix2Pix vid gen
> * https://arxiv.org/abs/2306.07154 InstructPix2Pix
> * https://arxiv.org/abs/2403.01779 OOTD clothing try on
> * https://arxiv.org/abs/1812.06162 Model training observations
> * https://arxiv.org/abs/2401.14423 Advanced Prompt Engineering
> * https://arxiv.org/abs/2403.12171 EasyJailbreak
> * https://arxiv.org/abs/1910.09700 Quantifying the Carbon Emissions of Machine Learning
> * https://arxiv.org/abs/2208.11695 How ImageNet Misrepresents Biodiversity
> * https://arxiv.org/abs/1912.11945 On the Morality of Artificial Intelligence
> * https://arxiv.org/search/cs?searchtype=author&query=Luccioni,+A All of this person's work is incredible tbh
> * https://arxiv.org/abs/2210.05559 CycleDiffusion Image2Image
> * https://arxiv.org/abs/2211.13227 Exemplar Based I2I Inpainting
> * https://blog.fal.ai/auraflow/
> * https://blog.segmind.com/segmind-vega-2/
> * https://stable-diffusion-art.com/samplers/
> * 
> [top](#top)


<a name="infographics"/>

## LOOK AT THIS GRAPH

### Related infographics

![gan1](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/latent-diffusion-arch.png)

![v2-2bacda7c7c47444c61c74066e8a6cc08_r](https://github.com/user-attachments/assets/202fa2a1-e63a-4cf7-a55c-be9e124f7536)

![Untitled--11-](https://github.com/user-attachments/assets/2091d2aa-53bd-4f2d-9549-7fd22f63ee61)

![v2-d5e874db6ca705f1feaad44faf6e46d0_r](https://github.com/user-attachments/assets/75e98cbb-9bb2-41a1-886b-7971d9ee6ed5)
![1_XmqyKSM3I68GWGJg3V5ZkQ](https://github.com/user-attachments/assets/297c5ec1-036e-4aac-ba2f-adacd850afca)

![wisui4k08rr91](https://github.com/user-attachments/assets/31db3b1b-2508-48d2-acb2-15db40dd6dcd)

![1_lb7Ww2wY0450eMNCHlwVTg](https://github.com/user-attachments/assets/c6d76831-8c94-4de3-8c5d-0af8c2bc9f92)

![1_v_0hELER1CwbScDszrE5yw](https://github.com/user-attachments/assets/40ead002-627c-4ff5-bec7-91cad2527204)

![0_Q9iM4_vhdCYDlTsO](https://github.com/user-attachments/assets/8fb58ffc-3d3e-4ae0-bf36-df8e92e6987c)

![LoRA_table-1](https://github.com/user-attachments/assets/c11fe6a7-0120-4b0a-b7a8-54cb2bcbfea5)

