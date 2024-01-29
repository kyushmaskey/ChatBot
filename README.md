
## Introduction

The Intent Recognition ChatBot is designed to recognize user intents and provide predefined responses based on the trained model. It uses PyTorch for building the neural network model and TfidfVectorizer for text vectorization.

## Features

- **Training Script (`train.py`):** Train the Intent Recognition model with configurable parameters such as epoch, learning rate, batch size, and feature count.
  
- **Chat Script (`chat.py`):** Interact with the trained model through a simple command-line interface. Get responses based on user input.

  ## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/Intent-Recognition-ChatBot.git
    cd Intent-Recognition-ChatBot
    ```

2. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Training

1. Adjust training parameters in `train.py` if needed.

2. Run the training script:

    ```bash
    python train.py -e 1000 -l 0.02 -b 0 -f 1000
    ```

### Chat

1. Run the chat script to interact with the trained model:

    ```bash
    python chat.py
    ```

2. Type your message, and the ChatBot will provide responses based on the trained model.

**Note:** Ensure you have the necessary dependencies installed before running the training and chat scripts. Refer to the "Installation" section for installing the required packages.

Feel free to customize this section further if there are additional details or instructions you'd like to include.
