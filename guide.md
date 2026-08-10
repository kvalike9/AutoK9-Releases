# Hướng dẫn sử dụng AutoK9

Tài liệu này được hiển thị trực tiếp trong tab **Hướng dẫn** của AutoK9. Khi tài liệu trên GitHub được cập nhật, nhấn **Làm mới** để tải nội dung mới mà không cần cập nhật lại phần mềm.

## 1. Chuẩn bị trước khi chạy Auto

- Mở Nox và đăng nhập đúng tài khoản game.
- Đưa game về màn hình chính, không để hộp thoại hoặc quảng cáo che giao diện.
- Giữ kích thước và tỉ lệ cửa sổ Nox ổn định. Cấu hình mặc định được thiết kế cho màn hình dọc.
- Mở AutoK9, kiểm tra thiết bị xuất hiện trong danh sách **Thiết bị Nox** và có trạng thái **Online**.
- Chọn đúng thiết bị rồi kiểm tra hình ảnh trong **Live Preview**.

Nếu nhận nhầm cửa sổ, chọn cửa sổ đó và nhấn **Xóa thiết bị**. Thao tác này cũng xóa cấu hình và thống kê riêng của thiết bị bị xóa.

## 2. Khởi động và dừng Auto

1. Chọn thiết bị trong danh sách **Thiết bị Nox**.
2. Bật các tác vụ cần dùng trong **Cấu hình nhanh**.
3. Kiểm tra Live Preview và trạng thái thiết bị.
4. Nhấn **Khởi động Auto**.
5. Theo dõi **Nhật ký hoạt động** để biết Auto đang xử lý bước nào.

Nhấn **Dừng** trước khi thay đổi ảnh mẫu, di chuyển cửa sổ Nox hoặc chỉnh hàng loạt tọa độ.

## 3. Cấu hình theo từng thiết bị

Mỗi cửa sổ Nox có cấu hình riêng và được tự động lưu ngay khi bật hoặc tắt một công tắc. Khi đổi sang thiết bị khác, hãy kiểm tra lại các công tắc vì thiết lập có thể khác nhau.

### Hệ thống

- **VIP:** bật xử lý chức năng VIP nếu tài khoản có hỗ trợ.
- **Chặn quảng cáo:** mặc định tắt. Chỉ bật khi cần xử lý luồng quảng cáo.
- **Tự mở game:** tự tìm và mở game khi chưa ở trong game.
- **Tự khởi động lại:** cho phép Auto phục hồi khi game gặp lỗi hoặc mất trạng thái.

### Nhiệm vụ

- **Tiếp khách:** tự nhận khách, giao vật phẩm và ghi thống kê thành công hoặc thiếu hàng.
- **Cư dân:** xử lý tác vụ cư dân.
- **Chỉ xây dựng vải:** giới hạn luồng xây dựng theo cấu hình vải.
- **Nhận phúc lợi:** nhận các phần thưởng/phúc lợi có thể nhận.
- **Nhập Redeem Code:** đồng bộ và nhập Code còn hiệu lực cho từng tài khoản.

### Nông trại và Hội

- **Trồng cây:** tự thực hiện luồng trồng cây.
- **Tưới cây:** tự tìm và tưới cây.
- **Thu cây:** thu hoạch cây đủ điều kiện.
- **Tăng tốc:** sử dụng thao tác tăng tốc theo ảnh và tọa độ đã cấu hình.
- **Treo bình:** kiểm tra trạng thái bình, treo và gỡ theo luồng tự động.
- **Mua nguyên liệu:** mặc định bật.
- **Thu cây hội / Nhiệm vụ hội:** thực hiện các tác vụ tương ứng trong Hội.

### Sự kiện

- **Sự kiện 1, 2, 3, 4** sử dụng thư mục ảnh riêng: `SuKien1`, `SuKien2`, `SuKien3`, `SuKien4`.
- Sự kiện 2, 3 và 4 không dùng bước gỡ bình.
- Có thể thay ảnh từng sự kiện độc lập để điều chỉnh nhanh mà không ảnh hưởng sự kiện khác.

## 4. Luồng Tiếp khách

Auto phân loại kết quả bằng màu và lưu thống kê theo ngày cho từng thiết bị.

- **Xanh / Vàng:** tính là thành công.
- **Đỏ:** tính là thiếu hàng hoặc loss.
- **Khách vàng:** nhấn Than Vàng, chờ 2 giây rồi mới tìm nút Đến Làm.
- **Khách xanh:** chờ 2 giây rồi thực hiện Giao.
- **Khách đỏ:** chờ 2 giây rồi nhấn Chưa Có Hàng.
- Các bước click xử lý có khoảng nghỉ để game kịp chuyển trạng thái.

Biểu đồ Tổng quan hiển thị thành công, loss, số lần restart game và restart Nox. Có thể xem thiết bị đang chọn hoặc tổng tất cả thiết bị.

## 5. Ảnh thiếu hàng

