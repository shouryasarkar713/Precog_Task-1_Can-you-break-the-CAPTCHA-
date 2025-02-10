# Precog_Task-1_Can-you-break-the-CAPTCHA

## Table of Contents
1. [Project Overview](#project-overview)
3. [Dependencies](#dependencies)
5. [How to Run the Project](#how-to-run-the-project)
6. [Usage](#usage)

## Project Overview

Optical Character Recognition (OCR) has traditionally relied on handcrafted features. With the advent of deep learning, neural network-based methods have greatly improved performance on challenging problems such as CAPTCHA-breaking and reading text from noisy images. 

This project is structured into several tasks that progressively build an OCR pipeline:

- **Task 0**: *Dataset Synthesis* – Create images with rendered words under different conditions to form the dataset.
- **Task 1**: *Classification* – Train a neural network to classify word images into one of 100 classes.
- **Task 2**: *Generation* – Design a model that extracts the text from an image, handling variable-length sequences using a CNN+RNN+CTC architecture.
- **Task 3 (Bonus)**: *Background-based Transformation Rule* – If the background is red, the word is rendered reversed, but the target output remains the correct word. Special handling during both training and inference is required.

Each task builds on the previous ones and involves careful preprocessing, model design, training, and evaluation. The ultimate goal of this project is to create a robust OCR pipeline capable of handling diverse and noisy text-image data.

## Dependencies

This project uses the following libraries:

- **numpy**: For numerical operations and array manipulations.
- **pandas**: To handle CSV files and dataframes.
- **nltk**: To access the NLTK words corpus for selecting random words.
- **matplotlib**: To visualize images (if needed) and to use its `font_manager` for retrieving system fonts.
- **Pillow**: For image creation and manipulation.
- **opencv-python**: To add Gaussian noise to images (via `cv2`).
- **torch & torchvision**: For building and training deep neural networks (used across tasks for classification and OCR models).
- **scikit-learn**: (Optional) For any additional machine learning utilities.

You can install these dependencies by running:

```bash
pip install -r requirements.txt



