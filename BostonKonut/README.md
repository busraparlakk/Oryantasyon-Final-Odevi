#  Trafik Kazası Riski Tahmini – Makine Öğrenmesi Projesi

Bu proje, ABD trafik kazası verilerini kullanarak, çeşitli faktörlere göre kaza riskini tahmin etmeyi amaçlayan bir makine öğrenmesi çalışmasıdır.  
Proje, Google Colab üzerinde geliştirilmiş ve Logistic Regression, Decision Tree ile XGBoost gibi sınıflandırma algoritmaları uygulanmıştır.

🔗 **Colab Not Defteri Bağlantısı:** [Google Colab'da Aç](https://colab.research.google.com/drive/16KToGcTx_xTFYK3ZvPxvRZsdd2xb2gak)

---

## 📌 Proje Özeti

Bu çalışmada, ABD'deki trafik kazalarına ilişkin geniş bir veri seti analiz edilerek, hava durumu, saat, lokasyon ve diğer faktörlere göre kaza riski tahmini yapılmaktadır.  
Amaç, yüksek riskli koşulları ve bölgeleri belirleyerek trafik güvenliğini artırmaktır.

---

## 🧰 Kullanılan Teknolojiler ve Kütüphaneler

- Python 3.6 veya üzeri  
- pandas  
- numpy  
- scikit-learn  
- xgboost  
- matplotlib  
- seaborn

---

## 🧪 Proje Aşamaları

### 1. Veri Ön İşleme
- Eksik verilerin temizlenmesi  
- Kategorik değişkenlerin kodlanması  
- Özellik mühendisliği

### 2. Model Eğitimi
- Logistic Regression  
- Decision Tree  
- XGBoost

### 3. Performans Değerlendirme
- Doğruluk (Accuracy)  
- Kesinlik (Precision)  
- Geri Çağırma (Recall)  
- F1-Score

---

##  Kullanım Talimatları

### 1. Repoyu Klonlayın
```bash
git clone https://github.com/busraparlakk/machine-learning.git
```

### 2. Gerekli Kütüphaneleri Yükleyin
```bash
pip install -r requirements.txt
```

### 3. Google Colab Üzerinden Not Defterini Açın
[Colab Not Defteri](https://colab.research.google.com/drive/16KToGcTx_xTFYK3ZvPxvRZsdd2xb2gak)

---

## 📌 Notlar

- Proje, gerçek dünya verileri kullanılarak geliştirilmiştir.  
- Model performansı, çeşitli metriklerle değerlendirilmiştir.  
- Google Colab ortamında çalıştırmak için internet bağlantısı gereklidir.
