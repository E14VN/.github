# E14VN
Dự án phát triển ứng dụng báo động khẩn cấp (cháy, cứu thương, cảnh sát, cứu hộ,...)

## Tiến độ
- **Lên ý tưởng**: Hoàn thành | 15/09 - 27/09
- **Nghiên cứu & thử nghiệm**: Đang thực hiện | 01/10 - Hiện tại
- **Lập trình dự án**: Đang thực hiện | 02/10 - Hiện tại
    - **Máy chủ**: Đang thực hiện | 02/10 - Hiện tại
    - **Ứng dụng**: Đang thực hiện | 02/10 - Hiện tại
    - **Phần mềm**: Đã lên kế hoạch | Hiện tại
- **Viết tài liệu**: Đang thực hiện | 02/10 - Hiện tại
- **Chạy thử & sửa lỗi**: Đã lên kế hoạch | Hiện tại

## Tính năng
**1. Tốc độ**:

- Máy chủ phát triển chiều ngang: Tăng tốc độ xử lí thông tin bằng cách thêm các Nodes và Balancer.
- Người dùng: Chỉ cần có điện thoại là đủ để sử dụng ứng dụng.

**2. Tiện lợi**:

- Ứng dụng thao tác một cách rõ ràng, dễ sử dụng, không gây rối, có thể sử dụng trên mọi thiết bị thông minh có kết nối mạng.
- Hệ thống máy chủ dễ bảo trì, có các tài liệu có sẵn để đọc và hiểu nhanh hơn.

**3. Riêng tư**:

- Không lưu bất kì dữ liệu về vị trí của người dùng vào máy chủ khi không cần thiết. (*)
- Tất cả mọi tính toán về vị trí đều được thực hiện ngay trong máy của người dùng.

*Lưu trữ vị trí chỉ được thực hiện trên người dùng khi chính người đó báo khẩn cấp.

**4. Miễn phí cho mọi người**:

Sản phẩm phi lợi nhuận với mục đích đem lại sự an toàn cho mọi người. Có thể quyên góp cho dự án.

Chi phí phải bỏ ra khi sử dụng dự án vào phương án phân phối:

**Phương án 1 (đang được tích hợp):**
- Hạ tầng máy chủ: Chạy máy chủ của E14 để nền tảng có thể hoạt động.
- [MongoDB](https://www.mongodb.com) (Nếu sử dụng loại hình dịch vụ): Lưu trữ thông tin người dùng đã đăng kí và vị trí của các trạm.
- [Twilio](https://www.twilio.com/): Xác minh số điện thoại.
- [Firebase](https://firebase.google.com/): Gửi thông báo (Không mất phí).
- [Google maps API](https://mapsplatform.google.com): Chọn địa điểm trên bản đồ.

**Phương án 2 (không được tích hợp):**
- Hạ tầng máy chủ: Chạy máy chủ của E14 để nền tảng có thể hoạt động.
- [Firebase](https://firebase.google.com/): Lưu trữ thông tin người dùng đã đăng kí, vị trí của các trạm, gửi thông báo.
- [Google maps API](https://mapsplatform.google.com/): Chọn địa điểm trên bản đồ.

Tuy là sản phẩm mã nguồn mở, nhưng có một số giới hạn về mục đích sử dụng.

Xem thêm: [Giấy phép E14 mã nguồn mở](https://github.com/E14VN/.github/blob/main/LICENSE.md)

Tóm tắt: Cho phép sử dụng để phục vụ mục đích học tập, tìm hiểu và cải tiến nền tảng. Không cho phép việc sử dụng dự án hay quá nhiều ý tưởng từ đó để tạo lợi nhuận.

### Ý tưởng của dự án được lập vào 15/09/2023 21h37
