# EITACIES INC Summer Internship Project

## Project Overview
During my internship at Eitacies Inc., I worked on innovative projects focused on enhancing the efficiency and security of conference calls applications such as Zoom, Webex, and MS Teams and detecting sensitive content through advanced text, audio, and video analysis. The work involved developing machine learning and deep learning models, applying NLP techniques, and integrating detection systems for real-time and post-event analysis.

## Goals and Objectives
- **Primary goals** :
  - Design and implement systems to detect inappropriate and sensitive content during conference calls in real time.
  - Ensure data security and compliance while processing sensitive information.
- **Key Focus Areas**
  - PCI DSS compliance detection
  - Financial Projection Detection
  - Flirting Detection
  - Emotion detection

## Responsibilities
- **Business Objective Alignment:** Designed models to align with goals for safeguarding video conferences.
- **Data Preprocessing:** Cleaned and prepared large datasets for analysis using NLP techniques.
- **Model Development:** Designed and implemented machine learning pipelines for specific tasks, including inappropriate content detection and emotion analysis.
- **Feature Engineering:** Applied advanced feature extraction techniques such as CountVectorizer, Word2Vec, and TF-IDF.
- **Database Management:** Stored flagged content and metadata in MongoDB for efficient retrieval and analysis.
- **Model Training & Tuning:** Trained models, utilized data augmentation and regularization techniques to enhance model accuracy and generalization.

## Architecture
The architecture of the CONFSEC project processes data in a secure and efficient way. The data is processed by the machine learning engine in a private ad secured zone, with the results stored in MongoDB. The backend API securely interacts with the user interface through role-based access control(RBAC).
![End-to-End Architecture](E2E Architecture.pdf)

## Key Tasks
### 1. Financial Projection Detection Using Text
- **Overview:** Detect financial projection discussions in text data to ensure regulatory compliance.
- **Techniques Utilized:**
  - Preprocessing with NLTK.
  - Feature extraction using CountVectorizer.
  - **ML Models:** Logistic Regression (85.53%), SVM (Linear Kernel) (88.16%), and Random Forest (72.37%).
- **Accuracy:** Achieved a cross-validation accuracy of 82.13% with Logistic Regression.
  

### 2. Flirting Detection
- **Overview:** Detect inappropriate flirting behavior in text conversations.
- **Techniques Utilized:**
  - Preprocessing with NLTK.
  - Feature extraction using CountVectorizer.
  - **ML Models:** Logistic Regression, SVM (Linear Kernel), and Random Forest, each achieving 97.96% accuracy.
- **Accuracy:** Achieved a cross-validation accuracy of 82.13% with Logistic Regression.

  
### 3. PCI-DSS Detection
- **Overview:**  Identify sensitive PCI-DSS (Payment Card Industry Data Security Standard) information in conversations.
- **Techniques Utilized:**
  - Preprocessing with NLTK.
  - Feature extraction using Word2Vec and TF-IDF.
  - **ML Models:** SVM (RBF Kernel) (97.22%) and Logistic Regression (95.37%).
- **Accuracy:** Achieved a cross-validation accuracy of 99.76%.

### 4. Emotion Detection in Conference Calls
- **Overview:** Analyze speech content and detect emotions during video conferences to flag sensitive discussions.
- **Techniques Utilized:**
  - Developed LSTM Neural Networks for speech-based emotion detection.
  - Utilized the Toronto Emotional Speech Set dataset.
- **Accuracy:** 70%

## Skills Utilized and Developed
- **Programming:** Python, Scikit-Learn, TensorFlow, MongoDB
- **Machine Learning:** Logistic Regression, Random Forest, Decision Trees, SVM
- **Deep Learning:** LSTM, CNN
- **NLP:** Bag of Words, Bag of n-grams, Word2Vec, TF-IDF
- **Databases:** MongoDB
- **Tools:** Jupyter Notebook, Google Colab

## Challenges Faced
- **Model Overfitting:** Mitigated overfitting in models using regularization and hyperparameter tuning, cross validation.
- **Data Collection:** Addressed challenges in obtaining high-quality data by generating synthetic data and applying robust validation strategies.
- **Sensitive Data Handling:** Ensured strict compliance with data security protocols when processing PII and sensitive content.

  ## Conclusion
This internship provided me with invaluable experience in designing and implementing machine learning and deep learning systems for real-world applications. I successfully contributed to improving the security and efficiency of conference call systems, developed end-to-end detection pipelines, and demonstrated expertise in handling sensitive data. The challenges I faced helped me strengthen my technical and problem-solving skills, laying a strong foundation for future projects in AI and data analysis.


  
