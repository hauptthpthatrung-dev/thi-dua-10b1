SỔ THI ĐUA ĐIỆN TỬ 10B1 - V5

V5 gồm:
- 46 học sinh, chia Tổ 1-4.
- STT 42: Hà Đức Thiện (A); STT 43: Hà Đức Thiện (B).
- Ghi nhận theo ngày, số lần x điểm/lần.
- Quy tắc -30 điểm/lần: Không đi chào cờ, hoạt động ngoại khoá.
- Tổng hợp tuần, tháng, năm và thi đua tổ.
- PWA: có manifest + service worker để cài như app trên điện thoại/máy tính.
- Dữ liệu mặc định lưu local trên thiết bị.

ĐỒNG BỘ NHIỀU THIẾT BỊ:
V5 có ô cấu hình Firebase/Firestore. Cần tạo Firebase project, bật Anonymous Authentication và Firestore, sau đó dán Firebase config vào mục "Đồng bộ & Cài app".
Không nên để Firestore mở toàn quyền khi triển khai thật; cần đặt Security Rules phù hợp.

CÀI ĐẶT:
- Tool PWA phải được phục vụ qua HTTPS (hoặc localhost để thử).
- Android/Chrome: menu -> Thêm vào màn hình chính / Install app.
- iPhone/iPad Safari: Chia sẻ -> Add to Home Screen.
- Máy tính Chrome/Edge: Install app.

Lưu ý: file HTML mở trực tiếp bằng file:// vẫn chạy chức năng local, nhưng service worker/PWA và Firebase cần HTTPS.
