# 🧠 Lojistik Regresyon ile Meme Kanseri Teşhisi

Bu proje, **meme kanseri teşhisi** yapmak amacıyla **lojistik regresyon algoritması** kullanılarak Python'da tamamen **sıfırdan (scratch)** geliştirilmiştir. NumPy, pandas gibi temel kütüphanelerle yazılmıştır ve makine öğrenmesinin temel prensiplerini anlamak için ideal bir örnektir.

## 📁 Veri Seti

Veri seti [Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)) veri setidir. `cancer.csv` dosyası içerisinde bulunmalıdır.

- `diagnosis` sütunu:
  - `M` (Malign – Kötü Huylu): 1
  - `B` (Benign – İyi Huylu): 0
- `id` ve `Unnamed: 32` gibi gereksiz sütunlar kaldırılmıştır.

## ⚙️ Kullanılan Kütüphaneler

- NumPy
- pandas
- matplotlib
- scikit-learn

## 🚀 Adımlar

1. **Veri Okuma ve Temizleme**
2. **Veri Normalizasyonu**
3. **Eğitim ve Test Verisinin Ayrılması**
4. **Lojistik Regresyonun Scratch Implementasyonu**
   - Ağırlık & Bias başlatma
   - Sigmoid aktivasyon fonksiyonu
   - (Forward & Backward Propagation
   - Gradient Descent ile öğrenme
5. **Maliyet (Loss) Grafiği**
6. **Model Değerlendirmesi (Accuracy)**



