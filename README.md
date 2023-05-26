# API MBBANK

# Cài đặt

Clone repo `git clone https://github.com/trchicuong/api-mbbank.git`. <br>
Tải xuống file zip và giải nén

# Sử dụng

Thay `$taikhoanmb` và `$sotaikhoanmb` tương ứng trong file `src/Mb.php` <br>
Mở trình duyệt Chrome trên máy tính và truy cập link https://online.mbbank.com.vn/information-account/source-account đăng nhập tài khoản MB và quay lại link vừa nãy. Tiếp theo F12 trên máy tính và chuyển qua tab "Network" (Mạng) và mở tab Payload và thay tương ứng giá trị F12 được vào `$deviceIdCommon` và `$sessionId` <br>
Dùng lệnh `php index.php` để chạy API <br>
> **Note**
> API có thể cron trên VPS/HOSTING/CLOUD. Bạn chỉ cần cron 1 lần là có thể chạy cả ngày hoặc thậm chí vài ngày không lo bị đăng xuất mất. Trong quá trình sử dụng API không được đăng nhập tài khoản MBBank trên WEB hay APP vì sẽ bị văng API và phải làm lại từ đầu.

## Đóng góp

Nếu code bổ ích hãy dành một chút yêu thương qua https://nhantien.momo.vn/0377474579.