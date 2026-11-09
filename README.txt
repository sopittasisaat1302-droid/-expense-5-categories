บัญชีรายจ่าย 5 หมวด — ชุดไฟล์ PWA

ไฟล์ในชุดนี้:
- index.html
- manifest.webmanifest
- sw.js
- icon.svg

วิธีนำขึ้น GitHub Pages:
1. เปิด Repository: sopittasisaat1302-droid/-expense-5-categories
2. เข้าแท็บ Code
3. กด Add file > Upload files
4. อัปโหลดไฟล์ทั้ง 4 ไฟล์นี้ไว้ที่โฟลเดอร์รากเดียวกับ index.html เดิม
5. หาก GitHub ถามให้แทนที่ไฟล์ ให้แทนที่ manifest.webmanifest และ sw.js (index.html ใช้ไฟล์ในชุดนี้แทนได้)
6. กด Commit changes
7. รอ GitHub Pages เผยแพร่ แล้วเปิด:
   https://sopittasisaat1302-droid.github.io/-expense-5-categories/

วิธีติดตั้งบน Android:
1. เปิดลิงก์เว็บไซต์ด้วย Chrome
2. กดเมนู ⋮
3. เลือก ติดตั้งแอป หรือ เพิ่มไปยังหน้าจอหลัก
4. ยืนยันติดตั้ง

หมายเหตุ:
- PWA ต้องเปิดผ่าน HTTPS; GitHub Pages รองรับ HTTPS
- ข้อมูลรายจ่ายเก็บในเบราว์เซอร์ของอุปกรณ์นี้ ควรสำรอง JSON เป็นประจำ
- Service worker ช่วยแคชหน้าเว็บและไฟล์แอปเพื่อเปิดหน้าแอปได้เมื่อไม่มีอินเทอร์เน็ต
- การบันทึกข้อมูลยังเป็นข้อมูลในเครื่อง ไม่ได้ซิงก์ข้ามอุปกรณ์
