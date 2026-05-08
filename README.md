📱 SMS Spam Detection Project
Bu proje, Veri Bilimine Giriş dersi kapsamında SMS mesajlarını spam veya normal (ham) olarak sınıflandırmak amacıyla geliştirilmiştir. Projede doğal dil işleme (NLP) teknikleri kullanılarak metin verileri temizlenmiş ve farklı makine öğrenmesi modellerinin performansları kapsamlı bir şekilde karşılaştırılmıştır.

📊 Veri Seti ve Analiz
Projede UCI SMS Spam Collection veri seti (5.574 mesaj) kullanılmıştır. Analiz sürecinde şu adımlar izlenmiştir:

Sınıf Dağılımı: Spam ve ham mesaj dağılımları incelenerek sınıfsal denge raporlanmıştır.

Yapısal Analiz: Mesaj uzunlukları karşılaştırılarak spam mesajların tipik özellikleri belirlenmiştir.

Görselleştirme: Tüm veri yapısı istatistiksel grafiklerle analiz edilmiştir.

🛠️ Veri Ön İşleme
Model eğitiminden önce metinler üzerinde şu NLP işlemleri uygulanmıştır:

Metin Temizleme: Küçük harfe dönüştürme ve noktalama işaretlerini temizleme.

Sadeleştirme: Stopwords (etkisiz kelimeler) kaldırılarak veri seti optimize edilmiştir.

Vektörleştirme: * Geleneksel modeller için TF-IDF kullanılmıştır.

LSTM modeli için Word Embedding yapısı tercih edilmiştir.

🧠 Kullanılan Modeller
Projede geleneksel makine öğrenmesi ve derin öğrenme yöntemleri aynı veri seti üzerinde test edilmiştir:

Makine Öğrenmesi Modelleri: SVM, Random Forest, Decision Tree, KNN, Logistic Regression.

Derin Öğrenme: LSTM (Long Short-Term Memory).

📈 Model Değerlendirme
Modeller %80 eğitim ve %20 test verisi ile eğitilmiş, performanslar şu metrikler üzerinden kıyaslanmıştır:

Temel Metrikler: Accuracy, Precision, Recall, F1-Score.

Gelişmiş Analiz: Confusion Matrix ve ROC-AUC eğrileri.

Hata Analizi: Her model için elde edilen hata matrisleri üzerinden yanlış sınıflandırma oranları detaylandırılmıştır.

💻 Kullanılan Teknolojiler
Python • Scikit-Learn • TensorFlow / Keras • Pandas • Matplotlib • Seaborn
