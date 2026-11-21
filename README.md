# image-relay

Kho chứa hình (image relay) cho trang publications của Thanh-Phong Lam.

- Hình được Vercel deploy tự động. URL của một hình có dạng `https://image-relay.vercel.app/images/<ten-hinh>`.
- Trang web chính vẫn ở https://limpaulfin.github.io/publications/ và chỉ **tham chiếu** hình từ đây, không chứa file hình.
- Ngày tạo: 2026-11-21.

## Quy ước đặt tên file hình trong `images/`

- Chữ thường, không dấu tiếng Việt, không khoảng trắng, các từ nối bằng dấu gạch ngang. Ví dụ: `story-genius-cover.jpg`, `bia-sach-ke-chuyen.png`.
- Định dạng ưu tiên: `.jpg` cho ảnh chụp và bìa sách, `.png` khi cần nền trong hoặc chữ sắc nét.
- Mỗi file hình nên dưới 2 MB; hình lớn hơn thì nén trước khi commit.
- Mọi hình nằm trong thư mục `images/`, không đặt ở nơi khác.
