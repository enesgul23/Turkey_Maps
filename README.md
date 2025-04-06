# 🇹🇷 Python'da GeoPandas Kullanarak Türkiye Haritası Çizdirmek

**Drawing a Turkey Map in Python by using GeoPandas**

Bu proje, Python programlama dili ile **GeoPandas** kütüphanesini kullanarak Türkiye haritasını çizmek ve illeri belirli gruplara göre renklendirmek amacıyla hazırlanmıştır.  
Burada paylaşılan shapefile/GeoJSON dosyaları ve kodlar yardımıyla; iller için veri toplama, gruplandırma veya bölgesel analiz gibi işlemler yapabilirsiniz.

<br/>

## 📸 Örnek Harita Çıktısı (İsimsiz)

Aşağıdaki görselde il sınırları yer almaktadır, ancak il isimleri **görünmemektedir**:

<p align="center">
  <img src="turkiye_il_gruplari_isimsiz.svg" alt="Türkiye Haritası İsimsiz" width="700"/>
</p>

> **Not:** Eğer il isimleri içeren bir sürüm görmek isterseniz, `turkiye_il_gruplari_isimli.svg` gibi alternatif dosyalara göz atabilirsiniz.

<br/>

## 📂 Proje Yapısı


- **TUR_adm1.***: Shapefile dosyaları (Türkiye illerinin coğrafi verisi).  
- **`turkey_province_maps.ipynb`**: GeoPandas kullanarak harita çizim ve renklendirme kodları.  
- **`turkiye_il_gruplari_isimsiz.svg`**: İsimsiz harita çıktısı.  
- **`turkiye_il_gruplari_isimli.svg`**: İsimli harita çıktısı (isteğe bağlı).  

<br/>

## ⚙️ Kurulum & Kullanım

1. **Ortamı hazırlayın**  
   - Tercihen bir sanal ortam veya conda ortamı oluşturun.
   - Gerekli kütüphaneleri yükleyin:
     ```bash
     pip install geopandas matplotlib adjustText
     ```
     Ya da conda kullanıyorsanız:
     ```bash
     conda install -c conda-forge geopandas matplotlib adjustText
     ```
2. **Kodları çalıştırın**  
   - `turkey_province_maps.ipynb` dosyasını açın.  
   - Çalıştırmadan önce shapefile dosyanızın adını veya dizin yolunu doğru belirlediğinizden emin olun.
   - Kod çalıştıktan sonra `turkiye_il_gruplari_isimsiz.svg` benzeri bir çıktı üretecektir.

3. **Haritayı inceleyin**  
   - Çıktı haritasını (örneğin `.svg` veya `.png` formatında) bir resim görüntüleyicisi veya tarayıcıda açıp görüntüleyebilirsiniz.

<br/>

## 🔎 Öne Çıkan Özellikler

- **GeoPandas** kullanarak `.shp` formatındaki coğrafi veriyi okuyabilir, kolayca pandas benzeri işlemler uygulayabilirsiniz.  
- **Gruplandırma** (ör. illeri bölgelere ayırma, farklı kategorilere göre renklendirme) kolayca yapılır.  
- **`adjustText`** kütüphanesiyle harita üzerindeki etiketlerin (il isimleri vb.) üst üste binmesi azaltılabilir.

<br/>

## 📌 Veri Kaynakları

- [GeoPandas Resmi Belgeleri](https://geopandas.org/)  
- [Türkiye Shapefile (TUR_adm1.shp)](https://github.com/ozancanozdemir/Python-da-GeoPandas-Kullanarak-Turkiye-Haritasi-Cizdirmek-Drawing-a-Turkey-Map-in-Python-)  
- [TUIK ADNKS 2021 Verileri](https://data.tuik.gov.tr) (Yaş/Nüfus istatistikleri, opsiyonel)

<br/>

## 🤝 Katkıda Bulunun

- Hatalı veri, yazım hatası veya geliştirme önerileriniz varsa **pull request** veya **issue** açarak projeye katkı sağlayabilirsiniz.

<br/>

## 💡 Lisans

Bu proje açık kaynak olarak paylaşılmaktadır. Lisans koşullarını `LICENSE` dosyasından inceleyebilirsiniz (yoksa ekleyebilirsiniz).

---

<p align="center">
  <b>İyi Çalışmalar!</b>
</p>
