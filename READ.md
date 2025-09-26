# ♻️ Garbage Classification with CNN & Keras Tuner

## 🎯 Proje Amacı
Bu proje, evsel atıkları görsel olarak sınıflandırmak amacıyla bir derin öğrenme modeli geliştirmeyi hedefler. Görüntü önişleme, veri artırımı, model eğitimi, hiperparametre optimizasyonu ve Grad-CAM görselleştirmesi adımlarını içerir.

## 📊 Veri Seti
Kaggle'dan alınan "Garbage Classification" veri seti, 6 sınıfa ayrılmış binlerce görsel içerir:
- cardboard
- glass
- metal
- paper
- plastic
- trash

Veri seti Kaggle Notebook üzerinden bağlanmıştır. `.txt` dosyaları dışlanmış, sadece görsel klasörleri kullanılmıştır.

## 🧠 Kullanılan Yöntemler
- Veri önişleme (resize, normalize, one-hot encoding)  
- Data augmentation (rotation, zoom, flip, brightness)  
- CNN mimarisi  
- Keras Tuner ile hiperparametre optimizasyonu  
- Model değerlendirme: Accuracy, Loss, Confusion Matrix  
- Grad-CAM ile görsel yorumlama

## 📈 Sonuçlar
- En iyi doğruluk: %XX (Keras Tuner ile optimize edilmiş model)  
- Confusion Matrix ile sınıf bazlı başarı analizi  
- Grad-CAM ile modelin dikkat bölgeleri görselleştirilmiştir

## 🔗 Kaggle Notebook
[Kaggle Notebook Linkini Buraya Ekleyin](https://www.kaggle.com/...)

