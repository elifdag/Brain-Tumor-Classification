# Brain Tumor Classification

**Akbank Derin Öğrenme Bootcamp** kapsamında, MRI görüntüleri kullanarak geliştirdiğim beyin tümörlerini sınıflandırma projemde **Convolutional Neural Network (CNN)** tabanlı bir model kullanılmıştır.

# Giriş  

Projemde kullandığım veri seti Kaggle üzerinde yer alan **Brain Tumor MRI Images Dataset** veri setidir. Veri setinde dört sınıf yer almaktadır:

- Glioma  
- Meningioma  
- Pituitary Tumor  
- No Tumor  

Proje sürecinde gerçekleştirilen temel adımlar:  
- Görsellerin yeniden boyutlandırılması ve normalizasyonu  
- Train/Validation/Test ayrımı  
- Veri artırma (Data Augmentation) → rotation, flip, zoom, shift gibi yöntemler  
- CNN modeli kurulumu ve eğitimi  
- Eğitim/Doğrulama setlerinde başarı takibi 

# Metrikler  

Model eğitimi sonucunda elde edilen performans metrikleri:  
- **Accuracy (Doğruluk):** %87 civarında  
- **Confusion Matrix** → sınıflar arası karışıklıklar analiz edildi  
- **Classification Report** → precision, recall ve f1-score değerleri raporlandı  
- **Epoch bazlı Accuracy/Loss grafikler** → overfitting/underfitting yorumlandı  
- **Grad-CAM** → modelin MRI görüntülerinde hangi bölgeleri dikkate aldığı görselleştirildi  

# Ekler  

Proje kapsamında ayrıca:  
- **Dropout** kullanılarak overfitting azaltılmaya çalışıldı.
- Notebook içerisinde aşamalar detaylı markdown hücreleriyle açıklandı. 

# Sonuç ve Gelecek Çalışmalar  


Sonuç olarak, üzerinde çalıştığım CNN modelimin geliştirilmesi ile sağlık alanında uzmanlara yardım edilebileceği ve başarılı işler yapılabileceği görüldü.

Gelecekte yapılabilecek geliştirmeler:
- Daha büyük ve dengeli veri setleriyle modelin yeniden eğitilmesi  
- **Transfer Learning** (ResNet, VGG16, EfficientNet) gibi hazır ağların kullanılması  
- Modelin **Streamlit/Gradio arayüzü** ile kullanıcıya sunulması  
- Dinamik veri toplama yöntemleriyle gerçek zamanlı kullanım senaryolarının denenmesi  

# Linkler  

📌 Kaggle Notebook: [Brain Tumor Classification Project](https://www.kaggle.com/code/elifdg/notebook9f887ae9aa)  
