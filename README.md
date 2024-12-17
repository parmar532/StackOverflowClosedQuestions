# Analysis & Detection of Closed Questions in Stack Overflow

This project focuses on predicting and analyzing the reasons for question closures on Stack Overflow using Natural Language Processing (NLP). The binary classifier achieved 80.71% accuracy, while the multi-class classifier reached 70.89%, helping users post higher-quality questions.

## Short Description
We use NLP techniques, including GRU-based RNNs and classical machine learning models, to predict if a question will be closed and identify closure reasons such as *duplicate, off-topic, unclear, too broad*, or *opinion-based*. This assists users in improving question quality before posting.

## Steps to Run the Project
1. **Download the Dataset:**
   - Go to [Stack Exchange Data Explorer](https://data.stackexchange.com/).
   - Use SQL queries to download closed questions in chunks (due to a 50,000-row limit).
   - Merge the downloaded chunks and prepare the dataset.

2. **Run the Project:**
   - Open and run the `so_questions_classical.ipynb` notebook.
   - Ensure all dependencies are installed (TF-IDF, Scikit-learn, etc.).

## Authors
- **Gaurav Parmar** 

