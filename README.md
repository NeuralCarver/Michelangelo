# Michelangelo

## [Conditional 3D Shape Generation based on Shape-Image-Text Aligned Latent Representation](https://neuralcarver.github.io/michelangelo)<br/>
[Zibo Zhao](https://github.com/Maikouuu),
[Wen Liu](https://github.com/StevenLiuWen),
[Xin Chen](https://chenxin.tech/),
[Xianfang Zeng](https://neuralcarver.github.io/michelangelo),
[Rui Wang](https://neuralcarver.github.io/michelangelo),
[Pei Cheng](https://neuralcarver.github.io/michelangelo),
[Bin Fu](https://neuralcarver.github.io/michelangelo),
[Tao Chen](https://eetchen.github.io),
[Gang Yu](https://www.skicyyu.org) and
[Shenghua Gao](https://sist.shanghaitech.edu.cn/sist_en/2020/0814/c7582a54772/page.htm)<br/>
### [Project Page](https://neuralcarver.github.io/michelangelo/) | [Arxiv](https://neuralcarver.github.io/michelangelo/) | [Paper](https://neuralcarver.github.io/michelangelo/static/paper.pdf)<br/>

https://github.com/NeuralCarver/Michelangelo/assets/37449470/123bae2c-fbb1-4d63-bd13-0e300a550868

Visualization of the 3D shape produced by our framework, which splits into triplets with a conditional input on the left, a normal map in the middle, and a triangle mesh on the right. The generated 3D shapes semantically conform to the visual or textural conditional inputs.<br/>

### Abstract
We present a novel _alignment-before-generation_ approach to tackle the challenging task of generating general 3D shapes based on 2D images or texts. Directly learning a conditional generative model from images or texts to 3D shapes is prone to producing inconsistent results with the conditions because 3D shapes have an additional dimension whose distribution significantly differs from that of 2D images and texts. To bridge the domain gap among the three modalities and facilitate multi-modal-conditioned 3D shape generation, we explore representing 3D shapes in a shape-image-text-aligned space. Our framework comprises two models: a Shape-Image-Text-Aligned Variational Auto-Encoder (SITA-VAE) and a conditional Aligned Shape Latent Diffusion Model (ASLDM). The former model encodes the 3D shapes into the shape latent space aligned to the image and text and reconstructs the fine-grained 3D neural fields corresponding to given shape embeddings via the transformer-based decoder. The latter model learns a probabilistic mapping function from the image or text space to the latent shape space. Our extensive experiments demonstrate that our proposed approach can generate higher-quality and more diverse 3D shapes that better semantically conform to the visual or textural conditional inputs, validating the effectiveness of the shape-image-text-aligned space for cross-modality 3D shape generation.



## 📰 News
- [2023/6/29] Upload paper and init project
