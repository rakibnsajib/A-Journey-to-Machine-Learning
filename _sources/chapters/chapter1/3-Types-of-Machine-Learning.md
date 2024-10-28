## Chapter 3: Types of Machine Learning

### 3.1 Supervised Learning
   - **Definition**: A learning paradigm where a model is trained using a labeled dataset, meaning each training example is paired with an output label. The model learns to map inputs to the correct outputs and generalizes this mapping to unseen data.
   - **Example Algorithms**: Linear Regression, Support Vector Machines (SVM), Decision Trees.
   - **Applications**: Image classification, spam detection, medical diagnosis.

### 3.2 Unsupervised Learning
   - **Definition**: A learning approach where a model is trained using data without labeled responses. The goal is to identify patterns or structures in the input data, such as clusters or associations.
   - **Example Algorithms**: K-Means Clustering, Principal Component Analysis (PCA), DBSCAN.
   - **Applications**: Market segmentation, anomaly detection, customer clustering.

### 3.3 Semi-Supervised Learning
   - **Definition**: A learning paradigm that combines a small set of labeled data with a larger set of unlabeled data during training. It aims to leverage the large unlabeled dataset to improve the learning process.
   - **Example Algorithms**: Self-training, Label Propagation.
   - **Applications**: Image and speech recognition, medical image analysis.

### 3.4 Reinforcement Learning (RL)
   - **Definition**: A learning paradigm where an agent interacts with an environment to learn behaviors that maximize cumulative rewards. It uses trial and error to make decisions, optimizing actions based on feedback from the environment.
   - **Example Algorithms**: Q-Learning, Deep Q-Networks (DQN).
   - **Applications**: Game AI, robotics, autonomous vehicles.

### 3.5 Comparison Table

| Learning Type    | Labeled Data | Key Idea                      | Example Algorithms               | Applications                            |
|------------------|--------------|-------------------------------|----------------------------------|-----------------------------------------|
| Supervised       | Yes          | Learns from input-output pairs| Linear Regression, SVM, Decision Trees | Image classification, spam detection    |
| Unsupervised     | No           | Identifies hidden patterns    | K-Means, PCA, DBSCAN             | Customer segmentation, anomaly detection|
| Semi-Supervised  | Mixed        | Leverages small labeled data  | Self-training, Label Propagation | Medical image analysis, text classification |
| Reinforcement    | N/A          | Learns through rewards/punishments | Q-Learning, DQN                | Game AI, robotics, autonomous driving   |

### 3.6 Summary
   - **Supervised Learning** models generalize from labeled data to predict outcomes.
   - **Unsupervised Learning** discovers inherent structures in data without labels.
   - **Semi-Supervised Learning** is effective when labeled data is scarce but plentiful unlabeled data exists.
   - **Reinforcement Learning** is suitable for scenarios requiring sequential decision-making and adaptive learning.
