<!-- Generated from Growth CMS by templates/catalog.md. Edit content in CMS; run npm run sync. -->

# Awesome 3D Prompts — 9 / 9

[← Awesome 3D Prompts](../README.md)

<p>
  <a href="../docs/catalog.en.9.md"><img alt="English" src="https://img.shields.io/badge/English-64748b?style=flat-square"></a>
  <a href="../docs/catalog.zh.9.md"><img alt="简体中文" src="https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-64748b?style=flat-square"></a>
  <a href="../docs/catalog.zh-Hant.9.md"><img alt="繁體中文" src="https://img.shields.io/badge/%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87-✓-238636?style=flat-square"></a>
  <a href="../docs/catalog.ja.9.md"><img alt="日本語" src="https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-64748b?style=flat-square"></a>
  <a href="../docs/catalog.ko.9.md"><img alt="한국어" src="https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-64748b?style=flat-square"></a>
  <a href="../docs/catalog.es.9.md"><img alt="Español" src="https://img.shields.io/badge/Espa%C3%B1ol-64748b?style=flat-square"></a>
  <a href="../docs/catalog.pt.9.md"><img alt="Português" src="https://img.shields.io/badge/Portugu%C3%AAs-64748b?style=flat-square"></a>
  <a href="../docs/catalog.de.9.md"><img alt="Deutsch" src="https://img.shields.io/badge/Deutsch-64748b?style=flat-square"></a>
  <a href="../docs/catalog.fr.9.md"><img alt="Français" src="https://img.shields.io/badge/Fran%C3%A7ais-64748b?style=flat-square"></a>
  <a href="../docs/catalog.it.9.md"><img alt="Italiano" src="https://img.shields.io/badge/Italiano-64748b?style=flat-square"></a>
  <a href="../docs/catalog.ru.9.md"><img alt="Русский" src="https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-64748b?style=flat-square"></a>
  <a href="../docs/catalog.tr.9.md"><img alt="Türkçe" src="https://img.shields.io/badge/T%C3%BCrk%C3%A7e-64748b?style=flat-square"></a>
  <a href="../docs/catalog.uk.9.md"><img alt="Українська" src="https://img.shields.io/badge/%D0%A3%D0%BA%D1%80%D0%B0%D1%97%D0%BD%D1%81%D1%8C%D0%BA%D0%B0-64748b?style=flat-square"></a>
  <a href="../docs/catalog.vi.9.md"><img alt="Tiếng Việt" src="https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-64748b?style=flat-square"></a>
</p>

[完整目錄](catalog.zh-Hant.md) · [←](catalog.zh-Hant.8.md) · **9 / 9**

<a id="all-prompts"></a>

<details>
<summary>瀏覽案例 (5)</summary>

