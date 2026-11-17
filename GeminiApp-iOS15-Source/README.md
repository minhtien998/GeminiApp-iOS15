# Gemini App cho iOS 15.8

## Hướng dẫn build file .ipa bằng GitHub Actions (Không cần macOS)

1. Tạo một Repository mới trên GitHub (chọn chế độ **Private**).
2. Giải nén file ZIP này và tải toàn bộ các file/thư mục bên trong (bao gồm cả thư mục ẩn `.github`) lên nhánh `main` của Repository vừa tạo.
3. Trên giao diện GitHub, chuyển sang tab **Actions**.
4. Chọn workflow **Build Unsigned IPA** ở cột bên trái -> bấm **Run workflow**.
5. Chờ khoảng 2-3 phút để hệ thống build xong. Khi hiện dấu tích xanh, bấm vào lần chạy đó, cuộn xuống mục **Artifacts** và tải về file **`GeminiApp-iOS15.ipa`**.
6. Cài đặt file `.ipa` lên iPhone chạy iOS 15.8 thông qua **TrollStore** (nếu máy hỗ trợ/đã Jailbreak) hoặc **Sideloadly** trên Windows.
