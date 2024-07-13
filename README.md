# DigitsInk: Digit Recognition using MNIST

DigitsInk is a project that demonstrates the use of PyTorch and the torchvision library to train a neural network on the MNIST dataset for handwritten digit recognition.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The goal of this project is to build a machine learning model that can accurately recognize handwritten digits using the MNIST dataset. The MNIST dataset is a collection of 70,000 images of handwritten digits (0-9) that has been widely used for training and testing in the field of machine learning.


## Images
![img3](https://github.com/user-attachments/assets/ab026ef9-9468-44d7-a516-1263a185c761)
![img2](https://github.com/user-attachments/assets/72f85f32-6b7d-454c-a911-63d4f53674f8)
![img1](https://github.com/user-attachments/assets/2c89219e-213a-4054-80dd-31f899bcf2f1)
![Screenshot 2024-07-11 215523](https://github.com/user-attachments/assets/c6921e23-306d-4c11-a603-7d58a9013c35)

## Installation
To run this project, you need to have Python installed along with some specific libraries. You can install the necessary dependencies using the following commands:

```bash
pip install torch torchvision matplotlib
```

Ensure you have a working environment with Jupyter Notebook to run the notebook.

## Usage
1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/DigitsInk.git
    cd DigitsInk
    ```

2. **Open the Jupyter Notebook**:
    ```bash
    jupyter notebook DigitsInk.ipynb
    ```

3. **Run the cells** in the notebook sequentially to load the data, train the model, and evaluate its performance.

## Project Structure
The project contains the following files:
- `DigitsInk.ipynb`: The main Jupyter Notebook file containing the code for loading data, training the model, and evaluating its performance.
- `README.md`: This README file.

## Dataset
The MNIST dataset is automatically downloaded when you run the notebook. It consists of:
- 60,000 training images
- 10,000 test images

Each image is a 28x28 grayscale image of a handwritten digit.

## Results
After running the notebook, the trained model's performance will be evaluated on the test dataset. The results, including accuracy and sample predictions, will be displayed within the notebook.

## Contributing
Contributions are welcome! If you have any improvements or suggestions, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
