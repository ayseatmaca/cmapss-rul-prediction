# NASA C-MAPSS Turbofan Motor RUL Tahmini

Bu proje, NASA C-MAPSS turbofan motor veri seti üzerinde Kalan Kullanım Ömrü (RUL) tahmini gerçekleştirmektedir.

## Kullanılan Yöntemler

* BiLSTM + Attention
* Transformer Encoder
* GRU Stacking Ensemble
* Cluster Normalization
* Physics-Informed Loss
* SHAP tabanlı açıklanabilirlik analizi

## Sonuçlar

| Subset | RMSE   | R²    |
| ------ | ------ | ----- |
| FD001  | 12.573 | 0.821 |
| FD002  | 15.230 | 0.758 |
| FD003  | 10.346 | 0.848 |
| FD004  | 13.877 | 0.741 |

## Teknolojiler

Python, PyTorch, NumPy, Pandas, Scikit-learn, SHAP, Matplotlib, Google Colab T4/L4 GPU.

## Proje Sahibi

Ayşe Atmaca
