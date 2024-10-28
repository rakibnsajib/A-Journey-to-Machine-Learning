# Chapter 2: Types of Machine Learning

Now that we have an understanding of what Machine Learning is and why it matters, let’s explore the different types of Machine Learning approaches. Broadly speaking, Machine Learning is classified into three main categories: Supervised Learning, Unsupervised Learning, and Reinforcement Learning. Each category represents a distinct method of how machines learn from data.

## 2.1 Supervised Learning

Supervised learning is the most common type of Machine Learning. In this approach, the model is trained on a labeled dataset, which means that the input data is paired with the correct output. The goal of the model is to learn the mapping between inputs and outputs so that it can make accurate predictions when presented with new data.

### Key Features:
- **Labeled Data:** Every example in the dataset comes with an associated output or label.
- **Training Process:** The model iteratively learns by adjusting itself based on errors in prediction.
- **Applications:** Supervised learning is widely used in image classification, speech recognition, fraud detection, and many other areas.

### Example Algorithms:
- Linear Regression
- Decision Trees
- Support Vector Machines (SVM)
- Neural Networks

## 2.2 Unsupervised Learning

In unsupervised learning, the model is provided with input data without any corresponding output labels. The goal here is not to predict outputs but to uncover hidden patterns, groupings, or structures within the data. Unsupervised learning is typically used in exploratory data analysis, where discovering underlying relationships is the primary objective.

### Key Features:
- **No Labeled Data:** The model works with data that doesn’t have predefined outputs.
- **Exploratory Learning:** The focus is on identifying structure within the data.
- **Applications:** Unsupervised learning is commonly used in clustering, anomaly detection, and market segmentation.

### Example Algorithms:
- K-Means Clustering
- Hierarchical Clustering
- Principal Component Analysis (PCA)
- Autoencoders

## 2.3 Reinforcement Learning

Reinforcement learning is a unique type of Machine Learning where an agent learns to make decisions by interacting with its environment. The agent takes actions to achieve a goal, and based on the outcomes, it receives feedback in the form of rewards or penalties. The aim is to learn a strategy that maximizes cumulative rewards over time.

### Key Features:
- **Trial and Error Learning:** The agent learns from the consequences of its actions.
- **Reward System:** Positive or negative rewards are used to reinforce learning.
- **Applications:** Reinforcement learning is widely used in robotics, gaming, and autonomous systems like self-driving cars.

### Example Algorithms:
- Q-Learning
- Deep Q-Networks (DQN)
- Policy Gradient Methods

## 2.4 Semi-Supervised Learning

While the three primary types of Machine Learning are widely recognized, a fourth approach, known as semi-supervised learning, exists as a hybrid method. In semi-supervised learning, the model is trained on a small amount of labeled data alongside a large amount of unlabeled data. This method aims to leverage the benefits of both supervised and unsupervised learning.

### Key Features:
- **Small Labeled Data:** Only a fraction of the data is labeled.
- **Improved Learning Efficiency:** The unlabeled data is used to generalize better from fewer labeled examples.
- **Applications:** Semi-supervised learning is often applied in scenarios where labeling data is expensive, such as medical image analysis.

### Example Algorithms:
- Self-Training
- Generative Adversarial Networks (GANs)