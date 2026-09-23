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
  <a href="../docs/catalog.ru.9.md"><img alt="Русский" src="https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-✓-238636?style=flat-square"></a>
  <a href="../docs/catalog.tr.9.md"><img alt="Türkçe" src="https://img.shields.io/badge/T%C3%BCrk%C3%A7e-64748b?style=flat-square"></a>
  <a href="../docs/catalog.uk.9.md"><img alt="Українська" src="https://img.shields.io/badge/%D0%A3%D0%BA%D1%80%D0%B0%D1%97%D0%BD%D1%81%D1%8C%D0%BA%D0%B0-64748b?style=flat-square"></a>
  <a href="../docs/catalog.vi.9.md"><img alt="Tiếng Việt" src="https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-64748b?style=flat-square"></a>
</p>

[Полный каталог](catalog.ru.md) · [←](catalog.ru.8.md) · **9 / 9**

<a id="all-prompts"></a>

<details>
<summary>Посмотреть примеры (5)</summary>

- [Промпт Kimi K3 для однофайлового трассировщика чёрной дыры WebGL2](#single-file-webgl2-black-hole-raytracer-2079590483727442205)
- [Промпт воксельной футбольной анимации Three.js в одном HTML-файле](#voxel-soccer-animation-in-a-single-html-file-2079553757302710442)
- [Промпт Fable 5 для моделирования Нью-Йорка в Blender](#modeling-new-york-city-in-blender-2079387760478073087)
- [Промпт Fable 5: воксельная футбольная анимация Three.js в одном файле](#single-file-three-js-voxel-soccer-animation-2079198084689723560)
- [Промпт Three.js для прогулки по самолёту](#three-js-airplane-walkthrough-experience-2078806166122197132)

</details>
<a id="single-file-webgl2-black-hole-raytracer-2079590483727442205"></a>

### Промпт Kimi K3 для однофайлового трассировщика чёрной дыры WebGL2

[Harsh](https://x.com/devloper_hs) · 2026-07-21 · Kimi K3 · Анимация

<a href="https://www.tripo3d.ai/ru/3d-prompts/single-file-webgl2-black-hole-raytracer-2079590483727442205"><img src="../assets/previews/5aff9deb1b2b504e0a15e14b6c97f70d2e06974efefa1eda0515703c4b1e4a08.webp" width="840" loading="lazy" alt="Промпт Kimi K3 для однофайлового трассировщика чёрной дыры WebGL2"></a>

**Промпт**

```text
Создай полноценный самостоятельный HTML-файл без внешних библиотек вроде Three.js, реализующий геодезический трассировщик лучей в реальном времени для чёрной дыры Шварцшильда в духе Гаргантюа.

Используй чистый WebGL2 и GLSL ES 3.00 в одном фрагментном шейдере. Реализуй точную физику: интегрирование нулевых геодезических решателем Рунге—Кутты 4-го порядка, горизонт событий, фотонную сферу, корректный рендеринг аккреционного диска, гравитационное линзирование, доплеровское усиление излучения и гравитационное красное смещение. Цель — стабильные 60 FPS.

Добавь вращение и приближение камеры мышью и панель управления в стиле киберпанк с ползунками параметров: масса, вращение, плотность диска, угол обзора и так далее. Добавь ненавязчивые частицы падающего вещества, динамическое освещение и тени.

Результат должен быть полностью законченным и сразу запускаться в современном браузере: без чёрного экрана, NaN, ошибок или недостающих функций. Прежде всего обеспечь численную корректность, обработку границ, строгость работы решателя и физическую точность. Проверь ключевые физические уравнения и прокомментируй их в коде. Сделай результат впечатляющим и интерактивным, как качественное физическое демо или игра.
```

[Подробнее ↗](https://www.tripo3d.ai/ru/3d-prompts/single-file-webgl2-black-hole-raytracer-2079590483727442205) · [Исходная публикация](https://x.com/devloper_hs/status/2079590483727442205) · [Назад к примерам](#all-prompts)

---

<a id="voxel-soccer-animation-in-a-single-html-file-2079553757302710442"></a>

### Промпт воксельной футбольной анимации Three.js в одном HTML-файле

[Thành](https://x.com/Zmthanh) · 2026-07-21 · Kimi K3 · Анимация

<a href="https://www.tripo3d.ai/ru/3d-prompts/voxel-soccer-animation-in-a-single-html-file-2079553757302710442"><img src="../assets/previews/771fe49a27ee707d5b3e4fe6f4ff4b4ab7eada49eda5ec2a5bd000b8fefb33da.webp" width="840" loading="lazy" alt="Промпт воксельной футбольной анимации Three.js в одном HTML-файле"></a>

**Промпт**

```text
Создай один HTML-файл с Three.js через CDN для простой футбольной анимации в воксельном стиле. Блочный игрок обводит двух защитников и забивает эффектный гол с праздничными частицами. Яркий стадион. Выведи ТОЛЬКО полный HTML-код.
```

[Подробнее ↗](https://www.tripo3d.ai/ru/3d-prompts/voxel-soccer-animation-in-a-single-html-file-2079553757302710442) · [Исходная публикация](https://x.com/Zmthanh/status/2079553757302710442) · [Назад к примерам](#all-prompts)

---

<a id="modeling-new-york-city-in-blender-2079387760478073087"></a>

### Промпт Fable 5 для моделирования Нью-Йорка в Blender

[Martin Puli](https://x.com/MartinPulitano) · 2026-07-21 · Claude Fable 5 · Сцены

<a href="https://www.tripo3d.ai/ru/3d-prompts/modeling-new-york-city-in-blender-2079387760478073087"><img src="../assets/previews/c1df84f5898cf9fec4ed0c498e4b43b923257fa908fc65dc156c5f84920caffb.webp" width="840" loading="lazy" alt="Промпт Fable 5 для моделирования Нью-Йорка в Blender"></a>

**Промпт**

```text
Это Нью-Йорк. Агент построил его сам, по ОДНОМУ промпту. Я и пальцем не пошевелил. До сих пор не могу это осознать.

Несколько дней назад я наткнулся на посты людей, моделирующих в Blender с GPT 5.6 Sol, и уже ни о чём другом не мог думать. Нужно было попробовать на чём-то настоящем.

Начал со своего дома. Получился мусор: кривой, серый, словно пластиковый макет.

Можно было на этом остановиться. Но я начал дорабатывать.

Я собрал агентов, которые вытягивают реальные данные о месте из тысячи источников: контуры зданий, высоты, координаты. С помощью Blender MCP + skills + библиотек они строят модель собственными инструментами Blender.

Когда система была готова, я ввёл промпт: «собери Нью-Йорк».

Она вернула Манхэттен. Реальные размеры, расположение с точностью до метра — и я не тронул ни одной вершины.

Чего я не ожидал: я проверил несколько моделей, и здесь GPT 5.6 Sol ОЧЕНЬ сильно обходит Fable 5.

Прошло всего несколько дней. Я всё ещё дорабатываю детализацию зданий. Если посмотрите предыдущие видео в моём профиле, увидите, насколько результат улучшался от обновления к обновлению.

Теперь пытаюсь охватить больше площади и деталей одним промптом. Если разбираетесь в текстурах и материалах Blender, я весь внимание 🙏

Но больше всего меня поражает не сама модель, а возможности, которые открываются дальше.

Файл .blend остаётся живым. Парой фраз можно добавить новую башню, передвинуть проспект или объединить целые города. Буэнос-Айрес поверх Нью-Йорка. Обелиск посреди Таймс-сквер.

Я не моделирую город. Я превращаю реальность в редактируемый черновик.

Репозиторий + .blend в первом комментарии 👇 Продолжу публиковать здесь каждый шаг. Если нравится развитие проекта, подписывайтесь: мы только начинаем.

Какой город смоделировать следующим?
```

[Подробнее ↗](https://www.tripo3d.ai/ru/3d-prompts/modeling-new-york-city-in-blender-2079387760478073087) · [Исходная публикация](https://x.com/MartinPulitano/status/2079387760478073087) · [Назад к примерам](#all-prompts)

---

<a id="single-file-three-js-voxel-soccer-animation-2079198084689723560"></a>

### Промпт Fable 5: воксельная футбольная анимация Three.js в одном файле

[Thành](https://x.com/Zmthanh) · 2026-07-20 · Claude Fable 5 · Анимация

<a href="https://www.tripo3d.ai/ru/3d-prompts/single-file-three-js-voxel-soccer-animation-2079198084689723560"><img src="../assets/previews/b9f30819cb6139a05f901035cc1270fd3ee098356dac161654629d6bef2db479.webp" width="840" loading="lazy" alt="Промпт Fable 5: воксельная футбольная анимация Three.js в одном файле"></a>

**Промпт**

```text
Создай один HTML-файл с Three.js через CDN для простой футбольной анимации в воксельном стиле. Блочный игрок обводит двух защитников и забивает эффектный гол с праздничными частицами. Яркий стадион. Выведи ТОЛЬКО полный HTML-код.
```

[Подробнее ↗](https://www.tripo3d.ai/ru/3d-prompts/single-file-three-js-voxel-soccer-animation-2079198084689723560) · [Исходная публикация](https://x.com/Zmthanh/status/2079198084689723560) · [Назад к примерам](#all-prompts)

---

<a id="three-js-airplane-walkthrough-experience-2078806166122197132"></a>

### Промпт Three.js для прогулки по самолёту

[FHILY👑](https://x.com/Oluwaphilemon1) · 2026-07-19 · Claude Fable 5 · Интерактив

<a href="https://www.tripo3d.ai/ru/3d-prompts/three-js-airplane-walkthrough-experience-2078806166122197132"><img src="../assets/previews/b045acf671506422acd90bc04f190e5d99618706982967e8f7a505cbe29507f2.webp" width="840" loading="lazy" alt="Промпт Three.js для прогулки по самолёту"></a>

**Промпт**

```text
Создай на Three.js сцену, в которой я могу рассматривать 3D-модель самолёта и ходить внутри него.
```

[Подробнее ↗](https://www.tripo3d.ai/ru/3d-prompts/three-js-airplane-walkthrough-experience-2078806166122197132) · [Исходная публикация](https://x.com/Oluwaphilemon1/status/2078806166122197132) · [Назад к примерам](#all-prompts)

---


[Полный каталог](catalog.ru.md) · [←](catalog.ru.8.md) · **9 / 9**

<p align="center"><strong><a href="https://www.tripo3d.ai/ru/3d-prompts?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts&amp;utm_content=catalog_footer">Полный каталог →</a></strong></p>
