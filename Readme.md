Hiệu ứng Domino (Credential Stuffing): Diễn đàn nhỏ bảo mật kém dễ bị lộ cặp (Email + Mật khẩu "123456"). Hacker dùng công cụ tự động (bot) đem thông tin này thử đăng nhập hàng loạt vào Gmail, Facebook, GitHub. Chiếm được Gmail (trung tâm khôi phục tài khoản), hacker dễ dàng chiếm nốt mọi dịch vụ khác.
Mật khẩu cảm tính vs. Mật khẩu máy sinh:



Cảm tính: Theo thói quen (tên, ngày sinh, dãy số dễ nhớ như 123456), có độ ngẫu nhiên (entropy) cực thấp nên bị công cụ dò từ điển (Dictionary Attack) bẻ khóa trong tích tắc.



Máy sinh: Chuỗi ký tự hoàn toàn ngẫu nhiên, không có quy luật, buộc hacker phải thử từng tổ hợp (Brute-force) mất hàng triệu năm.

Password Manager (chuẩn AES-256) vs. Ghi chép thủ công:Ghi chép thủ công: Sổ giấy dễ lộ/mất; file Notepad/Excel dễ bị mã độc đọc trộm trực tiếp và khiến người dùng ngại đặt mật khẩu dài.Password Manager (AES-256): Mã hóa toàn bộ kho mật khẩu bằng khóa 256-bit ($2^{256}$ khả năng — bất khả thi để vét cạn bằng siêu máy tính). Dữ liệu được khóa ngay trên thiết bị, giúp bạn dùng mật khẩu dài và khác nhau cho từng web mà chỉ cần nhớ duy nhất 1 Master Password.

