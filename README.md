# 💬 WhatsApp Chat Analyzer – Exploratory Text & Activity Analysis

## 📌 Project Overview

* **Domain:** Data Analytics / Text Analysis
* **Type:** Exploratory Data Analysis (EDA)
* **Input:** WhatsApp exported `.txt` chat file
* **Output:** Visual insights & statistics
* **Focus Areas:** Text preprocessing, frequency analysis, timelines, visualization


---

## 📂 Dataset

The dataset is a **WhatsApp chat export file**.

* **Format:** `.txt`
* **Export Method:**

  * WhatsApp → Chat → Export Chat
  * Select **Without Media**

Each message contains:

* Timestamp
* User name
* Message content (text / emoji / media placeholder)

---

## 🎯 Objective

To analyze WhatsApp conversations and answer questions such as:

* Who are the most active users?
* What words are used most frequently?
* Which emojis dominate the conversation?
* How does chat activity change over time?
* What are the most active days and months?

---

## 🧠 Approach

### 1. Data Parsing

* Extract timestamps and messages using regular expressions
* Separate user names and message content
* Identify and remove system-generated notifications

### 2. Data Preprocessing

* Removal of:

  * Group notifications
  * Media omitted messages
* Text normalization (lowercasing)
* Custom stopword handling (English + Hinglish)

### 3. Feature Extraction

* Message counts per user
* Word frequency counts
* Emoji extraction and frequency analysis
* Date-based features (year, month, day)

### 4. Visualization

* Bar charts for common words
* Pie charts for emoji distribution
* Line plots for monthly timelines
* Line plots for daily activity

---

## 📊 Analysis Performed

* User activity analysis
* Most common words analysis
* Emoji usage analysis
* Monthly activity timeline
* Daily activity timeline
* Group-level and user-level insights

---

## 🛠 Tech Stack

* **Language:** Python
* **Libraries:**

  * pandas
  * matplotlib
  * emoji
  * collections
  * urlextract
  * scikit-learn *(optional extensions)*
* **Environment:** Google Colab / Jupyter Notebook

---

## 📈 Results & Insights

* Identification of most active users
* Frequently used words after preprocessing
* Dominant emojis used in conversations
* Clear visibility of high and low activity periods
* Temporal patterns in chat behavior

> Key takeaway: **Data cleaning and preprocessing are crucial when working with real-world conversational data.**

---

## 🛠 Skills Practiced

* Text preprocessing
* Handling unstructured data
* Exploratory Data Analysis (EDA)
* Feature extraction
* Data visualization
* End-to-end analytics workflow

---

## 📚 References & Resources

* WhatsApp Chat Export Documentation
* pandas Documentation
* matplotlib Documentation
* emoji Python Library

---

## 🏷️ Acknowledgments

* WhatsApp for chat export format
* Open-source Python community
* Data analytics learning resources

---

## 📌 License

This project is created for **educational and learning purposes**.
All data used belongs to the respective chat owners.

---

## 🔗 Notebook Link
https://colab.research.google.com/drive/1iUoG7PR_nExsOx2dxOa_Jpx9JcSqBi0L?usp=sharing
---
# Whatsapp-Analyzer
