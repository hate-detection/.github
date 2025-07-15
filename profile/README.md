<h1 align="center">BOLI: Bad and Offensive Language Identification</h1>
<p align="center">
  <a href="#introduction">Introduction</a> •
  <a href="#overview">Overview</a> •
  <a href="#list-of-repos">List of Repos</a>
</p>

<br>

# Introduction

🙋‍♀️ Welcome to hate-detection. This organisation serves as a collection for all the code I have written for my Masters Thesis (MSc Cyber Security Module CYM500). It is currently under development!

👩‍💻 There are several repositories here. Some will be private due to the Data Protection Policies. [Email me](mailto:shrutipriya44@gmail.com) to get details about the private repos.

🍿 I wonder what would Mirza Ghalib think if we brought him to life today and told him man has set foot on the moon, he would probably be sad—हमने चाँद को नापाक कर दिया

## Overview

Here's a high-level layout of the project alongwith the implemented tech stack. 

![High-level layout](./high-level-layout.png)

## List of repos

| Repo | Status | Objetive|
|:------|:------|:------|
|[preprocessing](https://github.com/hate-detection/preprocessing)|Private|Prepocessing Pipeline for dataset in 2 phases. Current staus Private due to Data Usage Policies and requirements by dataset authors.
|[training](https://github.com/hate-detection/training)|Public|Fine-tuning the BERT-based model MuRIL for Sentiment Analysis in code-mixed Hinglish. Currently under development. I will add code for training `LoRA` Adapters instead of the entire model.
|[model-inference-api](https://github.com/hate-detection/model-inference-api)|Public|Serving the model through API for inference.
|[boli-app](https://github.com/hate-detection/boli-app)|Public|Frontend web-application for Machine Learning Model.
