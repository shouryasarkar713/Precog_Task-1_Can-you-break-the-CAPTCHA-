# Precog_Task-1_Can-you-break-the-CAPTCHA

## Table of Contents
1. [Project Overview](#project-overview)
2. [Directory Structure](#directory-structure)
3. [Dependencies](#dependencies)
4. [Installation](#installation)
5. [How to Run the Project](#how-to-run-the-project)
6. [Usage](#usage)
7. [License](#license)

## Project Overview

Optical Character Recognition (OCR) has traditionally relied on handcrafted
features. With the advent of deep learning, neural network–based methods have
greatly improved performance on challenging problems such as CAPTCHA-
breaking and reading text from noisy images. This project is structured into
several tasks that progressively build an OCR pipeline:
• Task 0: Dataset synthesis (creating images with rendered words under
different conditions).
• Task 1: Classification (training a neural network to classify word images
into one of 100 classes).
• Task 2: Generation (designing a model that extracts the text from
an image, handling variable-length sequences using a CNN+RNN+CTC
architecture).
• Task 3 (Bonus): Incorporating a background-based transforma-
tion rule—if the background is red, the word is rendered reversed, but the
target output is always the forward (correct) word. This requires special
handling during both training and inference.
Each task builds on the previous ones and requires careful preprocessing,
model design, training, and evaluation

## Directory Structure


