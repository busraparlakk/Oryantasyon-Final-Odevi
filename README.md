# Makine Öğrenimi ile Trafik Kazası Riski Tahmini

Bu repo, ABD'deki trafik kazası verilerini kullanarak kaza riskini tahmin etmeye yönelik makine öğrenmesi projelerini içermektedir.

---

## Proje Hakkında

Bu projede, ABD'deki trafik kazalarına ilişkin geniş bir veri seti kullanılarak; **hava durumu**, **saat**, **lokasyon** ve diğer faktörlere göre kaza riski tahmini yapılmaktadır.

Kullanılan sınıflandırma algoritmaları:
- Logistic Regression
- Decision Tree
- XGBoost

---

## İçerik

###  Veri Ön İşleme
- Eksik verilerin temizlenmesi  
- Kategorik değişkenlerin kodlanması  
- Özellik mühendisliği

###  Model Eğitimi
- Farklı algoritmaların uygulanması ve karşılaştırılması

###  Performans Değerlendirme
- Doğruluk (Accuracy)  
- Kesinlik (Precision)  
- Geri Çağırma (Recall)  
- F1-Score

###  Colab Not Defteri
Model geliştirme ve analiz işlemleri için Google Colab kullanılmıştır.

---

## Kullanım

###  Repoyu Klonlayın
```bash
git clone https://github.com/busraparlakk/machine-learning.git
```

###  Gerekli Kütüphaneleri Yükleyin
```bash
pip install -r requirements.txt
```

 Not: Google Colab üzerinden `.ipynb` dosyasını çalıştırabilirsiniz.

---

## Gereksinimler

- Python 3.6 veya üzeri  
- pandas  
- numpy  
- scikit-learn  
- xgboost  
- matplotlib  
- seaborn
