<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Transformer](#transformer)
- [Vision Transformer](#vision-transformer)
- [Switch Transformer](#switch-transformer)

<!-- /code_chunk_output -->

This repository contains the code for the different neural network architectures implemented in PyTorch. Focus on the Module parts, each jupyter notebook is self-contained.

> [!NOTE]
> The code in this repository not only provides the implementation of the neural network architectures. But not provided the training and validation code. You can use the code to build your own training and validation code.

---

# Transformer

- Code: [Jupyter Notebook](https://github.com/git-ai-zyy/Pytorch-DeepLearning/blob/main/Transformer.ipynb)
- Blog: [Transformer](https://yuyangs-project.super.site/another-page)
- Recommend: ⭐️⭐️⭐️⭐️⭐️ (Highly Recommend)
- Description:
  - Transformer is a model architecture that is based solely on attention mechanisms, dispensing with recurrence and convolutions entirely.
  - It is one of the most popular and important model architectures in the field of natural language processing (NLP) and the foundation of the state-of-the-art models.
- Reference:
  - [Attention is All You Need](https://arxiv.org/abs/1706.03762)
  - [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
  - [The Annotated Transformer](https://nlp.seas.harvard.edu/annotated-transformer/)

---

# Vision Transformer

- Code: [Jupyter Notebook](https://github.com/git-ai-zyy/Pytorch-DeepLearning/blob/main/VisionTransformer.ipynb)
- Blog: [Vision Transformer](https://yuyangs-project.super.site/another-pagess)
- Recommend: ⭐️⭐️⭐️⭐️⭐️ (Highly Recommend)
- Description:
  - Vision Transformer (ViT) is a transformer-based model for image recognition.
  - It applies the transformer architecture to image classification by treating images as sequences of patches.
- Reference:
  - [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)

# Switch Transformer

- Code: [Jupyter Notebook](https://github.com/git-ai-zyy/Pytorch-DeepLearning/blob/main/SwitchTransformer.ipynb)
- Recommend: ⭐️⭐️⭐️
- Description:
  - Switch Transformer is a model architecture that is based on the transformer architecture.
  - It introduces a new mechanism called the switch mechanism to dynamically route information between local and global attention.
  - It is the base of the DeepSeek model
- Reference:
  - [Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity](https://arxiv.org/abs/2101.03961)
