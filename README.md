# วิธีขึ้นเว็บด้วย GitHub Pages

## 1. สร้าง repository
1. สมัคร/ล็อกอิน https://github.com
2. กด **New repository** (ปุ่ม + มุมขวาบน)
3. ตั้งชื่อ repo เป็น **`username.github.io`** (แทน `username` ด้วยชื่อบัญชี GitHub ของคุณ)
   → เว็บจะอยู่ที่ `https://username.github.io`
4. เลือก **Public** แล้วกด **Create repository**

## 2. อัปโหลดไฟล์
1. ในหน้า repo กด **uploading an existing file**
2. ลาก `index.html` (และโฟลเดอร์ `images/` ถ้ามี) ลงไป
3. กด **Commit changes**

## 3. เปิดใช้ Pages
1. ไปที่ **Settings → Pages**
2. ตรง *Source* เลือก **Deploy from a branch**
3. Branch: **main**, โฟลเดอร์: **/ (root)** → กด **Save**
4. รอ 1–2 นาที แล้วเปิด `https://username.github.io`

## แก้ไขเว็บภายหลัง
เปิดไฟล์ `index.html` ใน repo → กดไอคอนดินสอ ✏️ → แก้ → **Commit changes** เว็บจะอัปเดตเองในไม่กี่นาที

## สิ่งที่ต้องแก้ใน index.html
- `ชื่อของคุณ`, `[ชื่อของคุณ]`, `[ประเภทงาน]`, `[จังหวัด]`
- บริการและราคา (`฿X,XXX`)
- ผลงาน 3 ชิ้น + รูป (ใส่ไว้ในโฟลเดอร์ `images/`)
- อีเมล `you@example.com` และ LINE ID `yourlineid`
- ลิงก์โซเชียลใน footer

## (ไม่บังคับ) ใช้โดเมนของตัวเอง
Settings → Pages → **Custom domain** ใส่โดเมน เช่น `yourname.com` แล้วตั้งค่า DNS ที่ผู้ให้บริการโดเมนตามคู่มือ:
https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site
