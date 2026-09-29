# Cẩm nang công tác họp của Văn phòng Đảng ủy xã

Đồ án môn Nhập môn Công nghệ thông tin (hệ ĐTTX). Website tài liệu xây bằng Docsify và xuất bản được bằng GitHub Pages. Nội dung minh họa quy trình tổ chức cuộc họp Thường trực Đảng ủy xã, ghi biên bản, soạn thông báo kết luận và theo dõi nhiệm vụ. Dữ liệu trong các ví dụ là giả định.

## Thông tin bàn giao

| Mục | Thông tin |
| --- | --- |
| Họ tên sinh viên | [Điền họ tên] |
| Nhóm / lớp | [Điền thông tin] |
| Đề tài | Cẩm nang công tác họp của Văn phòng Đảng ủy xã |
| Website | https://canloc0311.github.io/cam-nang-hop-dang-uy/#/ |
| Mã nguồn | https://github.com/canloc0311/cam-nang-hop-dang-uy |

## Năm trang nội dung

1. `trang-chu.md`: giới thiệu, sơ đồ quy trình, bảng điều hướng và bản đồ nhúng.
2. `chuan-bi-cuoc-hop.md`: chương trình, thành phần, tài liệu, bảng kiểm.
3. `ghi-bien-ban.md`: thông tin cần ghi, cách ghi theo vấn đề, ví dụ.
4. `thong-bao-ket-luan.md`: cấu trúc, mẫu giao việc, kiểm tra phát hành.
5. `theo-doi-nhiem-vu.md`: bảng tiến độ, trạng thái và báo cáo.

## Cấu trúc và kỹ thuật

- `index.html`: cấu hình Docsify, tìm kiếm và plugin sao chép mẫu văn bản.
- `_sidebar.md`: menu liên kết 5 trang.
- `assets/style.css`: trình bày trên máy tính và điện thoại.
- `assets/quy-trinh.svg`: sơ đồ quy trình tự tạo, có mô tả tiếp cận.
- `.nojekyll`: yêu cầu GitHub Pages phục vụ các tệp trực tiếp.
- Google Maps được nhúng bằng iframe ở trang chủ để minh họa khu vực sử dụng.

Website cần có mạng để tải Docsify từ jsDelivr và bản đồ từ Google Maps. Không đưa tài liệu nội bộ hoặc thông tin cá nhân thật vào kho công khai.

## Chạy thử tại máy

Mở terminal trong thư mục này và chạy:

```bash
python -m http.server 8000
```

Sau đó mở `http://localhost:8000`. Không mở trực tiếp `index.html` bằng đường dẫn `file://` vì trình duyệt có thể chặn việc đọc các tệp Markdown.

## Xuất bản trên GitHub Pages

Kho công khai đã được tạo trên GitHub. GitHub Pages đang lấy nội dung từ nhánh `main`, thư mục `/(root)`. Mở liên kết website ở bảng bàn giao để xem bản đã xuất bản.

## Quản lý phiên bản

Các tệp trên GitHub được tải lên theo từng nhóm nội dung và có lịch sử commit trong kho công khai. Bản nén bàn giao chỉ chứa mã nguồn; xem lịch sử cập nhật tại liên kết kho GitHub ở trên.
