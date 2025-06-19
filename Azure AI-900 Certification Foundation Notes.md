## Azure AI-900 Certification Foundation Notes by Sankeerth Boddu

---

### **1. Introduction to Artificial Intelligence (AI)**

- **Definition:**
AI is the simulation of human capabilities such as vision, speech, natural language processing, document intelligence, and knowledge representation.
- **Types of AI Approaches:**
    - *Logic-based:* Uses rule-based systems (e.g., if-then-else logic).
    - *Data-based:* Utilizes data-driven algorithms, such as machine learning.

---

### **2. Machine Learning (ML) Basics**

- **Definition:**
Machine learning is a subset of AI that enables computers to learn from data without explicit programming.
- **How ML Works:**
    - Provide labeled data to the computer.
    - The system generalizes patterns and creates a predictive model (e.g., decision trees, linear regression, SVM).
    - The process is iterative: train, test, tweak, and deploy.
- **Types of Data:**
    - *Numeric (Regression):* Predicts continuous values.
    - *Classification:* Binary (yes/no) or multiclass (multiple categories).
    - *Unsupervised:* No labels; finds groupings in data.


#### **Key ML Concepts**

- **Datasets:**
    - *Training Set:* Used to train the model.
    - *Validation Set:* Used to tune hyperparameters and evaluate the model.
    - *Test Set:* Used to confirm the model's final results.
- **Model Fit:**
    - *Underfitting:* Model is too simple, performs poorly on training data.
    - *Overfitting:* Model is too complex, memorizes training data, performs poorly on new data. Early stopping can help prevent overfitting.
    - *Balanced Fit:* Good performance on both training and evaluation data.
- **Data Components:**
    - *Features:* Input attributes.
    - *Values:* Actual data points.
    - *Labels:* Target outputs.

---

### **3. Types of Machine Learning**

- **Supervised Learning (Predictive Analysis):**
    - *Task Driven* (Classification/Regression)
    - Uses labeled data.
    - **Examples:** Fraud detection, customer churn prediction.
    - **Classification:** Categorizes data into predefined classes (e.g., spam filters, decision trees).
    - **Regression:** Predicts continuous values (e.g., house prices, linear regression, SVM).
    - **Logistic Regression:** Used for binary classification tasks.
- **Unsupervised Learning (Exploratory Data Analysis):**
    - *Data Driven* (Clustering)
    - Uses unlabeled data.
    - **Examples:** Market segmentation, anomaly detection, grouping customers by purchase history.
    - **K-means Clustering:** Groups data points by similarity.
- **Reinforcement Learning (Dynamic Decision-Making):**
    - *Rewards Based Learning*
    - Learns from feedback, trial and error.
    - **Examples:** Game playing, robotics, self-driving cars.

---

### **4. Deep Learning and Neural Networks**

- **Deep Learning:**
Utilizes multiple layers of neural networks (input, hidden, output layers). Each neuron uses an activation function, with weights and biases adjusted during training to minimize errors.
- **Neural Network Parameters:**
    - *Weights:* Adjust connection strength.
    - *Biases:* Adjust activation thresholds.


#### **Types of Neural Networks**

| Network Type | Description | Typical Use Cases |
| :-- | :-- | :-- |
| CNN (Convolutional Neural Network) | Analyzes spatial data (images, videos) | Image recognition, object detection |
| RNN (Recurrent Neural Network) | Processes sequential/time-series data | Time-series analysis, language modeling |
| FNN (Feedforward Neural Network) | Data flows one way, no feedback | Basic classification/regression |
| Transformer Networks | Handles sequence-to-sequence tasks | Language translation, NLP |


---

### **5. Natural Language Processing (NLP) and Generative AI**

- **Transformers:**
Powerful models for NLP tasks, such as translation and text generation.
- **Tokens:**
Basic units of text, represented as vectors (arrays of numbers).
- **Embeddings:**
Numerical vectors capturing semantic meaning and relationships of words/phrases.
- **Vectors:**
Numerical representations of tokens, enabling contextual understanding.
- **Prompt:**
Input/query to a language model to generate a response.
    - *Elements:* Instructions, context, input data.
    - *Zero-shot Prompting:* No examples, just the task.
    - *Few-shot Prompting:* Includes examples for context.
    - *Chain-of-thought Prompting:* Breaks complex tasks into steps (e.g., "think step by step").
- **AI Language Concepts:**
    - *Utterances:* Raw user inputs.
    - *Entities:* Key data within inputs.
    - *Intents:* User’s underlying goal.
    - *Conversational Language:* Entity recognition + intent classification.
    - *Sentiment Analysis:* Analyzes emotion or sentiment in text.

---

### **6. Computer Vision and Image Processing**

- **Computer Vision:**
Automates feature learning by generating filters (convolutional layers) whose weights are learned automatically.
- **Applications:**
    - *Object Detection:* Identifies and locates objects in images.
    - *Image Segmentation:* Partitions images for detailed analysis (e.g., MRI scans).
    - *Image Description:* Computer Vision can generate text descriptions of images.
- **Integration:**
Language Service can convert image descriptions into spoken language.

---

### **7. Azure AI Services Overview**

| Service | Description |
| :-- | :-- |
| Speech Service | Converts spoken language to text |
| Text-to-Speech | Converts text to lifelike audio |
| Document Translation | Translates text between languages |
| Object Detection | Identifies and locates objects in images |
| Pronunciation Assessment | Evaluates spoken word pronunciation |
| Knowledge Mining (Azure AI Search) | Combines document processing and search |
| Document Intelligence | Extracts information from documents (e.g., receipts) |


---

### **8. Knowledge Mining Workflow**

- **Steps:**

1. Data Ingestion
2. Data Enrichment
3. Index Creation
4. Query Processing

---

### **9. Model Evaluation Metrics**

| Metric | Description |
| :-- | :-- |
| Accuracy | Ratio of correctly predicted cases to total cases |
| Precision | Ratio of correctly predicted positive cases to total predicted positives |
| Recall (Sensitivity) | Ratio of correctly predicted positives to total actual positives |
| F1 Score | Harmonic mean of precision and recall |


---

### **10. Responsible AI Principles**

- **Fairness:**
Ensure models do not exhibit bias or discrimination.
- **Explainability:**
Models should provide understandable reasons for decisions (crucial for trust and transparency).
- **Regularization:**
Technique to prevent overfitting by adding a penalty to the loss function.
- **Variance:**
Measure of data spread; high variance can indicate overfitting.
- **Dimension Reduction:**
Techniques like PCA and SVD reduce feature count while retaining important information.


#### **Key Trade-offs in AI Systems**

| Trade-off | Description |
| :-- | :-- |
| Safety vs. Transparency | Balancing system safety with decision-making transparency |
| Interpretability vs. Performance | More interpretable models may have lower performance |
| Controllability vs. Complexity | Simpler systems are easier to control and audit |
| Bias vs. Variance | Reducing bias (underfitting) vs. minimizing variance (overfitting) |

- **Bias:** High bias = underfitting.
- **Variance:** High variance = overfitting.

---

**End of Notes**

<div style="text-align: center">⁂</div>

[^1]: ai.txt

