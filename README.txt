# Film Tavsiyesi Sistemi (Movie Recommendation System)

## **Proje Açıklaması**

Film Tavsiyesi Sistemi, kullanıcıların ilgi alanlarına uygun filmleri tahmin edebilen bir makine öğrenmesi modelidir. Bu proje, film özelliklerini analiz ederek ve derin öğrenme yöntemlerini kullanarak kişiselleştirilmiş film önerileri sağlar. Sistem, çeşitli sayısal özellikler (örneğin, popülerlik ve puanlar) ve metin verileri (örneğin, film özetleri) kullanarak kullanıcıların ilgisini çekebilecek filmleri öngörür.

## **Amaç**

Bu projenin amacı, film özelliklerini kullanarak kullanıcıların beğenebileceği filmleri tahmin etmek ve bu tahminleri derin öğrenme algoritmaları ile daha da geliştirmektir. Bu sistem, film endüstrisi için kullanıcı deneyimini iyileştirmek ve kişiselleştirilmiş öneriler sunmak için kullanılabilir.

## **Veri Setleri**

### 1. `tmdb_5000_movies.csv`
- **Film Özellikleri**: Film bütçesi, türler, anahtar kelimeler, popülerlik, oy puanı, vb.
- **Örnek Sütunlar**: `budget`, `genres`, `keywords`, `popularity`, `vote_average`, `title`

### 2. `tmdb_5000_credits.csv`
- **Oyuncular ve Yönetmenler**: Filmdeki oyuncular ve yönetmenler hakkında bilgiler.
- **Örnek Sütunlar**: `cast`, `crew`

## **Proje Adımları**

1. **Veri Okuma ve Temizleme**
   - CSV dosyalarını pandas ile okuma.
   - Gerekli sütunları seçme ve eksik verileri işleme.

2. **Veri Analizi ve Görselleştirme**
   - Sayısal verilerin dağılımını ve ilişkilerini analiz etme.
   - Histogram ve diğer görselleştirme teknikleri ile veri analizi.

3. **Özellik Seçimi ve İşleme**
   - Sayısal özelliklerin (örneğin, `popularity` ve `vote_average`) seçilmesi.
   - Özelliklerin ölçeklendirilmesi ve normalize edilmesi.

4. **Model Oluşturma**
   - Derin öğrenme modelinin (Yapay Sinir Ağı) tasarımı.
   - Modelin eğitim süreci ve hiperparametre ayarları.
   - Performans değerlendirmesi ve sonuçların analiz edilmesi.

5. **Sonuçların Değerlendirilmesi**
   - Modelin doğruluğunu test etme ve performans metrikleri ile değerlendirme.
   - Geliştirme ve iyileştirme önerileri.

## **Kullanılan Araçlar ve Kütüphaneler**

- **Python**: Genel programlama dili.
- **pandas**: Veri okuma ve temizleme.
- **numpy**: Sayısal hesaplamalar.
- **matplotlib ve seaborn**: Veri görselleştirme.
- **scikit-learn**: Özellik mühendisliği ve model değerlendirme.
- **TensorFlow/Keras**: Derin öğrenme modeli oluşturma ve eğitme.

## **Sonuçlar**

Proje tamamlandığında, kullanıcıların ilgi alanlarına göre önerilen filmleri içeren bir model elde edilecektir. Modelin performansı değerlendirilip, sonuçlar analiz edilerek sistemin doğruluğu hakkında bilgi edinilecektir.

