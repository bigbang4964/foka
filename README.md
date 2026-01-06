# foka
FokaPOS – Ứng dụng quản lý nhà hàng, quán ăn, cafe

FokaPOS là hệ thống POS & quản lý vận hành nhà hàng hiện đại, tối ưu cho quán ăn, quán cafe, nhà hàng nhỏ & vừa, hỗ trợ bán hàng – thu ngân – kế toán – hóa đơn điện tử – báo cáo thuế theo chuẩn Việt Nam.

🚀 Tính năng chính
🏪 1. Quản lý quán & cấu hình

Thông tin quán: tên, địa chỉ, MST, người đại diện

Phân loại mô hình:

Cá nhân kinh doanh (CNKD)

Doanh nghiệp (GTGT)

Cài đặt VAT mặc định (tự động theo mô hình)

Cấu hình in VAT trên hóa đơn

Vị trí GPS (bản đồ)

🍔 2. Bán hàng & gọi món (POS)

Gọi món theo:

Bàn / ghế

Mang đi

Theo dõi trạng thái món:

Chờ nấu → Đang nấu → Hoàn thành

Bắt buộc hoàn thành món trước khi thanh toán (tuỳ chọn)

Tính tiền tự động, hỗ trợ VAT

👨‍🍳 3. Bếp & vận hành

Màn hình bếp (Kitchen)

Hàng đợi món theo thời gian

Thông báo khi có món mới

Phạt trễ / thống kê thời gian nấu (tuỳ cấu hình)

🧾 4. Hóa đơn & thanh toán

Hóa đơn bán hàng (POS)

In hóa đơn Bluetooth

Hiển thị QR chuyển khoản ngân hàng

Lưu lịch sử hóa đơn

🧾 5. Hóa đơn điện tử (HĐĐT) 🇻🇳

Hỗ trợ “Hóa đơn điện tử khởi tạo từ máy tính tiền” theo quy định Tổng cục Thuế.

Nhà cung cấp hỗ trợ:

✅ MISA meInvoice

✅ VNPT Invoice

Tính năng:

Cấu hình provider riêng cho từng quán

Lưu credential bảo mật bằng SecureStore

Test kết nối HĐĐT

Phát hành hóa đơn điện tử trực tiếp từ POS

Lưu:

Số hóa đơn

Mã CQT

Mã tra cứu

QRCode

📊 6. Báo cáo & thuế

Báo cáo:

Doanh thu ngày / tháng / năm

Theo sản phẩm

Theo ca bán

Xuất:

📄 PDF

📊 Excel (chuẩn thuế VN)

Dữ liệu phục vụ:

Kê khai thuế

Quyết toán CNKD / GTGT

👥 7. Nhân sự & lương

Quản lý nhân viên

Chấm công

Tính lương theo:

Giờ

Ca

Doanh thu

🖨️ 8. In hóa đơn & phần cứng

Kết nối máy in Bluetooth

Lưu MAC Address máy in

Tương thích máy POS Android

🧱 Công nghệ sử dụng
Frontend

⚛️ React Native (Expo + TypeScript)

Expo SecureStore (lưu thông tin nhạy cảm)

React Navigation

Zustand (state management)

Backend / Data

🔥 Firebase

Firestore (database)

Authentication

Cloud Functions (mở rộng)

Real-time update

Tích hợp ngoài

Axios (API)

MISA / VNPT eInvoice API

Google Maps (GPS)

🔐 Bảo mật

Không lưu password HĐĐT trong Firestore

Credential HĐĐT lưu bằng SecureStore

Phân tách:

Dữ liệu nhạy cảm → thiết bị

Dữ liệu nghiệp vụ → cloud

Không dùng crypto native → tương thích Expo

Test & môi trường

Android POS

Android phone

iOS (qua Expo / TestFlight)

Firebase Emulator (dev)

📦 Build & phát hành

Android:

APK / AAB

Google Play Store

iOS:

EAS Build

App Store

🏷️ Đối tượng phù hợp

Quán ăn – quán cafe – trà sữa

Nhà hàng nhỏ & vừa

Cá nhân kinh doanh

Doanh nghiệp F&B cần xuất HĐĐT

📄 Bản quyền

© 2025 FokaSoft
FokaPOS là sản phẩm thương mại. Mọi quyền được bảo lưu.

📞 Liên hệ

Website: fokasoft.com

Email: support@fokasoft.com

Hotline: 0346987195
