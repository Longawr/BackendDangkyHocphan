# DKHP_BE_Project
- Backend ứng dụng đăng ký học phần
- Sử dụng java spring boot để tạo API từ phía local server và call API từ phía client, có sử dụng jwt để tạo token và phân quyền cơ bản


# Hướng dẫn cài đặt
Cần Xampp, Java Development Kit, Inteliji để sử dụng

* B1: Bật Xampp lên. Nhấn start 2 mục Apache và My SQL, sau đó nhấn vào Admin tại mục My SQL.
 
- Tại web mới hiện lên, ta tạo database mới và đặt tên là schoolmanagement. (Ở đây chúng em đã tạo rồi nên không tạo nữa)
 
* B2: Mở project api bằng Inteliji, sau đó ta theo đường dẫn src/main/java/resources sau đó:

- Tại file application.properties ta xóa 123456 đi tại dòng

 spring.datasource.password=123456

- Tương tự tại file hibernate.cfg.xml ta xóa 123456 tại 

  <property name="connection.password">123456</property>

- Sau đó run file ApiApplication.java (nếu chạy lỗi thì ta chạy lại thêm lần nữa)
