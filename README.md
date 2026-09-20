# 🎓 Thư mời dự lễ tốt nghiệp

Website thiệp mời tốt nghiệp cá nhân, một trang tĩnh (HTML + CSS + JavaScript), không cần backend hay đăng nhập.

## Cấu trúc

```
.
├── index.html   # toàn bộ thiệp (CSS, JS và ảnh đều nằm trong file này)
└── README.md
```

## Xem thử trên máy

Mở file `index.html` bằng trình duyệt là xem được.

## Chỉnh nội dung

Mở `index.html` bằng trình soạn thảo (VS Code, Notepad++...) và tìm:

| Muốn đổi | Tìm |
|---|---|
| Tên người được mời | `Trương Hoàng Mai` |
| Giờ | `10:30` |
| Ngày | `Thứ Bảy, ngày 26/09/2026` |
| Địa điểm, địa chỉ | `Phân hiệu Trường Đại học GTVT` |
| Lời nhắn | `Rất mong được gặp Mai` |
| Chữ ký | `<p class="sign` |
| Link Google Maps | `href="https://www.google.com/maps/search/` |

**Đổi ảnh:** bỏ ảnh mới (ví dụ `mai.jpg`) vào cùng thư mục với `index.html`, rồi thay
`src="data:image/jpeg;base64,..."` trong thẻ `<img>` thành `src="mai.jpg"`.

## Deploy bằng GitHub Pages

1. Đẩy code lên một repository trên GitHub (nhánh `main`).
2. Vào **Settings → Pages**.
3. Ở mục **Build and deployment**, chọn **Source: Deploy from a branch**, **Branch: `main`**, thư mục **`/ (root)`**, bấm **Save**.
4. Chờ 1–2 phút, trang có địa chỉ `https://<username>.github.io/<tên-repo>/`.

Mỗi lần `git push` mã mới lên `main`, GitHub Pages sẽ tự cập nhật lại trang.
# graduation-invitation-HM
# graduation-invitation-HM
# graduation-invitation-HM
