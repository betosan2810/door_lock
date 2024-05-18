# Khóa Cửa Sử Dụng RFID với Arduino

## Mô tả
Dự án này sử dụng Arduino Uno, mô-đun RFID, khóa điện tử 12V, relay và màn hình LCD I2C để tạo ra một hệ thống khóa cửa thông minh. Hệ thống cho phép mở khóa cửa bằng thẻ RFID và hiển thị thông báo trên màn hình LCD. Nếu thẻ không hợp lệ, hệ thống sẽ kích hoạt còi báo động và hiển thị thông báo lỗi.

## Linh kiện
- Arduino Uno
- RFID module
- Khóa điện tử 12V
- Relay
- LCD I2C
- Còi báo động

## Cách hoạt động
1. Quét thẻ RFID:
   - Nếu thẻ hợp lệ: 
     - Khóa điện tử mở.
     - Hiển thị thông báo "Mở khóa thành công" trên màn hình LCD.
   - Nếu thẻ không hợp lệ:
     - Kích hoạt còi báo động.
     - Hiển thị thông báo "Mở khóa chưa thành công" trên màn hình LCD.

## Hướng dẫn sử dụng
1. Kết nối các linh kiện theo sơ đồ mạch điện.
2. Tải mã nguồn lên Arduino Uno.
3. Cấp nguồn cho hệ thống.
4. Quét thẻ RFID để mở khóa cửa.

## Video Demo
[Video hướng dẫn](https://www.youtube.com/watch?v=HNTVLxkbRHY)
