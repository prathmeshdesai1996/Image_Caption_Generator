
# Image Captioning

This repository contains a Streamlit app for generating captions for images using transformer models. The app allows users to upload an image or provide an image URL and select the number of captions to generate using different transformer models.

- [Huggingface Webapp](https://huggingface.co/spaces/pd96/image_caption_generator)
- [Streamlit Webapp](https://prathmeshdesai1996-image-caption-generator-app-okeelm.streamlit.app/)

## Notebook

The `image_captioning.ipynb` notebook demonstrates the usage of different transformer models from Hugging Face for generating captions for images. It showcases both conditional and unconditional image captioning using the selected models. The notebook uses the following transformer models:

- Model 1: `ydshieh/vit-gpt2-coco-en`
- Model 2: `Salesforce/blip-image-captioning-base`
- Model 3: `Salesforce/blip-image-captioning-large`

## Installation
To use this application, you need to install the following dependencies:
```
pip install -r requirements.txt
```

## Usage

1. Run the Streamlit app:
```
streamlit run app.py
```
2. The app will launch in your default web browser.
3. Choose the image source: either upload an image or provide an image URL.
4. If you choose to upload an image, click on the "Upload an image" button and select the image file from your local machine.
5. If you choose to provide an image URL, enter the URL in the text input field.
6. Once the image is loaded, use the slider to select the number of captions to generate (1, 2, or 3).
7. Click on the "Generate Caption" button to generate the captions using the selected transformer models.
8. The generated captions will be displayed below the image.

