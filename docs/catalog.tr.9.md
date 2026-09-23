<!-- Generated from Growth CMS by templates/catalog.md. Edit content in CMS; run npm run sync. -->

# Awesome 3D Prompts — 9 / 9

[← Awesome 3D Prompts](../README.md)

<p>
  <a href="../docs/catalog.en.9.md"><img alt="English" src="https://img.shields.io/badge/English-64748b?style=flat-square"></a>
  <a href="../docs/catalog.zh.9.md"><img alt="简体中文" src="https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-64748b?style=flat-square"></a>
  <a href="../docs/catalog.zh-Hant.9.md"><img alt="繁體中文" src="https://img.shields.io/badge/%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87-64748b?style=flat-square"></a>
  <a href="../docs/catalog.ja.9.md"><img alt="日本語" src="https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-64748b?style=flat-square"></a>
  <a href="../docs/catalog.ko.9.md"><img alt="한국어" src="https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-64748b?style=flat-square"></a>
  <a href="../docs/catalog.es.9.md"><img alt="Español" src="https://img.shields.io/badge/Espa%C3%B1ol-64748b?style=flat-square"></a>
  <a href="../docs/catalog.pt.9.md"><img alt="Português" src="https://img.shields.io/badge/Portugu%C3%AAs-64748b?style=flat-square"></a>
  <a href="../docs/catalog.de.9.md"><img alt="Deutsch" src="https://img.shields.io/badge/Deutsch-64748b?style=flat-square"></a>
  <a href="../docs/catalog.fr.9.md"><img alt="Français" src="https://img.shields.io/badge/Fran%C3%A7ais-64748b?style=flat-square"></a>
  <a href="../docs/catalog.it.9.md"><img alt="Italiano" src="https://img.shields.io/badge/Italiano-64748b?style=flat-square"></a>
  <a href="../docs/catalog.ru.9.md"><img alt="Русский" src="https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-64748b?style=flat-square"></a>
  <a href="../docs/catalog.tr.9.md"><img alt="Türkçe" src="https://img.shields.io/badge/T%C3%BCrk%C3%A7e-✓-238636?style=flat-square"></a>
  <a href="../docs/catalog.uk.9.md"><img alt="Українська" src="https://img.shields.io/badge/%D0%A3%D0%BA%D1%80%D0%B0%D1%97%D0%BD%D1%81%D1%8C%D0%BA%D0%B0-64748b?style=flat-square"></a>
  <a href="../docs/catalog.vi.9.md"><img alt="Tiếng Việt" src="https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-64748b?style=flat-square"></a>
</p>

[Tam katalog](catalog.tr.md) · [←](catalog.tr.8.md) · **9 / 9**

<a id="all-prompts"></a>

<details>
<summary>Örnekleri keşfet (5)</summary>

