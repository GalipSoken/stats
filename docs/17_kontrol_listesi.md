# 17. Özet Kontrol Listesi

Bir analize ya da modele başlamadan önce kendine sor:

**Veriyi tanırken**
- [ ] Her değişkenin tipi ne? Nümerik (sürekli / kesikli) mi, kategorik (nominal / sıralı) mı? Kimlik alanlarını ayırdım mı?
- [ ] Dağılıma grafikle baktım mı? Çarpıklık ve basıklık ne durumda?
- [ ] Ortalama mı medyan mı daha doğru özet?
- [ ] Aykırı değerler hata mı, yoksa bilgi mi?
- [ ] Kullanacağım yöntem normallik istiyor mu? İstiyorsa **neyin** normal olması gerekiyor (veri mi, hatalar mı)?

**Sonuç çıkarırken**
- [ ] Tek sayı yerine güven aralığı verdim mi?
- [ ] p-değerinin yanında etkinin büyüklüğüne de baktım mı? (Ki-karede Cramér's V gibi)
- [ ] Kategorik değişkenlerde ki-kare için beklenen hücre değerleri yeterli mi?
- [ ] Kaç test yaptım? Çoklu test düzeltmesi gerekiyor mu?
- [ ] Bu bir korelasyon mu, yoksa gerçekten nedensellik mi? Karıştırıcı değişken var mı?

**Regresyon kurarken**
- [ ] Doğrusal regresyonda artık grafiklerine baktım mı? (doğrusallık, sabit varyans, bağımsızlık, normallik)
- [ ] VIF ile çoklu doğrusallığı kontrol ettim mi?
- [ ] Lojistik regresyonda nümerik değişkenler log-odds ile doğrusal mı? Değilse WoE / dönüşüm uyguladım mı?
- [ ] Çok sınıflı problemde sınıflar birbirini dışlıyor mu (softmax) yoksa çok etiketli mi (ayrı sigmoid'ler)?
- [ ] Çok sayıda ilişkili değişken varsa PCA'dan önce standartlaştırdım mı? PCA'yı sadece eğitim verisinde mi öğrendim?

**Model değerlendirirken**
- [ ] Eğitim ve test skorları arasında büyük fark var mı? (overfitting)
- [ ] Sınıflar dengesizse accuracy yerine doğru metriği seçtim mi?
- [ ] Olasılıklar kalibre mi?

**Zaman serisiyle çalışırken**
- [ ] Seriyi bileşenlerine ayırdım mı? Trend, mevsimsellik, takvim etkisi, yapısal kırılma var mı?
- [ ] ADF ve KPSS ile durağanlığı test ettim mi? Gerekirse fark / log fark aldım mı?
- [ ] ARIMA / SARIMA dereceleri için ACF–PACF ve AIC/BIC'e baktım mı? Artıklar beyaz gürültü mü (Ljung-Box)?
- [ ] Oynaklık zamanla değişiyor mu (ARCH-LM)? Değişiyorsa GARCH, asimetri varsa EGARCH / GJR-TGARCH denedim mi?
- [ ] Birden çok seri birbirini etkiliyorsa eşbütünleşmeyi (Johansen) test edip VAR ile VECM arasında doğru seçimi yaptım mı?
- [ ] Geçmişle eğitip gelecekle test ettim mi? Naive tahmini geçebiliyor muyum?

**Model canlıdayken**
- [ ] Girdi dağılımları (PSI) ve performans düzenli izleniyor mu?

---

[← 16. Canlıdaki Model: Dağılım Kayması](16_dagilim_kaymasi.md) · [Bölümler](../README.md#bölümler)
