# Dropout Regularization in a PyTorch Neural Network

## Description

This project demonstrates the use of dropout as a regularization technique to prevent overfitting in a simple neural network built with PyTorch. The Jupyter notebook `Dropout.ipynb` contains the code to train and evaluate two models: one with dropout and one without.

## Getting Started

To run this project, you will need to have Python 3 and Jupyter Notebook installed. The necessary Python libraries can be installed by running the first cell in the `Dropout.ipynb` notebook.

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repository.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd your-repository
    ```
3.  Open the Jupyter notebook:
    ```bash
    jupyter notebook Dropout.ipynb
    ```
4.  Run the cells in the notebook sequentially.

## Results

The notebook trains two neural networks on a synthetic dataset. The first model is trained without dropout, and the second model is trained with a dropout rate of 0.5. The results show that the model with dropout achieves a significantly higher accuracy on the validation set, demonstrating the effectiveness of dropout in preventing overfitting.

-   **Accuracy without dropout:** ~0.49
-   **Accuracy with dropout:** ~0.84
