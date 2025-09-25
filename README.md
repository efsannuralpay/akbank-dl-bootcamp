# 🏞️ Intel Image Classification - Akbank Derin Öğrenme Bootcamp

## Giriş
Bu proje, Akbank Derin Öğrenme Bootcamp kapsamında Intel Image Classification veri seti üzerinde Convolutional Neural Network (CNN) modeli geliştirmeyi amaçlamaktadır. Veri seti, 6 farklı kategoriden (binalar, orman, buzul, dağ, deniz, sokak) oluşan doğal ve yapay ortam görüntülerini içermektedir.

## Proje Detayları
- **Veri Seti:** Intel Image Classification
- **Sınıf Sayısı:** 6
- **Model:** Özel CNN Mimarisi
- **Framework:** TensorFlow/Keras

### Kullanılan Teknikler
- Veri ön işleme ve normalizasyon
- Data Augmentation (rotation, flip, zoom, shift)
- CNN katmanları (Conv2D, MaxPooling2D, Dropout)
- Transfer Learning konsepti
- Model değerlendirme metrikleri

## Metrikler
### Eğitim Sonuçları
- **Test Accuracy:** %81.17
- **Test Loss:** 0.5336
- **Eğitim Süresi:** 10 Epoch

### Model Performansı
Model, validation set üzerinde tutarlı bir performans sergilemiştir. Accuracy ve loss grafikleri incelendiğinde overfitting olmadığı gözlemlenmiştir. Confusion matrix analizi, özellikle "forest" ve "mountain" sınıflarında yüksek başarı gösterdiğini ortaya koymuştur.

### Yorumlar
- Data augmentation teknikleri modelin genelleme yeteneğini artırmıştır
- Dropout katmanları overfitting'i önlemede etkili olmuştur
- CNN mimarisi görüntü sınıflandırma için uygun bir seçimdir

## Ekler
### Notebook İçeriği
- Veri keşfi ve görselleştirme
- CNN modeli tasarımı ve eğitimi
- Model değerlendirme ve metrikler
- Grad-CAM görselleştirme konsepti
- Hiperparametre optimizasyon önerileri

### Teknik Detaylar
- Görüntü boyutu: 150x150 piksel
- Batch size: 32
- Optimizer: Adam
- Loss function: Categorical Crossentropy

## Sonuç ve Gelecek Çalışmalar
### Elde Edilen Sonuçlar
Proje başarıyla tamamlanmış olup, %81.17 test accuracy ile tatmin edici bir performans elde edilmiştir. Tüm bootcamp gereksinimleri karşılanmıştır.

### Gelecek Çalışmalar
1. **Transfer Learning:** VGG16, ResNet gibi önceden eğitilmiş modellerle performansı artırmak
2. **Hiperparametre Optimizasyonu:** Grid Search veya Bayesian Optimization ile daha iyi parametreler bulmak
3. **Model Deployment:** Streamlit ile kullanıcı dostu bir arayüz geliştirmek
4. **Veri Çeşitliliği:** Daha fazla veri toplayarak modelin genelleme yeteneğini artırmak
5. **Ensemble Methods:** Birden fazla modeli birleştirerek daha kararlı sonuçlar elde etmek

## Linkler
### Kaggle Notebook
- **Ana Notebook:** [Intel Image Classification - CNN Model](https://www.kaggle.com/code/efsannuralpay/akbankprojesi)

### GitHub Repo
- **Proje Reposu:** [akbank-dl-bootcamp](https://github.com/efsannuralpay/akbank-dl-bootcamp)

---

**Akbank Derin Öğrenme Bootcamp - Eylül 2025**  
*Efşannur Alpay
