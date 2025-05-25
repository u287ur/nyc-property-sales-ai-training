🌍 Available Languages:
[🇺🇸 English](README.md) | [🇹🇷 Türkçe](README.tr.md)

# NYC Emlak Satış Fiyatı Tahmini

Bu repo, New York City emlak satış verileri üzerinde makine öğrenmesi ile satış fiyatı tahmini yapmak amacıyla hazırlanmıştır. Projede, Kaggle'dan alınan "NYC Property Sales" veri seti kullanılmıştır. Farklı regresyon algoritmaları (Ridge, XGBoost) ile modelleme yapılmış ve sonuçlar karşılaştırılmıştır.

# Giriş

Bu projede, New York City'deki emlak satış verileri analiz edilerek, bir mülkün satış fiyatı tahmin edilmeye çalışılmıştır.  
Kullanılan veri seti: [Kaggle - NYC Property Sales](https://www.kaggle.com/datasets/new-york-city/nyc-property-sales)

Yapılan başlıca işlemler:
- Veri temizleme ve ön işleme (eksik değerler, aykırı değerler, tip dönüşümleri)
- Özellik mühendisliği (one-hot encoding, target encoding, yeni değişkenler)
- Eğitim/test veri seti ayrımı
- Ridge ve XGBoost regresyon modelleri ile tahmin
- Model değerlendirme ve karşılaştırma

Teknik detaylar ve kod açıklamaları, notebook dosyası içindeki markdown hücrelerinde detaylıca verilmiştir.

# Metrikler

Model performansı aşağıdaki metriklerle değerlendirilmiştir:
- Ortalama Kare Hatası (MSE)
- Ortalama Mutlak Hata (MAE)
- R² skoru

Elde edilen sonuçlar:
- **Ridge Regression R²:** 0.43
- **XGBoost Regression R²:** 0.66

Sonuçlara göre, XGBoost modeli daha yüksek bir başarı sağlamıştır.  
Modelin performansı, özellikle lokasyon bazlı fiyat farklılıklarını yakalamak için yapılan target encoding ile artmıştır.

# Sonuç ve Gelecek Çalışmalar

Bu çalışma, NYC emlak piyasasında satış fiyatı tahmini için temel bir makine öğrenmesi yaklaşımı sunmaktadır.  
Gelecekte, modelin başarısını artırmak için aşağıdaki geliştirmeler yapılabilir:
- Daha fazla kategorik değişkenin (ör. mahalle, bina tipi) modele dahil edilmesi
- Özellik seçimi ve hiperparametre optimizasyonunun daha kapsamlı yapılması
- Modelin web arayüzü ile son kullanıcıya sunulması
- Zaman serisi analizleri veya farklı regresyon algoritmalarının denenmesi

# Linkler

- [Kaggle - NYC Property Sales Veri Seti](https://www.kaggle.com/datasets/new-york-city/nyc-property-sales)
- [Kodlar (Kaggle)](https://www.kaggle.com/code/goker67/decision-trees-acc-metrics-feature-selection)