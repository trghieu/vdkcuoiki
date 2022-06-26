# vdkcuoiki
# **HỆ THỐNG BÁO MƯA TỰ ĐỘNG**
> ngày nay cùng với sự phát triển của khoa học xã hội thì hệ thống báo mưa tự động là một phương pháp hiệu quả để trồng cây trong nhà cũng như phục vụ nhiều hoạt động sống của con người.Từ những yếu tố đó , nhóm em đã hình thành ý tưởng xây dựng " hệ thống báo mưa tự động ".
## **Công cụ lập trình**

- Cài đặt IDE Arduino

## **Nguyên lý hoạt động**
(https://drive.google.com/file/d/1zh69raZWgnNMOPXKTEddiH4bct86PLsD/view?usp=sharing)

## **Linh kiện**
- Module Sim800L
- Cảm biến mưa MDL150
- Đèn led
- Mạch giảm áp LM2596
- Nguồn Adapter 5V-2A
- Dây nối
- Động cơ Servo
- Arduino Uno
- breadboard

## **Sơ đồ lắp mạch**

https://drive.google.com/file/d/12r105Z_tBr9-5jMlQXyehFUUFKbFSBYg/view?usp=sharing

| Linh kiện | Cách nối chi tiết |
| ------ | ------ |
| Đèn led  | Chân âm: GND , Chân dương: 13  |
| Cảm biến mưa | Chân âm: GND , Chân A0:, Chân D0: D5, Chân Vcc: 5v |
| Động cơ Servo |(https://arduinokit.vn/dieu-khien-dong-co-rc-servo-su-dung-arduino) |
| Module Sim800L | Rx: D11 , Tx: D10, Vcc: 4.2V ( adapter), GND: GND |

**Chú ý: Module Sim800L phải được cấp đúng 4.1V-4.2V**
> Cách giảm áp : Sử dụng mạch giảm áp LM2596

## **Cách chạy chương trình**
- Bước 1: Mở file code source.ino bằng IDE Arduino
- Bước 2: Chọn đúng Port
- Bước 3: Impot thư viện Servo.h
- Bước 4: Upload code và chờ kết quả

> Mã nguồn: (https://github.com/trghieu/vdkcuoiki)
