# Ucus-Gecikme-Analizi-ve-Veri-on-ısleme
Bu proje, uçuş verilerini (`ucus_gecikme.xlsx`) inceleyerek uçuşlardaki gecikme durumlarını analiz etmek, verileri temizlemek ve makine öğrenmesi modellerine hazır hale getirmek (özellik mühendisliği) amacıyla geliştirilmiş bir veri bilimi çalışmasıdır.
## Proje Amacı
Havacılık sektöründe operasyonel verimliliği artırmak ve rötar sürelerini tahmin etmek büyük önem taşır. Bu çalışmada, ham uçuş verisi üzerinde eksik veri yönetimi, kategorik değişkenlerin dönüştürülmesi ve verinin eğitim/test setlerine bölünmesi gibi uçtan uca veri ön işleme (data preprocessing) adımları uygulanmıştır.

## Veri Seti Yapısı
Projede kullanılan veri setinde uçuşlara ait şu temel bilgiler yer almaktadır:
- Havayolu şirketi, uçuş rotaları ve zamanlama bilgileri.
- Uçuşların rötar ve gecikme durumlarını gösteren hedef parametreler.

## Kullanılan Teknolojiler
- **Dil:** Python
- **Kütüphaneler:** `pandas`, `matplotlib`, `scikit-learn`

## Uygulanan Adımlar
1. **Veri Yükleme:** `ucus_gecikme.xlsx` dosyasının DataFrame olarak içeri aktarılması.
2. **Keşifsel Veri Analizi (EDA):** Veri yapısının incelenmesi ve eksik/hatalı verilerin tespiti.
3. **Özellik Mühendisliği (Feature Engineering):** Kategorik verilerin sayısal matrislere dönüştürülmesi.
4. **Veri Bölme:** Verinin makine öğrenmesi modellerinde kullanılmak üzere `x_train` ve test setlerine ayrılması.
