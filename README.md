# Lời nói đầu:
Project này được xây dựng trong thời gian tôi còn làm giảng viên Python tại IT-Plus. Đây là một project mẫu để các học viên có thể tham khảo và phát triển thành các pet-project để có thể tự tin tham gia phỏng vấn Fresher/Junior Python.

Tại thời điểm đó, tôi đang dùng Python3.6, có một số lỗi xảy ra với thư viện `flask_restplus_patched` nếu nó được cài đặt trực tiếp từ PyPi Thời gian gần đây, tôi đã cập nhật lên phiên bản Python3.8, phiên bản Flask 1.1 và thư viện `flask_restplus_patched` được install trực tiếp PyPi.


Đây là một ví dụ cho phép các học viên hiểu được:
- Cách xây dựng một API dựa trên Flask Framework và được hoàn thiện bằng cách sử dụng structed của flask-restplus.
- Cách sử dụng sqlachemy như một ORM để kết nối và truy vấn vào database.
- Cách xây dựng spec cho flask-api dưới dạng swagger.


# Đầu bài:
Cho một database có tên HR_sqlite.db, có các bảng dữ liệu như hình vẽ


![hr schema](/images/hrschema.JPG)

Xây dựng một hệ thống API cho phép thực hiện các chức năng cơ bản:
1. Lấy ra tất cả các bản ghi.
2. Lấy ra các bản ghi theo khóa phụ, khóa ngoại (FK)
3. Lấy ra một bản ghi theo ID
4. Thêm mới một bản ghi
5. Thay đổi dữ liệu bản ghi
6. Xóa một bản ghi
7. Xóa nhiều bản ghi

**Lưu ý**: Trong project này, tôi chỉ thực hiện viết code cho 3 bảng dữ liệu: Regions, Countries, Location

# Công nghệ sử dụng:
- Python3.8/Flask
- Python libs: flask_restplus_patched, sqlalchemy
- SQLite


# Hướng dẫn & screenshot
[Cài đặt](/geo-location-api/README.md)

Screenshot:

## swagger site
![API](/images/swagger.png)

## healthCheck
![healthCheck](/images/healthCheck.png)

## Action API
![action API](/images/swagger_API.png)

## Get all regions
![region API](/images/get_all.png)