- [Kimi K3 için tek dosyalı WebGL2 kara delik ışın izleyici istemi](#single-file-webgl2-black-hole-raytracer-2079590483727442205)
- [Tek HTML dosyasında Three.js voksel futbol animasyonu istemi](#voxel-soccer-animation-in-a-single-html-file-2079553757302710442)
- [Fable 5 ile New York kurmak için Blender şehir modelleme istemi](#modeling-new-york-city-in-blender-2079387760478073087)
- [Fable 5 için tek dosyalık Three.js voksel futbol animasyonu istemi](#single-file-three-js-voxel-soccer-animation-2079198084689723560)
- [Three.js uçak içi gezinti deneyimi istemi](#three-js-airplane-walkthrough-experience-2078806166122197132)

</details>
<a id="single-file-webgl2-black-hole-raytracer-2079590483727442205"></a>

### Kimi K3 için tek dosyalı WebGL2 kara delik ışın izleyici istemi

[Harsh](https://x.com/devloper_hs) · 2026-07-21 · Kimi K3 · Animasyon

<a href="https://www.tripo3d.ai/tr/3d-prompts/single-file-webgl2-black-hole-raytracer-2079590483727442205"><img src="../assets/previews/5aff9deb1b2b504e0a15e14b6c97f70d2e06974efefa1eda0515703c4b1e4a08.webp" width="840" loading="lazy" alt="Kimi K3 için tek dosyalı WebGL2 kara delik ışın izleyici istemi"></a>

**İstem**

```text
Gargantua'dan esinlenen bir Schwarzschild kara deliği için gerçek zamanlı jeodezik ışın izleyici uygulayan, eksiksiz ve bağımsız tek bir HTML dosyası oluştur (Three.js gibi harici kütüphaneler olmasın).

Tek bir fragment shader içinde GLSL ES 3.00 ile doğrudan WebGL2 kullan. Doğru fiziği uygula: dördüncü dereceden Runge-Kutta çözücüsüyle ışık benzeri jeodeziklerin integrasyonu, olay ufku, foton küresi, doğru render edilen yığılma diski, kütleçekimsel merceklenme, Doppler ışın demetleme ve kütleçekimsel kırmızıya kayma etkileri. Kararlı 60 FPS performansı hedefle.

Fareyle kamera yörüngesi ve yakınlaştırma kontrolleri, ayrıca parametreler için (kütle, spin, disk yoğunluğu, görüş açısı vb.) kaydırıcılar içeren siberpunk tarzı bir kontrol paneli ekle. İçeri düşen madde için hafif parçacık efektleri ve dinamik ışık/gölge ekle.

Çıktı %100 eksiksiz olmalı; modern bir tarayıcıda hemen çalışmalı, siyah ekran, NaN, hata veya eksik özellik içermemeli. Sayısal doğruluğu, sınır koşullarını, çözücü disiplinini ve fiziksel doğruluğu her şeyin önünde tut. Temel fizik denklemlerini doğrula ve kodda açıkla. Üst düzey bir fizik demosu/oyunu gibi görsel açıdan etkileyici ve etkileşimli olsun.
```

[Ayrıntıları görüntüle ↗](https://www.tripo3d.ai/tr/3d-prompts/single-file-webgl2-black-hole-raytracer-2079590483727442205) · [Orijinal gönderi](https://x.com/devloper_hs/status/2079590483727442205) · [Örneklere dön](#all-prompts)

---

<a id="voxel-soccer-animation-in-a-single-html-file-2079553757302710442"></a>

### Tek HTML dosyasında Three.js voksel futbol animasyonu istemi

[Thành](https://x.com/Zmthanh) · 2026-07-21 · Kimi K3 · Animasyon

<a href="https://www.tripo3d.ai/tr/3d-prompts/voxel-soccer-animation-in-a-single-html-file-2079553757302710442"><img src="../assets/previews/771fe49a27ee707d5b3e4fe6f4ff4b4ab7eada49eda5ec2a5bd000b8fefb33da.webp" width="840" loading="lazy" alt="Tek HTML dosyasında Three.js voksel futbol animasyonu istemi"></a>

**İstem**

```text
Basit voksel tarzı futbol animasyonu için Three.js (CDN) kullanan tek HTML dosyası oluştur. Blok oyuncu 2 savunmacıyı çalımlayıp kutlama parçacıklarıyla muhteşem gol atsın. Renkli stadyum görünümü kullan. YALNIZCA eksiksiz HTML kodunu döndür.
```

[Ayrıntıları görüntüle ↗](https://www.tripo3d.ai/tr/3d-prompts/voxel-soccer-animation-in-a-single-html-file-2079553757302710442) · [Orijinal gönderi](https://x.com/Zmthanh/status/2079553757302710442) · [Örneklere dön](#all-prompts)

---

<a id="modeling-new-york-city-in-blender-2079387760478073087"></a>

### Fable 5 ile New York kurmak için Blender şehir modelleme istemi

[Martin Puli](https://x.com/MartinPulitano) · 2026-07-21 · Claude Fable 5 · Sahneler

<a href="https://www.tripo3d.ai/tr/3d-prompts/modeling-new-york-city-in-blender-2079387760478073087"><img src="../assets/previews/c1df84f5898cf9fec4ed0c498e4b43b923257fa908fc65dc156c5f84920caffb.webp" width="840" loading="lazy" alt="Fable 5 ile New York kurmak için Blender şehir modelleme istemi"></a>

**İstem**

```text
Burası New York. Bir ajan TEK istemle kendi başına yaptı. Parmağımı bile oynatmadım. Hâlâ aklım almıyor.

Birkaç gün önce GPT 5.6 Sol ile Blender'da modelleme yapanların gönderilerini gördüm ve başka bir şey düşünemedim. Gerçek bir şeyle denemeliydim.

Kendi evimle başladım. Berbat oldu: yamuk, gri, plastik maket gibi.

Orada bırakabilirdim. Ama yinelemeye başladım.

Yer hakkında binlerce kaynaktan gerçek veri toplayan ajanlar kurdum. Bina ayak izleri, yükseklikler, koordinatlar. Blender MCP + skill'ler + kitaplıklarla Blender'ın kendi araçlarını kullanarak modeli kuruyorlar.

Sistem hazır olunca bir istem yazdım: “New York'u kur”.

Manhattan'ı verdi. Gerçek ölçüler, metre hassasiyetinde konum; tek bir köşeye dokunmadım.

Beklemediğim şey, farklı modelleri denediğimde GPT 5.6 Sol'un bu işte Fable 5'i ÇOK büyük farkla geçmesiydi.

Bu sadece birkaç gün sürdü. Bina ayrıntılarını hâlâ iyileştiriyorum. Profilimdeki önceki videolarda güncellemeler arasındaki ilerlemeyi görebilirsiniz.

Şimdi tek istemle daha fazla alanı ve ayrıntıyı kapsamasını sağlamaya çalışıyorum. (Blender'da doku ve malzemeden anlıyorsanız dinliyorum 🙏).

Ama beni asıl şaşırtan model değil. Sonrasında açılan olasılıklar.

.blend canlı kalıyor. Birkaç cümleyle yeni kule ekleyebilir, cadde taşıyabilir veya şehirleri birleştirebilirsiniz. New York'un üstünde Buenos Aires. Times Square'in ortasında Dikilitaş.

Şehir modellemiyorum. Gerçekliği düzenlenebilir bir taslağa dönüştürüyorum.

Depo + .blend ilk yorumda 👇 Her adımı burada paylaşmaya devam edeceğim. İlerleyişi seviyorsanız takip edin; daha yeni başlıyoruz.

Sırada hangi şehri modellememi istersiniz?
```

[Ayrıntıları görüntüle ↗](https://www.tripo3d.ai/tr/3d-prompts/modeling-new-york-city-in-blender-2079387760478073087) · [Orijinal gönderi](https://x.com/MartinPulitano/status/2079387760478073087) · [Örneklere dön](#all-prompts)

---

<a id="single-file-three-js-voxel-soccer-animation-2079198084689723560"></a>

### Fable 5 için tek dosyalık Three.js voksel futbol animasyonu istemi

[Thành](https://x.com/Zmthanh) · 2026-07-20 · Claude Fable 5 · Animasyon

<a href="https://www.tripo3d.ai/tr/3d-prompts/single-file-three-js-voxel-soccer-animation-2079198084689723560"><img src="../assets/previews/b9f30819cb6139a05f901035cc1270fd3ee098356dac161654629d6bef2db479.webp" width="840" loading="lazy" alt="Fable 5 için tek dosyalık Three.js voksel futbol animasyonu istemi"></a>

**İstem**

```text
Basit voksel tarzı futbol animasyonu için Three.js (CDN) kullanan tek HTML dosyası oluştur. Blok oyuncu 2 savunmacıyı çalımlayıp kutlama parçacıklarıyla muhteşem gol atsın. Renkli stadyum görünümü kullan. YALNIZCA eksiksiz HTML kodunu döndür.
```

[Ayrıntıları görüntüle ↗](https://www.tripo3d.ai/tr/3d-prompts/single-file-three-js-voxel-soccer-animation-2079198084689723560) · [Orijinal gönderi](https://x.com/Zmthanh/status/2079198084689723560) · [Örneklere dön](#all-prompts)

---

<a id="three-js-airplane-walkthrough-experience-2078806166122197132"></a>

### Three.js uçak içi gezinti deneyimi istemi

[FHILY👑](https://x.com/Oluwaphilemon1) · 2026-07-19 · Claude Fable 5 · Etkileşimli

<a href="https://www.tripo3d.ai/tr/3d-prompts/three-js-airplane-walkthrough-experience-2078806166122197132"><img src="../assets/previews/b045acf671506422acd90bc04f190e5d99618706982967e8f7a505cbe29507f2.webp" width="840" loading="lazy" alt="Three.js uçak içi gezinti deneyimi istemi"></a>

**İstem**

```text
Three.js'de 3B uçak modelini görselleştirip içinde yürüyebileceğim bir deneyim üret.
```

[Ayrıntıları görüntüle ↗](https://www.tripo3d.ai/tr/3d-prompts/three-js-airplane-walkthrough-experience-2078806166122197132) · [Orijinal gönderi](https://x.com/Oluwaphilemon1/status/2078806166122197132) · [Örneklere dön](#all-prompts)

---


[Tam katalog](catalog.tr.md) · [←](catalog.tr.8.md) · **9 / 9**

<p align="center"><strong><a href="https://www.tripo3d.ai/tr/3d-prompts?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts&amp;utm_content=catalog_footer">Tam katalog →</a></strong></p>
