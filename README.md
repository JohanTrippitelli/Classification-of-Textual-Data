# Classification-of-Textual-Data
## Project Overview
This GitHub repository showcases an in-depth exploration of textual data classification for emotion detection. The project involves preprocessing the Emotion dataset from Hugging Face and employing both a Naive Bayes model and a BERT model for classification. Tasks include implementing the Naive Bayes model from scratch and fine-tuning a pre-trained BERT model.

## Introduction
The project focuses on comparing the performance of different models for emotion classification, specifically on the Hugging Face emotions dataset. It encompasses designing a data preprocessing pipeline, implementing Naive Bayes from scratch, and experimenting with various BERT model variants. The evaluation involves the Naive Bayes model, pre-trained BERT model, trained BERT model, and trained BERT model with frozen pre-trained encoder weights.

## System Models
The Naive Bayes model prioritizes simplicity and efficient text data processing. It utilizes the CountVectorizer function from sklearn for feature extraction and Laplace smoothing to address zero word counts. In contrast, the BERT model is based on Bidirectional Encoder Representations from Transformers (BERT), specifically the BERT-Base, Uncased variation. The report underscores the importance of pre-training for BERT models, emphasizing their adaptability to diverse downstream natural language processing tasks.

## Experiments and Conclusions
The team conducts experiments on a dataset of 20,000 English Twitter messages labeled with six basic emotions.
As seen here:
<img width="199" alt="Screenshot 2023-12-21 at 15 48 56" src="https://github.com/JohanTrippitelli/Classification-of-Textual-Data/assets/154525880/037089b5-1bd5-4e4b-85d2-c59f404aed7f">

The performance of Naive Bayes and various BERT model variations is evaluated. Results indicate that the trained BERT model outperforms Naive Bayes, demonstrating the effectiveness of fine-tuning for task-specific adaptation. The report provides insights into the strengths and limitations of each approach, emphasizing the trade-offs involved in model selection and training strategies. A simple representation of the results is shown here: 
<img width="680" alt="Screenshot 2023-12-21 at 15 49 10" src="https://github.com/JohanTrippitelli/Classification-of-Textual-Data/assets/154525880/053bd883-7896-4845-8bee-bec26e5224b6">

**For more detailed information refer to the project report attached to this repository**
