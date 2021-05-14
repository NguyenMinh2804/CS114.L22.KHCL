# #CS114.L22.KHCL
## THÀNH VIÊN NHÓM
  + 17520757 - Nguyễn Văn Minh
  + 18521640 - Kiều Quang Việt
  + 19522440 - Nguyễn Ngọc Trưởng
## 1. Bài toán dự đoán điểm thi ĐGNL đợt 1 (ĐHQG TP.HHCM) của học sinh lớp 12

- Input: Điểm trung bình (float) môn học của 9 môn: Toán, Lý, Hóa, Sinh, Sử, Địa, GDCD, Anh Văn, Ngữ Văn của học kì 1 năm lớp 12
- Output: Điểm thi (int) dự đoán của kì thi ĐGNL đợt của học sinh 12 đó
- Thu thập dữ liệu: Điền form khảo sát từ các sinh viên năm nhất khóa 2018, khóa 2019, khóa 2020. Cách bất khả thi khác là xin thông tin từ phía nhà trường THPT và Đại học Quốc gia TPHCM
- Xử lý dữ liệu: 
    - Điền form khảo sát lấy được file excel, chuyển về file (.csv). Lấy đủ những thông tin cần thiết (điểm trung bình của 9 môn học, và điểm thi ĐGNL) loại bỏ đi cột thông tin như họ tên, ngày tháng năm sinh,...
    - Loại bỏ những dòng có trường dữ liệu nhập sai (điểm trung các môn thuộc đoạn [0, 10], điểm thi ĐGNL là số tự nhiên nhỏ hơn 1200)

## 2. Bài toán dự đoán giá của một chiếc xe đã qua sử dụng

- Input: Giá mua (== giá bán mới) (int), năm đăng kí (int), số km đã đi(int), năm sản xuất(int), đã sử chữa "máy" chưa (bool)
- Output: Giá bán của xe
- Lấy dữ liệu: 
    - Xin dữ liệu từ các cửa hàng mua lại xe cũ (có thể hơi khó khăn về mặt bí mật kinh doanh)
    - Cào dữ liệu từ các trang chợ tốt, lấy thông tin của tên loại xe để tiếp tục cào dữ liệu ở trang web khác, lấy thông tin giá bán mới của chiếc xe đó.
- Xử lý dữ liệu: Bỏ qua những trường không cần thiết (không có trong output). Chuyển tất cả dữ liệu vào file csv đồng nhất, xóa đi những hàng có chữa những trường thông tin như quy ước ở Input. 