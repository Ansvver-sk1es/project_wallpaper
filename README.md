# Wallpaper Studio (Android APK)

โครงสร้างโปรเจกต์
- `www/index.html` : เว็บแอปของคุณ (แก้ให้รองรับแอป Android แล้ว)
- `capacitor.config.json` : ชื่อแอป / appId
- `.github/workflows/build-apk.yml` : สคริปต์สร้าง APK อัตโนมัติ
- `assets/icon-only.png` : ไอคอนแอป (เปลี่ยนเป็นของคุณได้ ขนาด 1024x1024)

วิธีใช้ย่อ: สร้าง repo บน GitHub -> push โฟลเดอร์นี้ขึ้นไป -> แท็บ Actions -> รอจนเขียว -> ดาวน์โหลด APK จาก Artifacts
