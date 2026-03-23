# Bài tập Kha2 - HTTP Status Code

- TH1: Bỏ trống tên bệnh nhân:
Status: 400 Bad Request
Dữ liệu gửi lên không hợp lệ, thuộc lỗi phía client.

- TH2: ID = 999 không tồn tại:
Status: 404 Not Found
Request hợp lệ nhưng không tìm thấy resource trong database.

- TH3: Database MySQL bị sập:
Status: 500 Internal Server Error
Lỗi xảy ra từ phía server khác, hệ thống hiện tại bó tay

- TH4: Tuổi bị âm (-5): 
Status: 400 Bad Request
Dữ liệu không hợp lệ về mặt logic, lỗi phía client.