# heart_attack_prediction
Heart attack prediction using Machine Learning.

Kalp Krizi Riski Tahmincisi
Bu notebookta bir kişinin kalp krizi geçirme riskini tahmin etmemize yardımcı olacak bir proje yaptık.
Kalp kirizi geçirme riskini tahmin etmek için çeşitli algoritmalar kullanacağız.

Yapmamız gereken işler:
* Veri analizi
* Feature Engineering
* Standardization
* Model Building
* tahminleme

Dataset'imizi Açıklayalım:
* Age : Hastanın yaşı
* Sex : Hastanın cinsiyeti
* exang: göğüs ağrısı yapan egzersiz (1 = evet; 0 = hayır)
* ca: ana kan damarı sayısı (0-3)
* cp : Göğüs ağrısı tipi
* 0: tipik anjinal
* 1: atipik anjinal
* 2: anjinal olmayan ağrı
* 3: asemptomatik
* trtbps : dinlenme kan basıncı (mm Hg)
* chol : BMI sensörü aracılığıyla alınan mg/dl cinsinden kolesterol
* fbs : (açlık kan şekeri > 120 mg/dl) (1 = true; 0 = false)
* rest_ecg : dinlenme elektrokardiyografik sonuçları
* 0: normal
* 1: ST-T dalga anormalliği olan
* 2: Estes kriterlerine göre olası veya kesin sol ventrikül hipertrofisini gösteren
* thalach : ulaşılan maksimum kalp hızı
* target : 0= daha az kalp krizi geçirme olasılığı 1= daha fazla kalp krizi geçirme olasılığı
