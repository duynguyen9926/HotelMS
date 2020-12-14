# HotelMS
## 1. Mục tiêu, định hướng và kết quả cần đạt
### Xây dựng phần mềm quản lí khách sạn:
#### - phần mềm dạng ứng dụng cho máy tính cá nhân
#### - chỉ có nhân viên lễ tân, nhân viên bán hàng, quản lí khách sạn được sử dụng
## 2. Các công cụ và công nghệ được sử dụng
### 2.1 Công nghệ:
#### - PHP (with Laravel framework)
#### - HTML, CSS, Bootstrap, JavaScript
### 2.2 Công cụ:
#### - phpMyAdmin
#### - MySQL
#### - IDE: PHPStorm
## 3. Một số đặc tả về cách thức vận hành của khách sạn
#### - thông tin về khách sạn bao gồm : tên, địa chỉ, số sao, mô tả (bao gồm mô tả bằng text và bằng hình ảnh)
#### - trong khách sạn có nhiều phòng, mỗi phòng được mô tả bằng các thông tin: tên phòng (duy nhất, để phân biệt các phòng), loại phòng, giá niêm yết, các loại dịch vụ đi kèm, mô tả phòng
#### - mỗi khách hàng, khi đến ở hoặc đặt phòng, sẽ được lưu các thông tin bao gồm số CMND (số passport nếu là người nước ngoài), loại giấy tùy thân (CMND, passport), họ tên đầy đủ, địa chỉ, số điện thoại, ghi chú về phục vụ đặc biệt như cho người khuyết tật, ăn chay...
#### - mỗi phòng có thể được đặt/ở bởi nhiều khách hàng khác nhau tại những thời điểm khác nhau
#### -	mỗi khách hàng có thể đặt/ở nhiều phòng khác nhau tại những thời điểm khác nhau
#### -	tại một thời điểm, chỉ có một khách ở trong một phòng, và xác định một giá phòng cụ thể
#### -	khách hàng chỉ có thể đặt phòng nếu phòng đó còn trống trong suốt thời gian khách hàng muốn đặt
#### -	khách hàng có thể thanh toán nhiều lần cho đến ngày trả phòng
#### -	mỗi lần thanh toán, lễ tân sẽ in hóa đơn cho lần thanh toán đó bao gồm các thông tin: họ tên và địa chỉ khách hàng, số phòng, ngày đến, ngày đi, giá phòng, các dịch vụ đi kèm (mỗi dịch vụ bao gồm tên dịch vụ, đơn vị tính, đơn giá, tổng tiền), số tiền thanh toán
#### -	khách hàng có thể hủy đặt phòng (miên phí) nếu hủy trước ngày đến. Nếu khách hàng hủy sau ngày đặt thì khách hàng bị lưu vào danh sách đen và có thể bị từ chối đặt phòng trong các lần tiếp theo
## 4. Các chức năng chính
### 4.1 Nhân viên lễ tân
#### - có thể tìm phòng trống theo yêu cầu trực tiếp của khách
#### - checkin cho khách đã đặt phòng hoặc đặt phòng trực tiếp 
#### - checkout cho khách và in hóa đơn thanh toán cho khách
### 4.2 Quản lí
#### - thêm/sửa/xóa thông tin phòng
#### - xem các báo cáo doanh thu theo thời gian/theo phòng/theo loại phòng
#### - xem báo cáo tỉ lệ phòng trống theo thời gian/theo phòng/theo loại phòng
#### - xem báo cáo khách hàng đặt nhiều theo thời gian/theo nguồn gốc khách hàng
### 4.3 Nhân viên bán hàng
#### - tìm phòng trống 
#### - đặt phòng theo yêu cầu của khách

