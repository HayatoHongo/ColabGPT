# **Everyones_nanoGPT - Build LLM from scratch on Colab**

<div align="center">
  <img src="assets/Google_Colaboratory_SVG_Logo.svg.png" alt="Google Colab Logo" width="150" style="margin-bottom:0;">
  <h3 style="margin-top:1px;">Support Free Google Colab account!</h3>
</div>

🌐 Select Language /
<img src="https://flagcdn.com/24x18/jp.png" width="20"/> [日本語](https://github.com/HayatoHongo/Everyones_nanoGPT/tree/ja) |
<img src="https://flagcdn.com/24x18/cn.png" width="20"/> [中文](https://github.com/HayatoHongo/Everyones_nanoGPT/tree/ch) /
<img src="https://flagcdn.com/24x18/bd.png" width="20"/> [বাংলা](https://github.com/HayatoHongo/Everyones_nanoGPT/tree/bn) |
[Others](README.otherlanguages.md)
<br>

> This is a complete guide for those who love ChatGPT and want to build their own.<br>
> You type "Hello," and it replies, "How can I help you today?"<br>
> When you realize this runs on simple math, your heart races. You cannot sleep.<br>
> Welcome to deep learning. There is no way back.<br>
> I wrote this guide on the train to school, squeezed into a tiny seat on the Nanboku Line.<br>
> Every time I read an excited comment from a student,<br>
> I feel that those days in that tiny seat had a big meaning.<br>  

## **Demo output**
![nanoGPT_demo_output](assets/Everyones_nanoGPT_demo_output.png)

Let's make nano-GPT model!😎<br>
This tutorial gives you clear explanations and **over 100 fill-in-the-blank questions!🫨** <br>
Perfect for ealry birds who want to change their interests into real growth.<br>
If you meet the prerequisites, you can finish in 12–18 hours.<br>
Everything runs in Google Colab. This tutorial is based on [Andrej Karpathy’s nano-GPT](https://colab.research.google.com/drive/1JMLa53HDuA-i7ZBmqV7ZnA3c_fvtXnx-?usp=sharing). <br>
I'd like to express my deepest gratitude for his work.


## Table of Contents
You can translate the notebooks to almost any language on earth with this [notebook translator.](README.otherlanguages.md)<br>
I couldn’t translate the images with the tool, and I’d really appreciate your help translating the [images](https://www.canva.com/design/DAGw0J7yCsE/xdcjITCHd02iLSUMw8wlXA/edit?utm_content=DAGw0J7yCsE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton).<br>


🌐 Select Language /
<img src="https://flagcdn.com/24x18/jp.png" width="20"/> [日本語](https://github.com/HayatoHongo/Everyones_nanoGPT/tree/ja) |
<img src="https://flagcdn.com/24x18/cn.png" width="20"/> [中文](https://github.com/HayatoHongo/Everyones_nanoGPT/tree/ch) /
<img src="https://flagcdn.com/24x18/bd.png" width="20"/> [বাংলা](https://github.com/HayatoHongo/Everyones_nanoGPT/tree/bn) |
[Others](README.otherlanguages.md)


| Chapter  | Estimated Time | English 🇺🇸 |
|---|---|---|
| Chapter 00: Start Tutorial      | 1-2 hour    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/main/notebooks/todo/Everyones_nanoGPT_colab_Chapter00_todo.ipynb) |
| Chapter 01: Dataloader         | 1-2 hour    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/main/notebooks/todo/Everyones_nanoGPT_colab_Chapter01_todo.ipynb) |
| Chapter 02: TokenEmbedding     | 0.5-1 hour  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/main/notebooks/todo/Everyones_nanoGPT_colab_Chapter02_todo.ipynb) |
| Chapter 03: PositionEmbedding  | 0.5-1 hour  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/main/notebooks/todo/Everyones_nanoGPT_colab_Chapter03_todo.ipynb) |
| Chapter 04: EmbeddingModule    | 0.5-1 hour  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/main/notebooks/todo/Everyones_nanoGPT_colab_Chapter04_todo.ipynb) |
| Chapter 05: LayerNorm          | 1-2 hour    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/main/notebooks/todo/Everyones_nanoGPT_colab_Chapter05_todo.ipynb) |
| Chapter 06: AttentionHead      | 3-4 hour    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/main/notebooks/todo/Everyones_nanoGPT_colab_Chapter06_todo.ipynb) |
| Chapter 07: MultiHeadAttention | 1-2 hour    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/main/notebooks/todo/Everyones_nanoGPT_colab_Chapter07_todo.ipynb) |
| Chapter 08: FeedForward        | 1-2 hour    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/main/notebooks/todo/Everyones_nanoGPT_colab_Chapter08_todo.ipynb) |
| Chapter 09: TransformerBlock   | 0.5-1 hour  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/main/notebooks/todo/Everyones_nanoGPT_colab_Chapter09_todo.ipynb) |
| Chapter 10: VocabularyLogits   | 0.5-1 hour  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/main/notebooks/todo/Everyones_nanoGPT_colab_Chapter10_todo.ipynb) |
| Chapter 11: nanoGPT| 1-2 hour    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/main/notebooks/todo/Everyones_nanoGPT_colab_Chapter11_todo.ipynb) |
| Chapter 12: Trainer            | 1-2 hour    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/main/notebooks/todo/Everyones_nanoGPT_colab_Chapter12_todo.ipynb) |


