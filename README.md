---
license: llama2
---

<div align="center">
  <a href="https://huggingface.co/DSMI/LLaMA-E/tree/main#/">
    <img src="https://huggingface.co/DSMI/LLaMA-E/resolve/main/LLaMA-E.png?download=true" alt="LLaMA-E">
  </a>
  <h1>LLaMA-E</h1>
</div>

### Model Introduction
LLaMA-E is meticulously crafted for e-commerce authoring tasks, incorporating specialized features to excel in generating product descriptions, advertisements, and other related content, as outlined in https://arxiv.org/abs/2308.04913#/.

### Usage
Inference using Huggingface transformers on NVIDIA GPUs. Requirements tested on python 3.10:
```
python inference.py --load_8bit --base_model 'meta-llama/Llama-2-7b-hf' --lora_weights 'DSMI/LLaMA-E'
```

```
***Instruction: Where can I buy the handmade jewellery?
***Response: Etsy, NOVICA, UncommonGoods, World Market, and Global Crafts offer unique handmade jewelry from artisans worldwide.

***Instruction: Create an attractive advertisement for the Christmas sale of the following product.
***Input: Custom Photo Music Plaque,Personalized Photo Frame,Album Cover Song Plaque,Music Photo Name Night Lamp,Photo and Music Gift, Music Prints
***Response: Personalize your music space with a Custom Photo Music Plaque. Add your favorite photo and song lyrics to create a unique gift for music lovers.
```

### Citation
If you find our work helpful, please consider [citing][paper] the following papers.

```bibtex
@article{shi2023llama,
  title={LLaMA-E: Empowering E-commerce Authoring with Multi-Aspect Instruction Following},
  author={Shi, Kaize and Sun, Xueyao and Wang, Dingxian and Fu, Yinlin and Xu, Guandong and Li, Qing},
  journal={arXiv preprint arXiv:2308.04913},
  year={2023}
}
```

### License
The model released here is under the [Llama-2 LICENSE][license] to ensure more flexible accessibility; please adhere to the corresponding licence.

### Acknowledgements
Our code for the inference is based on the [tloen][tloen].

[license]: <https://ai.meta.com/llama/license/#/>
[paper]: <https://arxiv.org/abs/2308.04913#/>
[tloen]: <https://huggingface.co/tloen/alpaca-lora-7b#/># LLaMA-E
