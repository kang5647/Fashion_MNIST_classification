# Fashion MNIST with Transformers

## Objective
The goal of this project is to explore the application of Transformer models on the Fashion MNIST dataset, a collection of 28x28 grayscale images of 10 fashion categories. We start by establishing a baseline using a Convolutional Neural Network (CNN) and then progressively experiment with more sophisticated Transformer-based models. We aim to enhance the model's performance first through fine-tuning a pre-trained Google Vision Transformer (ViT) and then employing a novel fine-tuning technique known as visual prompting.

## Project Structure

1. **CNN Baseline Model**
   - **Notebook**: [01_fashionmnist_base_cnn.ipynb](01_fashionmnist_base_cnn.ipynb)
   - **Description**: This notebook develops a CNN to serve as a baseline for comparison with Transformer models.

2. **Base Transformer Model**
   - **Notebook**: [02_fashionmnist_base_transformer.ipynb](02_fashionmnist_base_transformer.ipynb)
   - **Description**: Implementation of a basic Transformer model to understand its efficacy on image classification tasks for Fashion MNIST.

3. **Fine-Tuning Pre-trained Transformer (ViT)**
   - **Notebook**: [03_fashionmnist_finetune_transformer.ipynb](03_fashionmnist_finetune_transformer.ipynb)
   - **Description**: Applies fine-tuning to a pre-trained Google Vision Transformer on the Fashion MNIST dataset to leverage learned features from larger datasets.

4. **Visual Prompt Tuning of Pre-trained Transformer**
   - **Notebook**: in progress
   - **Description**: Explores the technique of Visual Prompt Tuning to adapt a pre-trained Transformer model to our specific task without extensive retraining.


