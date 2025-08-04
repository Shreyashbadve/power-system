
# ⚡ Power Fault Detection Using Machine Learning

A capstone project that uses Machine Learning to detect and classify faults in power distribution systems such as **line breakages**, **transformer failures**, and **equipment overheating**. Built using Python, trained on Kaggle datasets, and deployed using **IBM Watson Machine Learning (IBM Cloud Lite)** for real-time fault detection via API.

---

## 📌 Project Description

The reliability of power grids is crucial for energy distribution. However, traditional fault detection systems are often **reactive**, leading to delays and service disruptions. This project presents a **machine learning-based solution** that classifies power faults using **electrical and environmental data** to ensure **rapid fault identification** and support **predictive maintenance**.

---

## 💡 Objectives

- Detect various power distribution faults using ML.
- Achieve real-time classification and alerting.
- Deploy the solution on a scalable cloud platform (IBM Watson ML).
- Improve grid resilience and reduce manual inspection.

---

## 🛠️ Tech Stack

| Component            | Tools/Frameworks                           |
|---------------------|---------------------------------------------|
| Programming Language| Python                                      |
| ML Libraries         | Scikit-learn, Pandas, NumPy, Seaborn, Matplotlib |
| ML Algorithms        | Random Forest, Decision Tree, Gradient Boosting |
| Deployment           | IBM Watson Machine Learning (IBM Cloud Lite) |
| Dataset              | [Kaggle - Network Intrusion Detection Dataset](https://www.kaggle.com) |

---

## 🧪 Workflow

1. **Data Collection & Preprocessing**  
   - Normalization, missing value handling

2. **Feature Engineering**

3. **Model Selection & Training**  
   - Train/test split (70% / 30%)  
   - Model comparison and evaluation

4. **Deployment**  
   - Model saved as `.pkl`  
   - Deployed on IBM Watson ML  
   - REST API created for real-time inference

---

## 🎯 Results

- ✅ Accuracy: ~95% with **Random Forest**
- 📊 Evaluation Metrics:  
  - Confusion Matrix  
  - Classification Report (Precision, Recall, F1-Score)
- 🧪 Live prediction endpoint on IBM Cloud Lite

---

## 🚀 Future Enhancements

- Add Deep Learning models (LSTM, CNN)
- Real-time data streaming and packet sniffing
- Expand to IoT and smart grid networks
- Auto-updating threat/fault database

---

## 📚 References

- Kaggle NIDS Dataset  
- IBM Cloud Lite Documentation  
- Research papers on ML for power grid security

---

## 👨‍💻 Author

**Shreyash Sunil Badve**  
MIT Academy of Engineering – E&TC  
_IBM Internship Capstone Project_

---

## 📎 License

This project is licensed under the [MIT License](LICENSE).

