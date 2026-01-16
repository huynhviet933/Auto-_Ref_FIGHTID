# Auto_Ref_FIGHTID

Aidrop Free  ;https://t.me/HVchannelss/259

Tham Gia Discor ( Vip ) : https://discord.gg/gKxvTNu5

Tham gia NHóm VIp Với Chi Phí 8u/1thang Lợi ích tham gia nhóm ViP Sẽ được cấp keey sử dụng các tool vip trong discor hỗ trợ Và tham khao Code các tool dự án mà các bạn đề xuất

Gửi Phí tháng vào đây và chụp hình gửi trực tiếp cho tôi tại discor để xác nhận Role VIp ☕ https://huynhviet933.github.io/donate_viet_mmo/ Có thể tặng tôi ít cafe tại đây

================================================================
HƯỚNG DẪN SỬ DỤNG TOOL FIGHT.ID MULTI-THREAD
================================================================

1. CHUẨN BỊ CÁC FILE DỮ LIỆU (Tạo trong cùng thư mục với index.js)
----------------------------------------------------------------
- proxy.txt      : Danh sách Proxy (Định dạng: ip:port hoặc user:pass@ip:port).
- ref.txt        : Danh sách mã giới thiệu (Mỗi dòng 1 mã).
- User-Agent.txt : Danh sách User-Agent (Mỗi dòng 1 chuỗi).
- profiles.json  : (Tự động tạo) Nơi lưu trữ tài khoản đã đăng ký thành công.
- license.key    : (Tự động tạo) Lưu mã bản quyền sau lần nhập đầu tiên.

2. CÁC CHẾ ĐỘ CHẠY (MODES)
----------------------------------------------------------------
- Chế độ 1: Đăng ký tài khoản mới hàng loạt, tự động giải OTP qua mail.tm và bind ref.
- Chế độ 2: Kiểm tra và tự động làm mới (Refresh) Token cho các tài khoản trong profiles.json.

3. LỆNH CÀI ĐẶT THƯ VIỆN VÀ CHẠY TOOL (COPY DÁN VÀO CMD/TERMINAL)
----------------------------------------------------------------
npm install axios readline-sync https-proxy-agent uuid && node index.js

4. LƯU Ý QUAN TRỌNG
----------------------------------------------------------------
- Tool yêu cầu License Key để hoạt động (Xác thực qua License Server).
- Số luồng (Parallel threads) nên đặt phù hợp với số lượng Proxy bạn có.
- Nếu Proxy chết hoặc lỗi mạng, tool sẽ tự động thử lại (Retry) với IP khác.
- Tuyệt đối không xóa file profiles.json vì đây là nơi chứa dữ liệu tài khoản của bạn.
================================================================
