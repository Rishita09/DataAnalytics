# Text Classification for Beginners: Building and Evaluating Models with Real Data

**Project Overview**
This project is an exploration into text classification, focusing on categorizing YouTube video transcripts into five distinct categories: Laptops, Tech Accessories, Home Automation, Smartphones, and Tech Wearables. The project demonstrates the complete process, from data collection and preprocessing to model implementation and evaluation.

You can read my blog on this at https://medium.com/@rishitashah2803/text-classification-with-real-data-67423b8e26e7

**Key Steps Covered**
- Data Collection: Extracted transcripts using the YouTubeTranscriptApi.
- Preprocessing: Breaking down transcripts into sentences, removing words less than 2 letters long, and handling class imbalance using SMOTE.
- Feature Extraction: Implemented TF-IDF for feature extraction and label encoding for the target variable.
- Modeling: Built and evaluated multiple classification algorithms including Logistic Regression, Random Forest, SVM, Naive Bayes, and a Voting Classifier.
- Challenges and Lessons: Discussed the challenges faced, including lower-than-expected accuracy, and the lessons learned from the process.

**Results**

Despite thorough preprocessing and model tuning, the best model achieved an accuracy of just over 60%. This highlights the complexity of the task and the need for further refinement or perhaps a different approach. The project is a reflection of the learning journey, emphasizing the challenges of working with real-world data and the importance of iterative improvement.

**How to Run the Project**
- Clone the repository.
- Run the Jupyter Notebook (text_classification.ipynb) to reproduce the results.

**Files Included**
- text_classification.ipynb: The main Jupyter Notebook containing all code, explanations, and results.
- all_transcripts.json: The dataset used for this project, containing the processed transcripts.

**Connect with Me**
I'm always open to suggestions and feedback! If you have ideas on how to improve the accuracy or any other aspect of the project, feel free to reach out to me at rishitashah2803@gmail.com. Your insights could help make this project even better.
