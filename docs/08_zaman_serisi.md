# 8. Zaman Serisi Temelleri

Zaman içinde ölçülen verinin (aylık kredi hacmi, günlük mevduat, kur) kendine özgü kuralları vardır: **dün, bugünü etkiler.**

## Bileşenler

Bir zaman serisi genelde üç parçaya ayrılabilir:

![Zaman serisi bileşenleri](img/19_zaman_serisi.png)

- **Trend:** Uzun vadeli yön.
- **Mevsimsellik:** Düzenli tekrar eden desen (yılbaşı, maaş günleri, bayramlar, çeyrek sonları).
- **Gürültü:** Geriye kalan rastgele dalgalanma.

## Durağanlık

**Durağan** bir serinin ortalaması ve dalgalanması zaman içinde sabittir. Fiyatlar ve hacimler genelde durağan değildir; ama **değişimleri** (getiriler, aylık büyüme) çoğunlukla durağana yakındır.

![Durağanlık](img/20_duraganlik.png)

> ⚠️ **Sahte regresyon:** Durağan olmayan iki seriyi (ör. iki farklı ülkenin GSYH'si) birbirine regresyonla bağlarsan, aralarında hiçbir ilişki yokken çok güçlü bir ilişki bulursun. Çünkü ikisi de zamanla büyüyor. Önce farklarını al.

## Otokorelasyon

Serinin kendi geçmişiyle korelasyonu. "Bu ay yüksekse gelecek ay da yüksek olur mu?" ACF ve PACF grafikleri, geçmişin kaç adım geriye kadar etkili olduğunu gösterir ve ARIMA gibi modellerin kurulmasında yol gösterir.

---

[← 7. Model Değerlendirme](07_model_degerlendirme.md) · [Bölümler](../README.md#bölümler) · [9. Nedensellik ve Bayesçi Düşünce →](09_nedensellik_ve_bayesci_dusunce.md)