Trước khi nhấn **Chưa Có Hàng**, Auto chụp vùng vật phẩm để lưu lại và giúp kiểm tra tài khoản đang thiếu gì.

- Ảnh được quản lý riêng theo từng thiết bị trong tab **Thiếu hàng**.
- Nếu vùng ảnh mới giống ảnh đã lưu, Auto chỉ tăng số lần gặp và không tạo ảnh trùng.
- Có thể mở thư mục ảnh hoặc nhấp đúp vào ảnh để xem kích thước đầy đủ.
- Vùng mặc định hiện dùng tọa độ `X=216, Y=346, W=200, H=300`; nên chỉnh lại nếu giao diện game thay đổi.

## 6. Tọa độ và vùng kiểm tra

Tab **Tọa độ** quản lý tọa độ riêng theo từng Auto, gồm tọa độ click và các vùng ảnh dùng để kiểm tra trạng thái.

1. Chọn tên Auto cần chỉnh.
2. Chỉnh `X`, `Y`, `W`, `H` hoặc tọa độ click.
3. Nhấn **Lưu tọa độ**.
4. Chạy thử một thiết bị và theo dõi log.

Nhấn **Khôi phục mặc định** để trở về cấu hình gốc của Auto đang chọn.

Trong Live Preview:

- Click một điểm để xem `X`, `Y`.
- Kéo chuột thành vùng để xem `X`, `Y`, `W`, `H`.
- Dùng các giá trị này để cập nhật nhanh trong tab Tọa độ.

## 7. Redeem Code

- Ô Code nhanh dưới **Lịch sử Code** dùng thời hạn mặc định 30 phút.
- Trang Redeem cho phép chọn nhanh 30 phút, 1 giờ, 2 giờ, 12 giờ, 24 giờ hoặc 48 giờ.
- Sau khi đồng bộ thành công, Code được tự tải về các thiết bị và lịch sử sẽ làm mới.
- Lịch sử Code có thể xem toàn bộ Code của một ngày và các tài khoản đã nhập.
- Khi nhập Code lỗi, Auto thực hiện thao tác quay lại màn hình chính trước khi tiếp tục.

Chỉ tài khoản có quyền phù hợp mới được phép phát hành Code.

## 8. TikTok LIVE và nhận diện Code

Dịch vụ TikTok mặc định tắt và chỉ chạy khi nhấn **Kết nối**.

1. Nhập link hoặc username kênh LIVE.
2. Nhấn **Kết nối** để bắt đầu nhận bình luận công khai.
3. Xem toàn bộ bình luận trong danh sách.
4. Khi Auto nhận diện chuỗi giống Code, kiểm tra lại tại ô **Kết quả nhận diện**.
5. Nhấn **Đồng bộ 30 phút** để phát hành Code đã kiểm tra.

Không bắt buộc nhập user theo dõi. Danh sách user phát Code dùng để đánh dấu, ghi chú và quản lý các tài khoản thường đăng Code.

## 9. Nhật ký và thống kê

- **Nhật ký hoạt động** hiển thị tác vụ theo thời gian thực và màu riêng của từng thiết bị.
- Thống kê Tiếp khách lưu theo ngày trong JSON và có giới hạn dữ liệu cần thiết, không lưu ảnh màn hình liên tục.
- Số liệu gồm thành công, loss, restart game và restart Nox.
- Khi xóa thiết bị, dữ liệu thống kê riêng của thiết bị đó cũng bị xóa.

## 10. Xử lý lỗi thường gặp

### Không thấy thiết bị Nox

- Kiểm tra Nox đã mở hoàn toàn.
- Nhấn **Làm mới**.
- Đảm bảo tiêu đề cửa sổ Nox không bị công cụ khác thay đổi.

### Live Preview không đúng hoặc Auto click sai

- Đưa game về màn hình chính.
- Kiểm tra đúng thiết bị đang chọn.
- Không đổi tỉ lệ cửa sổ trong lúc Auto chạy.
- Dùng tab Tọa độ để đo và cập nhật lại vùng kiểm tra.

### Auto dừng ở một bước

- Xem dòng cuối trong Nhật ký hoạt động.
- Kiểm tra ảnh mẫu của đúng Auto và đúng thư mục sự kiện.
- Kiểm tra popup, quảng cáo hoặc màn hình tải có che game hay không.
- Dừng Auto, đưa game về màn hình chính rồi khởi động lại.

### Không tải được hướng dẫn GitHub

Auto sẽ dùng bản đã lưu trong `Config/guide-cache.md`. Khi có mạng, mở tab Hướng dẫn và nhấn **Làm mới**.

## 11. Cập nhật phần mềm

Nhấn **Kiểm tra cập nhật** trên trang Tổng quan. Không xóa thư mục `Config` khi cập nhật để giữ key kích hoạt, cấu hình thiết bị, lịch sử và các thiết lập cá nhân.

## Hỗ trợ và bản quyền

- Bản quyền: **kva99**
- Tác giả: **Vũ Anh Khoa**
- Zalo hỗ trợ: **0776945899**

