# 📚 Web Scraping: Books to Scrape Sitesinden Kitap Verisi Çekme

## 🧾 Proje Açıklaması (TR)

Bu proje, Python kullanarak [Books to Scrape](https://books.toscrape.com) adlı örnek bir e-ticaret sitesinden kitap verilerini toplamayı amaçlar.  
Veriler arasında **kitap isimleri** ve **fiyatlar** bulunmaktadır.  
Toplanan veriler tabloya dönüştürülür, işlenir ve `.csv` dosyasına kaydedilir.  
Ayrıca veriler üzerinde **filtreleme** ve **grafiksel analizler** yapılabilir.

---

## 🚀 Kullanılan Teknolojiler

- Python 3.x
- requests
- BeautifulSoup4
- pandas
- matplotlib (grafikler için - opsiyonel)

---

## ⚙️ Nasıl Çalıştırılır?

1. Google Colab ya da Jupyter Notebook açın.
2. `requests` ve `beautifulsoup4` kütüphanelerini yükleyin:
   ```python
   !pip install requests beautifulsoup4

