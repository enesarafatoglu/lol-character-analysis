# League of Legends Şampiyonları Veri Analizi

Bu proje, League of Legends şampiyonlarına ait bir veri setini analiz ederek onların özellikleri ve rolleri hakkında bilgi edinmeyi amaçlamaktadır. Bu projede kullanılan veri setine Kaggle üzerinden [buradan](https://www.kaggle.com/code/omarmedhat1/league-of-legends-champions-data-analysis) ulaşabilirsiniz.

## Proje Özeti

Bu analizde, veri seti çeşitli aşamalardan geçirilerek incelenmiştir. Projede gerçekleştirilen ana görevler şunlardır:

1. **Veri Yükleme ve Keşif**:
   - Veri seti yüklendi ve yapısının anlaşılması için ilk keşif yapıldı.
   - Özelliklerin özet istatistikleri görüntülendi ve eksik değerler kontrol edildi.

2. **Veri Ön İşleme**:
   - Kategorik sütunlardaki eksik değerler en sık rastlanan değer ile dolduruldu.
   - Kategorik değişkenler kodlandı ve sayısal özellikler ölçeklendirildi.

3. **Görselleştirme**:
   - Eksik değerler için ısı haritası, korelasyon ısı haritası ve özellikler arasındaki ilişkileri keşfetmek için dağılma grafikleri oluşturuldu.
   - `Resourse type` içinde her `Range type`'in dağılımını görselleştiren bir sayım grafiği oluşturuldu.

4. **Makine Öğrenimi Modelleri**:
   - İki makine öğrenimi modeli uygulandı ve değerlendirildi: Rastgele Orman Sınıflandırıcı (Random Forest Classifier) ve Karar Ağacı Sınıflandırıcı (Decision Tree Classifier).
   - Model performansı sınıflandırma raporları ve kafa karışıklığı matrisleri kullanılarak değerlendirildi.

## Nasıl Çalıştırılır

1. Gerekli kütüphanelerin kurulu olduğundan emin olun: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`.
2. Veri setini Kaggle'dan indirin ve proje dizinine yerleştirin.
3. Sağlanan Python betiğini çalıştırarak veri analizi ve modelleme işlemlerini gerçekleştirin.

## Sonuçlar

Modellerin performansı değerlendirildi ve kafa karışıklığı matrisleri tahminlerin doğruluğunu görselleştirmek için kullanıldı. Proje, League of Legends şampiyonlarının özellikleri ve `Range type`'a göre sınıflandırılması hakkında bilgiler sunmaktadır.

Detaylar ve sonuçlar için lütfen sağlanan kod ve çıktılara bakınız.

## Teşekkürler

Bu projede kullanılan veri seti Kaggle üzerinde mevcuttur. Bu değerli kaynağı sağladığı için orijinal yazara teşekkürler.

[Kaggle'daki Veri Seti](https://www.kaggle.com/code/omarmedhat1/league-of-legends-champions-data-analysis)
