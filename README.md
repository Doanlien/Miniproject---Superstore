# Miniproject---Superstore

Trong project này sử dụng bộ dữ liệu superstore về các hóa đơn được lưu trữ trong một file excel. File này chứa 3 bảng dữ liệu khác nhau bao gồm: Orders, Returns, People.

Những yêu cầu với bộ dữ liệu trên:

1.Lợi nhuận (profit) và doanh thu (sale) thay đổi như thế nào theo từng tháng?

2.So sánh tỷ lệ lợi nhuận (profit/sale) của từng tiểu bang trong năm 2017 (dữ liệu mới chỉ có đến 2017)?

3.Có bao nhiêu sản phẩm được trả lại (returned)? Những tiểu bang (state) và danh mục sản phẩm (category) nào có tỷ lệ trả lại cao nhất?

Mình dùng Mysql để lấy dữ liệu phục vụ việc trả lời các câu hỏi.

Câu 1. Với câu hỏi 1 thì mình cần 3 thông tin là lợi nhuận (profit), doanh thu (sale) và thời gian (order_date). Cả 3 cột này đều ở một bảng là order. dùng sql để lấy dữ thành bảng gồm các cột: Doanh thu, lợi nhuận, tỷ lệ lợi nhuận = lợi nhuận/doanh thu, Tháng năm. Dùng python để vẽ biểu đồ biểu diễn doanh thu, lợi nhuận, tỷ lệ lợi nhuận theo thời gian.

Câu 2. để trả lời câu hỏi này mình cần đến các thông tin: lợi nhuận (profit), doanh thu (sale), tiểu bang (state) và thời gian(order_date). Dùng sql để lấy dữ thành bảng gồm cột: tỷ lệ lợi nhuận và tiểu bang Câu 2 mình dùng Tableau để visualization

Câu 3. để có tỷ lệ trả lại của mỗi tiểu bang và theo từng danh mục cần các thông tin: danh mục đơn hàng, tiểu bang và đơn hoàn trả từ 2 bảng orders và returns. 2 bảng này có cột chung là cột order_Id. Dùng sql để lấy dữ liệu thành bảng có các cột: Tổng hóa đơn, tổng hóa đơn trả, tỷ lệ trả hàng = tổng hóa đơn trả/tổng hóa đơn, tiểu bang, danh mục. Dùng Taleau để visualization.
Phần Visualization của câu 2 và câu 3 tại: https://public.tableau.com/profile/doan4431#!/vizhome/miniproject-superstore/Dashboard1

Vì là người mới nên có thể mình làm vẫn chưa đúng nên rất mong nhận được sự góp ý từ người đọc.
Feel free to comment!
