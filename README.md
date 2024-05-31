
### Model Introduction
LLaMA-E is meticulously crafted for e-commerce authoring tasks, incorporating specialized features to excel in generating product descriptions, advertisements, and other related content.

### Usage
Inference using Huggingface transformers on NVIDIA GPUs. Requirements tested on python 3.10:
```
python inference.py --load_8bit --base_model 'meta-llama/Llama-2-7b-hf' --lora_weights XXXXXX
```

```
***Instruction: Where can I buy the handmade jewellery?
***Response: Etsy, NOVICA, UncommonGoods, World Market, and Global Crafts offer unique handmade jewelry from artisans worldwide.

***Instruction: Create an attractive advertisement for the Christmas sale of the following product.
***Input: Custom Photo Music Plaque,Personalized Photo Frame,Album Cover Song Plaque,Music Photo Name Night Lamp,Photo and Music Gift, Music Prints
***Response: Personalize your music space with a Custom Photo Music Plaque. Add your favorite photo and song lyrics to create a unique gift for music lovers.
```

### License
The model released here is under the [Llama-2 LICENSE][license] to ensure more flexible accessibility; please adhere to the corresponding licence.

[license]: <https://ai.meta.com/llama/license/#/>
[paper]: <https://arxiv.org/abs/2308.04913#/>
