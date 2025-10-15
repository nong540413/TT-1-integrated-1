# 📦 Inventory Management System

> เว็บแอปพลิเคชันสำหรับจัดการสต็อกสินค้าสำหรับร้านค้าขนาดเล็ก พัฒนาขึ้นเพื่อเรียนรู้การสร้าง Fullstack Application ที่เชื่อมต่อระหว่าง Frontend, Backend, และ Database

โปรเจกต์นี้เป็นส่วนหนึ่งของวิชา `1-2568_INT222 Integrated Information Technology Project II` คณะเทคโนโลยีสารสนเทศและการสื่อสาร มหาวิทยาลัย `เทคโนโลยีพระจอมเกล้าธนบุรี`

---

## 🎯 เป้าหมายของโปรเจกต์ (Project Goals)

* เพื่อศึกษาและทำความเข้าใจสถาปัตยกรรมของเว็บแอปพลิเคชันสมัยใหม่
* เรียนรู้การสร้างและเชื่อมต่อ REST API ระหว่าง Frontend (Vue.js) และ Backend (Java)
* ฝึกฝนการทำงานร่วมกันเป็นทีมโดยใช้ Git และ Sourcetree ในการจัดการเวอร์ชันของโค้ด

---

## 📸 ภาพหน้าจอ (Screenshots)

| หน้าเข้าสู่ระบบ (Login Page) | หน้าแดชบอร์ด (Dashboard) |
| :----------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------- |
| ![ภาพหน้าจอสำหรับล็อกอินและสมัครสมาชิก](https://github.com/user-attachments/assets/6c1e6632-a93d-49ca-b58d-51f583b681f6) | ![ภาพหน้าจอแดชบอร์ดแสดงข้อมูลสินค้า](https://github.com/user-attachments/assets/398a847d-b2ce-42cb-a028-b24cf52c7289) |

---

## ✨ ฟีเจอร์หลัก (Key Features)

* **👤 User Authentication:** ระบบยืนยันตัวตนผู้ใช้งาน (สมัครสมาชิก, เข้าสู่ระบบ, ออกจากระบบ)
* **📦 Product Management (CRUD):** ระบบจัดการสินค้าที่สามารถ เพิ่ม (Create), อ่าน (Read), แก้ไข (Update), และลบ (Delete) ข้อมูลได้
* **🔍 Advanced Search & Filter:** ฟังก์ชันสำหรับค้นหาและกรองข้อมูลสินค้าจากชื่อหรือรหัสได้อย่างรวดเร็ว
* **🛒 Shopping Cart System:** (ถ้ามี) ระบบตะกร้าสินค้าสำหรับผู้ใช้งาน

---

## 🛠️ เทคโนโลยีที่ใช้ (Tech Stack)

| Category     | Technology                                   |
| :----------- | :------------------------------------------- |
| **Frontend** | Vue.js, Vite, Tailwind CSS                   |
| **Backend** | Java                                         |
| **Database** | MySQL                                        |
| **Tools** | Git, Sourcetree, Postman, VS Code, IntelliJ IDEA |

---

## ⚙️ การติดตั้งและใช้งาน (Getting Started)

### สิ่งที่ต้องมี (Prerequisites)

* [Node.js](https://nodejs.org/) (เวอร์ชัน 18.x หรือสูงกว่า)
* [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/) (เวอร์ชัน 17 หรือสูงกว่า)
* [Git](https://git-scm.com/) และ [Sourcetree](https://www.sourcetreeapp.com/)
* [MySQL Server](https://dev.mysql.com/downloads/mysql/)

### ขั้นตอนการติดตั้ง (Installation)

1.  **Clone a repository**
    ```sh
    git clone https://github.com/rk-v7/TT-1-integrated-1.git
    ```

2.  **ตั้งค่าฐานข้อมูล (Database Setup)**
    * สร้าง Database ใหม่ใน MySQL
    * Import ไฟล์ `.sql` (ถ้ามี) หรือตั้งค่า Schema ตามที่ Backend กำหนด

3.  **ตั้งค่า Backend (Java)**
    * เปิดโปรเจกต์ในโฟลเดอร์ `backend` ด้วย IntelliJ IDEA หรือ IDE ที่ใช้
    * แก้ไขไฟล์ `application.properties` เพื่อกำหนดค่าการเชื่อมต่อ Database
    * ทำการ Build และ Run โปรเจกต์

4.  **ตั้งค่าและรัน Frontend (Vue.js)**
    ```sh
    # เข้าไปที่โฟลเดอร์ client
    cd frontend

    # ติดตั้ง dependencies
    npm install

    # รัน Frontend development server
    npm run dev
    ```
    จากนั้นเปิดเบราว์เซอร์ไปที่ `http://localhost:5173` (หรือพอร์ตที่ Vite กำหนด)

---

## 🧑‍💻 ทีมผู้จัดทำ (Team Members)

| รหัสนักศึกษา | ชื่อ-นามสกุล | บทบาท (Role) | GitHub Profile |
| :--- | :--- | :--- | :--- |
| 66130500074 | Ratchapon Klinprathum | Fullstack Development | `https://github.com/oakrk` |
| 66130500078 | Witchapon Kangwanpanitch | Backend Development | `https://github.com/KarnZige` |
| 66130500098 | Thanawat Cauynukul | Frontend Development | `https://github.com/nong540413` |
