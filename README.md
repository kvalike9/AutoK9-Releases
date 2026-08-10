# AutoK9 — Phần mềm Automation Nox đa thiết bị trên Windows

> **AutoK9** là phần mềm quản lý và tự động hóa nhiều cửa sổ Nox trên Windows, được xây dựng bằng **WPF Fluent UI**. Ứng dụng hỗ trợ cấu hình riêng theo từng thiết bị, Live Preview, thống kê thời gian thực, quản lý Redeem Code và theo dõi bình luận TikTok LIVE.

[![Platform](https://img.shields.io/badge/Platform-Windows-0078D4?logo=windows&logoColor=white)](https://github.com/kvalike9/AutoK9-Releases)
[![Framework](https://img.shields.io/badge/.NET-Framework%204.8-512BD4?logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![UI](https://img.shields.io/badge/UI-WPF%20Fluent-0EA5E9)](https://github.com/lepoco/wpfui)
[![Latest Release](https://img.shields.io/github/v/release/kvalike9/AutoK9-Releases?label=Phi%C3%AAn%20b%E1%BA%A3n)](https://github.com/kvalike9/AutoK9-Releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/kvalike9/AutoK9-Releases/total?label=L%C6%B0%E1%BB%A3t%20t%E1%BA%A3i)](https://github.com/kvalike9/AutoK9-Releases/releases)

## Tải AutoK9

Tải phiên bản mới nhất tại:

### [Tải AutoK9 cho Windows](https://github.com/kvalike9/AutoK9-Releases/releases/latest)

> Khi cập nhật, không xóa thư mục `Config` nếu muốn giữ key kích hoạt, cấu hình thiết bị, lịch sử và thiết lập cá nhân.

## AutoK9 phù hợp với ai?

AutoK9 phù hợp với người dùng cần:

- Quản lý nhiều cửa sổ Nox từ một giao diện duy nhất.
- Cấu hình automation độc lập cho từng tài khoản hoặc thiết bị.
- Theo dõi trạng thái, hình ảnh và nhật ký hoạt động theo thời gian thực.
- Kiểm soát kết quả Tiếp khách bằng thống kê trực quan.
- Quản lý lịch sử Redeem Code và tài khoản đã nhập Code.
- Theo dõi bình luận TikTok LIVE để phát hiện Code nhanh hơn.

## Tính năng nổi bật

### Quản lý nhiều thiết bị Nox

- Tự động nhận diện các cửa sổ Nox đang hoạt động.
- Hiển thị tên thiết bị, Handle và trạng thái Online/Offline.
- Màu nhận diện riêng cho từng thiết bị trong danh sách và nhật ký.
- Xóa thiết bị không mong muốn cùng cấu hình và thống kê liên quan.
- Xem từng thiết bị hoặc tổng hợp tất cả thiết bị trên Dashboard.

### Automation theo từng thiết bị

Mỗi thiết bị có cấu hình riêng và được tự động lưu khi thay đổi.

- Tiếp khách.
- Cư dân.
- Nhận phúc lợi.
- Trồng cây, tưới cây và thu hoạch.
- Tăng tốc và mua nguyên liệu.
- Treo bình và các nhiệm vụ Hội.
- Nhập Redeem Code tự động.
- Sự kiện 1, 2, 3 và 4 với thư mục ảnh độc lập.
- Tự mở game và phục hồi khi game gặp lỗi.

### Live Preview và cấu hình tọa độ

- Xem trực tiếp màn hình Nox theo tỉ lệ dọc 9:16.
- Click trên Live Preview để lấy tọa độ `X`, `Y`.
- Kéo chuột để lấy vùng `X`, `Y`, `W`, `H`.
- Quản lý tọa độ click và vùng nhận diện riêng theo từng Auto.
- Khôi phục nhanh cấu hình tọa độ mặc định.

### Thống kê Tiếp khách thời gian thực

- Biểu đồ cột và đường hiển thị trực tiếp trên trang Tổng quan.
- Phân biệt rõ thành công, loss, restart game và restart Nox.
- Xem theo thiết bị đang chọn hoặc tổng tất cả thiết bị.
- Lưu thống kê theo ngày bằng JSON nhẹ và dễ sao lưu.
- Tooltip và số liệu trực tiếp trên biểu đồ.

### Quản lý ảnh thiếu hàng

- Chụp vùng vật phẩm trước khi xác nhận Chưa Có Hàng.
- Lưu ảnh riêng theo từng thiết bị.
- Tự nhận diện ảnh trùng và chỉ tăng số lần gặp, không tạo file thừa.
- Có thư viện ảnh để kiểm tra tài khoản đang thiếu vật phẩm nào.
- Cho phép tùy chỉnh vùng chụp trong cấu hình tọa độ.

### Redeem Code

- Phát hành Code nhanh với thời hạn mặc định 30 phút.
- Các mốc nhanh: 30 phút, 1 giờ, 2 giờ, 12 giờ, 24 giờ và 48 giờ.
- Theo dõi toàn bộ Code trong ngày.
- Hiển thị những tài khoản đã nhập Code để dễ phát hiện nhập thiếu.
- Lưu lịch sử Code cục bộ bằng JSON mà không ảnh hưởng hệ thống máy chủ.

### Theo dõi bình luận TikTok LIVE

- Kết nối TikTok LIVE ở chế độ đọc bình luận công khai.
- Xem toàn bộ bình luận theo thời gian thực.
- Nhận diện chuỗi có khả năng là Redeem Code từ dữ liệu lịch sử.
- Đánh dấu và quản lý user thường phát hành Code.
- Cho phép kiểm tra, sửa Code rồi đồng bộ với thời hạn 30 phút.
- Dịch vụ mặc định tắt và chỉ chạy khi người dùng chủ động kết nối.

### Giao diện Fluent hiện đại

- Giao diện WPF Fluent UI tối ưu cho Windows.
- Light Mode và Dark Mode theo hệ thống.
- Card bo góc, màu sắc thống nhất và bố cục linh hoạt.
- Snackbar và ContentDialog hiện đại thay cho MessageBox truyền thống.
- Hướng dẫn sử dụng được cập nhật trực tiếp từ GitHub.

## Hình ảnh giao diện

Bạn có thể tạo thư mục `screenshots` trong repository rồi thay các đường dẫn bên dưới:

```markdown
![Dashboard AutoK9](screenshots/autok9-dashboard.png)
![Automation Nox](screenshots/autok9-automation.png)
![TikTok LIVE Comments](screenshots/autok9-tiktok-live.png)
```

> Nên dùng ảnh PNG hoặc WebP rộng khoảng 1200–1600 px, che License Key, Device ID và các thông tin cá nhân trước khi đăng.

## Yêu cầu hệ thống

- Windows 10 hoặc Windows 11 64-bit.
- Microsoft .NET Framework 4.8.
- NoxPlayer và game đã được cài đặt, đăng nhập.
- Kết nối Internet cho kích hoạt bản quyền, cập nhật và các chức năng trực tuyến.
- Độ phân giải màn hình đủ để hiển thị cửa sổ AutoK9 và Nox.

## Cài đặt

1. Mở trang [Releases](https://github.com/kvalike9/AutoK9-Releases/releases/latest).
2. Tải file `AutoK9-vX.X.X.zip` của phiên bản mới nhất.
3. Giải nén vào một thư mục riêng, ví dụ `E:\AutoK9-Main`.
4. Chạy `AutoK9.exe`.
5. Nhập License Key ở lần sử dụng đầu tiên.
6. Mở Nox, chọn đúng thiết bị và kiểm tra Live Preview trước khi chạy Auto.

Windows có thể hiển thị cảnh báo SmartScreen với ứng dụng mới chưa có chứng thư ký số. Hãy chỉ tải AutoK9 từ repository chính thức này.

## Cập nhật phần mềm

AutoK9 có cơ chế kiểm tra cập nhật từ GitHub Releases:

1. Mở trang **Tổng quan**.
2. Nhấn **Kiểm tra cập nhật**.
3. Xem thông tin phiên bản và xác nhận cài đặt.
4. AutoK9 tải gói, kiểm tra SHA-256 và thực hiện cập nhật.

Dữ liệu trong `Config` được giữ lại trong quá trình cập nhật.

## Hướng dẫn sử dụng

- Xem trực tiếp trong tab **Hướng dẫn** của AutoK9.
- Đọc file hướng dẫn đầy đủ tại [guide.md](guide.md).
- Nhấn **Làm mới** trong phần mềm để tải tài liệu mới nhất từ GitHub mà không cần nâng phiên bản ứng dụng.

## Câu hỏi thường gặp

### Vì sao AutoK9 không thấy thiết bị Nox?

Hãy kiểm tra Nox đã mở hoàn toàn, sau đó nhấn **Làm mới**. Không nên thay đổi tiêu đề cửa sổ Nox bằng phần mềm khác.

### Vì sao Auto click sai vị trí?

Kiểm tra tỉ lệ và kích thước cửa sổ Nox. Dùng Live Preview và tab **Tọa độ** để đo lại `X`, `Y`, `W`, `H` cho Auto tương ứng.

### Cập nhật có phải nhập lại License Key không?

Không, nếu thư mục `Config` được giữ nguyên. Không xóa hoặc ghi đè dữ liệu cấu hình cá nhân khi giải nén thủ công.

### Mất mạng có xem được hướng dẫn không?

Có. AutoK9 lưu bản gần nhất trong `Config/guide-cache.md` và tự sử dụng khi GitHub không truy cập được.

### Dịch vụ TikTok có tự chạy cùng Windows không?

Không. Dịch vụ mặc định tắt và chỉ khởi động khi người dùng nhấn **Kết nối** trong tab TikTok LIVE.

## An toàn và lưu ý

- Chỉ tải bản phát hành từ repository chính thức `kvalike9/AutoK9-Releases`.
- Không chia sẻ License Key hoặc Device ID công khai.
- Sao lưu thư mục `Config` trước các thay đổi lớn.
- Kiểm tra Live Preview và nhật ký khi chạy cấu hình mới.
- Người dùng tự chịu trách nhiệm tuân thủ điều khoản của các nền tảng và phần mềm bên thứ ba đang sử dụng.

AutoK9 là công cụ độc lập, không thuộc, không được tài trợ hoặc chứng thực bởi NoxPlayer, TikTok hay các nền tảng bên thứ ba được nhắc đến.

## Hỗ trợ và bản quyền

- Thương hiệu: **kva99**
- Tác giả: **Vũ Anh Khoa**
- Zalo hỗ trợ: **0776945899**
- GitHub: [kvalike9/AutoK9-Releases](https://github.com/kvalike9/AutoK9-Releases)

Nếu AutoK9 hữu ích, hãy nhấn **Star** repository để theo dõi các phiên bản và tính năng mới.

---

**Từ khóa:** AutoK9, Auto Nox, Nox Automation, phần mềm quản lý Nox, automation đa thiết bị, WPF Fluent UI, quản lý Redeem Code, TikTok LIVE comments, thống kê tiếp khách, Auto game Windows, NoxPlayer automation Việt Nam.

<!--
SEO keywords: AutoK9, Auto Nox, Nox automation Windows, multi instance Nox manager,
WPF automation dashboard, redeem code manager, TikTok LIVE comment monitor,
Vietnamese Nox automation software, phần mềm auto Nox, quản lý nhiều cửa sổ Nox.
-->
