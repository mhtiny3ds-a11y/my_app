# Bamedonghanh

Trang giới thiệu 3 web app học tập miễn phí cho con, đang chạy tại **https://bamedonghanh.pro.vn/**:

- **Lumi English**: Tiếng Anh lớp 1–5 → https://mhtiny3ds-a11y.github.io/lumi-english-free/
- **Học Toán Vui**: Toán tư duy 4–8 tuổi → https://mhtiny3ds-a11y.github.io/hoc-toan-vui/
- **Toán Vui cùng Pi**: Toán lớp 1–5 → https://mhtiny3ds-a11y.github.io/maths-easy/

Một trang HTML tĩnh duy nhất (`index.html`), không cần build. Ảnh linh vật nằm trong `assets/`.

## Tên miền

Trang dùng tên miền **bamedonghanh.pro.vn** (file `CNAME`, cài trong *Settings → Pages → Custom domain*). Địa chỉ cũ `mhtiny3ds-a11y.github.io/my_app/` tự chuyển về tên miền này.
Nếu đổi tên miền: sửa ở *Custom domain*, rồi đổi `canonical` và `og:url` trong `index.html`.

## Hướng dẫn đưa App ra màn hình điện thoại

Nút **📲 Đưa App ra màn hình điện thoại** mở bảng hướng dẫn 2 tab Android / iPhone–iPad (tự chọn tab theo máy).
Có thể gửi thẳng link mở sẵn bảng hướng dẫn: `https://bamedonghanh.pro.vn/#cai-dat`.

## Hướng dẫn sử dụng từng App

Dưới mỗi ô App có nút **📖 Hướng dẫn sử dụng**, mở bảng hướng dẫn nhanh của App đó (Học Toán Vui và Toán Vui cùng Pi có thêm link tới file PDF đầy đủ).
Link mở thẳng: `#huong-dan-lumi`, `#huong-dan-toan-vui`, `#huong-dan-pi` (ví dụ `https://bamedonghanh.pro.vn/#huong-dan-pi`).
Nội dung nằm trong khối `<dialog id="howto">` của `index.html`.

## Cập nhật mới của 3 App (11/2026)

| | 🐾 Thú cưng | 🔓 Mở khóa bài theo trình độ |
|---|---|---|
| **Lumi English** | Gà con, Cún con, Mèo con, Rồng con. Mỗi bài xong được ăn (3 sao = 2 bữa), lớn từ Quả trứng đến Siêu sao. | Tài khoản → Mở khóa bài theo trình độ của con → 🔓 Chọn bài: mở Unit bất kỳ hoặc cả lớp; "Về lộ trình" để khóa lại. |
| **Học Toán Vui** | Rồng Lửa, Mèo Mây, Cún Sao. Lớn theo số bài và thử thách đã xong, từ Quả trứng đến Huyền thoại. | Tổng quan hoặc Tài khoản → Mở khóa bài theo trình độ: tích từng bài, mở cả chặng hoặc cả 120 bài. |
| **Toán Vui cùng Pi** | Rồng Mây, Thỏ Bông, Cún Đốm, Gà Lửa. Mỗi bước học xong được ăn, nhiệm vụ được duyệt +3 điểm lớn; 6 giai đoạn đến Huyền thoại. | Thẻ của con ở Tổng quan hoặc Tài khoản: mở bài bất kỳ, "Bắt đầu từ đây", "Mở cả lớp", "Khóa lại như cũ". |

Trên trang giới thiệu: mỗi ô App có nhãn **🐾 Thú cưng**, và bảng **📖 Hướng dẫn sử dụng** của từng App có thêm 2 mục gắn nhãn **MỚI**.

## Đám mây slogan cho ba mẹ

- Màn hình ngang rộng (từ 1180px): 4 đám mây trôi ở hai bên lề.
- Màn hình dọc đủ cao (điện thoại lớn, máy tính bảng): 1 đám mây phía trên logo, tự đổi câu mỗi 5 giây.
- Màn hình nhỏ hoặc thấp: ẩn để trang vẫn gọn trong 1 màn hình.
- Sửa câu slogan: 4 câu trong khối `<div class="clouds">` và danh sách `SLOGANS` trong phần `<script>` của `index.html`.

## Sửa nội dung

- Đổi link app: sửa thuộc tính `href` của 3 thẻ `<a class="app ...">` trong `index.html`.
- Đổi ảnh: thay file trong `assets/` (giữ nguyên tên) hoặc sửa `src` của thẻ `<img>`.
- Đổi chữ Sứ mệnh / Ba mẹ đồng hành: sửa 2 khối `.box` cuối `index.html`.
