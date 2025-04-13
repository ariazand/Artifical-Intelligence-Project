# AI and Finance: Innovating the Loan Approval Process with Machine Learning

## 👋 Hi, we are Team 15!

<div style="text-align: center;">
  <img src="https://upload.wikimedia.org/wikipedia/commons/d/df/WM_Business_School_Internal_Logo.png" alt="WM Business School Logo" width="300">
</div>

| GitHub Username    | Name                        |
|--------------------|-----------------------------|
| [@ariazand](https://github.com/ariazand)         | Aria Zand                  |
| [@yihangfan2095](https://github.com/yihangfan2095) | Cathy Fan                  |
| [@jctagbor](https://github.com/jctagbor)         | John Carl Tagbor           |
| [@mpquinat](https://github.com/mpquinat)         | Melissa Parada-Quinatoa    |

## Scope: AI-Powered Loan Approval Prediction Model
In many traditional banking systems, loan approval lacks transparency, consistency, and adaptability to nuanced applicant profiles. Our goal was to develop an AI-powered loan approval model capable of evaluating client data and predicting loan approval based on various financial and personal criteria.

<div style="text-align: center;">
  <strong></strong><br>
  <img src="https://thumbs.dreamstime.com/b/credit-card-companies-design-vector-illustration-most-popular-cards-isolated-white-background-124770411.jpg" width="300">
</div>

---

## 🌐 [Live Web Demo](https://script.google.com/macros/s/AKfycby2SsZ1k9NDGLgtGwHcbn6EhHlDICunmO-n9LS2GBy1VmtwUA7WYdUmLXMZbMnTsvDtPg/exec)

<img src="https://twenty-four.io/wp-content/uploads/2024/06/Google-Apps-Script-1.png" alt="Google Apps Script Image" width="300">

Built using **Vibe Coding**, our live demo lets users interact with a simplified version of the loan approval prediction system.

👉 **How it works**:
1. The front-end form, built using Google Apps Script, allows users to input their financial details.
2. Upon submission, the data is passed to a backend system powered by a trained machine learning model.
3. The backend evaluates the applicant’s profile and provides a loan approval prediction.
4. This setup showcases how AI can provide **real-time**, **accessible predictions** to assist financial decision-making.

---

### 🔍 Key Tech Stack

Python · Scikit-learn · SHAP · Pandas · NumPy · Jupyter · HTML/CSS · Vibe Coding via ChatGPT and Claude

<div style="text-align: center;">
  <img src="https://blog.routinehub.co/content/images/2023/02/openAI-chat-gpt-1.jpg" alt="OpenAI ChatGPT Illustration" width="400">
</div>

---

## 📄 [Project Details](https://docs.google.com/document/d/1xI-PdhQZypXD82kAGWUpnDZrmSbDvlUv0V9oMo42jek/edit?tab=t.0)

### 💡 Why This Project?

As Generative AI becomes more prevalent, financial institutions are increasingly seeing the benefits of using AI for decision-making. Our project focuses on developing AI-powered systems for loan decision-making to enhance accuracy, speed, and transparency. Inspired by the paper *Monotonic Neural Additive Models: Pursuing Regulated Machine Learning Models for Credit Scoring* (International Conference on AI in Finance 2022), we aimed to use a machine learning model on Kaggle’s loan dataset to better assess applicants based on multiple indicators.

---

## I. Planning

Our project was divided into four key phases:

1. **Data Collection**: Gather customer loan application data via a front-end interface.  
2. **Data Storage**: Store the data in Google Sheets for easy access.  
3. **Data Analysis**: Use a trained machine learning model to analyze the data.  
4. **Results Display**: Present insights and results through an administrative dashboard.  

---

## II. Front-End Interface

We designed the front-end interface as a web-based questionnaire where users submit personal and loan information. The data is instantly transferred to Google Sheets for analysis using Google Apps Script and HTML.

---

## III. Back-End Interface

The back-end interface connects the front-end data collection system to the machine learning model, which analyzes the information and decides whether to approve or decline the loan request. This integration was achieved using Google Apps Script and a Python-based model.

Here’s how it works:

1. **Data Extraction**  
   The data is pulled from Google Sheets and prepared for the model.

2. **AI Model Integration**  
   A Python-based machine learning model evaluates the applicant’s data and makes a prediction.

3. **Result Handling**  
   Bank employees can review the model’s decision, then trigger an automated email to notify the applicant.
---

### 📚 Article References: From the International Conference on AI in Finance

- **Chen, Dangxing & Ye, Weicheng.** (2024). *Monotonic Neural Additive Models: Pursuing Regulated Machine Learning Models for Credit Scoring*.  
  This paper outlines neural networks that align better with financial regulations and promote explainability in credit scoring models.

 - **Yurrita, M., Draws, T., Balayn, A., Murray-Rust, D., Tintarev, N., & Bozzon, A.** (2024). *Disentangling Fairness Perceptions in Algorithmic Decision-Making*.
This article explores how people perceive fairness in AI decisions, especially in high-stakes cases like loan approvals. It highlights the need for human oversight, clear explanations for applicants, and transparency to build trust and detect bias in data.

<div style="text-align: center;">
  <img src="https://media.licdn.com/dms/image/v2/D5612AQGwSrOg4YKSDA/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1721056474304?e=2147483647&v=beta&t=3SLqGAi03Fmjd4SFsaH64ORnppFj_ikmy0E5MUXNH9k" alt="Image" width="400">
</div>

---

## ✅ Code Repository & Structure

[Loan Approval Prediction Repository](https://github.com/ariazand/loan-approval-prediction)

Key files and folders include:
- `notebooks/Loan_Approval_Model.ipynb`
- `scripts/data_preprocessing.py`
- `requirements.txt`
- `README.md`

---

## 🔮 What’s Next: Future Development & Responsible AI

### 🚀 What’s Next: Future Development
We’re continuing to improve both the model and the user experience. Here are our top priorities moving forward:  
1. **Model Refinement** – Enhance performance, reduce bias, and improve accuracy.  
2. **Deployment Experience** – Streamline the front-end interface for a more intuitive user journey.  
3. **Dashboard Enhancements** – Expand functionality to provide better insights for administrators.

### 🧠 Responsible AI Considerations
As we build, we're committed to ethical AI development and user-centered design. Key focus areas include:  
1. **Fairness & Bias Mitigation** – Address demographic imbalances and ensure equitable outcomes.  
2. **Transparency & Explainability** – Provide clear reasoning behind AI decisions, especially for users with non-technical backgrounds.  
3. **Data Privacy & Security** – Use secure methods to protect sensitive information.  
4. **Human Oversight & Accountability** – Keep humans in the loop for final decisions and appeals.


---
<h2>📌 Project Kanban Board</h2>
<p>Track our project progress on GitHub using our Kanban board:</p>

<a href="https://github.com/users/ariazand/projects/1/views/1" target="_blank" style="text-decoration: none;">
  <div style="padding: 12px 24px; background-color: #2b3137; color: #ffffff; border-radius: 8px; display: inline-block; font-weight: bold;">
    🚀 View Kanban Board
  </div>
</a>

---

## 📬 Let's Connect!
<table>
  <tr>
    <th>Name</th>
    <th>LinkedIn Profile</th>
  </tr>
  <tr>
    <td>Aria Zand</td>
    <td><a href="https://www.linkedin.com/in/aria-zand" target="_blank">linkedin.com/in/aria-zand</a></td>
  </tr>
  <tr>
    <td>Melissa Parada-Quinatoa</td>
    <td><a href="https://www.linkedin.com/in/melissa-parada-quinatoa/" target="_blank">linkedin.com/in/melissa-parada-quinatoa</a></td>
  </tr>
  <tr>
    <td>John Carl Tagbor</td>
    <td><a href="https://www.linkedin.com/in/jctagbor/" target="_blank">linkedin.com/in/jctagbor</a></td>
  </tr>
  <tr>
    <td>Cathy Fan</td>
    <td><a href="https://www.linkedin.com/in/yihang-fan-0b4b08276/" target="_blank">linkedin.com/in/yihang-fan-0b4b08276</a></td>
  </tr>
</table>

---

## 📄 [References](#)

- [Kaggle Loan Training Dataset](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset/data)
- [Test Dataset](https://github.com/jctagbor/loan-ml-api/blob/main/loan_approval_dataset.csv)
- Professor Chung!
- ACM Digital Library
- ChatGPT (OpenAI)
- Claude (Anthropic)
- Google Colab
- Google Apps Script

<div style="text-align: center;">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f4/Kaggle_Logo.svg/1200px-Kaggle_Logo.svg.png" alt="Kaggle Logo" width="200">
</div>
