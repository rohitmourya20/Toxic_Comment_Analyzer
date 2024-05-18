# Toxic_Comment_Analyzer

The Toxic Comment Analyzer project is designed to automate the assessment of comment toxicity using a Bidirectional LSTM deep learning model. It follows a structured workflow involving key stages and technologies to achieve its goal of accurately categorizing comments based on their toxicity levels.

The project begins with data preprocessing, where a labeled dataset containing comments tagged with various toxicity classifications undergoes cleaning and formatting. This step is crucial for preparing the data for model training and ensuring its quality.

In terms of technology, the project leverages Python along with essential libraries such as Pandas for data manipulation, NLTK for text preprocessing, TensorFlow for deep learning tasks, and Gradio for interface development. The choice of a Bidirectional LSTM architecture enables the model to capture contextual information bidirectionally, making it well-suited for sequence analysis tasks like toxicity detection.

The core of the project lies in constructing the deep learning model. The model architecture includes layers for word embedding, Bidirectional LSTM, and classification. It is compiled with an optimizer and loss function suitable for multi-label classification tasks, optimizing its learning process.

Training and evaluation are pivotal stages where the model is trained on a portion of the dataset and validated for performance using metrics like accuracy. This ensures that the model can effectively predict toxicity levels on unseen data.

The project's user interface is developed using Gradio, providing an interactive platform for users to input comments and receive toxicity predictions. This interface enhances accessibility and usability, making toxicity analysis more approachable.

A threshold logic is applied post-prediction to convert probabilistic predictions into binary classifications based on predefined confidence thresholds. This step aids in decision-making by categorizing comments as toxic or non-toxic based on the model's confidence levels.

In summary, the Toxic Comment Analyzer project showcases the integration of deep learning techniques, data preprocessing methodologies, and user-friendly interfaces to address the challenge of comment toxicity analysis. Its medium-scale implementation encompasses data cleaning, model development, training, evaluation, interface creation, and post-processing logic, making it a valuable tool for content moderation and sentiment analysis in online platforms.

Gradio in interface to detect the toxicity in comment in terms of percentage:

![Screenshot 2024-05-18 202605](https://github.com/rohitmourya20/Toxic_Comment_Analyzer/assets/170001383/343b39cb-af77-4159-8673-21cbae581ba2)


Gradio in interface to detect the toxicity in comment in terms of True/False:

![Screenshot 2024-05-18 204442](https://github.com/rohitmourya20/Toxic_Comment_Analyzer/assets/170001383/c72d6f6a-185d-46a8-a501-4830b18270e1)


![Screenshot 2024-05-18 202545](https://github.com/rohitmourya20/Toxic_Comment_Analyzer/assets/170001383/386fad55-137d-4fef-9c7d-f6649c2b27ea)
