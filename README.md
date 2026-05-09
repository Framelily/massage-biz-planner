# massage-biz-planner

แผนธุรกิจ + plan implementation สำหรับเปิดร้าน Khum Lanna Spa (boutique Lanna wellness spa) ที่นิมมาน เชียงใหม่

## 📁 เอกสารในโปรเจกต์

- `docs/superpowers/specs/2026-05-09-massage-shop-business-plan-design.md` — แผนธุรกิจฉบับเต็ม (9 sections)
- `docs/superpowers/plans/2026-05-09-massage-shop-implementation.md` — Plan ลงมือ (10 tracks, 6 เดือน pre-launch)
- `docs/recruitment/spa-manager-jd.md` — Job description ผู้จัดการสปา (TH + EN)
- `docs/index.html` — Web UI สำหรับอ่านเอกสารทั้งหมด (mobile-friendly)

## 📱 ดูเอกสารบนเว็บ / มือถือ

### วิธีที่ 1: เปิดในเครื่องตัวเอง (Local)

```bash
cd docs
python3 -m http.server 8000
```

แล้วเปิด <http://localhost:8000> ในเบราว์เซอร์

> ⚠️ **อย่าเปิด `index.html` ตรงๆ ด้วย `file://`** — browser จะ block fetch ทำให้โหลด markdown ไม่ได้

### วิธีที่ 2: Deploy ขึ้น GitHub Pages (ฟรี ถาวร)

1. Push repo ขึ้น GitHub:

   ```bash
   gh repo create massage-biz-planner --public --source=. --push
   ```

   (ถ้ายังไม่ได้ติดตั้ง `gh`: <https://cli.github.com/>)

2. ไปที่ repo บน GitHub → **Settings** → **Pages**
3. ตั้งค่า:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/docs`
4. Save → รอ 1-2 นาที
5. URL ที่ได้: `https://<your-username>.github.io/massage-biz-planner/`

📱 เปิด URL นั้นบนมือถือ → bookmark / เพิ่มลงหน้าจอหลัก (Add to Home Screen) ใช้เหมือนแอป

### วิธีที่ 3: Deploy บน Netlify (ฟรี + custom domain ได้)

1. ไป <https://app.netlify.com/drop>
2. ลากโฟลเดอร์ `docs/` ทั้งโฟลเดอร์เข้าหน้าเว็บ
3. ได้ URL ทันที (เช่น `random-name.netlify.app`)
4. เปลี่ยน subdomain ได้ฟรีในหน้า settings

### วิธีที่ 4: Vercel (ฟรี เร็วสุด)

```bash
npx vercel docs
```

(ครั้งแรกจะให้ login + ตั้งค่า → ครั้งถัดไป redeploy ใช้คำสั่งเดียว)

## 🔄 อัปเดตเอกสาร

แก้ไฟล์ `.md` ใน `docs/` แล้ว commit + push → web auto-update (สำหรับ GitHub Pages / Netlify / Vercel)

## 🛠️ Stack

- Markdown (เนื้อหา)
- Single-file HTML SPA (`docs/index.html`)
- [marked.js](https://marked.js.org/) (CDN — render markdown client-side)
- Google Fonts: Sarabun + Playfair Display
- ไม่มี build step / dependencies
