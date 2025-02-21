# 📈 Time-Series Forecasting with RNN, LSTM, and GRU  

This repository contains a **deep learning-based time-series forecasting project**, comparing different models (**Basic RNN, LSTM, and GRU**) for predicting financial data.  

---

## 🚀 Project Overview  

In this project, we:  
✅ Preprocess and analyze time-series data.  
✅ Train and evaluate **RNN, LSTM, and GRU** models.  
✅ Fine-tune hyperparameters using **Grid Search**.  
✅ Compare model performance using **RMSE, MAE, and Sign Prediction Accuracy**.  

---

## 📊 Model Performance Comparison  

| **Model**   | **Train RMSE** | **Valid RMSE** | **Test RMSE** | **Train MAE** | **Valid MAE** | **Test MAE** | **Time (s)** |
|------------|--------------|--------------|-------------|-------------|-------------|------------|------------|
| **BasicRNN** | 0.0122 | 0.0187 | 0.0168 | 0.0089 | 0.0133 | 0.0135 | **39.56 s** |
| **LSTM** | 0.0083 | 0.0139 | 0.0146 | 0.0056 | 0.0104 | 0.0117 | 88.20 s |
| **GRU** | **0.0079** | **0.0129** | **0.0122** | **0.0052** | **0.0092** | **0.0092** | 78.66 s |

🏆 **Conclusion**:  
- **GRU is the best-performing model**, balancing accuracy and computation time.  
- **LSTM is slightly less accurate but takes longer to train**.  
- **BasicRNN is the fastest but has the highest error**.  

---

## 🔧 Installation & Setup  

To run the project locally:  

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
conda create --name time-series-env python=3.9
conda activate time-series-env
pip install -r requirements.txt
