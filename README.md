# 📱 PhoneSphere - E-commerce Website

> เว็บแอปพลิเคชัน E-commerce สำหรับซื้อขายโทรศัพท์มือถือ ที่รองรับทั้งฝั่งผู้ซื้อ (Buyer) และผู้ขาย (Seller) พัฒนาขึ้นเพื่อเรียนรู้การสร้าง Fullstack Application ที่เชื่อมต่อระหว่าง Frontend, Backend, และ Database

โปรเจกต์นี้เป็นส่วนหนึ่งของวิชา `1-2568_INT222 Integrated Information Technology Project II` คณะเทคโนโลยีสารสนเทศและการสื่อสาร มหาวิทยาลัยเทคโนโลยีพระจอมเกล้าธนบุรี

---

## 🚀 Live Demo & Screenshots

### **[👉 คลิกลิงก์เพื่อดูเว็บไซต์](https://intproj24.sit.kmutt.ac.th/tt1/)**

| หน้าแสดงสินค้าสำหรับผู้ซื้อ (Buyer View) | หน้าจัดการสินค้าสำหรับผู้ขาย (Seller View) |
| :----------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------- |
| ![ภาพหน้าจอสำหรับล็อกอินและสมัครสมาชิก](https://github.com/user-attachments/assets/6c1e6632-a93d-49ca-b58d-51f583b681f6) | ![ภาพหน้าจอแดชบอร์ดแสดงข้อมูลสินค้า](https://github.com/user-attachments/assets/398a847d-b2ce-42cb-a028-b24cf52c7289) |

---

## ✨ ฟีเจอร์หลัก (Key Features)

แอปพลิเคชันถูกออกแบบมาให้รองรับผู้ใช้งานสองกลุ่มหลัก:

### 🛒 สำหรับผู้ซื้อ (Buyer)
* **เลือกดูและค้นหาสินค้า:** สามารถดูรายการโทรศัพท์มือถือทั้งหมด พร้อมทั้งค้นหาและกรองสินค้าตามที่ต้องการ
* **ระบบตะกร้าสินค้า:** เพิ่ม, ลบ, และปรับจำนวนสินค้าในตะกร้าก่อนทำการสั่งซื้อ
* **การสั่งซื้อ (Order Placement):** ยืนยันการสั่งซื้อสินค้าจากในตะกร้า
* **ประวัติการสั่งซื้อ:** ดูรายการสั่งซื้อย้อนหลังของตนเอง
* **ระบบสมาชิก:** สมัครสมาชิก, เข้าสู่ระบบ และจัดการข้อมูลส่วนตัว

### 💼 สำหรับผู้ขาย (Seller / Admin)
* **ระบบจัดการสินค้า (CRUD):** เพิ่ม, ลบ, แก้ไขข้อมูล และจัดการสต็อกโทรศัพท์มือถือในร้านค้า
* **ระบบจัดการคำสั่งซื้อ (Order Management):** ดูรายการคำสั่งซื้อที่เข้ามาจากผู้ซื้อ และจัดการสถานะของออเดอร์

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

1.  **Clone the repository**
    ```sh
    git clone [https://github.com/rk-v7/TT-1-integrated-1.git](https://github.com/rk-v7/TT-1-integrated-1.git)
    ```

2.  **ตั้งค่าฐานข้อมูล (Database Setup)**
    * สร้าง Database ใหม่ใน MySQL
    * Import ไฟล์ `.sql` (ถ้ามี) เพื่อสร้างตารางที่จำเป็น

3.  **ตั้งค่าและรัน Backend (Java)**
    * เปิดโปรเจกต์ในโฟลเดอร์ `backend` ด้วย IntelliJ IDEA
    * แก้ไขไฟล์ `application.properties` เพื่อกำหนดค่าการเชื่อมต่อ Database ให้ถูกต้อง
    * Build และ Run โปรเจกต์

4.  **ตั้งค่าและรัน Frontend (Vue.js)**
    ```sh
    # เข้าไปที่โฟลเดอร์ frontend
    cd frontend

    # ติดตั้ง dependencies
    npm install

    # รัน Frontend development server
    npm run dev
    ```
    จากนั้นเปิดเบราว์เซอร์ไปที่ `http://localhost:5173` (หรือพอร์ตที่ Vite กำหนด)

---

## 🧑‍💻 ทีมผู้จัดทำ (Team Members)

| รหัสนักศึกษา | ชื่อ-นามสกุล                 | บทบาท (Role)            | GitHub Profile                               |
| :----------- | :-------------------------- | :---------------------- | :------------------------------------------- |
| 66130500074  | Ratchapon Klinprathum       | Fullstack Development   | [@oakrk](https://github.com/oakrk)           |
| 66130500078  | Witchapon Kangwanpanitch    | Backend Development     | [@KarnZige](https://github.com/KarnZige)     |
| 66130500098  | Thanawat Cauynukul          | Frontend Development    | [@nong540413](https://github.com/nong540413) |