## **Tensor Map**
**You must create the following Tensor Map by yourself!** There are plenty of hints, so don't worry.<br>
[View the full-resolution Tensor Map of nanoGPT model on Canva.](https://www.canva.com/design/DAGskS8QP6k/1zs7IklaMrB_LncHn2I8pA/edit?utm_content=DAGskS8QP6k&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)<br>

![Everyones TensorMap](assets/Everyones_nanoGPT_TensorMap_answer.png)

## **Prerequisites**

**Understanding**  
- Understand matrix multiplication and addition  
- Understand mean and variance  
- Understand ResNet’s residual connections  
- Understand Word2Vector  
<br>  
<br>  

**Experience**  
- Have built an MNIST digit recognition model using Pytorch’s.
- Have used cross-entropy as a loss function in digit recognition models like the above  
- Have implemented mini-batch processing and batch normalization  
- Have implemented an autoencoder or VAE

We are also working hard to release fun, entry-level tutorials for those who have never used PyTorch or programming by 2025.8.30.

## **Model**

It uses a bigram model, where each token is just one character.<br> 
Also, the internal structure is very simple.<br>  
The training text dataset is Shakespeare’s writings. Since they are very old, they are copyright-free.<br>

Compared to the real GPT-2, it’s quite basic. But start here to master the GPT basics.<br>  
In just 2-4 minutes of CPU training (on a 16GB memory PC), you can generate Shakespeare-like text.<br> 
It’s guaranteed to impress!<br>

## **Development Environment**

To keep setup simple, try running all examples in Google Colab.<br>

However, Google Colab doesn't save the checkbox marks.<br>
If you want to save your progress with checkbox marks, VS Code is a great choice.<br> 
It’s also handy if you like to work in small bursts, such as 30 minutes at a time.<br> 
In that case, fork and clone this repo to your own computer.<br>

Python 3.12 and PyTorch 2.6.0 work best, but most versions are fine.<br> 
Usually, your installed PyTorch will just work.<br>
 If you hit issues, you can set up a virtual environment using `requirements.txt`.<br>
Or, if you use Docker Desktop, you can use the included `Dockerfile` and Dev Container extension for an even more stable setup.

## **About Project EveryonesAI**

![EveryonesAI Logo](assets/EveryonesAI_logo.png)
![EveryonesAI Goal](assets/EveryonesAI_goal.png)
![EveryonesAI Idea](assets/EveryonesAI_idea.png)
![EveryonesAI Prerequites](assets/EveryonesAI_prerequites.png)
![EveryonesAI Plan](assets/EveryonesAI_plan.png)