# Machine Learning Projects

Three end-to-end machine learning projects: two fully engineered and deployed on AWS (SageMaker, Lambda, API Gateway, S3), and one LangGraph-based agentic system that combines a flight-delay prediction model with conversational and tool-driven interaction.

---


## ✈️ Aero-Delay-Project
> A conversational LangGraph agent paired with an end-to-end flight delay prediction model, helping passengers understand the likelihood of future flight delays using historical U.S. flight data. The agent can query the prediction model and other tools to deliver useful, contextualised flight information.

- Interactive LangGraph agent capable of answering flight-related queries
- Built-in evaluation layer to reduce incorrect or harmful responses
- Full ML pipeline: preprocessing → training → evaluation → inference


🔗 [GitHub Repository](https://github.com/Harish8622/Aero-delay-prediction)

---

## 🛡️ Phishing Detection
> Real-time phishing URL classifier using XGBoost, deployed with Amazon SageMaker, Lambda, API Gateway, and S3.

- Predicts phishing vs. legitimate URLs using features derived directly from the URL string  
- Fully serverless and low-latency deployment  
- Frontend demo hosted via S3 static website

🔗 [GitHub Repository](https://github.com/Harish8622/AWS_Phishing_Detection)

---

## 📷 SentryCam - AWS
> Smart surveillance camera pipeline that detects high-risk vehicles near ATMs, built with Amazon SageMaker, Lambda, Step Functions, and SNS.

- Uses deep learning (CNN) to classify whether a vehicle is suspicious or not  
- Event-driven design triggered by image uploads to S3  
- Sends real-time alerts via email for suspicious detections

🔗 [GitHub Repository](https://github.com/Harish8622/SentryCam-AWS)

---


