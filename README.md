# CNTT1-nh-p-m-n-c-ng-ngh-th-ng-tin-Session10_Ex05
1. Phân tích sai lầm của Nam
Nén nhị phân vs. Dòng bản thô: .docx là tệp nén ZIP chứa nhiều file XML. Git coi đây là file nhị phân nên không thể so sánh từng dòng (line-by-line diff). Sửa một dấu phẩy làm đổi toàn bộ mã băm của gói nén, gây xung đột toàn bộ file.

Sai công cụ: Word là định dạng đóng (Rich Text/WYSIWYG) dùng cho in ấn/trình bày, không tối ưu cho cộng tác mã nguồn hay đọc trực tiếp trên trình duyệt Web (GitHub).

Vì sao Markdown an toàn và nhẹ hơn?

Nhẹ & Git Diff: Tệp .md chỉ là Plain Text (văn bản thô), dung lượng siêu nhẹ. Git dễ dàng theo dõi chi tiết từng dòng thay đổi.

Chống hư hại file: Nếu mất 1 byte, .docx vỡ cấu trúc ZIP và hỏng hoàn toàn (không thể mở). Với .md, bạn chỉ mất đúng 1 ký tự lỗi đó, toàn bộ phần còn lại vẫn đọc được bình thường.

2. File Markdown hoàn chỉnh (.md)
Markdown
# Dự án GreenTech

## 1. Giới thiệu
GreenTech là giải pháp công nghệ xanh hỗ trợ theo dõi tiêu thụ năng lượng và tái chế rác thải điện tử dành cho sinh viên PTIT.

## 2. Tính năng chính
- **Giám sát năng lượng:** Thống kê lượng điện theo thời gian thực.
- **Gợi ý thông minh:** Mẹo tiết kiệm điện theo thói quen.
- **Tái chế rác điện tử:** Kết nối điểm thu gom thiết bị cũ.

## 3. Thành viên & Công nghệ
- **Nhóm thực hiện:** Sinh viên PTIT
- **Công nghệ:** Python, Web, Git, Markdown
