# Snake Game Console

Một trò chơi Snake đơn giản viết bằng C++ cho Windows Console. Dự án chạy trên Visual Studio và sử dụng các hàm `windows.h`, `conio.h` để điều khiển console, vẽ menu, và di chuyển rắn.

## Tính năng

- Menu điều khiển bằng phím mũi tên
- Chế độ chơi Snake truyền thống trong cửa sổ console
- Vẽ tường biên, đầu rắn, thân rắn, quả ăn, hoa và chướng ngại vật
- Lưu điểm cao nhất vào file và hiển thị thành tích
- Quản lý dữ liệu đơn giản với `fstream`

## Cấu trúc dự án

- `Snake_Game.cpp`: Điểm vào chương trình, hiển thị tiêu đề và menu chính.
- `Global.h`: Hàm tiện ích console, di chuyển con trỏ, thay đổi màu sắc, nhận phím.
- `SourceMenu.h`: Hiển thị menu, xử lý lựa chọn và điều khiển bắt đầu trò chơi, thông tin, thành tích, thoát.
- `HighestScore.h`: Chứa logic trò chơi Snake, vẽ tường, khởi tạo và di chuyển rắn, kiểm tra va chạm.
- `HighestScore.h` (file dữ liệu điểm cao): Lưu điểm cao vào file để duy trì giữa các lần chạy.
- `Snake_Game.sln`: Solution Visual Studio để mở và biên dịch.

## Hướng dẫn chạy

1. Mở `Snake_Game.sln` bằng Visual Studio.
2. Chọn cấu hình `Debug` hoặc `Release`.
3. Biên dịch và chạy dự án.

## Điều khiển

- Phím mũi tên `Up`, `Down`, `Left`, `Right` để di chuyển rắn
- Nhấn `Esc` hoặc chọn `EXIT` trong menu để thoát

## Ghi chú

- Dự án chạy trên Windows vì sử dụng `windows.h` và API console Windows.
- File điểm cao hiện được đọc/ghi từ đường dẫn tuyệt đối trong mã nguồn.
- Có thể mở rộng thêm chế độ cài đặt, skor, hoặc sửa đường dẫn lưu file để chạy linh hoạt hơn.