- [Kimi K3 的單檔案 WebGL2 黑洞光線追蹤器提示詞](#single-file-webgl2-black-hole-raytracer-2079590483727442205)
- [用於單檔案 HTML 的 Three.js 體素風足球動畫提示詞](#voxel-soccer-animation-in-a-single-html-file-2079553757302710442)
- [用於使用 Fable 5 建置紐約的 Blender 城市建模提示詞](#modeling-new-york-city-in-blender-2079387760478073087)
- [用於 Fable 5 的單檔案 Three.js 體素足球動畫提示詞](#single-file-three-js-voxel-soccer-animation-2079198084689723560)
- [Three.js 飛機內部漫遊體驗提示詞](#three-js-airplane-walkthrough-experience-2078806166122197132)

</details>
<a id="single-file-webgl2-black-hole-raytracer-2079590483727442205"></a>

### Kimi K3 的單檔案 WebGL2 黑洞光線追蹤器提示詞

[Harsh](https://x.com/devloper_hs) · 2026-07-21 · Kimi K3 · 動畫

<a href="https://www.tripo3d.ai/zh-Hant/3d-prompts/single-file-webgl2-black-hole-raytracer-2079590483727442205"><img src="../assets/previews/5aff9deb1b2b504e0a15e14b6c97f70d2e06974efefa1eda0515703c4b1e4a08.webp" width="840" loading="lazy" alt="Kimi K3 的單檔案 WebGL2 黑洞光線追蹤器提示詞"></a>

**提示詞**

```text
建立一個完整的、自包含的單個 HTML 檔案（不使用 Three.js 等外部庫），實現一個受 Gargantua 啟發的史瓦西黑洞實時測地線光線追蹤器。

使用原生 WebGL2 和單個片段著色器中的 GLSL ES 3.00。實現準確的物理效果：帶有四階 Runge-Kutta 求解器的零測地線積分、事件視界、光子球、具有正確渲染的吸積盤、引力透鏡、多普勒增亮和引力紅移效應。目標是穩定 60 FPS 效能。

包含滑鼠控制的攝像機環繞/縮放，以及一個賽博朋克風格的控制面板，帶有引數滑塊（質量、自旋、盤密度、視角等）。新增用於落入物質的細微粒子效果和動態光照/陰影。

輸出必須 100% 完整，可在現代瀏覽器中立即執行，沒有黑屏、NaN、錯誤或缺失功能。優先保證數值正確性、邊界處理、求解器紀律和物理準確性。請在程式碼中驗證並註釋關鍵物理方程。讓它在視覺上令人驚豔，並像高階物理演示/遊戲一樣具有互動性。
```

[查看詳情 ↗](https://www.tripo3d.ai/zh-Hant/3d-prompts/single-file-webgl2-black-hole-raytracer-2079590483727442205) · [查看原文](https://x.com/devloper_hs/status/2079590483727442205) · [返回案例導覽](#all-prompts)

---

<a id="voxel-soccer-animation-in-a-single-html-file-2079553757302710442"></a>

### 用於單檔案 HTML 的 Three.js 體素風足球動畫提示詞

[Thành](https://x.com/Zmthanh) · 2026-07-21 · Kimi K3 · 動畫

<a href="https://www.tripo3d.ai/zh-Hant/3d-prompts/voxel-soccer-animation-in-a-single-html-file-2079553757302710442"><img src="../assets/previews/771fe49a27ee707d5b3e4fe6f4ff4b4ab7eada49eda5ec2a5bd000b8fefb33da.webp" width="840" loading="lazy" alt="用於單檔案 HTML 的 Three.js 體素風足球動畫提示詞"></a>

**提示詞**

```text
建立一個包含 Three.js（CDN）的單個 HTML 檔案，用於一個簡單的體素風格足球動畫。一個方塊風球員帶球過掉 2 名防守隊員，並以壯觀的進球和慶祝粒子得分。球場風格色彩鮮明。僅輸出完整的 HTML 程式碼。
```

[查看詳情 ↗](https://www.tripo3d.ai/zh-Hant/3d-prompts/voxel-soccer-animation-in-a-single-html-file-2079553757302710442) · [查看原文](https://x.com/Zmthanh/status/2079553757302710442) · [返回案例導覽](#all-prompts)

---

<a id="modeling-new-york-city-in-blender-2079387760478073087"></a>

### 用於使用 Fable 5 建置紐約的 Blender 城市建模提示詞

[Martin Puli](https://x.com/MartinPulitano) · 2026-07-21 · Claude Fable 5 · 場景

<a href="https://www.tripo3d.ai/zh-Hant/3d-prompts/modeling-new-york-city-in-blender-2079387760478073087"><img src="../assets/previews/c1df84f5898cf9fec4ed0c498e4b43b923257fa908fc65dc156c5f84920caffb.webp" width="840" loading="lazy" alt="用於使用 Fable 5 建置紐約的 Blender 城市建模提示詞"></a>

**提示詞**

```text
這是紐約。一個代理自己建出來的，只用了一條提示詞。我一點都沒動手。我到現在還是無法理解。

幾天前，我看到了人們用 GPT 5.6 Sol 在 Blender 裡建模的帖子，之後就再也沒法想別的了。我必須用真實的東西試試。

我先從自己的房子開始。結果爛得離譜：變形、灰色、像個塑膠模型。

我本可以就此停下。但我開始迭代。

我組裝了一些代理，它們從上千個來源抓取關於這個地方的真實資料。佔地、高度、座標。藉助 Blender MCP + skills + libraries，它們使用 Blender 自己的工具來建置模型。

當系統準備好後，我輸入了一條提示詞：“armá Nueva York”

它返回了曼哈頓。真實尺寸，位置精確到米，完全不用我碰一個頂點。

我沒想到的是，我測試了好幾個模型，在這方面 GPT 5.6 Sol 遠遠勝過 Fable 5。

這隻用了幾天。我還在繼續迭代建築細節。如果你看看我個人主頁上之前的影片，就會發現它在每次更新之間進步了多少。

現在我正嘗試用一條提示詞覆蓋更大的區域並增加更多細節。（如果你瞭解 Blender 裡的紋理和材質，我在聽 🙏）

但真正讓我震驚的不是模型本身，而是之後能開啟的東西。

.blend 檔案是“活著”的。只需幾句話，你就能新增一座新塔樓，移動一條大道，或者把整座城市融合在一起。布宜諾斯艾利斯疊在紐約上方。方尖碑矗立在時代廣場中央。

我不是在建模一座城市。我是在把現實變成一個可以編輯的草稿。

儲存庫 + .blend 在第一條評論裡 👇 我會繼續在這裡發每一步。如果你喜歡它的進展，請關注我，因為我們才剛剛開始。

你想讓我接下來建模哪個城市？
```

[查看詳情 ↗](https://www.tripo3d.ai/zh-Hant/3d-prompts/modeling-new-york-city-in-blender-2079387760478073087) · [查看原文](https://x.com/MartinPulitano/status/2079387760478073087) · [返回案例導覽](#all-prompts)

---

<a id="single-file-three-js-voxel-soccer-animation-2079198084689723560"></a>

### 用於 Fable 5 的單檔案 Three.js 體素足球動畫提示詞

[Thành](https://x.com/Zmthanh) · 2026-07-20 · Claude Fable 5 · 動畫

<a href="https://www.tripo3d.ai/zh-Hant/3d-prompts/single-file-three-js-voxel-soccer-animation-2079198084689723560"><img src="../assets/previews/b9f30819cb6139a05f901035cc1270fd3ee098356dac161654629d6bef2db479.webp" width="840" loading="lazy" alt="用於 Fable 5 的單檔案 Three.js 體素足球動畫提示詞"></a>

**提示詞**

```text
建立一個包含 Three.js（CDN）的單個 HTML 檔案，用於一個簡單的體素風格足球動畫。一個方塊風球員帶球過掉 2 名防守隊員，並以壯觀的進球和慶祝粒子得分。球場風格色彩鮮明。僅輸出完整的 HTML 程式碼。
```

[查看詳情 ↗](https://www.tripo3d.ai/zh-Hant/3d-prompts/single-file-three-js-voxel-soccer-animation-2079198084689723560) · [查看原文](https://x.com/Zmthanh/status/2079198084689723560) · [返回案例導覽](#all-prompts)

---

<a id="three-js-airplane-walkthrough-experience-2078806166122197132"></a>

### Three.js 飛機內部漫遊體驗提示詞

[FHILY👑](https://x.com/Oluwaphilemon1) · 2026-07-19 · Claude Fable 5 · 互動

<a href="https://www.tripo3d.ai/zh-Hant/3d-prompts/three-js-airplane-walkthrough-experience-2078806166122197132"><img src="../assets/previews/b045acf671506422acd90bc04f190e5d99618706982967e8f7a505cbe29507f2.webp" width="840" loading="lazy" alt="Three.js 飛機內部漫遊體驗提示詞"></a>

**提示詞**

```text
用 Three.js 生成一個體驗，讓我可以檢視一個 3D 飛機模型並在其中行走。
```

[查看詳情 ↗](https://www.tripo3d.ai/zh-Hant/3d-prompts/three-js-airplane-walkthrough-experience-2078806166122197132) · [查看原文](https://x.com/Oluwaphilemon1/status/2078806166122197132) · [返回案例導覽](#all-prompts)

---


[完整目錄](catalog.zh-Hant.md) · [←](catalog.zh-Hant.8.md) · **9 / 9**

<p align="center"><strong><a href="https://www.tripo3d.ai/zh-Hant/3d-prompts?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts&amp;utm_content=catalog_footer">完整目錄 →</a></strong></p>
