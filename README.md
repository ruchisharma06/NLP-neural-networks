# NLP-neural-networks

The project focuses on training neural networks for French-to-English translation using sequence-to-sequence (seq2seq) models. The primary reference is the PyTorch tutorial on sequence-to-sequence networks and attention mechanisms.

## French-to-English Translation Using Seq2Seq Models

This repository contains code for training neural networks to perform French-to-English translation using sequence-to-sequence (seq2seq) models with and without attention mechanisms. The project is based on the PyTorch tutorial "Translation with a Sequence to Sequence Network and Attention."

## Project Overview

The project involves:

1. **Data Preparation**
2. **Building Seq2Seq Models**
3. **Implementing Attention Mechanisms**
4. **Training and Evaluating Models**
5. **Visualizing Attention Weights**
6. **Inference with Trained Models**

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Images Side by Side</title>
    <style>
        .image-container {
            display: flex;
            justify-content: center; /* Aligns the images in the center */
            gap: 10px; /* Optional: Adds space between the images */
        }
        .image-container img {
            max-width: 100%;
            height: auto; /* Maintains aspect ratio */
        }
    </style>
</head>
<body>
    <div class="image-container">
        <img src="https://github.com/ruchisharma06/NLP-neural-networks/assets/116240606/4debb142-b809-4de2-94e1-c4b86220f243" alt="First Image" width="300">
        <img src="https://github.com/ruchisharma06/NLP-neural-networks/assets/116240606/05f584c6-b7cd-4302-9b22-7264cc5c3cc5" alt="First Image" width="300">

    </div>
</body>
</html>

## Installation

To run this project, ensure you have the following dependencies installed:

```bash
pip install torch numpy matplotlib

## Running the Code
Prepare Data:

Ensure the dataset is in the correct format with translation pairs separated by tabs or commas.

Build and Train Models:

The code includes three model variants:

Seq2Seq without Attention
Seq2Seq with Additive Attention (Bahdanau)
Seq2Seq with Dot-Product Attention (Luong)
Training:

Train the models for 20 and 50 epochs using the provided training script.

Evaluate:

Evaluate the models using validation loss and visualize the results.

Inference:

Perform inference on provided French sentences and compare the outputs with expected English translations.




