- Quy tắc đặt tên
	- Quy tắc Pascal
		- Từ đầu tiên của chữ viết hoa
		- VD: HelloWorld, MyName...
		- Áp dụng: đặt tên class
	- Quy tắc Camel
		- Từ đầu tiên của chữ đầu tiên viết thường, từ đầu tiên của các chữ kế tiếp viết hoa
		- VD: helloWorld, myName...
		- Áp dụng: đặt tên hàm, tên biến
	- Quy tắc Snake
		- Các chữ viết thường va cách nhau bằng dấu _
		- VD: hello_world, my_name...
		- Áp dụng: đặt tên biến
- Hàm setTimeout: thực hiện lại hàm 1 lần
	- Cú pháp
		setTimeout(tenham,duration);
			tenham: có thể gọi một hàm hoặc hàm anonymouse
			duration: tính bằng miligiay, 1 giay = 1000 miligiay
- Hàm setInterval: thực hiện lại hàm nhiều lần. Tham số giống hàm setTimeout
	- Muốn dừng hàm setInterval thì sử dụng: clearInterval(id)
- Đối tượng về thời gian
	- var thoigian = new Date();
	- Ngày: thoigian.getDate();
		- thoigian.getDay(); sẽ trả về số từ 0 đến 6 tương ứng thứ 2 đến chủ nhật
	- Tháng: thoigian.getMonth(); tháng sẽ là số từ 0 đến 11 tương ứng với tháng từ 1 đến 12
	- Năm: thoigian.getFullYear();
	- Giờ: thoigian.getHours();
	- Phút: thoigian.getMinutes();
	- Giây: thoigian.getSeconds();
- Array: bao gồm 2 thành phần
	- Key: là chỉ số của array, key chạy từ 0 đến n
	- Value: là giá trị tương ứng với phần tử key
	- Khởi tạo array: 
		- Cách 1
			var bien = new Array();
		- Cách 2
			var bien = new Array(giatri1,giatri2,giatri3...)
	- Truy xuất giá trị của phần tử thứ key: bien[key]