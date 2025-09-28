# Game News & Wiki (GitHub Pages + Jekyll)

- Không cần cài Node/DB.
- Nội dung:
  - `_posts` (tin tức, dạng blog)
  - `_characters` (nhân vật/tướng)
  - `_items` (vật phẩm)
- Tìm kiếm: trang `/search.html` dùng Lunr.js (client-side)

## Cách viết bài
- Tin tức: tạo file trong `_posts/YYYY-MM-DD-slug.md`
- Nhân vật: tạo file trong `_characters/name.md`
- Vật phẩm: tạo file trong `_items/name.md`

## Bật GitHub Pages
Settings > Pages > Build and deployment:
- Source: Deploy from a branch
- Branch: main
- Folder: /(root)

URL sẽ là: `https://duylam0290.github.io/game-news-wiki/` (đợi 1–3 phút build)

## Domain riêng (sau này)
- Thêm CNAME trong Settings > Pages > Custom domain (ví dụ: `yourdomain.com`)
- DNS:
  - `www` CNAME -> `duylam0290.github.io`
  - root `@` (tùy chọn) A -> 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
