# Contributing Guidelines

ขอบคุณที่มาช่วยพัฒนาส่วนเสริมนี้นะครับ ♥

## 📋 ข้อปฏิบัติ

- หากท่านกำลังจะทำฟีเจอร์ใหม่ กรุณาจองหรือเปิด [Issue](https://github.com/rootEnginear/KMUTT-PEP-Enhancer/issues) ก่อนเพื่อจะได้สกรีนงานเบื้องต้นก่อนลงมือทำ
- Branch `master` นั้นจะใช้สำหรับในการ publish ตัวส่วนเสริมเท่านั้น **กรุณาส่ง Pull Request ใน branch `dev` เท่านั้น**
- โปรเจกต์นี้ใช้ Vue.js กับ ES6 ก่อนส่ง Pull Request กรุณาตรวจสอบก่อนว่า Syntax ที่ใช้เป็น ES6 ด้วยคำสั่ง `npm run es-check`
- กรุณาอย่าลืม minify ไฟล์หลังแก้ไขด้วยคำสั่ง `npm run build` ทุกครั้ง เพราะส่วนเสริมจะชี้ไปที่ไฟล์ที่ minify แล้ว
- ถ้าหากท่านเพิ่มไลบรารีตัวใหม่ลงไป ขอให้ใช้เป็นเวอร์ชันที่ minified แล้วนะครับ
- หากมีการเปลี่ยนแปลง User Interface ใดๆ กรุณาแนบภาพ Before/After มาใน Pull Request ด้วย

## 🛠 Development Setup

หลังจาก clone แล้ว ให้ทำการติดตั้ง packages ด้วยคำสั่ง:

```bash
$ npm install
```

คำสั่งที่มี:

```bash
# minify ไฟล์ CSS และ JS
$ npm run build

# minify แค่ไฟล์ CSS
$ npm run build-css

# minify แค่ไฟล์ JS
$ npm run build-js

# ตรวจสอบว่า JS ที่เขียนเป็น ES6 หรือไม่
$ npm run es-check
```
