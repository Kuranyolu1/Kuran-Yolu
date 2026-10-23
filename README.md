# 📖 Kur'an Yolu — Açık Kaynak Veri Havuzu

Bu depo, **Kur'an Yolu** mobil uygulaması için hazırlanan yüksek kaliteli, doğrulanmış İslami veri setlerini (Hadis Külliyatı, Mealler vb.) içerir.

---

## 📚 Kütüb-i Sitte Hadis Külliyatı

Tüm hadisler Arapça metinleri, Türkçe mealleri, tahric/derecelendirme bilgileri (Sahih, Hasen, Zayıf), ravi zincirleri ve bab başlıkları ile birlikte eksiksiz olarak JSON formatında derlenmiştir.

### 📊 Külliyat İstatistikleri

| Kitap | Klasör | Bölüm (Kitab) Sayısı | Toplam Hadis |
| :--- | :--- | :---: | :---: |
| **Sahih-i Buhârî** (صحيح البخاري) | [`hadisler/buhari/`](hadisler/buhari/) | 97 | 7.583 |
| **Sahih-i Müslim** (صحيح مسلم) | [`hadisler/muslim/`](hadisler/muslim/) | 57 | 7.469 |
| **Sünen-i Nesâî** (سنن النسائي) | [`hadisler/nesai/`](hadisler/nesai/) | 51 | 5.765 |
| **Sünen-i Ebû Dâvûd** (سنن أبي داود) | [`hadisler/ebudavud/`](hadisler/ebudavud/) | 43 | 5.274 |
| **Sünen-i Tirmizî** (جامع الترمذي) | [`hadisler/tirmizi/`](hadisler/tirmizi/) | 49 | 3.976 |
| **Sünen-i İbn Mâce** (سنن ابن ماجه) | [`hadisler/ibnmace/`](hadisler/ibnmace/) | 38 | 4.343 |
| **GENEL TOPLAM** | | **335 Bölüm** | **34.410 Hadis** |

---

## 🚀 CDN / Doğrudan Erişim URL Formatı

Uygulama veya web servisleri üzerinden doğrudan çekmek için raw GitHub URL'leri:

- **Kitap Meta Bilgisi:**  
  `https://raw.githubusercontent.com/Kuranyolu1/Kuran-Yolu/main/hadisler/{kitap}/meta.json`  
  *(Örn: `.../hadisler/buhari/meta.json`)*

- **Bölüm Hadisleri (JSON Array):**  
  `https://raw.githubusercontent.com/Kuranyolu1/Kuran-Yolu/main/hadisler/{kitap}/kitab_{bolumNo}.json`  
  *(Örn: `.../hadisler/buhari/kitab_1.json`, `.../hadisler/muslim/kitab_0.json`)*

- **Tek Parça Kitap (Tüm Bölümler & Hadisler):**  
  `https://raw.githubusercontent.com/Kuranyolu1/Kuran-Yolu/main/hadisler/{kitap}/{kitap}_tamami.json`

- **Genel Hadis İndeksi:**  
  `https://raw.githubusercontent.com/Kuranyolu1/Kuran-Yolu/main/hadisler/hadisler_index.json`
