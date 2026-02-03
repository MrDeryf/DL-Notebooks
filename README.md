# Deep Learning Course Notebooks

This repository contains Jupyter notebooks created during the **Deep Learning** course at [MIREA – Russian Technological University](https://www.mirea.ru/) (2024-2025 academic year).

Each notebook corresponds to a practical assignment covering key topics in Deep Learning.
## 📁 Notebooks Content

1. **Fully Connected Neural Network**  
   Building a fully connected neural network for the MNIST and EMNIST datasets.

2. **Neural Network Tuning**  
   Consists of two parts:  
   - Implementation of autograd and a fully connected neural network (FCNN).  
   - Hyperparameter tuning of the FCNN. 
   
   Results were logged to Weights & Biases (`wandb`):  
   [https://wandb.ai/shadaevf-rtu-mirea/ml2_2_part_3](https://wandb.ai/shadaevf-rtu-mirea/ml2_2_part_3)

3. **Convolutional Neural Network**  
   Building a convolutional neural network (CNN) for the CIFAR-10 and EMNIST datasets.  
   Results were logged to `wandb`:  
   [https://wandb.ai/shadaevf-rtu-mirea/ML2_6](https://wandb.ai/shadaevf-rtu-mirea/ML2_6)

4. **CNN Architectures**  
   Consists of two parts:  
   - Evaluation of various regularization techniques.  
   - Comparison of three CNN architectures:  
     - ResNet  
     - VGG  
     - MobileNet 
   
   Results were logged to `wandb`:  
   [https://wandb.ai/shadaevf-rtu-mirea/ML2_4_2](https://wandb.ai/shadaevf-rtu-mirea/ML2_4_2)

5. **Autoencoders and NLP**  
   Consists of two parts:  
   - Building an autoencoder for the MNIST dataset.  
   - Comparison of three sequential models:  
     - RNN  
     - LSTM  
     - GRU  

## 🛠️ Technologies Used

| Category              | Libraries                          |
|-----------------------|------------------------------------|
| Core                  | Python 3.13, Jupyter Notebook      |
| Neural Networks       | `torch`, `torchvision`             |
| Metrics               | `scikit-learn`                     |
| Hyperparameter Tuning | `ray[tune]`                        |
| Visualization         | `matplotlib`, `wandb`              |

🔗 See [`pyproject.toml`](./pyproject.toml) for the complete dependency list.

## ▶️ How to Run
To run the notebooks locally, follow these steps:

1. Clone this repository:  
   ```bash
   git clone https://github.com/MrDeryf/DL-Notebooks
   ```
2. Install dependencies using [Poetry](https://python-poetry.org/):
    ```bash
   poetry install
   ```
3. Launch Jupyter Notebook:  
    ```bash
   jupyter notebook
   ```