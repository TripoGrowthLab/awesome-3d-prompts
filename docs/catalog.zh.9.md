<!-- Generated from Growth CMS by templates/catalog.md. Edit content in CMS; run npm run sync. -->

# Awesome 3D Prompts — 9 / 9

[← Awesome 3D Prompts](../README.zh-CN.md)

<p>
  <a href="../docs/catalog.en.9.md"><img alt="English" src="https://img.shields.io/badge/English-64748b?style=flat-square"></a>
  <a href="../docs/catalog.zh.9.md"><img alt="简体中文" src="https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-✓-238636?style=flat-square"></a>
  <a href="../docs/catalog.zh-Hant.9.md"><img alt="繁體中文" src="https://img.shields.io/badge/%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87-64748b?style=flat-square"></a>
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

[完整目录](catalog.zh.md) · [←](catalog.zh.8.md) · **9 / 9**

<a id="all-prompts"></a>

<details>
<summary>浏览案例 (5)</summary>

- [Kimi K3 的单文件 WebGL2 黑洞光线追踪器提示词](#single-file-webgl2-black-hole-raytracer-2079590483727442205)
- [用于单文件 HTML 的 Three.js 体素风足球动画提示词](#voxel-soccer-animation-in-a-single-html-file-2079553757302710442)
- [用于使用 Fable 5 构建纽约的 Blender 城市建模提示词](#modeling-new-york-city-in-blender-2079387760478073087)
- [用于 Fable 5 的单文件 Three.js 体素足球动画提示词](#single-file-three-js-voxel-soccer-animation-2079198084689723560)
- [Three.js 飞机内部漫游体验提示词](#three-js-airplane-walkthrough-experience-2078806166122197132)

</details>
<a id="single-file-webgl2-black-hole-raytracer-2079590483727442205"></a>

### Kimi K3 的单文件 WebGL2 黑洞光线追踪器提示词

[Harsh](https://x.com/devloper_hs) · 2026-07-21 · Kimi K3 · 动画

<a href="https://www.tripo3d.ai/zh/3d-prompts/single-file-webgl2-black-hole-raytracer-2079590483727442205"><img src="../assets/previews/5aff9deb1b2b504e0a15e14b6c97f70d2e06974efefa1eda0515703c4b1e4a08.webp" width="840" loading="lazy" alt="Kimi K3 的单文件 WebGL2 黑洞光线追踪器提示词"></a>

**提示词**

```text
创建一个完整的、自包含的单个 HTML 文件（不使用 Three.js 等外部库），实现一个受 Gargantua 启发的史瓦西黑洞实时测地线光线追踪器。

使用原生 WebGL2 和单个片段着色器中的 GLSL ES 3.00。实现准确的物理效果：带有四阶 Runge-Kutta 求解器的零测地线积分、事件视界、光子球、具有正确渲染的吸积盘、引力透镜、多普勒增亮和引力红移效应。目标是稳定 60 FPS 性能。

包含鼠标控制的摄像机环绕/缩放，以及一个赛博朋克风格的控制面板，带有参数滑块（质量、自旋、盘密度、视角等）。添加用于落入物质的细微粒子效果和动态光照/阴影。

输出必须 100% 完整，可在现代浏览器中立即运行，没有黑屏、NaN、错误或缺失功能。优先保证数值正确性、边界处理、求解器纪律和物理准确性。请在代码中验证并注释关键物理方程。让它在视觉上令人惊艳，并像高级物理演示/游戏一样具有交互性。
```

[查看详情 ↗](https://www.tripo3d.ai/zh/3d-prompts/single-file-webgl2-black-hole-raytracer-2079590483727442205) · [查看原帖](https://x.com/devloper_hs/status/2079590483727442205) · [返回案例导航](#all-prompts)

---

<a id="voxel-soccer-animation-in-a-single-html-file-2079553757302710442"></a>

### 用于单文件 HTML 的 Three.js 体素风足球动画提示词

[Thành](https://x.com/Zmthanh) · 2026-07-21 · Kimi K3 · 动画

<a href="https://www.tripo3d.ai/zh/3d-prompts/voxel-soccer-animation-in-a-single-html-file-2079553757302710442"><img src="../assets/previews/771fe49a27ee707d5b3e4fe6f4ff4b4ab7eada49eda5ec2a5bd000b8fefb33da.webp" width="840" loading="lazy" alt="用于单文件 HTML 的 Three.js 体素风足球动画提示词"></a>

**提示词**

```text
创建一个包含 Three.js（CDN）的单个 HTML 文件，用于一个简单的体素风格足球动画。一个方块风球员带球过掉 2 名防守队员，并以壮观的进球和庆祝粒子得分。球场风格色彩鲜明。仅输出完整的 HTML 代码。
```

[查看详情 ↗](https://www.tripo3d.ai/zh/3d-prompts/voxel-soccer-animation-in-a-single-html-file-2079553757302710442) · [查看原帖](https://x.com/Zmthanh/status/2079553757302710442) · [返回案例导航](#all-prompts)

---

<a id="modeling-new-york-city-in-blender-2079387760478073087"></a>

### 用于使用 Fable 5 构建纽约的 Blender 城市建模提示词

[Martin Puli](https://x.com/MartinPulitano) · 2026-07-21 · Claude Fable 5 · 场景

<a href="https://www.tripo3d.ai/zh/3d-prompts/modeling-new-york-city-in-blender-2079387760478073087"><img src="../assets/previews/c1df84f5898cf9fec4ed0c498e4b43b923257fa908fc65dc156c5f84920caffb.webp" width="840" loading="lazy" alt="用于使用 Fable 5 构建纽约的 Blender 城市建模提示词"></a>

**提示词**

```text
这是纽约。一个代理自己建出来的，只用了一条提示词。我一点都没动手。我到现在还是无法理解。

几天前，我看到了人们用 GPT 5.6 Sol 在 Blender 里建模的帖子，之后就再也没法想别的了。我必须用真实的东西试试。

我先从自己的房子开始。结果烂得离谱：变形、灰色、像个塑料模型。

我本可以就此停下。但我开始迭代。

我组装了一些代理，它们从上千个来源抓取关于这个地方的真实数据。占地、高度、坐标。借助 Blender MCP + skills + libraries，它们使用 Blender 自己的工具来构建模型。

当系统准备好后，我输入了一条提示词：“armá Nueva York”

它返回了曼哈顿。真实尺寸，位置精确到米，完全不用我碰一个顶点。

我没想到的是，我测试了好几个模型，在这方面 GPT 5.6 Sol 远远胜过 Fable 5。

这只用了几天。我还在继续迭代建筑细节。如果你看看我个人主页上之前的视频，就会发现它在每次更新之间进步了多少。

现在我正尝试用一条提示词覆盖更大的区域并增加更多细节。（如果你了解 Blender 里的纹理和材质，我在听 🙏）

但真正让我震惊的不是模型本身，而是之后能开启的东西。

.blend 文件是“活着”的。只需几句话，你就能添加一座新塔楼，移动一条大道，或者把整座城市融合在一起。布宜诺斯艾利斯叠在纽约上方。方尖碑矗立在时代广场中央。

我不是在建模一座城市。我是在把现实变成一个可以编辑的草稿。

仓库 + .blend 在第一条评论里 👇 我会继续在这里发每一步。如果你喜欢它的进展，请关注我，因为我们才刚刚开始。

你想让我接下来建模哪个城市？
```

[查看详情 ↗](https://www.tripo3d.ai/zh/3d-prompts/modeling-new-york-city-in-blender-2079387760478073087) · [查看原帖](https://x.com/MartinPulitano/status/2079387760478073087) · [返回案例导航](#all-prompts)

---

<a id="single-file-three-js-voxel-soccer-animation-2079198084689723560"></a>

### 用于 Fable 5 的单文件 Three.js 体素足球动画提示词

[Thành](https://x.com/Zmthanh) · 2026-07-20 · Claude Fable 5 · 动画

<a href="https://www.tripo3d.ai/zh/3d-prompts/single-file-three-js-voxel-soccer-animation-2079198084689723560"><img src="../assets/previews/b9f30819cb6139a05f901035cc1270fd3ee098356dac161654629d6bef2db479.webp" width="840" loading="lazy" alt="用于 Fable 5 的单文件 Three.js 体素足球动画提示词"></a>

**提示词**

```text
创建一个包含 Three.js（CDN）的单个 HTML 文件，用于一个简单的体素风格足球动画。一个方块风球员带球过掉 2 名防守队员，并以壮观的进球和庆祝粒子得分。球场风格色彩鲜明。仅输出完整的 HTML 代码。
```

[查看详情 ↗](https://www.tripo3d.ai/zh/3d-prompts/single-file-three-js-voxel-soccer-animation-2079198084689723560) · [查看原帖](https://x.com/Zmthanh/status/2079198084689723560) · [返回案例导航](#all-prompts)

---

<a id="three-js-airplane-walkthrough-experience-2078806166122197132"></a>

### Three.js 飞机内部漫游体验提示词

[FHILY👑](https://x.com/Oluwaphilemon1) · 2026-07-19 · Claude Fable 5 · 互动

<a href="https://www.tripo3d.ai/zh/3d-prompts/three-js-airplane-walkthrough-experience-2078806166122197132"><img src="../assets/previews/b045acf671506422acd90bc04f190e5d99618706982967e8f7a505cbe29507f2.webp" width="840" loading="lazy" alt="Three.js 飞机内部漫游体验提示词"></a>

**提示词**

```text
用 Three.js 生成一个体验，让我可以查看一个 3D 飞机模型并在其中行走。
```

[查看详情 ↗](https://www.tripo3d.ai/zh/3d-prompts/three-js-airplane-walkthrough-experience-2078806166122197132) · [查看原帖](https://x.com/Oluwaphilemon1/status/2078806166122197132) · [返回案例导航](#all-prompts)

---


[完整目录](catalog.zh.md) · [←](catalog.zh.8.md) · **9 / 9**

<p align="center"><strong><a href="https://www.tripo3d.ai/zh/3d-prompts?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts&amp;utm_content=catalog_footer">查看全部 405 条案例与在线演示 →</a></strong></p>
