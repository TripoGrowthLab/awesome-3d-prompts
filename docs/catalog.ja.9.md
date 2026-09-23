<!-- Generated from Growth CMS by templates/catalog.md. Edit content in CMS; run npm run sync. -->

# Awesome 3D Prompts — 9 / 9

[← Awesome 3D Prompts](../README.md)

<p>
  <a href="../docs/catalog.en.9.md"><img alt="English" src="https://img.shields.io/badge/English-64748b?style=flat-square"></a>
  <a href="../docs/catalog.zh.9.md"><img alt="简体中文" src="https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-64748b?style=flat-square"></a>
  <a href="../docs/catalog.zh-Hant.9.md"><img alt="繁體中文" src="https://img.shields.io/badge/%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87-64748b?style=flat-square"></a>
  <a href="../docs/catalog.ja.9.md"><img alt="日本語" src="https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-✓-238636?style=flat-square"></a>
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

[全カタログ](catalog.ja.md) · [←](catalog.ja.8.md) · **9 / 9**

<a id="all-prompts"></a>

<details>
<summary>作例を見る (5)</summary>

- [HTML 一つで WebGL2 ブラックホールを光線追跡する Kimi K3 プロンプト](#single-file-webgl2-black-hole-raytracer-2079590483727442205)
- [HTML 一つで作る Three.js ボクセル風サッカーアニメーション](#voxel-soccer-animation-in-a-single-html-file-2079553757302710442)
- [Fable 5 でニューヨークを作る Blender 都市モデリングのプロンプト](#modeling-new-york-city-in-blender-2079387760478073087)
- [単一ファイルでボクセルサッカーを動かす Fable 5 の Three.js プロンプト](#single-file-three-js-voxel-soccer-animation-2079198084689723560)
- [Three.js の飛行機内を歩く体験プロンプト](#three-js-airplane-walkthrough-experience-2078806166122197132)

</details>
<a id="single-file-webgl2-black-hole-raytracer-2079590483727442205"></a>

### HTML 一つで WebGL2 ブラックホールを光線追跡する Kimi K3 プロンプト

[Harsh](https://x.com/devloper_hs) · 2026-07-21 · Kimi K3 · アニメーション

<a href="https://www.tripo3d.ai/ja/3d-prompts/single-file-webgl2-black-hole-raytracer-2079590483727442205"><img src="../assets/previews/5aff9deb1b2b504e0a15e14b6c97f70d2e06974efefa1eda0515703c4b1e4a08.webp" width="840" loading="lazy" alt="HTML 一つで WebGL2 ブラックホールを光線追跡する Kimi K3 プロンプト"></a>

**プロンプト**

```text
ガルガンチュアに着想を得たシュヴァルツシルト・ブラックホールの、リアルタイム測地線レイトレーサーを実装してください。Three.js などの外部ライブラリを使わず、完全に自己完結する一つの HTML ファイルにしてください。

素の WebGL2 と GLSL ES 3.00 を使い、単一のフラグメントシェーダーで実装します。4 次ルンゲ＝クッタ法によるヌル測地線積分、事象の地平面、光子球、適切に描画された降着円盤、重力レンズ、ドップラービーミング、重力赤方偏移を正確に実装してください。安定した 60 FPS を目標にします。

マウスによるカメラ周回とズーム、質量・スピン・円盤密度・視角などを調整するスライダー付きサイバーパンク風パネルを用意してください。落下する物質の控えめな粒子効果、動的な照明と影も加えてください。

出力は 100% 完成した状態で、現代のブラウザですぐに動く必要があります。黒画面、NaN、エラー、機能欠落は不可です。数値の正確さ、境界処理、ソルバーの厳密さ、物理的精度を最優先してください。主要な物理式を検証し、コード内で説明してください。上質な物理デモ／ゲームのように、美しく操作できる体験にしてください。
```

[詳細を見る ↗](https://www.tripo3d.ai/ja/3d-prompts/single-file-webgl2-black-hole-raytracer-2079590483727442205) · [元の投稿](https://x.com/devloper_hs/status/2079590483727442205) · [作例一覧に戻る](#all-prompts)

---

<a id="voxel-soccer-animation-in-a-single-html-file-2079553757302710442"></a>

### HTML 一つで作る Three.js ボクセル風サッカーアニメーション

[Thành](https://x.com/Zmthanh) · 2026-07-21 · Kimi K3 · アニメーション

<a href="https://www.tripo3d.ai/ja/3d-prompts/voxel-soccer-animation-in-a-single-html-file-2079553757302710442"><img src="../assets/previews/771fe49a27ee707d5b3e4fe6f4ff4b4ab7eada49eda5ec2a5bd000b8fefb33da.webp" width="840" loading="lazy" alt="HTML 一つで作る Three.js ボクセル風サッカーアニメーション"></a>

**プロンプト**

```text
Three.js（CDN）を使い、単一の HTML ファイルでシンプルなボクセル風サッカーアニメーションを作成してください。ブロック状の選手が守備 2 人をドリブルで抜き、見事なゴールを決め、祝福の粒子が舞います。色鮮やかなスタジアム風にしてください。完全な HTML コードだけを出力してください。
```

[詳細を見る ↗](https://www.tripo3d.ai/ja/3d-prompts/voxel-soccer-animation-in-a-single-html-file-2079553757302710442) · [元の投稿](https://x.com/Zmthanh/status/2079553757302710442) · [作例一覧に戻る](#all-prompts)

---

<a id="modeling-new-york-city-in-blender-2079387760478073087"></a>

### Fable 5 でニューヨークを作る Blender 都市モデリングのプロンプト

[Martin Puli](https://x.com/MartinPulitano) · 2026-07-21 · Claude Fable 5 · シーン

<a href="https://www.tripo3d.ai/ja/3d-prompts/modeling-new-york-city-in-blender-2079387760478073087"><img src="../assets/previews/c1df84f5898cf9fec4ed0c498e4b43b923257fa908fc65dc156c5f84920caffb.webp" width="840" loading="lazy" alt="Fable 5 でニューヨークを作る Blender 都市モデリングのプロンプト"></a>

**プロンプト**

```text
これはニューヨークです。エージェントがたった一つのプロンプトで、自分だけで作りました。私は指一本動かしていません。まだ信じられません。

数日前、GPT 5.6 Sol で Blender のモデリングをする投稿を見かけ、それしか考えられなくなりました。実在するものを題材に試すしかありませんでした。

まず自宅から始めました。結果はひどく、変形した灰色のプラモデルのようでした。

そこでやめることもできました。でも改善を繰り返しました。

さまざまな情報源から建物の平面形状、高さ、座標など、現地の実データを集めるエージェントを組みました。Blender MCP、スキル、ライブラリを使い、Blender 本来のツールでモデルを構築します。

仕組みが整ったところで、「armá Nueva York（ニューヨークを作って）」と入力しました。

返ってきたのはマンハッタンです。実寸で、位置はメートル単位で正確。私は頂点を一つも触っていません。

予想外だったのは、いくつかのモデルを試した結果、この用途では GPT 5.6 Sol が Fable 5 を大きく上回ったことです。

これは数日間の成果です。今も建物の細部を改善しています。プロフィールの以前の動画を見れば、更新ごとの進歩が分かります。

次は一つのプロンプトで、より広い範囲をより精細に作ろうとしています。（Blender のテクスチャと素材に詳しい方、ぜひ教えてください 🙏）

でも本当に驚いているのはモデルそのものではなく、その先にできることです。

.blend は編集可能なままです。数フレーズで新しい塔を加え、大通りを動かし、都市全体を融合できます。ニューヨークにブエノスアイレスを重ね、タイムズスクエアの中央にオベリスクを立てることもできます。

都市をモデリングしているのではなく、現実を編集できる下書きに変えているのです。

リポジトリと .blend は最初のコメントに 👇 ここで進捗をすべて投稿していきます。進化が気になったらフォローしてください。まだ始まったばかりです。

次はどの都市を作ってほしいですか？
```

[詳細を見る ↗](https://www.tripo3d.ai/ja/3d-prompts/modeling-new-york-city-in-blender-2079387760478073087) · [元の投稿](https://x.com/MartinPulitano/status/2079387760478073087) · [作例一覧に戻る](#all-prompts)

---

<a id="single-file-three-js-voxel-soccer-animation-2079198084689723560"></a>

### 単一ファイルでボクセルサッカーを動かす Fable 5 の Three.js プロンプト

[Thành](https://x.com/Zmthanh) · 2026-07-20 · Claude Fable 5 · アニメーション

<a href="https://www.tripo3d.ai/ja/3d-prompts/single-file-three-js-voxel-soccer-animation-2079198084689723560"><img src="../assets/previews/b9f30819cb6139a05f901035cc1270fd3ee098356dac161654629d6bef2db479.webp" width="840" loading="lazy" alt="単一ファイルでボクセルサッカーを動かす Fable 5 の Three.js プロンプト"></a>

**プロンプト**

```text
Three.js（CDN）を使い、単一の HTML ファイルでシンプルなボクセル風サッカーアニメーションを作成してください。ブロック状の選手が守備 2 人をドリブルで抜き、見事なゴールを決め、祝福の粒子が舞います。色鮮やかなスタジアム風にしてください。完全な HTML コードだけを出力してください。
```

[詳細を見る ↗](https://www.tripo3d.ai/ja/3d-prompts/single-file-three-js-voxel-soccer-animation-2079198084689723560) · [元の投稿](https://x.com/Zmthanh/status/2079198084689723560) · [作例一覧に戻る](#all-prompts)

---

<a id="three-js-airplane-walkthrough-experience-2078806166122197132"></a>

### Three.js の飛行機内を歩く体験プロンプト

[FHILY👑](https://x.com/Oluwaphilemon1) · 2026-07-19 · Claude Fable 5 · インタラクティブ

<a href="https://www.tripo3d.ai/ja/3d-prompts/three-js-airplane-walkthrough-experience-2078806166122197132"><img src="../assets/previews/b045acf671506422acd90bc04f190e5d99618706982967e8f7a505cbe29507f2.webp" width="840" loading="lazy" alt="Three.js の飛行機内を歩く体験プロンプト"></a>

**プロンプト**

```text
3D の飛行機モデルを眺め、その中を歩ける体験を Three.js で生成してください。
```

[詳細を見る ↗](https://www.tripo3d.ai/ja/3d-prompts/three-js-airplane-walkthrough-experience-2078806166122197132) · [元の投稿](https://x.com/Oluwaphilemon1/status/2078806166122197132) · [作例一覧に戻る](#all-prompts)

---


[全カタログ](catalog.ja.md) · [←](catalog.ja.8.md) · **9 / 9**

<p align="center"><strong><a href="https://www.tripo3d.ai/ja/3d-prompts?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts&amp;utm_content=catalog_footer">全カタログ →</a></strong></p>
