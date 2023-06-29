# Gezinomi Müşteri Segmentasyonu ve Gelir Tahmini
Bu proje, Gezinomi şirketinin gerçek işletme verileri üzerinde yapılan bir analiz çalışmasını içermektedir. Amacımız, şirketin yaptığı satışların bazı özelliklerini kullanarak seviye tabanlı yeni satış tanımları oluşturmak ve bu tanımlara göre müşteri segmentleri oluşturarak yeni müşterilerin şirkete ortalama ne kadar kazandırabileceğini tahmin etmektir.
## Veri Seti
Veri seti **"gezinomi_data.xlsx"** adlı dosyada yer almaktadır ve Gezinomi şirketinin yaptığı satışların fiyatlarını ve bu satışlara ait bilgileri içermektedir.

## Analiz Çalışması
Bu analiz çalışması, Python kullanılarak gerçekleştirilmiştir. Veri seti pandas kütüphanesi kullanılarak temizlenmiş ve incelenmiştir. **BG/NDB** ve **GAMMA GAMMA** modelleri kullanılarak **CLTV ( Customer Lifetime Value)** hesaplanmış, müşteri segmentasyonu yapılmış ve gelecekteki müşterilerin şirkete ortalama ne kadar kazandırabileceği tahmin edilmiştir.
