# Comment-Toxicity-Level-Detection-Model-using-Python-and-Deep-Learning
We will be able to take sentences of natural language from a dataset which was provided in jigsaw toxic comment classification challenge and then pass it through a deep learning model and then detect the different elements of toxicity within them.

Steps:
1. Data Loading
2. Comments Preprocessing
3. Creating a Deep Natural Language Processing (NLP) Model
4. Evaluation of Model Performance
5. Creating a Gradio Deep Learning App to test our model


Project Overview: Comment-Toxicity-Level-Detection-Model-using-Python-and-Deep-Learning

- Objective: Build a model to classify toxic comments into six categories: toxic, severe toxic, obscene, threat, insult, and identity hate.
- Data: Utilized the Jigsaw Toxic Comment Classification Challenge dataset for training.
- Technologies:
  - Libraries: TensorFlow, Pandas, Matplotlib, Scikit-learn, Gradio.
  - Tools: TextVectorization for text preprocessing, Bidirectional LSTM for sequence modeling.
- Preprocessing:
  - Text data vectorization using `TextVectorization`.
  - Splitting data into training (70%), validation (20%), and test sets (10%).
- Model Architecture:
  - Sequential model with:
    - Embedding layer with 200,000 words vocabulary.
    - Bidirectional LSTM layer with 32 units.
    - Fully connected dense layers with 128, 256, and 128 units respectively.
    - Output layer with 6 units and sigmoid activation.
- Training:
  - Compiled model using Binary Crossentropy loss and Adam optimizer.
  - Trained model for 1 epoch with validation data.
- Evaluation:
  - Metrics: Precision, Recall, Categorical Accuracy.
  - Predictions made on test set.
  - Precision, Recall, and Accuracy calculated for model performance.
- Deployment:
  - Saved the trained model using `model.save`.
  - Created a Gradio interface for real-time comment scoring.

This project showcases the complete pipeline from data preprocessing and model training to evaluation and deployment, demonstrating strong skills in deep learning, NLP, and model deployment.
