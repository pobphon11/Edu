For Education System

เว็บแพลตฟอร์มคอร์สเรียนออนไลน์ (คอร์ส, บทเรียน, แบบทดสอบ, เวิร์กช็อป, ใบประกาศนียบัตร, สั่งซื้อ/ชำระเงิน, แดชบอร์ดผู้ดูแล)

โปรเจกต์ทีม 3 คน นี่คือ fork ของ ALtzaza/Edu เพื่อรวบรวมงานของผมไว้ใน branch pobphon (ประวัติ commit ต้นฉบับยังอยู่ครบ)

Tech Stack

React 19 + Vite · Node.js / Express 5 · MongoDB (Mongoose)

ส่วนที่ผมรับผิดชอบ (pobphon11)
วางโครงสร้าง backend, เขียน schema ตั้งต้น และเชื่อมฐานข้อมูล MongoDB (Mongoose)
REST API: คอร์ส, หมวดหมู่, section, ความคืบหน้าการเรียน (progress), การแจ้งเตือน
ระบบ authentication: login / register / forgot-reset password, AuthContext และ middleware ควบคุมสิทธิ์เข้าคอร์สตามสถานะการชำระเงิน
Frontend: หน้า Login, Forgot/Reset Password, Profile, Purchases, About Us และการเชื่อมหน้าเหล่านี้กับ API
ส่วนของเพื่อนร่วมทีม
@ALtzaza: Quiz, Quiz results, Certificates, Workshop, Lesson page, Admin dashboard
@NopparatSawatuea: หน้า frontend ชุดแรก, login/register/review เวอร์ชันแรก
ดูประวัติ commit ของผม

commits โดย pobphon11

วิธีรัน
cd backend && npm install แล้วสร้างไฟล์ .env (PORT, MONGO_URI, JWT_SECRET) ด้วยค่าของคุณเอง
npm start
อีก terminal: cd frontend && npm install && npm run dev
