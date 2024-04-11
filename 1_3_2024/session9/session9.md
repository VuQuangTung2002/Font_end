- Thông tin hiện trạng website
    - Truy cập trang vnexpress: ứng với cỡ màn hình khác nhau thì sẽ hiển thị cấu trúc website khác nhau -> sử dụng html 5 để responsive
    - Truy cập trang dantri.com.vn
        - Nếu sử dụng laptop để truy cập trang đó thì sẽ dẫn đến link: dantri.com.vn
        - Nếu sử dụng ipad hoặc điện thoại truy cập trang đó thì sẽ dẫn đến link: m.dantri.com.vn
        -> có nghĩa là hệ thống website dân trí xây dựng 2 website
            1. website sử dụng cho các thiết bị dị desktop
            2. website sử dụng cho các thiết bị mobile
    - Từ 2 ví dụ trên thì có thể thấy responsive sẽ có 2 trường phái
        1. Xây dựng nhiều website, mỗi website sẽ tương ứng với một cỡ màn hình khác nhau -> các responsive trước đây khi html5 chưa sử dụng chính thức. VD: trang dân trí
        2. Xây dựng 1 website và respsonve ngay trên chính website đó khi cơ màn hình thay đổi -> sử dụng html 5 và css 3. VD: trang vnexpress
- Responsive là thuật ngữ ra đời năm 2007, chỉ sự phù hợp của website tương ứng với các cỡ màn hình khác nhau. Trong nội dung bài học sẽ hướng dẫn các bạn tìm hiểu responsive sử dụng html 5 và css 3
    - Responsive thực chất là việc viết lại css tương ứng với các cỡ màn hình khác nhau
        - Một câu hỏi đặt ra là làm sao để phát hiện được các cỡ màn hình khác nhau trên trình duyệt -> css 3 có thể phát hiện ra sự thay đổi về kích thước của trình duyệt thông qua thuộc tính @media. Một số thuật ngữ như sau:
            @media all -> chỉ tất cả các thiết bị
            @media screen -> chỉ phát hiện thiết bị là màn hình
            max-width: độ rộng tối đa
            min-width: độ rộng tối thiểu
            max-height: độ cao tối đa
            min-height: độ cao tối thiểu
    - Các cỡ màn hình (break point) -> >= 1400px, >= 1200px, >= 992px, >= 768px, >= 576px
- Một số cách thực hiện trong css để set các thẻ block ngang hàng nhau
    - display: flex -> thực hiện ở cấp cha, khi đó con cấp 1 sẽ hiển thị theo chiều ngang
    - display: grid -> hiển thị theo kiểu gridbox
    - float: left -> đây là css 2 để căn thẻ ngan hàng nhau. Sử dụng thuộc tính này thì cần chú ý clear:both để các thẻ sau không phụ thuộc vào thuộc tính float:left của thẻ trước