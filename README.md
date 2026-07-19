# Portfolio Kỹ thuật số — Nguyễn Thành Nguyên

Sinh viên ngành Kinh tế và Kinh doanh quốc tế · Đại học Kinh tế – ĐHQGHN
Học phần: Nhập môn Công nghệ số & Ứng dụng Trí tuệ nhân tạo.

## Cấu trúc

```
index.html      Trang giới thiệu
du-an.html      7 ô bài tập (đang để trống, chờ tải PDF lên)
tong-ket.html   Trang tổng kết
style.css       Toàn bộ giao diện
pdf/            Nơi đặt file bài tập
```

## Cách thêm bài tập

1. Copy file PDF vào thư mục `pdf/`, đặt tên `bai-1.pdf` … `bai-7.pdf`.
   Nút **Mở PDF** của ô tương ứng trong `du-an.html` sẽ chạy được ngay.
2. Sửa tiêu đề / mô tả từng ô: mở `du-an.html`, thay chữ trong thẻ `<h3>` và `<p>`.
3. Khi ô đã có nội dung: xoá dòng `<div class="slot-note">…</div>` và bỏ chữ `empty`
   trong `class="card pj empty"` để ô hiển thị như thẻ hoàn chỉnh.

## Xem thử

Mở trực tiếp `index.html` bằng trình duyệt, hoặc chạy:

```
python -m http.server 8000
```

rồi vào http://localhost:8000
