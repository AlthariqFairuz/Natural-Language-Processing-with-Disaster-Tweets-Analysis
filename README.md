## Natural Language Processing with Disaster Tweets Analysis
This project presents a comprehensive analysis of the Disaster Tweets dataset from Kaggle, exploring how natural language processing techniques can be used to identify tweets about real disasters. 
By leveraging various NLP approaches and machine learning models, this notebook aims to build a robust system that can distinguish between tweets reporting actual disasters and those that use disaster-related words in other contexts.

## 📋 Overview
The dataset comes from the Kaggle competition [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started/overview).

## 🛠️ Requirements
The project requires the following main dependencies:
- Python 3.x
- Tensorflow (for neural network implementation)
- Weights & Biases (for experiment tracking)
- Matplotlib and Seaborn (for visualization)
- scikit-learn (for evaluation metrics)
- Jupyter Notebook (for interactive development)

## ⚙️ Setup and Configuration

Before running the project, you'll need to set up authentication for necessary services:

### Weights & Biases Setup
1. Create an account at [Weights & Biases](https://wandb.ai)
2. Obtain your API key from the [authorization page](https://wandb.ai/authorize)
3. Set up your API key in your environment:
   ```bash
   WANDB_API_KEY='your-api-key'
   ```

## 🚀 Getting Started

1. Clone the repository:
  ```bash
    git clone https://github.com/AlthariqFairuz/disaster-tweets-predictions.git
    cd disaster-tweets-predictions
  ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook from local or google colab

## 🤖 Model Architecture
There are 7 models that being used in this notebook:
1. Gaussian Naive Bayes (Baseline)
2. Simple Dense Model
3. LSTM
4. GRU
5. Convolutional Neural Network (1D)
6. Bidirectional RNN
7. Simple Dense Model but using Universal Sentence Encoder (USE) as the embedding layer.

## 📈 Performance Tracking
You can monitor the model's performance in real-time through [here](https://wandb.ai/althariqfairuz273-institut-teknologi-bandung/nlp-disaster-tweets?nw=nwuseralthariqfairuz273).
