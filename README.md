# Audio Caption Generation System for the Visually Impaired

## Overview
This project implements an **image captioning model** using **deep learning** to generate **audio descriptions** for visually impaired users. The model is based on **VGG16 for feature extraction** and **LSTM for text generation**. The generated captions are converted to speech using a **text-to-speech (TTS) system**.

## Dataset
The model is trained on the **Flickr8k Dataset**, which contains 8,000 images with multiple human-annotated captions.
- **Dataset Link**: [Flickr8k Dataset on Kaggle](https://www.kaggle.com/datasets/adityajn105/flickr8k)

## Features
- **VGG16-based feature extraction** for images
- **LSTM-based caption generation**
- **Text-to-Speech (TTS) integration** for accessibility
- **Pretrained word embeddings** for better text representation
- **Keras and TensorFlow implementation**

## Installation
Clone the repository:
```bash
git clone https://github.com/yourusername/audio-caption-generation.git
cd audio-caption-generation
```
Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
Run the Jupyter Notebook:
```bash
jupyter notebook Image_Caption_Generation.ipynb
```

## Model Architecture
1. **VGG16 Model** (Pretrained on ImageNet) extracts **4096-dimensional** image features.
2. **LSTM Model** generates captions from extracted features.
3. **Text-to-Speech Module** converts generated text into audio.

## Results
The model achieves **high-quality caption generation**, with accurate descriptions aligned with image content.

## Future Improvements
- Train on larger datasets (e.g., MS-COCO)
- Fine-tune transformer-based models (e.g., GPT-4, BLIP-2)
- Improve caption fluency with attention mechanisms
