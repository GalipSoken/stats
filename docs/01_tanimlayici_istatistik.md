# 1. Veriyi Özetlemek: Tanımlayıcı İstatistik

## Ortalama, Medyan, Mod

Elimizde binlerce sayı var ve tek bir sayıyla "tipik değeri" söylemek istiyoruz. Üç yolu var:

- **Ortalama:** Hepsini topla, kişi sayısına böl. Herkesin eşit pay aldığı hayali dünya.
- **Medyan:** Herkesi küçükten büyüğe diz, tam ortadaki kişiye bak. Yarısı bundan az, yarısı fazla kazanır.
- **Mod:** En sık görülen değer.

![Ortalama, medyan ve mod](img/01_ortalama_medyan_mod.png)

**Neden önemli?** Gelir, kredi tutarı, mevduat bakiyesi gibi verilerde birkaç çok büyük değer ortalamayı yukarı çeker. Bir şubeye bir milyarder müşteri gelse ortalama bakiye fırlar ama "tipik müşteri" değişmez. Bu yüzden **çarpık veride medyan daha dürüst bir özettir.**

> 💡 Ortalama ile medyan arasındaki fark büyükse, veride uzun bir kuyruk var demektir.

## Yayılım: Standart Sapma ve IQR

Ortalama tek başına yetmez. Aşağıdaki iki şubenin ortalaması aynı ama biri her gün neredeyse aynı sayıda işlem yaparken diğeri çok dalgalı.

![Yayılım ve kutu grafiği](img/02_yayilim_boxplot.png)

- **Standart sapma:** Değerlerin ortalamadan "tipik olarak" ne kadar uzaklaştığı. Küçükse veri toplu, büyükse dağınık.
- **IQR (çeyrekler arası açıklık):** Ortadaki %50'lik dilimin genişliği. Uç değerlerden etkilenmez.
- **Kutu grafiği (boxplot):** Medyanı, ortadaki %50'yi ve aykırı değerleri tek bakışta gösterir. Veriyi tanımanın en hızlı yollarından biri.

## Aykırı Değerler

Aykırı değer her zaman "hata" değildir. Bankacılıkta bazen **en ilginç bilgi tam oradadır** (dolandırıcılık, olağandışı işlem). Silmeden önce sor: *Bu bir veri girişi hatası mı, yoksa gerçek ve nadir bir olay mı?*

## Çarpıklık

Veri bir tarafa uzun kuyruk yapıyorsa **çarpıktır**. Sağa çarpık veri (gelir, tutar) çok yaygındır. Pratik ipucu: böyle verilerde logaritma almak çoğu zaman dağılımı toparlar ve modelleri rahatlatır.

---

[Bölümler](../README.md#bölümler) · [2. Olasılık ve Bayes Düşüncesi →](02_olasilik_ve_bayes.md)
