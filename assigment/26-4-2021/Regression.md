# CS114.L21
## ĐỀ BÀI
- Mỗi nhóm tìm dăm ba ví dụ về bài toán regression ***TRONG THỰC TẾ***
- Ghi rõ input, output và cách thu thập + xử lý data, commit vào github repository và dẫn link lên classroom.

## NHÓM THỰC HIỆN
- Lại Nguyễn Vĩnh Phú: 19522020
- Nguyễn Chí Cường: 19521299
- Trương Thế Trương: 195222447

## BÀI LÀM
1. Dự đoán doanh thu bộ phim.

Input:
- Doanh thu trung bình của hãng phim(USD/Phim) - int
- Doanh thu trung bình của đạo diễn(USD/Phim) - int
- Tổng ngân sách đầu tư cho phim - int
- Điểm IMDB trung bình của các bộ phim của đạo diễn - double
- Đánh giá MPAA - [G, PG, PG-13, R, NC-17]
- Tổng số giải thưởng của đạo diễn - int
- Tổng số giải thưởng các các diễn viên chính - int

Output: Tổng doanh thu của phim đến khi hết công chiếu

Thu thập dữ liệu: Tìm hiểu từ các trang web chình thức của hãng phim, hoặc phỏng vấn các hãng phim.

2. Dự đoán giá trị của Bitcoin.

- Input: Mốc thời gian(ngày/tháng/năm)

- Output: Giá trị của Bitcoin tại thời điểm đó (USD) - int

- Dữ liệu train: mốc thời gian(ngày/tháng/năm) giá trị Bitcoin tại ngày đó (từ 10/1/2013 đến 4/28/2021), dữ liệu thu thập tại [Bitcoin](https://www.coindesk.com/price/bitcoin).

3. Dự đoán số người thất nghiệp của Mỹ trong tương lai.

Input:

- Năm thống kê - int
- Tổng số dân của Mỹ - int
- Tổng GDP của Mỹ - double
- Số người nghỉ hưu- int
- Tỷ lệ tăng dân - double

Output: số người thất nghiệp tại Mỹ.

Dự liệu train: cục quản lý dân số tại Mỹ, và GDP của [US](https://tradingeconomics.com/united-states/indicators?fbclid=IwAR0mQcPdKeaeBy-QR66ED-DT6vOUTdDGfnEEZ03dUswEHOr4cn10Xh32-So) các năm
.