# Awesome-learning-in-latent-space
Here I list papers about learning different tasks in latent space. 


## Image generation
- Neural Discrete Representation Learning (VQ-VAE). [[code]](https://github.com/MishaLaskin/vqvae)
- Latent Diffusion Models. [[paper]](https://arxiv.org/abs/2112.10752) [[code]](https://github.com/CompVis/latent-diffusion)
- Synthesizing Coherent Story with Auto-Regressive Latent Diffusion Models. [[paper]](https://openaccess.thecvf.com/content/WACV2024/papers/Pan_Synthesizing_Coherent_Story_With_Auto-Regressive_Latent_Diffusion_Models_WACV_2024_paper.pdf) [[code]](https://github.com/xichenpan/ARLDM)
- Scalable Diffusion Models with Transformers (DiT). [[code]](https://github.com/facebookresearch/DiT)
- Language Quantized AutoEncoders. [[code]](https://github.com/lhao499/language-quantized-autoencoders/tree/main?tab=readme-ov-file)
  - Use fixed RoBerta codebook for image encoder pretraining

## Robot learning
- Learning Generalizable Feature Fields for Mobile Manipulation. [[project]](https://geff-b1.github.io)
- Improving Vision-and-Language Navigation by Generating Future-View Image Semantics. [[project]](https://jialuli-luka.github.io/VLN-SIG)
- CLIP-Fields: Weakly Supervised Semantic Fields for Robotic Memory. [[code]](https://github.com/notmahi/clip-fields)
- Latent Plans for Task-Agnostic Offline Reinforcement Learning. [[project]](http://tacorl.cs.uni-freiburg.de/)

## Robot control
- Fourier latent dynamics. [[code]](https://github.com/mit-biomimetics/fld)

## Reinforcement learning
- Unsupervised Zero-Shot Reinforcement Learning via Functional Reward Encodings. [[code]](https://github.com/kvfrans/fre)

## Robot manipulation
### With foundation models
- PIVOT: Iterative Visual Prompting Elicits Actionable Knowledge for VLMs. [[paper]](https://arxiv.org/pdf/2402.07872.pdf). *Insight: VLM strugglese to produce precise spatial outputs directly, but they can readily select among a discrete set of coarse choices, and this in turn can be used to refine the set to provide more precise choices at the next iteration.*
### W/o foundation models
