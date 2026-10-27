# 3. Dağılımlar: Verinin Şekli

Dağılım, "hangi değerin ne sıklıkla geldiğini" anlatan şekildir. Doğru dağılımı tanımak, doğru modeli ve doğru testi seçmenin yarısıdır.

![Temel dağılımlar](img/04_dagilimlar.png)

| Dağılım | Ne zaman görülür? | Bankacılık örneği |
|---|---|---|
| **Normal (çan eğrisi)** | Birçok küçük etkinin toplamı | Ölçüm hataları, ortalamalar |
| **Binom** | "Kaç tanesi evet dedi?" | 20 müşteriden kaçı kampanyaya katıldı |
| **Poisson** | Belirli sürede kaç olay oldu? | Saatte gelen şikayet, günlük ATM arızası |
| **Log-normal** | Pozitif, sağa çarpık büyüklükler | Kredi tutarı, gelir, bakiye |

## Kalın Kuyruklar: Finansın Tuzağı

Normal dağılım, uç olayların **neredeyse imkansız** olduğunu varsayar. Gerçek piyasa getirileri ise öyle değildir: büyük çöküşler, normal dağılımın söylediğinden **binlerce kat daha sık** yaşanır.

![Kalın kuyruk](img/05_kalin_kuyruk.png)

> 💡 Risk modellerinde "normal dağılım varsayalım" demek, en tehlikeli senaryoları görmezden gelmek anlamına gelebilir. Uç değerlerin sıklığını her zaman veriyle kontrol et.

---

[← 2. Olasılık ve Bayes Düşüncesi](02_olasilik_ve_bayes.md) · [Bölümler](../README.md#bölümler) · [4. Örneklem ve Tahmin →](04_orneklem_ve_tahmin.md)
