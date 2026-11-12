# 🦆 Dual-Camera Real-Time Duck Detection and Counting System

โปรเจกต์ระบบตรวจจับและนับจำนวนเป็ดแบบเรียลไทม์ด้วยกล้อง 2 ตัว (BD532 Term Project)

## 📁 โครงสร้างองค์ประกอบโปรเจกต์ (Component Documentation)
* `app.py`: หน้าจอเว็บ Dashboard (Streamlit) สำหรับแสดงผลสตรีมวิดีโอจากกล้อง 2 ตัวและตัวเลขสรุปยอดแบบ Real-time
* `camera_stream.py`: โมดูลจัดการการอ่านภาพจากกล้องหลายตัวแบบ Multi-threading ป้องกันอาการภาพกระตุก
* `requirements.txt`: รายชื่อไลบรารี Python และแพ็กเกจทั้งหมดที่จำเป็นต้องติดตั้ง

## ⚙️ ขั้นตอนการติดตั้ง (Setup Instructions)
1. โคลนหรือดาวน์โหลดโปรเจกต์นี้ลงเครื่องคอมพิวเตอร์
2. เปิด Terminal หรือ Command Prompt ในโฟลเดอร์โปรเจกต์ แล้วติดตั้งไลบรารีด้วยคำสั่ง:
   ```bash