# Poetry and Music Generation from Images: Thesis Project

Welcome to the repository for the thesis project, "Poetry and Music Generation from Images using NLP and CV Tools." This project encompasses the development of several models leveraging advancements in Natural Language Processing (NLP) and Computer Vision (CV).

## Models Developed

### 1. Image to Poetry Model
The primary model, which demonstrates the highest cosine similarity in style matching and closely corresponds with the input image, can be accessed through this link: 
- [vit-rugpt3-large-poetry-ft](https://huggingface.co/AnyaSchen/vit-rugpt3-large-poetry-ft)

### 2. Poet-Specific Models
The following models have been specifically designed for individual poets. These models demonstrate slightly less correlation between the generated poetry and the input image compared to the main model. However, they offer lower memory usage due to specific configurations and offer poet-specific outputs:
- [Esenin Model](https://huggingface.co/AnyaSchen/vit-rugpt3-medium-esenin)
- [Pushkin Model](https://huggingface.co/AnyaSchen/vit-rugpt3-medium-pushkin)
- [Blok Model](https://huggingface.co/AnyaSchen/vit-rugpt3-medium-blok)
- [Tyutchev Model](https://huggingface.co/AnyaSchen/vit-rugpt3-medium-tyutchev)
- [Mayakovsky Model](https://huggingface.co/AnyaSchen/vit-rugpt3-medium-mayak)

### 3. Keyword to Poetry Models
These models are designed to generate poetry based on input keywords:
- [Medium Configuration](https://huggingface.co/AnyaSchen/rugpt3-medium-key2poetry)
- [Large Configuration](https://huggingface.co/AnyaSchen/rugpt3-large-key2poetry)

### 4. Datasets
As part of this thesis project, the following datasets have been compiled:
- [Image2Poetry Dataset](https://huggingface.co/datasets/AnyaSchen/image2poetry_ru)
- [Keywords2Poetry Dataset](https://huggingface.co/datasets/AnyaSchen/russian_poetry_with_keywords)
