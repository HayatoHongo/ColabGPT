# **Everyones_nanoGPT fill-in-the-blank এক্সপেরিমেন্ট**

🌐 ভাষা বেছে নিন /
<img src="https://flagcdn.com/24x18/jp.png" width="20"/> [日本語](https://github.com/HayatoHongo/Everyones_nanoGPT/tree/ja) |
<img src="https://flagcdn.com/24x18/cn.png" width="20"/> [中文](https://github.com/HayatoHongo/Everyones_nanoGPT/tree/ch) /
<img src="https://flagcdn.com/24x18/bd.png" width="20"/> [বাংলা](https://github.com/HayatoHongo/Everyones_nanoGPT/tree/bn) |
[Others](README.otherlanguages.md)

<br>

> ChatGPT ভালোবাসেন, নিজেরটা বানাতে চান?<br>
> এখানে পুরো গাইড! আপনি “Hello” লিখলেন, ও বলল “How can I help you today?”<br>
> বুঝলেন—সবই গাণিতিক কৌশল! তখন বুকের মধ্যে টানটান উত্তেজনা। ঘুমও আসে না।<br>
> এটাই ডিপ লার্নিংয়ের দুনিয়া। আর পেছনে ফেরা নেই।<br>
> আমি এই গাইড ট্রেনের ছোট্ট সিটে বসে, স্কুলে যেতে যেতে লিখেছিলাম।<br>
> প্রতিবার ছাত্রদের উৎসাহিত কমেন্ট পড়লে,<br>
> মনে হয়, সেই ছোট্ট সিটের দিনগুলোর ছিল আসলেই অনেক মূল্য।<br>  

## **ডেমো আউটপুট**
![nanoGPT_demo_output](assets/Everyones_nanoGPT_demo_output.png)

চলো, nano-GPT মডেল বানাই!😎<br>
এই এক্সপেরিমেন্টে আছে পরিষ্কার ব্যাখ্যা আর **১০০+ ফিল-ইন-দ্য-ব্ল্যাঙ্ক প্রশ্ন!🫨** <br>
যারা শিখতে আগ্রহী, তাদের জন্য একেবারে দারুণ সুযোগ।<br>
প্রয়োজনীয় বিষয়গুলো জানা থাকলে ১২–১৮ ঘণ্টায় শেষ করা সম্ভব।<br>
সবকিছু Google Colab-এ চলে। এই এক্সপেরিমেন্টের ভিত্তি [Andrej Karpathy’র nano-GPT](https://colab.research.google.com/drive/1JMLa53HDuA-i7ZBmqV7ZnA3c_fvtXnx-?usp=sharing)। <br>
তাঁর প্রতি আমার গভীর কৃতজ্ঞতা।


## বিষয়বস্তু তালিকা
এই [notebook translator-এ](README.otherlanguages.md) পুরো এক্সপেরিমেন্ট পৃথিবীর প্রায় যেকোনো ভাষায় অনুবাদ করা যায়।

🌐 ভাষা বেছে নিন /
<img src="https://flagcdn.com/24x18/jp.png" width="20"/> [日本語](https://github.com/HayatoHongo/Everyones_nanoGPT/tree/ja) |
<img src="https://flagcdn.com/24x18/cn.png" width="20"/> [中文](https://github.com/HayatoHongo/Everyones_nanoGPT/tree/ch) /
<img src="https://flagcdn.com/24x18/bd.png" width="20"/> [বাংলা](https://github.com/HayatoHongo/Everyones_nanoGPT/tree/bn) |
[Others](README.otherlanguages.md)


| অধ্যায়  | আনুমানিক সময় | বাংলা 🇧🇩 |
|---|---|---|
| Chapter 00: Start Tutorial      | ১-২ ঘণ্টা    | [![কলাবে খুলুন](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/bn/notebooks/todo/Everyones_nanoGPT_colab_Chapter00_todo_bn.ipynb) |
| Chapter 01: Dataloader         | ১-২ ঘণ্টা    | [![কলাবে খুলুন](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/bn/notebooks/todo/Everyones_nanoGPT_colab_Chapter01_todo_bn.ipynb) |
| Chapter 02: TokenEmbedding     | ০.৫-১ ঘণ্টা  | [![কলাবে খুলুন](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/bn/notebooks/todo/Everyones_nanoGPT_colab_Chapter02_todo_bn.ipynb) |
| Chapter 03: PositionEmbedding  | ০.৫-১ ঘণ্টা  | [![কলাবে খুলুন](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/bn/notebooks/todo/Everyones_nanoGPT_colab_Chapter03_todo_bn.ipynb) |
| Chapter 04: EmbeddingModule    | ০.৫-১ ঘণ্টা  | [![কলাবে খুলুন](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/bn/notebooks/todo/Everyones_nanoGPT_colab_Chapter04_todo_bn.ipynb) |
| Chapter 05: LayerNorm          | ১-২ ঘণ্টা    | [![কলাবে খুলুন](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/bn/notebooks/todo/Everyones_nanoGPT_colab_Chapter05_todo_bn.ipynb) |
| Chapter 06: AttentionHead      | ৩-৪ ঘণ্টা    | [![কলাবে খুলুন](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/bn/notebooks/todo/Everyones_nanoGPT_colab_Chapter06_todo_bn.ipynb) |
| Chapter 07: MultiHeadAttention | ১-২ ঘণ্টা    | [![কলাবে খুলুন](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/bn/notebooks/todo/Everyones_nanoGPT_colab_Chapter07_todo_bn.ipynb) |
| Chapter 08: FeedForward        | ১-২ ঘণ্টা    | [![কলাবে খুলুন](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/bn/notebooks/todo/Everyones_nanoGPT_colab_Chapter08_todo_bn.ipynb) |
| Chapter 09: TransformerBlock   | ০.৫-১ ঘণ্টা  | [![কলাবে খুলুন](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/bn/notebooks/todo/Everyones_nanoGPT_colab_Chapter09_todo_bn.ipynb) |
| Chapter 10: VocabularyLogits   | ০.৫-১ ঘণ্টা  | [![কলাবে খুলুন](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/bn/notebooks/todo/Everyones_nanoGPT_colab_Chapter10_todo_bn.ipynb) |
| Chapter 11: nanoGPT| ১-২ ঘণ্টা    | [![কলাবে খুলুন](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/bn/notebooks/todo/Everyones_nanoGPT_colab_Chapter11_todo_bn.ipynb) |
| Chapter 12: Trainer            | ১-২ ঘণ্টা    | [![কলাবে খুলুন](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HayatoHongo/Everyones_nanoGPT/blob/bn/notebooks/todo/Everyones_nanoGPT_colab_Chapter12_todo_bn.ipynb) |





## **টেনসর ম্যাপ**
**তোমাকেই এই টেনসর ম্যাপ বানাতে হবে!** প্রচুর হিন্ট আছে, দুশ্চিন্তা কোরো না।<br>
[Canva-তে nanoGPT মডেলের ফুল রেজুলুশন টেনসর ম্যাপ দেখুন।](https://www.canva.com/design/DAGskS8QP6k/1zs7IklaMrB_LncHn2I8pA/edit?utm_content=DAGskS8QP6k&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)<br>

![Everyones TensorMap](assets/Everyones_nanoGPT_TensorMap_answer.png)

## **প্রয়োজনীয়তা**

**বোঝাপড়া**  
- ম্যাট্রিক্স গুণ ও যোগফল বোঝা  
- গড় ও বৈচিত্র্য বোঝা  
- ResNet-এর রেসিডুয়াল সংযোগ বোঝা  
- Word2Vector কীভাবে কাজ করে তা জানা  
<br>  
<br>  

**অভিজ্ঞতা**  
- PyTorch দিয়ে MNIST ডিজিট রিকগনিশন মডেল বানানোর অভিজ্ঞতা।
- ডিজিট রিকগনিশন মডেলে cross-entropy লস ফাংশন ব্যবহার করেছেন  
- mini-batch প্রসেসিং ও batch normalization ইমপ্লিমেন্ট করেছেন  
- autoencoder বা VAE ইমপ্লিমেন্ট করেছেন

যারা কখনও PyTorch বা প্রোগ্রামিং করেননি, তাদের জন্য ২০২৫.৮.৩০-এর মধ্যে মজার, একেবারে শুরু থেকে শেখার এক্সপেরিমেন্ট বের করার চেষ্টা চলছে।

## **মডেল**

এখানে bigram মডেল ব্যবহার করা হয়েছে, যেখানে প্রতিটি token মানে শুধু একটা অক্ষর।<br> 
ভেতরের গঠনও খুবই সহজ।<br>  
প্রশিক্ষণ ডেটাসেট হিসেবে ব্যবহার করা হয়েছে Shakespeare-এর লেখা। পুরনো হওয়ায়, এগুলো কপিরাইটমুক্ত।<br>

আসল GPT-2-র তুলনায় এটি বেশ সহজ। কিন্তু, GPT শেখার মূল টেকনিকগুলো আয়ত্ত করার জন্য এখান থেকেই শুরু করা সেরা।<br>  
মাত্র ২-৪ মিনিট CPU-তে ট্রেনিং (১৬GB RAM পিসি হলে)–এ Shakespeare-এর মত টেক্সট বানানো যাবে!<br> 
দেখলেই মুগ্ধ হয়ে যাবা!<br>

## **ডেভেলপমেন্ট এনভায়রনমেন্ট**

যতটা সম্ভব সহজ রাখতে চাইলে, সব এক্সাম্পল Google Colab-এ চালাও।<br>

তবে, Google Colab-এ checkbox মার্ক সংরক্ষণ হয় না।<br>
প্রগতি ট্র্যাক করতে চাইলে, VS Code খুব ভালো।<br> 
একটু একটু করে, ৩০ মিনিট করে কাজ করতে পছন্দ করলেও এটা বেশ সুবিধাজনক।<br> 
তখন, এই রিপো-টা ফর্ক করে নিজের কম্পিউটারে ক্লোন করো।<br>

Python 3.12 আর PyTorch 2.6.0 সবচেয়ে ভালো চলে, তবে বেশিরভাগ ভার্সন ঠিকই কাজ করে।<br> 
সাধারণত, তোমার ইন্সটল করা PyTorch চলবে।<br>
সমস্যা হলে, `requirements.txt` দিয়ে ভার্চুয়াল এনভায়রনমেন্ট সেটআপ করতে পারো।<br>
বা, Docker Desktop ব্যবহার করলে, সঙ্গে দেয়া `Dockerfile` আর Dev Container এক্সটেনশনেও সহজে চালানো যাবে।

## **About Project EveryonesAI**

![EveryonesAI Logo](assets/EveryonesAI_logo.png)
![EveryonesAI Goal](assets/EveryonesAI_goal.png)
![EveryonesAI Idea](assets/EveryonesAI_idea.png)
![EveryonesAI Prerequites](assets/EveryonesAI_prerequites.png)
![EveryonesAI Plan](assets/EveryonesAI_plan.png)