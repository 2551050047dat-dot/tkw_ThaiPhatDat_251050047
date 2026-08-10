# Luna Atelier — Wedding Photography Website

Dự án này là bản thiết kế website dịch vụ chụp ảnh cưới theo dạng landing page + nhiều trang nội dung, sử dụng HTML5, Tailwind CSS v4 và JavaScript ES6 thuần.

## 1. Mục tiêu dự án

- Thiết kế website thương hiệu chụp ảnh cưới chuyên nghiệp
- Thực hiện đúng 8 bước quy định của giảng viên: phân tích Figma, design tokens, layout semantic, responsive, JavaScript thực tế và tối ưu UX/UI
- Tạo trải nghiệm đẹp, giàu cảm xúc, dễ dùng trên mobile, tablet và desktop

## 2. Công nghệ sử dụng

- HTML5 semantic elements
- Tailwind CSS v4
- Vanilla JavaScript
- JSON / localStorage
- Responsive breakpoint: mobile, tablet, desktop

## 3. Cấu trúc thư mục

```text
.
├── index.html
├── pages/
│   ├── portfolio.html
│   ├── pricing.html
│   ├── about.html
│   ├── booking.html
│   └── reviews.html
├── js/
│   └── main.js
├── src/
│   └── input.css
├── dist/
│   └── output.css
├── data/
│   └── records.json
├── assets/
│   └── icons/
├── package.json
├── README.md
└── .gitignore
```

## 4. Cách chạy dự án

```bash
npm install
npm run dev
```

Sau đó mở file `index.html` bằng Live Server hoặc chạy local server và truy cập vào giao diện web.

## 5. Tính năng chính

- Portfolio Gallery filter theo chủ đề ảnh
- Lightbox modal xem ảnh lớn với điều hướng Previous/Next
- Booking form validation và lưu dữ liệu vào localStorage
- Price calculator tính tổng phí tự động theo gói + dịch vụ đi kèm
- Responsive menu mobile dạng hamburger
- SEO và accessibility cơ bản

## 6. Phân công công việc 3 thành viên

| Thành viên | Nhiệm vụ chính |
|---|---|
| Thành viên 1 | Home page, Portfolio page, gallery filter, lightbox |
| Thành viên 2 | Pricing page, booking form, validation, localStorage, calculator |
| Thành viên 3 | About page, Reviews page, accessibility, README, final polish |

## 7. Nhật ký commit gợi ý

```bash
git init
git add .
git commit -m "feat: setup wedding photography project"
git commit -m "feat: add homepage and responsive layout"
git commit -m "feat: add gallery filter and lightbox"
git commit -m "feat: add pricing and booking form"
git commit -m "docs: add project README"
```

## 8. Checklist cuối

- [x] 6 trang khác nhau
- [x] HTML semantic sử dụng đúng thẻ
- [x] 1 h1 trên mỗi trang
- [x] Form validation đầy đủ
- [x] Responsive mobile/tablet/desktop
- [x] Lightbox modal hoạt động
- [x] Price calculator đúng
- [x] CSS tokens được tập trung trong `src/input.css`

## 9. Ghi chú

Dự án này đang ở mức hoàn thiện theo hướng bài tập lớn môn Thiết kế Web. Học viên có thể tiếp tục bổ sung nội dung thực tế, hình ảnh, và nâng cấp trải nghiệm thêm ở giai đoạn cuối trước khi nộp bài.
