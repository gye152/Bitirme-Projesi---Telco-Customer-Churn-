# 📊 Telco Customer Churn – Bitirme Projesi

Bu proje, **makine öğrenmesi modelleri** kullanılarak **Telco Customer Churn** veri seti üzerinde müşteri kaybını tahmin etmek amacıyla yapılmıştır.  

## 🔍 Projenin Amacı
- Bir telekomünikasyon şirketinin müşteri verilerini analiz ederek, hangi müşterilerin ayrılma ihtimalinin yüksek olduğunu öngörmek.
- Farklı makine öğrenmesi modellerinin performanslarını karşılaştırmak.
- Dengesiz veri setlerinde **SMOTE** ve **threshold ayarlamaları** ile performansı iyileştirmek.

## 🤖 Kullanılan Modeller
- Logistic Regression  
- Decision Tree  
- Random Forest  
- SVC  
- XGBoost  

Her model için hem temel hem de **SMOTE + threshold** uygulanmış sürümler çalıştırılmıştır.  

## 📈 Değerlendirme Metrikleri
Modeller, aşağıdaki performans ölçütleri ile değerlendirilmiştir:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

## 📁 Klasörler
- `notebooks/` → Çalışma defterleri  
- `docs/tez.pdf` → Bitirme proje raporu  

## 📄 Proje Raporu
Tüm sürecin detaylı açıklaması ve karşılaştırmalı sonuçlar için:
[Bitirme Projesi Raporu](docs/tez.pdf)
