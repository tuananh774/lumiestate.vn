# LUMI Estate — Landing Page

Landing page một trang cho **LUMI Estate** — hệ sinh thái bất động sản: Cho thuê · Xây dựng · Vận hành.

## Cấu trúc

```
index.html        # Toàn bộ trang (HTML + CSS, logo nhúng sẵn)
netlify.toml      # Cấu hình Netlify
assets/
  logo-gold.png   # Logo vàng (nền trong suốt)
  logo-white.png  # Logo trắng (nền trong suốt)
  favicon.png     # Favicon 64px
  icon-192.png    # Icon 192px (apple-touch-icon)
  icon-512.png    # Icon 512px (og:image)
```

## Deploy lên Netlify

**Cách 1 — Kéo thả (nhanh nhất):** vào https://app.netlify.com/drop và kéo cả thư mục này vào.

**Cách 2 — Qua GitHub:**
1. Tạo repo mới trên GitHub, push toàn bộ thư mục này lên.
2. Vào Netlify → **Add new site → Import an existing project** → chọn repo.
3. Build command để trống, Publish directory: `.` → **Deploy**.

Sau khi deploy, có thể gắn tên miền riêng (vd `lumiestate.vn`) trong **Domain settings**.

## Liên hệ

contact@lumiestate.vn
