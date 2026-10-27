# 11. Özet Kontrol Listesi

Bir analize ya da modele başlamadan önce kendine sor:

**Veriyi tanırken**
- [ ] Dağılıma grafikle baktım mı? Çarpık mı, kalın kuyruklu mu?
- [ ] Ortalama mı medyan mı daha doğru özet?
- [ ] Aykırı değerler hata mı, yoksa bilgi mi?

**Sonuç çıkarırken**
- [ ] Tek sayı yerine güven aralığı verdim mi?
- [ ] p-değerinin yanında etkinin büyüklüğüne de baktım mı?
- [ ] Kaç test yaptım? Çoklu test düzeltmesi gerekiyor mu?
- [ ] Bu bir korelasyon mu, yoksa gerçekten nedensellik mi? Karıştırıcı değişken var mı?

**Model kurarken**
- [ ] Eğitim ve test skorları arasında büyük fark var mı? (overfitting)
- [ ] Zaman içeren veride geçmişle eğitip gelecekle mi test ettim?
- [ ] Sınıflar dengesizse accuracy yerine doğru metriği seçtim mi?
- [ ] Olasılıklar kalibre mi?

**Model canlıdayken**
- [ ] Girdi dağılımları (PSI) ve performans düzenli izleniyor mu?

---

## Önerilen Öğrenme Sırası

| Hafta | Konular |
|---|---|
| 1 | Tanımlayıcı istatistik, görselleştirme, dağılımlar |
| 2 | Olasılık, Bayes, örneklem, MLT, güven aralığı, bootstrap |
| 3 | Hipotez testleri, A/B testi, çoklu test |
| 4 | Korelasyon, doğrusal ve lojistik regresyon |
| 5 | Model değerlendirme: overfitting, CV, metrikler, kalibrasyon |
| 6 | Zaman serisi temelleri, nedensellik, model izleme |

---

[← 10. Canlıdaki Model: Dağılım Kayması](10_dagilim_kaymasi.md) · [Bölümler](../README.md#bölümler)
