# 6. Korelasyon ve Regresyon

## Korelasyon

İki değişkenin **birlikte hareket etme** derecesi. -1 ile +1 arasında bir sayıdır.

![Korelasyon örnekleri](img/11_korelasyon.png)

Dikkat edilecek üç nokta:
1. **Pearson korelasyonu sadece doğrusal ilişkiyi ölçer.** Sağdaki grafikte çok güçlü bir ilişki var ama korelasyon sıfıra yakın. Her zaman önce grafiğe bak.
2. **Spearman korelasyonu** sıralamaya bakar; aykırı değerlere ve doğrusal olmayan (ama tek yönlü) ilişkilere karşı daha dayanıklıdır.
3. **Korelasyon nedensellik değildir.** Dondurma satışı ile boğulma vakaları birlikte artar; sebep ikisinin de yazın artmasıdır.

## Doğrusal Regresyon

Noktaların arasından geçen "en iyi" çizgiyi bulur. Her noktanın çizgiye olan dikey uzaklığı **hata (artık)** olarak adlandırılır; regresyon bu hataları toplamda en küçük yapan çizgiyi seçer.

![Regresyon ve artıklar](img/12_regresyon.png)

**Katsayı yorumu:** "Diğer her şey sabitken, X bir birim artınca Y ortalama şu kadar artar."

**Artık grafiği** modelin sağlık raporudur:
- Rastgele bir bulut → model iyi.
- Eğri, huni ya da dalga şekli → model bir şeyi kaçırıyor.

## Regresyonun Tuzakları

- **Çoklu doğrusallık:** Birbirine çok benzeyen değişkenler (ör. "toplam kredi" ve "nakdi kredi") modele birlikte girerse katsayılar anlamsızlaşır. **VIF** değeri bunu tespit eder; 5-10'un üstü alarm işaretidir.
- **Değişen varyans:** Hataların büyüklüğü tahminle birlikte büyüyorsa (huni şekli) güven aralıkları yanıltıcı olur.
- **Aykırı değerler** çizgiyi kendine doğru çekebilir.

## Lojistik Regresyon

Sonuç "evet/hayır" ise (temerrüt etti mi, ürünü aldı mı, fraud mu) kullanılır. Düz bir çizgi yerine 0 ile 1 arasında kalan **S şeklinde** bir eğri çizer; çıktısı bir **olasılıktır**.

![Lojistik regresyon](img/13_lojistik.png)

Bankacılıkta kredi skorkartlarının büyük çoğunluğu hâlâ lojistik regresyonla kurulur; çünkü yorumlanabilir, kararlı ve düzenleyicilere açıklanması kolaydır.

---

[← 5. Hipotez Testleri](05_hipotez_testleri.md) · [Bölümler](../README.md#bölümler) · [7. Model Değerlendirme →](07_model_degerlendirme.md)
