# Data Scientist İçin Temel İstatistik

*Formülsüz, grafiklerle, herkesin anlayacağı dilde*

Bu repo, bir data scientist'in her gün kullandığı istatistik fikirlerini **sezgisel olarak** anlatan Türkçe bir rehberdir. Amaç formül ezberletmek değil; bir grafiğe, bir model çıktısına, bir A/B testi ya da zaman serisi sonucuna bakınca **doğru soruyu sorabilmeyi** öğretmek. Örneklerin çoğu bankacılık dünyasından: fraud alarmları, temerrüt, kredi skoru, faiz, kur ve mevduat.

![Bayes ızgarası](docs/img/03_bayes_izgara.png)

## Bölümler

### Temeller

| # | Bölüm | Neler var? |
|---|---|---|
| 1 | [Veri Tipleri](docs/01_veri_tipleri.md) | Nümerik (sürekli, kesikli) · kategorik (nominal, sıralı) · tipe göre yöntem seçimi · kodlama |
| 2 | [Tanımlayıcı İstatistik](docs/02_tanimlayici_istatistik.md) | Ortalama, medyan, mod · varyans, standart sapma, IQR · aykırı değerler · momentler: çarpıklık ve basıklık |
| 3 | [Olasılık ve Bayes Düşüncesi](docs/03_olasilik_ve_bayes.md) | Koşullu olasılık · Bayes teoremi ve fraud alarmı örneği |
| 4 | [Dağılımlar](docs/04_dagilimlar.md) | Normal, binom, Poisson, log-normal · 68-95-99.7 kuralı · normal dağılım varsayımları · normallik testleri ve Q-Q grafiği · kalın kuyruklar |
| 5 | [Örneklem ve Tahmin](docs/05_orneklem_ve_tahmin.md) | Merkezi Limit Teoremi · büyük sayılar yasası · güven aralığı · bootstrap |
| 6 | [Hipotez Testleri](docs/06_hipotez_testleri.md) | p-değeri · Tip I/II hata · hangi test ne zaman · ki-kare testi · çoklu test · A/B testi |

### Modelleme

| # | Bölüm | Neler var? |
|---|---|---|
| 7 | [Korelasyon ve Doğrusal Regresyon](docs/07_korelasyon_ve_dogrusal_regresyon.md) | Pearson / Spearman · doğrusal regresyon · varsayımlar (LINE + çoklu doğrusallık) ve testleri |
| 8 | [Lojistik Regresyon, Sigmoid ve Softmax](docs/08_lojistik_regresyon_sigmoid_softmax.md) | Odds ve log-odds · lojistik regresyon varsayımları · sigmoid · softmax |
| 9 | [Temel Bileşenler Analizi (PCA)](docs/09_temel_bilesenler_analizi.md) | Boyut indirgeme · scree grafiği · faiz eğrisi ve anomali uygulamaları |
| 10 | [Model Değerlendirme](docs/10_model_degerlendirme.md) | Overfitting · bias-variance · cross-validation · precision/recall · ROC-AUC · dengesiz sınıflar · kalibrasyon |

### Zaman Serileri

| # | Bölüm | Neler var? |
|---|---|---|
| 11 | [Zaman Serisi Temelleri](docs/11_zaman_serisi_temelleri.md) | Bileşenler · durağanlık, fark alma, ADF/KPSS · ACF ve PACF |
| 12 | [ARIMA ve SARIMA](docs/12_arima_sarima.md) | AR, I, MA · Box-Jenkins yaklaşımı · mevsimsel model · ARIMAX |
| 13 | [ARCH, GARCH ve Türevleri](docs/13_arch_garch.md) | Volatilite kümelenmesi · ARCH · GARCH · EGARCH · GJR / TGARCH · haber etkisi eğrisi |
| 14 | [VAR ve VECM](docs/14_var_vecm.md) | Vektör otoregresyon · etki-tepki · Granger nedenselliği · eşbütünleşme · hata düzeltme |

### İleri Konular ve Pratik

| # | Bölüm | Neler var? |
|---|---|---|
| 15 | [Nedensellik ve Bayesçi Düşünce](docs/15_nedensellik_ve_bayesci_dusunce.md) | Karıştırıcı değişkenler · Simpson paradoksu · prior/posterior |
| 16 | [Canlıdaki Model: Dağılım Kayması](docs/16_dagilim_kaymasi.md) | PSI · performans ve kavram kayması |
| 17 | [Özet Kontrol Listesi](docs/17_kontrol_listesi.md) | Analiz ve model öncesi sorulacak sorular |

## Önerilen Öğrenme Sırası

| Hafta | Konular |
|---|---|
| 1 | Veri tipleri, tanımlayıcı istatistik, varyans ve momentler |
| 2 | Olasılık, Bayes, dağılımlar, normallik testleri |
| 3 | Örneklem, Merkezi Limit Teoremi, güven aralığı, bootstrap |
| 4 | Hipotez testleri, ki-kare, A/B testi, çoklu test |
| 5 | Korelasyon, doğrusal ve lojistik regresyon, varsayımlar, sigmoid / softmax |
| 6 | PCA ve model değerlendirme |
| 7 | Zaman serisi temelleri, durağanlık, ARIMA / SARIMA |
| 8 | ARCH / GARCH ailesi, VAR / VECM, nedensellik, model izleme |

## Repo Yapısı

```
stats/
├── README.md
└── docs/
    ├── 01_veri_tipleri.md
    ├── ...
    ├── 17_kontrol_listesi.md
    └── img/            # bölümlerdeki grafikler
```

> Grafiklerdeki veriler eğitim amaçlı simülasyondur, gerçek bir kurumu temsil etmez.
