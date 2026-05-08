
📱 SMS Spam Detection Project
Bu proje, Veri Bilimine Giriş dersi kapsamında SMS mesajlarını spam veya normal (ham) olarak sınıflandırmak amacıyla geliştirilmiştir. Projede doğal dil işleme (NLP) teknikleri kullanılarak metin verileri temizlenmiş ve farklı makine öğrenmesi modellerinin performansları kapsamlı bir şekilde karşılaştırılmıştır.

📊 Veri Seti ve Analiz
Projede UCI SMS Spam Collection veri seti (5.574 mesaj) kullanılmıştır. Analiz sürecinde şu adımlar izlenmiştir:

Spam ve ham mesaj dağılımları incelenerek sınıfsal denge raporlanmıştır.

Mesaj uzunlukları karşılaştırılarak spam mesajların yapısal özellikleri belirlenmiştir.

Tüm veri yapısı istatistiksel grafiklerle görselleştirilmiştir.

🛠️ Veri Ön İşleme
Model eğitiminden önce metinler üzerinde şu NLP işlemleri uygulanmıştır:

Küçük harfe dönüştürme ve noktalama işaretlerini temizleme.

Stopwords (etkisiz kelimeler) kaldırılarak veri sadeleştirilmiştir.

Geleneksel modeller için TF-IDF, LSTM modeli için ise Word Embedding yapısı kullanılarak metinler sayısal forma dönüştürülmüştür.

🧠 Kullanılan Modeller
Projede hem geleneksel makine öğrenmesi hem de derin öğrenme yöntemleri aynı veri seti üzerinde test edilmiştir:

Makine Öğrenmesi Modelleri: SVM, Random Forest, Decision Tree, KNN, Logistic Regression.

Derin Öğrenme: LSTM (Long Short-Term Memory).

📈 Model Değerlendirme
Modeller %80 eğitim ve %20 test verisi ile eğitilmiş, performanslar şu metrikler üzerinden kıyaslanmıştır:

Metrikler: Accuracy, Precision, Recall, F1-Score, Confusion Matrix ve ROC-AUC.

Her model için elde edilen hata matrisleri üzerinden yanlış sınıflandırma oranları analiz edilmiştir.

💻 Kullanılan Teknolojiler
Python | Scikit-Learn | TensorFlow / Keras | Pandas | Matplotlib | Seaborn
