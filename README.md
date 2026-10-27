# Data Scientist İçin Temel İstatistik

*Formülsüz, grafiklerle, herkesin anlayacağı dilde*

Bu repo, bir data scientist'in her gün kullandığı istatistik fikirlerini **sezgisel olarak** anlatan Türkçe bir rehberdir. Amaç formül ezberletmek değil; bir grafiğe, bir model çıktısına ya da bir A/B testi sonucuna bakınca **doğru soruyu sorabilmeyi** öğretmek. Örneklerin çoğu bankacılık dünyasından: fraud alarmları, temerrüt, kredi skoru, kampanya etkisi.

![Bayes ızgarası](docs/img/03_bayes_izgara.png)

## Bölümler

| # | Bölüm | Neler var? |
|---|---|---|
| 1 | [Tanımlayıcı İstatistik](docs/01_tanimlayici_istatistik.md) | Ortalama, medyan, mod · standart sapma, IQR · aykırı değerler · çarpıklık |
| 2 | [Olasılık ve Bayes Düşüncesi](docs/02_olasilik_ve_bayes.md) | Koşullu olasılık · Bayes teoremi ve fraud alarmı örneği |
| 3 | [Dağılımlar](docs/03_dagilimlar.md) | Normal, binom, Poisson, log-normal · kalın kuyruklar |
| 4 | [Örneklem ve Tahmin](docs/04_orneklem_ve_tahmin.md) | Merkezi Limit Teoremi · büyük sayılar yasası · güven aralığı · bootstrap |
| 5 | [Hipotez Testleri](docs/05_hipotez_testleri.md) | p-değeri · Tip I/II hata · hangi test ne zaman · çoklu test · A/B testi |
| 6 | [Korelasyon ve Regresyon](docs/06_korelasyon_ve_regresyon.md) | Pearson / Spearman · doğrusal ve lojistik regresyon · VIF, artıklar |
| 7 | [Model Değerlendirme](docs/07_model_degerlendirme.md) | Overfitting · bias-variance · cross-validation · precision/recall · ROC-AUC · dengesiz sınıflar · kalibrasyon |
| 8 | [Zaman Serisi Temelleri](docs/08_zaman_serisi.md) | Trend, mevsimsellik · durağanlık · otokorelasyon |
| 9 | [Nedensellik ve Bayesçi Düşünce](docs/09_nedensellik_ve_bayesci_dusunce.md) | Karıştırıcı değişkenler · Simpson paradoksu · prior/posterior |
| 10 | [Canlıdaki Model: Dağılım Kayması](docs/10_dagilim_kaymasi.md) | PSI · performans ve kavram kayması |
| 11 | [Özet Kontrol Listesi](docs/11_kontrol_listesi.md) | Analiz ve model öncesi sorulacak sorular |

## Önerilen Öğrenme Sırası

| Hafta | Konular |
|---|---|
| 1 | Tanımlayıcı istatistik, dağılımlar |
| 2 | Olasılık, Bayes, örneklem, Merkezi Limit Teoremi, güven aralığı, bootstrap |
| 3 | Hipotez testleri, A/B testi, çoklu test |
| 4 | Korelasyon, doğrusal ve lojistik regresyon |
| 5 | Model değerlendirme: overfitting, cross-validation, metrikler, kalibrasyon |
| 6 | Zaman serisi temelleri, nedensellik, model izleme |

## Repo Yapısı

```
stats/
├── README.md
└── docs/
    ├── 01_tanimlayici_istatistik.md
    ├── ...
    ├── 11_kontrol_listesi.md
    └── img/            # bölümlerdeki grafikler
```

> Grafiklerdeki veriler eğitim amaçlı simülasyondur, gerçek bir kurumu temsil etmez.
