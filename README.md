# Bamedonghanh

Trang giới thiệu 3 web app học tập miễn phí cho con, chạy tại **bamedonghanh.com**:

- **Lumi English**: Tiếng Anh lớp 1–5 → https://mhtiny3ds-a11y.github.io/lumi-english-free/
- **Học Toán Vui**: Toán tư duy 4–8 tuổi → https://mhtiny3ds-a11y.github.io/hoc-toan-vui/
- **Toán Vui cùng Pi**: Toán lớp 1–5 → https://mhtiny3ds-a11y.github.io/maths-easy/

Một trang HTML tĩnh duy nhất (`index.html`), không cần build. Ảnh linh vật nằm trong `assets/`.

## Đưa lên GitHub Pages với tên miền riêng

1. **Settings → Pages**: chọn *Deploy from a branch*, nhánh `main`, thư mục `/ (root)`.
2. File `CNAME` đã có sẵn `bamedonghanh.com`. Ở mục *Custom domain* nhập `bamedonghanh.com` và bật *Enforce HTTPS*.
3. Tại nhà cung cấp tên miền, tạo bản ghi DNS:
   - 4 bản ghi `A` cho `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - 1 bản ghi `CNAME` cho `www` → `mhtiny3ds-a11y.github.io`

## Sửa nội dung

- Đổi link app: sửa thuộc tính `href` của 3 thẻ `<a class="app ...">` trong `index.html`.
- Đổi ảnh: thay file trong `assets/` (giữ nguyên tên) hoặc sửa `src` của thẻ `<img>`.
- Đổi chữ Sứ mệnh / Ba mẹ đồng hành: sửa 2 khối `.box` cuối `index.html`.
