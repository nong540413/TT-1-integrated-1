# 🌐 [ใส่ชื่อโปรเจกต์ที่น่าสนใจ เช่น "ระบบจัดการสต็อกสินค้า"]

> เว็บแอปพลิเคชันสำหรับจัดการสต็อกสินค้าสำหรับร้านค้าขนาดเล็ก พัฒนาขึ้นเพื่อเรียนรู้การเชื่อมต่อระหว่าง Frontend และ Backend

โปรเจกต์นี้เป็นส่วนหนึ่งของวิชา `[ใส่ชื่อวิชา]` คณะเทคโนโลยีสารสนเทศและการสื่อสาร มหาวิทยาลัย `[ใส่ชื่อมหาวิทยาลัย]`

---

## 📸 ภาพหน้าจอ (Screenshots)

| หน้าเข้าสู่ระบบ (Login Page) | หน้าแดชบอร์ด (Dashboard) |
| :---: | :---: |
| ![ภาพหน้าจอสำหรับล็อกอินและสมัครสมาชิก](https://github.com/user-attachments/assets/6c1e6632-a93d-49ca-b58d-51f583b681f6) | ![ภาพหน้าจอแดชบอร์ดแสดงข้อมูลสินค้า](https://github.com/user-attachments/assets/398a847d-b2ce-42cb-a028-b24cf52c7289) |

---

## ✨ ฟีเจอร์หลัก (Key Features)

* **👤 ระบบสมาชิก:** สมัครสมาชิก, เข้าสู่ระบบ และออกจากระบบ
* **📦 การจัดการสินค้า:** เพิ่ม, ลบ, แก้ไข และดูรายการสินค้าทั้งหมด
* **🔍 การค้นหา:** ค้นหาสินค้าจากชื่อหรือรหัสสินค้าได้อย่างรวดเร็ว
* **[เพิ่มฟีเจอร์อื่นๆ ของคุณ]:** เช่น ระบบตะกร้าสินค้า, การแสดงผลแบบ Real-time

---

## 🛠️ เทคโนโลยีที่ใช้ (Tech Stack)

| Category | Technology |
| :--- | :--- |
| **Frontend** | [ระบุเทคโนโลยี เช่น: Vue.js, Vite, Tailwind CSS] |
| **Backend** | [ระบุเทคโนโลยี เช่น: Java] |
| **Database** | [ระบุเทคโนโลยี เช่น:  MySQL] |
| **Tools** | Git, Sourcetree, Postman, VS Code |

---

## ⚙️ การติดตั้งและใช้งาน (Getting Started)

ทำตามขั้นตอนต่อไปนี้เพื่อรันโปรเจกต์บนเครื่องของคุณ

### สิ่งที่ต้องมี (Prerequisites)

* [Node.js](https://nodejs.org/) (เวอร์ชัน 18.x หรือสูงกว่า)
* [Git](https://git-scm.com/)
* [โปรแกรมจัดการฐานข้อมูล เช่น MongoDB Compass]

### ขั้นตอนการติดตั้ง (Installation)

1.  **Clone a repository**
    ```sh
    git clone [https://github.com/](https://github.com/)[your-github-username]/TT-1-INTEGRATED-1.git
    ```

2.  **เข้าไปยังโฟลเดอร์โปรเจกต์**
    ```sh
    cd TT-1-INTEGRATED-1
    ```

3.  **ติดตั้ง Dependencies สำหรับ Frontend และ Backend**
    ```sh
    # ติดตั้งฝั่ง Backend
    cd server
    npm install

    # กลับมาแล้วติดตั้งฝั่ง Frontend
    cd ../client
    npm install
    ```

4.  **ตั้งค่า Environment Variables**
    * สร้างไฟล์ `.env` ในโฟลเดอร์ `server`
    * คัดลอกเนื้อหาจาก `.env.example` มาวาง แล้วใส่ค่าที่ถูกต้อง
    ```
    PORT=5000
    DATABASE_URL="your_mongodb_connection_string"
    JWT_SECRET="your_jwt_secret_key"
    ```

5.  **รันโปรเจกต์ (เปิด Terminal 2 หน้าต่าง)**
    ```sh
    # Terminal 1: รัน Backend (จากโฟลเดอร์ server)
    npm start

    # Terminal 2: รัน Frontend (จากโฟลเดอร์ client)
    npm start
    ```
    จากนั้นเปิดเบราว์เซอร์ไปที่ `http://localhost:3000`

---

## 🧑‍💻 ทีมผู้จัดทำ (Team Members)

| รหัสนักศึกษา | ชื่อ-นามสกุล | บทบาท (Role) | GitHub |
| :--- | :--- | :--- | :--- |
| 66130500074 | Ratchapon Klinprathum | Fullstack Development | `[@username]` |
| 66130500078 | Witchapon Kangwanpanitch | Backend Development | `[@username]` |
| 66130500098 | Thanawat Cauynukul | Frontend Development | `[@username]` |
