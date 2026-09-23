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
  <a href="../docs/catalog.tr.9.md"><img alt="Türkçe" src="https://img.shields.io/badge/T%C3%BCrk%C3%A7e-64748b?style=flat-square"></a>
  <a href="../docs/catalog.uk.9.md"><img alt="Українська" src="https://img.shields.io/badge/%D0%A3%D0%BA%D1%80%D0%B0%D1%97%D0%BD%D1%81%D1%8C%D0%BA%D0%B0-✓-238636?style=flat-square"></a>
  <a href="../docs/catalog.vi.9.md"><img alt="Tiếng Việt" src="https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-64748b?style=flat-square"></a>
</p>

[Повний каталог](catalog.uk.md) · [←](catalog.uk.8.md) · **9 / 9**

<a id="all-prompts"></a>

<details>
<summary>Переглянути приклади (5)</summary>

- [Промпт Kimi K3 для однофайлового трасувальника чорної діри WebGL2](#single-file-webgl2-black-hole-raytracer-2079590483727442205)
- [Промпт воксельної футбольної анімації Three.js в одному HTML-файлі](#voxel-soccer-animation-in-a-single-html-file-2079553757302710442)
- [Промпт Fable 5 для моделювання Нью-Йорка в Blender](#modeling-new-york-city-in-blender-2079387760478073087)
- [Промпт Fable 5: воксельна футбольна анімація Three.js в одному файлі](#single-file-three-js-voxel-soccer-animation-2079198084689723560)
- [Промпт Three.js для прогулянки літаком](#three-js-airplane-walkthrough-experience-2078806166122197132)

</details>
<a id="single-file-webgl2-black-hole-raytracer-2079590483727442205"></a>

### Промпт Kimi K3 для однофайлового трасувальника чорної діри WebGL2

[Harsh](https://x.com/devloper_hs) · 2026-07-21 · Kimi K3 · Анімація

<a href="https://www.tripo3d.ai/uk/3d-prompts/single-file-webgl2-black-hole-raytracer-2079590483727442205"><img src="../assets/previews/5aff9deb1b2b504e0a15e14b6c97f70d2e06974efefa1eda0515703c4b1e4a08.webp" width="840" loading="lazy" alt="Промпт Kimi K3 для однофайлового трасувальника чорної діри WebGL2"></a>

**Промпт**

```text
Створи повний самодостатній HTML-файл без зовнішніх бібліотек на кшталт Three.js, що реалізує геодезичний трасувальник променів у реальному часі для чорної діри Шварцшильда в дусі Гаргантюа.

Використай чистий WebGL2 і GLSL ES 3.00 в одному фрагментному шейдері. Реалізуй точну фізику: інтегрування нульових геодезичних розв’язувачем Рунге—Кутти 4-го порядку, горизонт подій, фотонну сферу, коректний рендеринг акреційного диска, гравітаційне лінзування, доплерівське підсилення випромінювання та гравітаційне червоне зміщення. Ціль — стабільні 60 FPS.

Додай обертання й наближення камери мишею та панель керування в стилі кіберпанк із повзунками параметрів: маса, обертання, щільність диска, кут огляду тощо. Додай ненав’язливі частинки речовини, що падає, та динамічне освітлення й тіні.

Результат має бути на 100% завершеним і одразу запускатися в сучасному браузері: без чорного екрана, NaN, помилок чи відсутніх функцій. Найвищий пріоритет — чисельна коректність, обробка меж, дисципліна розв’язувача й фізична точність. Перевір ключові фізичні рівняння та прокоментуй їх у коді. Зроби результат візуально вражаючим та інтерактивним, як якісне фізичне демо чи гра.
```

[Докладніше ↗](https://www.tripo3d.ai/uk/3d-prompts/single-file-webgl2-black-hole-raytracer-2079590483727442205) · [Оригінальний допис](https://x.com/devloper_hs/status/2079590483727442205) · [Назад до прикладів](#all-prompts)

---

<a id="voxel-soccer-animation-in-a-single-html-file-2079553757302710442"></a>

### Промпт воксельної футбольної анімації Three.js в одному HTML-файлі

[Thành](https://x.com/Zmthanh) · 2026-07-21 · Kimi K3 · Анімація

<a href="https://www.tripo3d.ai/uk/3d-prompts/voxel-soccer-animation-in-a-single-html-file-2079553757302710442"><img src="../assets/previews/771fe49a27ee707d5b3e4fe6f4ff4b4ab7eada49eda5ec2a5bd000b8fefb33da.webp" width="840" loading="lazy" alt="Промпт воксельної футбольної анімації Three.js в одному HTML-файлі"></a>

**Промпт**

```text
Створи один HTML-файл із Three.js через CDN для простої футбольної анімації у воксельному стилі. Блоковий гравець обводить двох захисників і забиває видовищний гол зі святковими частинками. Яскравий стадіон. Виведи ЛИШЕ повний HTML-код.
```

[Докладніше ↗](https://www.tripo3d.ai/uk/3d-prompts/voxel-soccer-animation-in-a-single-html-file-2079553757302710442) · [Оригінальний допис](https://x.com/Zmthanh/status/2079553757302710442) · [Назад до прикладів](#all-prompts)

---

<a id="modeling-new-york-city-in-blender-2079387760478073087"></a>

### Промпт Fable 5 для моделювання Нью-Йорка в Blender

[Martin Puli](https://x.com/MartinPulitano) · 2026-07-21 · Claude Fable 5 · Сцени

<a href="https://www.tripo3d.ai/uk/3d-prompts/modeling-new-york-city-in-blender-2079387760478073087"><img src="../assets/previews/c1df84f5898cf9fec4ed0c498e4b43b923257fa908fc65dc156c5f84920caffb.webp" width="840" loading="lazy" alt="Промпт Fable 5 для моделювання Нью-Йорка в Blender"></a>

**Промпт**

```text
Це Нью-Йорк. Агент побудував його сам, за ОДНИМ промптом. Я й пальцем не поворухнув. Досі не можу це осягнути.

Кілька днів тому я натрапив на дописи людей, які моделюють у Blender з GPT 5.6 Sol, і вже ні про що інше не міг думати. Треба було спробувати на чомусь справжньому.

Почав зі свого будинку. Вийшло казна-що: покручене, сіре, наче пластиковий макет.

Міг би на цьому зупинитися. Але почав удосконалювати.

Я зібрав агентів, які збирають реальні дані про місце з тисячі джерел: контури будівель, висоти, координати. За допомогою Blender MCP + skills + бібліотек вони будують модель власними інструментами Blender.

Коли система була готова, я ввів промпт: «збери Нью-Йорк».

Вона повернула Мангеттен. Справжні розміри, розташування з точністю до метра — і я не торкнувся жодної вершини.

Чого я не очікував: я перевірив кілька моделей, і тут GPT 5.6 Sol ДУЖЕ суттєво випереджає Fable 5.

Минуло лише кілька днів. Я досі вдосконалюю деталі будівель. У попередніх відео мого профілю видно, наскільки результат поліпшувався від оновлення до оновлення.

Тепер намагаюся охопити більше площі й деталей одним промптом. Якщо знаєтеся на текстурах і матеріалах Blender, я слухаю 🙏

Та найбільше мене вражає не сама модель, а те, що відкривається після неї.

Файл .blend залишається живим. Кількома фразами можна додати нову вежу, пересунути проспект чи об’єднати цілі міста. Буенос-Айрес поверх Нью-Йорка. Обеліск посеред Таймс-сквер.

Я не моделюю місто. Я перетворюю реальність на чернетку, яку можна редагувати.

Репозиторій + .blend у першому коментарі 👇 Далі публікуватиму тут кожен крок. Якщо подобається розвиток, підписуйтеся: ми лише починаємо.

Яке місто змоделювати наступним?
```

[Докладніше ↗](https://www.tripo3d.ai/uk/3d-prompts/modeling-new-york-city-in-blender-2079387760478073087) · [Оригінальний допис](https://x.com/MartinPulitano/status/2079387760478073087) · [Назад до прикладів](#all-prompts)

---

<a id="single-file-three-js-voxel-soccer-animation-2079198084689723560"></a>

### Промпт Fable 5: воксельна футбольна анімація Three.js в одному файлі

[Thành](https://x.com/Zmthanh) · 2026-07-20 · Claude Fable 5 · Анімація

<a href="https://www.tripo3d.ai/uk/3d-prompts/single-file-three-js-voxel-soccer-animation-2079198084689723560"><img src="../assets/previews/b9f30819cb6139a05f901035cc1270fd3ee098356dac161654629d6bef2db479.webp" width="840" loading="lazy" alt="Промпт Fable 5: воксельна футбольна анімація Three.js в одному файлі"></a>

**Промпт**

```text
Створи один HTML-файл із Three.js через CDN для простої футбольної анімації у воксельному стилі. Блоковий гравець обводить двох захисників і забиває видовищний гол зі святковими частинками. Яскравий стадіон. Виведи ЛИШЕ повний HTML-код.
```

[Докладніше ↗](https://www.tripo3d.ai/uk/3d-prompts/single-file-three-js-voxel-soccer-animation-2079198084689723560) · [Оригінальний допис](https://x.com/Zmthanh/status/2079198084689723560) · [Назад до прикладів](#all-prompts)

---

<a id="three-js-airplane-walkthrough-experience-2078806166122197132"></a>

### Промпт Three.js для прогулянки літаком

[FHILY👑](https://x.com/Oluwaphilemon1) · 2026-07-19 · Claude Fable 5 · Інтерактив

<a href="https://www.tripo3d.ai/uk/3d-prompts/three-js-airplane-walkthrough-experience-2078806166122197132"><img src="../assets/previews/b045acf671506422acd90bc04f190e5d99618706982967e8f7a505cbe29507f2.webp" width="840" loading="lazy" alt="Промпт Three.js для прогулянки літаком"></a>

**Промпт**

```text
Створи на Three.js сцену, яка дає мені оглядати 3D-модель літака та ходити всередині нього.
```

[Докладніше ↗](https://www.tripo3d.ai/uk/3d-prompts/three-js-airplane-walkthrough-experience-2078806166122197132) · [Оригінальний допис](https://x.com/Oluwaphilemon1/status/2078806166122197132) · [Назад до прикладів](#all-prompts)

---


[Повний каталог](catalog.uk.md) · [←](catalog.uk.8.md) · **9 / 9**

<p align="center"><strong><a href="https://www.tripo3d.ai/uk/3d-prompts?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts&amp;utm_content=catalog_footer">Повний каталог →</a></strong></p>
