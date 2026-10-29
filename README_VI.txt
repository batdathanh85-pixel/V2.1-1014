MÁY TÍNH CHIA Ô KHUNG SẮT — HƯỚNG DẪN CÀI ĐẶT

NỘI DUNG ZIP
- index.html: ứng dụng
- manifest.webmanifest: thông tin cài ứng dụng
- sw.js: hỗ trợ lưu bộ nhớ đệm để dùng lại khi offline
- icon-192.png, icon-512.png: biểu tượng ứng dụng

CÁCH ĐƯA LÊN GITHUB PAGES
1. Giải nén ZIP trên điện thoại hoặc máy tính.
2. Mở repository GitHub muốn dùng, chọn Add file > Upload files.
3. Tải LÊN CÁC FILE BÊN TRONG ZIP (index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png), không tải nguyên file ZIP và không để chúng nằm trong thư mục con.
4. Commit changes.
5. Vào Settings > Pages, chọn Deploy from a branch, nhánh main và thư mục /(root), rồi Save.
6. Đợi GitHub Pages xuất bản website.
7. Mở đường dẫn GitHub Pages bằng Chrome trên Android, bấm menu ⋮ > Cài đặt ứng dụng/Thêm vào màn hình chính.

LƯU Ý SỬ DỤNG
- Chọn Lọt lòng nếu bạn nhập kích thước bên trong khung.
- Chọn Phủ bì nếu bạn nhập kích thước ngoài; nhập bề rộng khung hai bên để trừ ra chiều lọt lòng. Phần kiểm tra tổng sẽ cộng lại hai thanh biên để khớp đúng kích thước phủ bì.
- Bề rộng thanh chia là kích thước thanh chiếm theo chiều ngang.
- Chế độ chia đều: nhập số ô mong muốn.
- Chế độ xen kẽ: có thể cố định ô nhỏ để tìm ô to, hoặc cố định ô to để tìm ô nhỏ. Khoảng tìm được nhập ở hai ô nhỏ nhất/lớn nhất.
- Ở chế độ lọt lòng, vị trí lấy dấu tính từ mép trong bên trái. Ở chế độ phủ bì, vị trí lấy dấu tính từ mép ngoài bên trái và đã cộng bề rộng thanh biên trái. Bảng hiển thị mép trái, tâm và mép phải mỗi thanh chia bên trong.
- Ứng dụng kiểm tra tổng kích thước tính toán, nhưng hãy kiểm tra cách cấu tạo khung thực tế trước khi cắt hàn.


Bản cập nhật logo: đã thay icon-192.png và icon-512.png bằng logo mới người dùng cung cấp; cập nhật manifest và cache version. Để Chrome nhận diện biểu tượng mới, cập nhật các file lên GitHub Pages, chờ triển khai xong rồi gỡ lối tắt cũ và cài lại bằng mục “Cài đặt ứng dụng/Install app” nếu Chrome hiển thị mục này.
