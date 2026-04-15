Proje, Seaborn kütüphanesinde yer alan ham Titanic verisini alır, eksik verileri tamamlar, anlamlı özellikler (feature engineering) türetir ve iki farklı algoritma (Logistic Regression ve Random Forest) ile hayatta kalma durumunu tahmin eder.

One Cıkan Ozellikler
Veri Temizleme: Eksik yas verilerinin medyan ile doldurulması, gereksiz sutunların (deck, embark_town vb.) drop edilmesi.
Gorsellestirme: Matplotlib ve Seaborn kullanarak infografik stilinde (Cinsiyet, Bilet Sınıfı ve Yas yogunlugu) analizler.
Ozellik Muhendisligi: family_size degiskeninin uretilmesi ve kategorik verilerin sayısal formata (One-Hot Encoding) donusturulmesi.
Model Kıyaslama: Lojistik Regresyon ve Random Forest modellerinin dogruluk skorlarının karsılastırılması.
Kisiye Ozel Tahmin: Kullanıcının kendi girdigi verilere gore "Ben Titanic'te olsaydım hayatta kalır mıydım?" sorusuna yanıt veren tahmin sistemi.


Kullanılan Teknolojiler
Python 3.x
Pandas & NumPy: Veri manipülasyonu.
Seaborn & Matplotlib: Veri görselleştirme ve istatistiksel grafikler.
Scikit-Learn:StandardScaler (Veri Olcekleme) train_test_split (Veri Setini Ayırma) LogisticRegression & RandomForestClassifier (Modelleme) Confusion Matrix & Classification Report (Metrikler)

Model Basarısı ve Faktorler
En Onemli Faktorler: Model kararlarında Cinsiyet (Sex), Yas (Age) ve Bilet Fiyatı (Fare) en yuksek oneme sahip degiskenlerdir.
Karmasıklık Matrisi (Confusion Matrix): Modelin hata payı ve dogru tahmin oranları gorsel bir karne (heatmap) ile sunulmaktadır.
