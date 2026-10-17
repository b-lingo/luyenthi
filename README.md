# B-Lingo – Hệ thống học & luyện thi tiếng Anh THPT

Sản phẩm dự thi Giáo viên sáng tạo · Phiên bản 1.0 (10/2026)

## Trong gói có gì

| Tệp | Vai trò |
|---|---|
| `index.html` | Toàn bộ ứng dụng: giao diện, làm bài, chấm điểm, bộ phát nghe, flashcard, trang quản trị |
| `tests.json` | Ngân hàng đề đã soạn (19 đề, 637 câu ngoài các đề mẫu có sẵn trong ứng dụng) |
| `README.md` | Tệp này |

## Đưa lên mạng bằng GitHub Pages (miễn phí)

1. Vào https://github.com, đăng nhập, bấm **New repository**, đặt tên `b-lingo`, chọn **Public**, bấm **Create repository**.
2. Bấm **uploading an existing file**, kéo cả 3 tệp trong gói vào, bấm **Commit changes**.
3. Vào **Settings → Pages**. Ở mục *Branch* chọn `main` và thư mục `/ (root)`, bấm **Save**.
4. Chờ 1–2 phút, trang sẽ có địa chỉ dạng `https://<tên-tài-khoản>.github.io/b-lingo/`.

## Quản trị nội dung

- Bấm **⚙ Quản trị**, nhập mật khẩu mặc định `admin2026`, rồi đổi ngay ở tab *Bảng điểm & xuất bản*.
- Soạn, sửa, xóa câu hỏi; nhập đề hàng loạt từ Word; tạo đề bằng AI (cần khóa Gemini API miễn phí).
- Mọi thay đổi là **bản nháp trên máy bạn**. Để học sinh thấy: tab *Bảng điểm & xuất bản* → **Tải tệp tests.json** → lên GitHub, mở tệp `tests.json` cũ, bấm biểu tượng thùng rác để xóa, rồi tải tệp mới lên (hoặc dùng *Add file → Upload files* để ghi đè).

## Lưu ý

- Mở trực tiếp `index.html` bằng cách nháy đúp sẽ không đọc được `tests.json` (trình duyệt chặn). Hãy dùng bản trên GitHub Pages.
- Mật khẩu quản trị chỉ là lớp chặn đơn giản trên trình duyệt, không phải bảo mật tuyệt đối.
- Điểm của học sinh lưu trên máy của từng em.
