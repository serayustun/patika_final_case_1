# ✈️ Airline Passenger Satisfaction - Veri Analizi Projesi

Bu proje kapsamında, havayolu yolcularının memnuniyetini etkileyen faktörler analiz edilmiştir. Kaggle üzerinden alınan [Airline Passenger Satisfaction Dataset](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction) kullanılmış ve veri ön işleme, sayısal özetleme, eksik ve aykırı değer analizi ile görselleştirme adımları uygulanmıştır.

---

## 🔍 Proje Amacı

Yolcu memnuniyetini etkileyen hizmet kalemlerini daha iyi anlamak, verideki yapısal bozuklukları (eksik/aykırı değerler) tespit etmek ve bu bilgileri daha ileri modelleme süreçlerine temel oluşturacak şekilde sunmaktır.

---

## 📁 Kullanılan Veri Seti

- **Kaynak:** Kaggle  
- **Gözlem Sayısı:** 25.976  
- **Sütun Sayısı:** 25  
- **Hedef Değişken:** `satisfaction` (Yolcu memnuniyet düzeyi)

---

## ⚙️ Kullanılan Teknolojiler

- VS Code (Ortam)
- Python 3.x
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook (.ipynb dosyası)

---

## 🧪 Gerçekleştirilen Adımlar

### 1. Veri Setinin Tanıtımı
- Veri yapısı, değişkenler ve genel istatistiksel yapı incelendi.

### 2. Sayısal Özetler
- Ortalama, medyan, çeyrekler, minimum–maksimum değerler hesaplandı.
- Değişkenlerin genel eğilimleri değerlendirildi.

### 3. Eksik Değer Analizi
- `Arrival Delay in Minutes` sütununda %0.32 oranında eksik veri tespit edildi.

### 4. Aykırı Değer Analizi
- IQR (çeyrekler arası aralık) yöntemi kullanılarak sayısal sütunlardaki aykırı değerler belirlendi.
- En fazla aykırı değer içeren değişkenler:
  - `Departure Delay in Minutes`
  - `Arrival Delay in Minutes`
  - `Checkin service`
  - `Flight Distance`

### 5. Görselleştirme
- Boxplot ve histogram grafiklerle hem dağılımlar hem de uç noktalar görsel olarak yorumlandı.
  
---



