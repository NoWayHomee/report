# 🏨 HỆ THỐNG ĐẶT PHÒNG TRỰC TUYẾN NOWAYHOME

**Tổ chức:** NoWayHomee
**Tài liệu:** Thiết kế Kiến trúc, Logic xử lý và Cơ sở dữ liệu

Tài liệu này cung cấp cái nhìn tổng thể về thiết kế của hệ thống NoWayHome, bao gồm mô hình dữ liệu, phân rã chức năng và luồng xử lý nghiệp vụ cho hai phân hệ chính: **Khách hàng** và **Đối tác**.

---

## 📊 1. Thiết Kế Cơ Sở Dữ Liệu (Database Design)
Mô hình thực thể kết nối (ERD) thể hiện cấu trúc lưu trữ, các bảng dữ liệu và mối quan hệ giữa các thực thể cốt lõi trong hệ thống.

![Sơ đồ ERD](diagrams/ERD.drawio.png)
> 🔗 [Mở bản gốc ERD trên draw.io](Link_DrawIO_Của_Nhóm_Vào_Đây)

---

## 🌐 2. Sơ Đồ Tổng Quan Hệ Thống (System Overview)
Sơ đồ Use Case tổng quan thể hiện các tác nhân (Actors) và những chức năng mức cao nhất mà hệ thống cung cấp.

![UC Tổng quan](diagrams/uc-tổng%20quan%20hệ%20thống.drawio.png)
> 🔗 [Mở bản gốc UC Tổng quan trên draw.io](Link_DrawIO_Của_Nhóm_Vào_Đây)

---

## 👤 3. Phân Hệ Khách Hàng (Customer Module)
Phân hệ dành cho người dùng cuối (End-user) thực hiện các thao tác tìm kiếm, đặt phòng và quản lý tài khoản.

### 3.1. Use Case Tổng Quan Khách Hàng
![UC Khách hàng](diagrams/uctq-phân%20hệ%20khách%20hàng.drawio.png)
> 🔗 [Mở bản gốc UC Khách hàng trên draw.io](Link_DrawIO_Của_Nhóm_Vào_Đây)

### 3.2. Phân Rã Chức Năng (WBS) Khách Hàng
![Phân rã chức năng Khách hàng](diagrams/Khách%20hàng-prcn.drawio.png)
> 🔗 [Mở bản gốc PRCN Khách hàng trên draw.io](Link_DrawIO_Của_Nhóm_Vào_Đây)

### 3.3. Luồng Xử Lý Tuần Tự (Sequence Diagram) Khách Hàng
![Luồng tuần tự Khách hàng](diagrams/Luồng%20Khách%20Hàng-tuần%20tự.drawio.png)
> 🔗 [Mở bản gốc Luồng Khách Hàng trên draw.io](Link_DrawIO_Của_Nhóm_Vào_Đây)

---

## 🏢 4. Phân Hệ Đối Tác (Partner/Host Module)
Phân hệ dành cho chủ khách sạn/chỗ nghỉ (Host) để quản lý phòng, giá cả và theo dõi đơn đặt phòng.

### 4.1. Use Case Tổng Quan Đối Tác
![UC Đối tác](diagrams/uctq-phân%20hệ%20đối%20tác.drawio.png)
> 🔗 [Mở bản gốc UC Đối tác trên draw.io](Link_DrawIO_Của_Nhóm_Vào_Đây)

### 4.2. Phân Rã Chức Năng (WBS) Đối Tác
![Phân rã chức năng Đối tác](diagrams/Đối%20tác-prcn.drawio.png)
> 🔗 [Mở bản gốc PRCN Đối tác trên draw.io](Link_DrawIO_Của_Nhóm_Vào_Đây)

### 4.3. Luồng Xử Lý Tuần Tự (Sequence Diagram) Đối Tác
![Luồng tuần tự Đối tác](diagrams/Luồng%20Đối%20tác-tuần%20tự.drawio.png)
> 🔗 [Mở bản gốc Luồng Đối tác trên draw.io](Link_DrawIO_Của_Nhóm_Vào_Đây)
