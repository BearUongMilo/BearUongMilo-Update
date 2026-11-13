# BearUongMilo 2.0.1

Giao diện desktop mới, tiếp nối BearCute 1.x.

**[Tải BearUongMilo 2.0.1 cho Windows x64](https://github.com/BearUongMilo/BearUongMilo-Update/releases/tag/v2.0.1)**

## Đang dùng bản 1.x

Mở ứng dụng cũ, chọn **Kiểm tra cập nhật** rồi tải/cài bản **2.0.1** theo hướng
dẫn. Kênh cập nhật và khóa xác minh chữ ký được giữ nguyên để ứng dụng cũ nhận
đúng gói mới.

Trình cập nhật thay file chạy chính và cài runtime mới vào `_milo`. Các thư mục
và tệp dữ liệu cũ ngoài payload được giữ nguyên. Key đã lưu trên cùng tài khoản
Windows được nhập khi kho key mới chưa có dữ liệu và vẫn phải xác thực online.
Những workflow JSON có sẵn vẫn có thể mở/import vào Workflow Studio.

## Cài mới

1. Tải ZIP trong trang phát hành ở trên.
2. Giải nén **toàn bộ** ZIP vào một thư mục.
3. Chạy `BearUongMilo.exe`; giữ thư mục `_milo` cạnh file EXE.

Yêu cầu Windows 10/11 x64 và Microsoft Edge WebView2 Runtime. Gói đã có Python
runtime và thư viện cần thiết; không cần cài Python hoặc Node.js.

## Bản 2.0.1

- Giao diện desktop mới với Dashboard, Workflow Studio, Debug Workflow và các
  công cụ đang dùng.
- Hỗ trợ EN/VI, theme sáng/tối, màu cá nhân và ảnh nền.
- Dùng graph và lõi thực thi workflow tương thích trong gói mới.

Màn cập nhật **bên trong giao diện 2.0.1** hiện là bản xem trước, chưa tự tải/cài
các lần phát hành tiếp theo. Việc cập nhật **từ app 1.x lên 2.0.1** qua kênh cũ
đã được nối thật.

Repo này cung cấp gói phát hành cùng `version.json` và `integrity.json` có chữ ký.
Lịch sử Git được giữ lại; các Release/tag 1.x đã được ngừng phân phối.
