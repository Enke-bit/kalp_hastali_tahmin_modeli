# Kalp Hastalığı Tahmini

Bu proje, Logistic Regression algoritması kullanılarak kalp hastalığı tahmini yapmak için bir makine öğrenimi modeli geliştirdi. 

## Veri Seti

Veri seti, ([veri_kaynağı_linki](https://drive.google.com/file/d/1CEql-OEexf9p02M5vCC1RDLXibHYE9Xz/view)) kaynağından elde edilmiştir ve kalp hastalığı teşhisi ile ilgili çeşitli klinik ve demografik özellikleri içerir.

## Model Performansı

- **Eğitim Verilerinde Doğruluk**: 0.8512
- **Test Verilerinde Doğruluk**: 0.8197

## Gereksinimler

Bu projeyi çalıştırmak için Python 3.x ve aşağıdaki Python kütüphanelerinin yüklü olması gerekmektedir:

- pandas
- numpy
- scikit-learn

Gereksinimleri yüklemek için aşağıdaki komutları kullanabilirsiniz:

- pip install pandas numpy scikit-learn

  
## Nasıl Kullanılır

1. **Veri Yükleme ve Ön İşleme**: Veri setini yükleyin ve ön işleme adımlarını (eksik veri doldurma, özellik seçimi vb.) uygulayın.
   
2. **Model Eğitimi**: Logistic Regression modelini eğitin. Modelinizi `model.fit(X_train, y_train)` şeklinde eğitim verileri ile eğitin.

3. **Model Değerlendirmesi**: Eğitilmiş modelinizi test verileri üzerinde değerlendirin. Doğruluk skorunu hesaplayın ve sonuçları yorumlayın.

## Katkıda Bulunma

Katkıda bulunmak isterseniz, lütfen forklayın ve pull request gönderin. Geliştirme ve iyileştirme önerileri her zaman açıktır.
