# ts15-prompt-rules

Kho quản lý phiên bản prompt, schema và bộ quy tắc (bài thực hành GH-02 trong MUSE PLAYBOOK 1.0).

Mục tiêu: tránh nhiều bản "mới nhất" không rõ khác nhau — mọi thay đổi đều ghi rõ lý do, bản trước, bản đề xuất, tác động và người duyệt.

## Cấu trúc

- `docs/` — đặc tả và hướng dẫn (playbook, đặc tả bài toán)
- `rules/` — prompt, schema, bộ quy tắc được version hóa
- `src/` — mã chương trình
- `tests/` — kiểm thử và dữ liệu giả lập
- `CHANGELOG.md` — lịch sử thay đổi

## Quy tắc thay đổi

1. Mọi thay đổi mở nhánh riêng, không commit trực tiếp vào `main`.
2. Mỗi thay đổi phải ghi rõ: lý do, bản trước, bản đề xuất, tác động tới dữ liệu cũ, cách kiểm tra, người duyệt.
3. Mở PR và chỉ merge sau khi được duyệt.
4. Đổi schema phải kèm cách chuyển đổi dữ liệu và giữ khả năng truy vết bản cũ.
5. Version trên GitHub không đồng nghĩa quy tắc đã được phê duyệt để áp dụng trong dự án.

## Trạng thái

HƯỚNG DẪN ĐỀ XUẤT — repo thực hành theo playbook, chưa phải SOP dự án được phê duyệt.
