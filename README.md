# Sentiment-Analysis-Using-Convolutional-Neural-Network
A Convolutional Neural Network (CNN)-based sentiment analysis project on the Solo Destination application, utilizing data from X, Google Play Store, and ULAS to support service quality improvement. The model achieved 93.39% accuracy (loss: 0.1647) on training and 93.45% accuracy (loss: 0.1958) on testing.

---

# 🧠 Sentiment Analysis using Convolutional Neural Network (CNN)

## 📌 Project Overview  
This project is part of my undergraduate thesis research, where the goal is to build a **Convolutional Neural Network (CNN)** model to perform sentiment analysis on public opinions about the **Solo Destination application**.  

The dataset was collected from multiple sources:  
- **Social Media X (formerly Twitter)**  
- **Google Play Store reviews**  
- **Website ULAS**  

The research aims to provide insights into how users perceive the application and support service quality improvements through data-driven analysis.  

---

## 📊 Research Workflow  

The research workflow consists of several stages:  

### 1️⃣ Data Collection  
- Crawling public opinion data from:  
  - Social Media X  
  - Google Play Store reviews  
  - Website ULAS  

### 2️⃣ Data Preprocessing  
- **Cleaning** and **Case Folding**  
- **Word Normalization**  
- **Stopword Removal**  
- **Stemming**  
- **Tokenization**  

### 3️⃣ Data Augmentation  
- Enhancing dataset diversity using **synonym replacement** technique.  

### 4️⃣ Data Labelling  
- **Translation**: Non-English texts are translated into English using **ChatGPT (gpt-3.5-turbo-1106)**, which provides more accurate contextual translation compared to Google Translate.  
- **Sentiment Labelling**: After translation, each text is labelled as **positive** or **negative** using the **TextBlob library**.  

### 5️⃣ CNN Model Development  
- Building the CNN architecture for sentiment analysis.  
- Performing **hyperparameter tuning** to optimize model performance.  

### 6️⃣ Model Training & Testing  
- **Training Process:** Feeding training dataset into CNN, producing training accuracy & training loss.  
- **Testing Process:** Feeding testing dataset into CNN, producing testing accuracy & testing loss.  

---

## 📈 Expected Outcomes  
- A trained **CNN-based sentiment analysis model** capable of classifying public opinion into positive and negative sentiments.  
- Insights into how users perceive the **Solo Destination application** based on multiple data sources.  
- A framework that can be used as a reference for service quality improvement.  

---

## 📂 Contents  
- 🗂 **Data Collection Scripts**: Crawling from X, Google Play Store, and ULAS  
- 🧹 **Preprocessing Notebook**: Cleaning, normalization, and tokenization  
- 🔄 **Data Augmentation & Labeling**: Synonym replacement, translation with ChatGPT, and sentiment labelling with TextBlob  
- 🏗 **CNN Model Development**: Architecture design and tuning  
- 📊 **Training & Testing Results**: Accuracy and loss visualization  

---

✨ Thank you for reading!  
This project demonstrates the implementation of **Deep Learning for Sentiment Analysis** and can be extended for other customer feedback analysis use cases.  
