# Chronic Disease – Diabetes Prediction using IBM Cloud

This project uses a machine learning model deployed on IBM Cloud to predict the risk of diabetes based on patient health data (PIMA dataset).

## 🔧 Technologies Used
- IBM Watson Machine Learning
- IBM Cloud
- Python (Jupyter Notebook)
- PIMA Diabetes Dataset
- JSON API for predictions

## 🚀 Features
- Predicts diabetes risk using patient data
- Deployed model accessible via REST API
- Real-time testing with JSON input and output

## 🖼️ Screenshots
Screenshots of the project include:
- Model Training Summary
- Deployment Process
- Final Prediction Output

## 📎 Project Files
- 📝 [Final PPT (IBM Project)](./finalprojectibm.pdf)
- 📄 [JSON Test Output](./ChronicDiseasedeploy2_test_result.json)

## 📊 Example Prediction Output

```json
[
  {
    "fields": ["prediction", "probability"],
    "values": [
      [1, [0.27, 0.72]],
      [1, [0.32, 0.67]],
      [0, [0.61, 0.38]],
      [0, [0.76, 0.23]],
      [0, [0.82, 0.17]]
    ]
  }
]
```

## 🔗 IBM Deployment Endpoint (for reference)
`https://eu-de.ml.cloud.ibm.com/ml/v4/deployments/159d6a90-8e0f-4c42-a684-06077e317ef1/predictions?version=2021-05-01`
