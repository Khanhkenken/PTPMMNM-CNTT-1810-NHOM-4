# PTPMMNM-CNTT-1810-NHOM-4 — Bài tập thực hành

Kho mã chứa các bài thực hành môn **Phát triển phần mềm mã nguồn mở** của nhóm 4. Mỗi bài nằm trên một **branch riêng** để giữ lịch sử commit độc lập theo yêu cầu nộp bài.

## Danh sách bài

| Bài    | Tên đề tài                                  | Branch | Xem trên GitHub |
|--------|---------------------------------------------|--------|-----------------|
| Lab 01 | Linux và shell script                       | [`lab1`](https://github.com/Khanhkenken/PTPMMNM-CNTT-1810-NHOM-4/tree/lab1) | [Mở branch lab1](https://github.com/Khanhkenken/PTPMMNM-CNTT-1810-NHOM-4/tree/lab1) |
| Lab 02 | Module PHP kiểm tra điều kiện đăng ký       | [`lab2`](https://github.com/Khanhkenken/PTPMMNM-CNTT-1810-NHOM-4/tree/lab2) | [Mở branch lab2](https://github.com/Khanhkenken/PTPMMNM-CNTT-1810-NHOM-4/tree/lab2) |
| Lab 03 | Danh sách sự kiện, tìm kiếm và form         | [`lab3`](https://github.com/Khanhkenken/PTPMMNM-CNTT-1810-NHOM-4/tree/lab3) | [Mở branch lab3](https://github.com/Khanhkenken/PTPMMNM-CNTT-1810-NHOM-4/tree/lab3) |
| Lab 04 | Bản nháp bằng Session và Cookie             | [`lab4`](https://github.com/Khanhkenken/PTPMMNM-CNTT-1810-NHOM-4/tree/lab4) | [Mở branch lab4](https://github.com/Khanhkenken/PTPMMNM-CNTT-1810-NHOM-4/tree/lab4) |
| Lab 05 | Lưu, truy vấn và thống kê với cơ sở dữ liệu | [`lab5`](https://github.com/Khanhkenken/PTPMMNM-CNTT-1810-NHOM-4/tree/lab5) | [Mở branch lab5](https://github.com/Khanhkenken/PTPMMNM-CNTT-1810-NHOM-4/tree/lab5) |

> **Mặc định GitHub đang mở branch `main`.** Hãy chuyển sang branch tương ứng ở góc trên bên trái (nút branch dropdown) để xem mã nguồn của từng bài.

## Cách chuyển branch

Trên giao diện GitHub: nhìn lên đầu trang, ngay phía trên danh sách file, có nút hiển thị branch hiện tại (mặc định là `main`). Bấm vào đó rồi chọn `lab1`, `lab2`, `lab3`, `lab4` hoặc `lab5`.

Trên terminal (sau khi clone):

```
git clone https://github.com/Khanhkenken/PTPMMNM-CNTT-1810-NHOM-4.git
cd PTPMMNM-CNTT-1810-NHOM-4
git checkout lab1   # hoặc lab2, lab3, lab4, lab5
```

## Tóm tắt nội dung từng bài

### Lab 01 — Linux và shell script *(branch `lab1`)*

Làm quen với môi trường dòng lệnh Ubuntu/WSL, chạy shell script `lab.sh`, kiểm tra môi trường và chạy chương trình PHP mẫu trên cổng `8101`.

### Lab 02 — Module PHP kiểm tra điều kiện đăng ký *(branch `lab2`)*

Module PHP kiểm tra điều kiện đăng ký sự kiện, kết quả hiển thị ngay trong terminal.

### Lab 03 — Danh sách sự kiện, tìm kiếm và form *(branch `lab3`)*

Trang danh sách sự kiện có tìm kiếm, form đăng ký kiểm tra phía máy chủ và hiển thị bản xem trước. Máy chủ chạy trên cổng `8103`.

### Lab 04 — Session và Cookie *(branch `lab4`)*

Bản nháp đăng ký lưu bằng Session và Cookie: nhập, xem lại, sửa, hủy và hoàn tất. Máy chủ chạy trên cổng `8104`.

### Lab 05 — Cơ sở dữ liệu *(branch `lab5`)*

Lưu, truy vấn và thống kê dữ liệu đăng ký bằng cơ sở dữ liệu (có cả bản MySQL). Máy chủ chạy trên cổng `8105`.

```
bash lab.sh check   # kiểm tra môi trường
bash lab.sh test    # kiểm thử phần mẫu
bash lab.sh extend  # kiểm thử phần mở rộng
```

## Công cụ chung

- PHP 8.1 trở lên
- Git
- Terminal Ubuntu hoặc Ubuntu trong WSL

## Thành viên

Nhóm 4 — CNTT 1810.

| STT |    Họ và tên   | Mã sinh viên | Vai trò     |
|-----|----------------|--------------|-------------|
| 1   | Hồ Ngọc Khánh  | 1871020324   | Nhóm trưởng |
| 2   | Đỗ Bảo Đăng    | 1871020120   | Thành viên  |
