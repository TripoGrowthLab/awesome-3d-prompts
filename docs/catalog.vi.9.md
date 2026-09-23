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
  <a href="../docs/catalog.uk.9.md"><img alt="Українська" src="https://img.shields.io/badge/%D0%A3%D0%BA%D1%80%D0%B0%D1%97%D0%BD%D1%81%D1%8C%D0%BA%D0%B0-64748b?style=flat-square"></a>
  <a href="../docs/catalog.vi.9.md"><img alt="Tiếng Việt" src="https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-✓-238636?style=flat-square"></a>
</p>

[Danh mục đầy đủ](catalog.vi.md) · [←](catalog.vi.8.md) · **9 / 9**

<a id="all-prompts"></a>

<details>
<summary>Khám phá ví dụ (5)</summary>

- [Prompt Kimi K3 dựng raytracer hố đen WebGL2 một tệp](#single-file-webgl2-black-hole-raytracer-2079590483727442205)
- [Prompt hoạt ảnh bóng đá voxel Three.js trong một tệp HTML](#voxel-soccer-animation-in-a-single-html-file-2079553757302710442)
- [Prompt Fable 5 dựng New York trong Blender](#modeling-new-york-city-in-blender-2079387760478073087)
- [Prompt Fable 5: hoạt ảnh bóng đá voxel Three.js trong một tệp](#single-file-three-js-voxel-soccer-animation-2079198084689723560)
- [Prompt Three.js cho trải nghiệm đi bên trong máy bay](#three-js-airplane-walkthrough-experience-2078806166122197132)

</details>
<a id="single-file-webgl2-black-hole-raytracer-2079590483727442205"></a>

### Prompt Kimi K3 dựng raytracer hố đen WebGL2 một tệp

[Harsh](https://x.com/devloper_hs) · 2026-07-21 · Kimi K3 · Hoạt ảnh

<a href="https://www.tripo3d.ai/vi/3d-prompts/single-file-webgl2-black-hole-raytracer-2079590483727442205"><img src="../assets/previews/5aff9deb1b2b504e0a15e14b6c97f70d2e06974efefa1eda0515703c4b1e4a08.webp" width="840" loading="lazy" alt="Prompt Kimi K3 dựng raytracer hố đen WebGL2 một tệp"></a>

**Prompt**

```text
Tạo một tệp HTML hoàn chỉnh, độc lập, không dùng thư viện ngoài như Three.js, triển khai raytracer trắc địa thời gian thực cho hố đen Schwarzschild lấy cảm hứng Gargantua.

Dùng WebGL2 thuần với GLSL ES 3.00 trong một fragment shader. Triển khai vật lý chính xác: tích phân đường trắc địa null bằng bộ giải Runge-Kutta bậc 4, chân trời sự kiện, cầu photon, đĩa bồi tụ render đúng, thấu kính hấp dẫn, tăng sáng Doppler và dịch đỏ hấp dẫn. Hướng đến hiệu năng ổn định 60 FPS.

Có camera xoay/phóng to bằng chuột và bảng điều khiển cyberpunk với thanh trượt thông số: khối lượng, spin, mật độ đĩa, góc nhìn, v.v. Thêm hiệu ứng hạt nhẹ cho vật chất rơi vào và ánh sáng/bóng động.

Đầu ra phải hoàn chỉnh 100%, chạy ngay trong trình duyệt hiện đại, không màn đen, NaN, lỗi hay tính năng thiếu. Ưu tiên cao nhất tính đúng số học, xử lý biên, kỷ luật bộ giải và độ chính xác vật lý. Xác minh và chú thích các phương trình vật lý quan trọng trong mã. Làm hình ảnh ấn tượng, tương tác như demo/game vật lý cao cấp.
```

[Xem chi tiết ↗](https://www.tripo3d.ai/vi/3d-prompts/single-file-webgl2-black-hole-raytracer-2079590483727442205) · [Bài đăng gốc](https://x.com/devloper_hs/status/2079590483727442205) · [Về danh sách ví dụ](#all-prompts)

---

<a id="voxel-soccer-animation-in-a-single-html-file-2079553757302710442"></a>

### Prompt hoạt ảnh bóng đá voxel Three.js trong một tệp HTML

[Thành](https://x.com/Zmthanh) · 2026-07-21 · Kimi K3 · Hoạt ảnh

<a href="https://www.tripo3d.ai/vi/3d-prompts/voxel-soccer-animation-in-a-single-html-file-2079553757302710442"><img src="../assets/previews/771fe49a27ee707d5b3e4fe6f4ff4b4ab7eada49eda5ec2a5bd000b8fefb33da.webp" width="840" loading="lazy" alt="Prompt hoạt ảnh bóng đá voxel Three.js trong một tệp HTML"></a>

**Prompt**

```text
Tạo một tệp HTML với Three.js qua CDN cho hoạt ảnh bóng đá voxel đơn giản. Cầu thủ dạng khối rê bóng qua 2 hậu vệ rồi ghi bàn ngoạn mục với hạt ăn mừng. Sân vận động đầy màu sắc. CHỈ xuất toàn bộ mã HTML.
```

[Xem chi tiết ↗](https://www.tripo3d.ai/vi/3d-prompts/voxel-soccer-animation-in-a-single-html-file-2079553757302710442) · [Bài đăng gốc](https://x.com/Zmthanh/status/2079553757302710442) · [Về danh sách ví dụ](#all-prompts)

---

<a id="modeling-new-york-city-in-blender-2079387760478073087"></a>

### Prompt Fable 5 dựng New York trong Blender

[Martin Puli](https://x.com/MartinPulitano) · 2026-07-21 · Claude Fable 5 · Bối cảnh

<a href="https://www.tripo3d.ai/vi/3d-prompts/modeling-new-york-city-in-blender-2079387760478073087"><img src="../assets/previews/c1df84f5898cf9fec4ed0c498e4b43b923257fa908fc65dc156c5f84920caffb.webp" width="840" loading="lazy" alt="Prompt Fable 5 dựng New York trong Blender"></a>

**Prompt**

```text
Đây là New York. Một agent tự dựng nó bằng MỘT prompt. Tôi không động tay. Đến giờ vẫn chưa tin nổi.

Vài ngày trước tôi thấy các bài về việc dựng hình Blender bằng GPT 5.6 Sol và không thể nghĩ đến điều gì khác. Tôi phải thử với thứ gì đó thật.

Tôi bắt đầu từ nhà mình. Kết quả tệ hại: méo mó, xám xịt, như mô hình nhựa.

Tôi có thể dừng ở đó. Nhưng tôi bắt đầu lặp và sửa.

Tôi ghép vài agent thu thập dữ liệu thật về địa điểm từ hàng nghìn nguồn: dấu chân công trình, chiều cao, tọa độ. Với Blender MCP + skills + thư viện, chúng dựng mô hình bằng công cụ của chính Blender.

Khi hệ thống sẵn sàng, tôi gõ: “dựng New York”.

Nó trả về Manhattan. Kích thước thật, vị trí chính xác đến từng mét, tôi không chạm một đỉnh nào.

Điều tôi không ngờ là khi thử nhiều mô hình, GPT 5.6 Sol vượt Fable 5 RẤT XA ở tác vụ này.

Mới chỉ vài ngày. Tôi vẫn đang tinh chỉnh chi tiết công trình. Xem các video trước trong hồ sơ sẽ thấy nó tiến bộ bao nhiêu sau mỗi lần cập nhật.

Giờ tôi đang cố tăng diện tích và độ chi tiết với một prompt. Nếu bạn hiểu texture và vật liệu Blender, tôi rất muốn nghe 🙏

Nhưng thứ khiến tôi choáng nhất không phải mô hình, mà là những khả năng mở ra sau đó.

Tệp .blend vẫn sống. Chỉ vài câu là có thể thêm tòa tháp, chuyển đại lộ hay nhập cả thành phố với nhau. Buenos Aires nằm trên New York. Tháp Obelisk đứng giữa Times Square.

Tôi không dựng một thành phố. Tôi biến thực tế thành bản nháp có thể chỉnh sửa.

Repo + .blend ở bình luận đầu 👇 Tôi sẽ tiếp tục đăng từng bước ở đây. Nếu thích tiến trình này, hãy theo dõi vì chúng ta mới bắt đầu.

Bạn muốn tôi dựng thành phố nào tiếp theo?
```

[Xem chi tiết ↗](https://www.tripo3d.ai/vi/3d-prompts/modeling-new-york-city-in-blender-2079387760478073087) · [Bài đăng gốc](https://x.com/MartinPulitano/status/2079387760478073087) · [Về danh sách ví dụ](#all-prompts)

---

<a id="single-file-three-js-voxel-soccer-animation-2079198084689723560"></a>

### Prompt Fable 5: hoạt ảnh bóng đá voxel Three.js trong một tệp

[Thành](https://x.com/Zmthanh) · 2026-07-20 · Claude Fable 5 · Hoạt ảnh

<a href="https://www.tripo3d.ai/vi/3d-prompts/single-file-three-js-voxel-soccer-animation-2079198084689723560"><img src="../assets/previews/b9f30819cb6139a05f901035cc1270fd3ee098356dac161654629d6bef2db479.webp" width="840" loading="lazy" alt="Prompt Fable 5: hoạt ảnh bóng đá voxel Three.js trong một tệp"></a>

**Prompt**

```text
Tạo một tệp HTML với Three.js qua CDN cho hoạt ảnh bóng đá voxel đơn giản. Cầu thủ dạng khối rê bóng qua 2 hậu vệ rồi ghi bàn ngoạn mục với hạt ăn mừng. Sân vận động đầy màu sắc. CHỈ xuất toàn bộ mã HTML.
```

[Xem chi tiết ↗](https://www.tripo3d.ai/vi/3d-prompts/single-file-three-js-voxel-soccer-animation-2079198084689723560) · [Bài đăng gốc](https://x.com/Zmthanh/status/2079198084689723560) · [Về danh sách ví dụ](#all-prompts)

---

<a id="three-js-airplane-walkthrough-experience-2078806166122197132"></a>

### Prompt Three.js cho trải nghiệm đi bên trong máy bay

[FHILY👑](https://x.com/Oluwaphilemon1) · 2026-07-19 · Claude Fable 5 · Tương tác

<a href="https://www.tripo3d.ai/vi/3d-prompts/three-js-airplane-walkthrough-experience-2078806166122197132"><img src="../assets/previews/b045acf671506422acd90bc04f190e5d99618706982967e8f7a505cbe29507f2.webp" width="840" loading="lazy" alt="Prompt Three.js cho trải nghiệm đi bên trong máy bay"></a>

**Prompt**

```text
Tạo trải nghiệm Three.js cho phép tôi xem mô hình máy bay 3D và đi bên trong.
```

[Xem chi tiết ↗](https://www.tripo3d.ai/vi/3d-prompts/three-js-airplane-walkthrough-experience-2078806166122197132) · [Bài đăng gốc](https://x.com/Oluwaphilemon1/status/2078806166122197132) · [Về danh sách ví dụ](#all-prompts)

---


[Danh mục đầy đủ](catalog.vi.md) · [←](catalog.vi.8.md) · **9 / 9**

<p align="center"><strong><a href="https://www.tripo3d.ai/vi/3d-prompts?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts&amp;utm_content=catalog_footer">Danh mục đầy đủ →</a></strong></p>
