# Mạch cấp nguồn bổ sung MKE-M12 5VDC 5A power supply module

![](/image/MKE_M12_1.jpg)

## Giới thiệu

Mạch cấp nguồn bổ sung MKE-M12 5VDC 5A power supply module được thiết kế chuyên dụng cho các mạch MakerEdu Shield giúp tăng công suất cấp nguồn 5VDC của cổng POWER+ lên đến 5VDC/5A sử dụng cho các mạch và động cơ RC Servo trong các cơ cấu robot, xe tự hành cần nguồn 5VDC công suất lớn, mạch lấy nguồn đầu vào từ chân VIN của cổng POWER+ để chuyển đổi thành nguồn 5VDC nên cần lưu ý cấp đủ công suất cho nguồn VIN để đầu ra của mạch có thể đạt công suất tối đa.

Mạch cấp nguồn bổ sung MKE-M12 5VDC 5A power supply module còn có thể sử dụng như một mạch giảm áp xung 5VDC/5A thông thường với kết nối đầu vào (VIN) và đầu ra (VOUT) dễ dàng qua cổng Domino, mạch thuộc hệ sinh thái phần cứng Robotics MakerEdu với chuẩn kết nối connector XH2.54 thông dụng.

## Thông số kỹ thuật

- Điện áp đầu vào VIN: 6~30VDC
- Điện áp đầu ra VOUT: 5VDC
- Dòng đầu ra tối đa: 5A
- IC giảm áp xung: XL4015
- Hiệu suất chuyển đổi: 96%
- Tần số nguồn xung: 180Khz
- Bổ sung thêm cổng VIN và VOUT dạng Domino cấp nguồn linh hoạt.
- Bổ sung thêm các thiết kế ổn định, chống nhiễu.
- Chuẩn kết nối:
  - 2 x Conector XH2.54 4Pins
  - 2 x Conector Domino 2P
- Thuộc hệ sinh thái phần cứng Robotics MakerEdu, tương thích tốt nhất khi sử dụng với các mạch điều khiển của MakerEdu và MakerEdu Shield.

## Kích thước

![](/image/MKE_M12_2.jpg)

## Các chân tín hiệu

![](/image/MKE_M12_3.jpg)

<table><thead>
  <tr>
    <th>MKE-M12</th>
    <th>Ghi chú</th>
  </tr></thead>
<tbody>
  <tr>
    <td>VIN (Domino)</td>
    <td>Cấp nguồn từ 6~30VDC</td>
  </tr>
  <tr>
    <td>VOUT (Domino)</td>
    <td>Nguồn đầu ra 5VDC/5A</td>
  </tr>
  <tr>
    <td>IN (EDU Shield)</td>
    <td>Nối với cổng POWER+ Out của MakerEdu Shield</td>
  </tr>
  <tr>
    <td>OUT (Load)</td>
    <td>Là cổng đầu POWER+ đã được bổ sung công suất cấp nguồn lên 5VDC/5A</td>
  </tr>
</tbody>
</table>

## Hướng dẫn sử dụng với MakerEdu Shield

### Các phần cứng sử dụng

- Mạch cấp nguồn bổ sung MKE-M12 5VDC 5A power supply module
- Mạch Vietduino Uno (Arduino Uno Compatible)
- Mạch MakerEdu Shield for Vietduino

> **Lưu ý:**
Nếu không có mạch Vietduino Uno bạn vẫn có thể sử dụng mạch Vietduino Mega 2560, Arduino Uno, Arduino Mega 2560 hoặc các mạch phần cứng có cấu trúc các chân GPIO tương tự.

### Các bước tiến hành

1. Kết nối mạch MakerEdu Shield for Vietduino vào mạch Vietduino Uno.
1. Kết nối cổng (IN) của Mạch cấp nguồn bổ sung MKE-M12 5VDC 5A power supply module vào cổng (POWER+ (Out)) trên mạch MakerEdu Shield for Vietduino.
1. Sau khi thực hiện xong bước 2 thì cổng (OUT) của Mạch cấp nguồn bổ sung MKE-M12 5VDC 5A power supply module đã trở thành cổng (POWER+ (Out)) được bổ sung công suất cấp nguồn lên 5VDC/5A, lưu ý các chân nguồn còn lại (VIN, 3V3, GND) của cổng (POWER+ (Out)) vẫn giữ nguyên trạng thái hoạt động.

> **Lưu ý:**
Để sử dụng Mạch cấp nguồn bổ sung MKL-M12 5VDC 5A power supply module như một mạch giảm áp xung thông thường ta kết nối nguồn đầu vào tại cổng Domino (VIN) từ 6~30VDC, khi đó tại cổng Domino (VOUT) của mạch sẽ cung cấp nguồn đầu ra 5VDC với dòng tối đa là 5A để cấp nguồn cho các thiết bị.

## Nhà phân phối

Có thể mua Mạch cấp nguồn bổ sung MKE-M12 5VDC 5A power supply module tại các nhà phân phối sau:

- [Hshop.vn - Điện tử & Robot.](hshop.vn)
