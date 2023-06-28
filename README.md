# Flower Classification with Pretrained ResNet50 Model

This project demonstrates the use of a pretrained ResNet50 model to classify flower images from the Kaggle flower dataset. The code is implemented in Python using the PyTorch library and can be run in a Colab notebook.

## Dataset

The dataset used for this project is the flower dataset from Kaggle, which consists of labeled images of various flower species. You can find the dataset on Kaggle [here](https://www.kaggle.com/alxmamaev/flowers-recognition). Please download the dataset and ensure that the images are organized in the following structure:

```
dataset/
    ├── class_1/
    │   ├── image_1.jpg
    │   ├── image_2.jpg
    │   └── ...
    ├── class_2/
    │   ├── image_1.jpg
    │   ├── image_2.jpg
    │   └── ...
    ├── class_3/
    │   ├── image_1.jpg
    │   ├── image_2.jpg
    │   └── ...
    └── ...
```

Make sure to replace `class_1`, `class_2`, etc., with the actual class names.

## Prerequisites

To run this project, you will need the following:

- Python 3.x
- PyTorch
- Torchvision
- NumPy
- Matplotlib

You can install the required packages by running the following command:

```bash
pip install torch torchvision numpy matplotlib
```

## Usage

1. Clone this repository to your local machine or download the Colab notebook.

2. Place the flower dataset in the appropriate folder structure as described above.

3. Open the Colab notebook in Google Colab or run it locally using Jupyter Notebook.

4. Run the code cells in the notebook sequentially to train the model and evaluate its performance.

5. Optionally, modify the hyperparameters or experiment with different configurations to improve the model's performance.

## Model Architecture

This project utilizes a pretrained ResNet50 model, which is a deep convolutional neural network architecture. The ResNet50 model has been trained on a large-scale dataset and has achieved state-of-the-art performance on various computer vision tasks.

The final fully connected layer of the ResNet50 model is replaced with a new linear layer to adapt it to the number of flower classes in the dataset.

## Results

After training the model, the notebook provides an evaluation of the model's performance.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as per your requirements.

## Acknowledgements

- The flower dataset used in this project was obtained from Kaggle, which was originally compiled by [Alexander Mamaev](https://www.kaggle.com/alxmamaev).
- The pretrained ResNet50 model used in this project is provided by the PyTorch library.
- This project is inspired by various computer vision tutorials and examples available online.

## Contributing

If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request. Your contributions are highly appreciated.

