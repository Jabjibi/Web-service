# 🌐 Web Technology and Web Services Final Project  

- 📚 **Subject:** Web Technology and Web Services  
- 🏢 **Project Detail:** ระบบจองห้องพัก (Room Reservation)  
- 👥 **Type:** Group Project (โปรเจกต์กลุ่ม)  

---

## 🎯 Objective (วัตถุประสงค์)  
เรียนรู้เกี่ยวกับ **Front-end และ Back-end** วิธีเชื่อมต่อฐานข้อมูล และเข้าใจแนวคิดเกี่ยวกับ **Web Technology และ Web Services**  

---

## 🚀 How to start (วิธีเริ่มต้นใช้งาน)  

### 📌 **Requirement (เครื่องมือที่ต้องใช้)**  
✅ Visual Studio Code  
✅ Extensions **'Vetur'** ใน Visual Studio Code  
✅ Git  
✅ Node.js  
✅ PgAdmin  
✅ HeidiSQL (ถ้าต้องการแก้ไขฐานข้อมูล)  

---

## 1️⃣ Clone this repo  
```cmd
git clone https://github.com/Jabjibi/Web-service.git
```
📌 **หมายเหตุ:** อย่าลืมติดตั้ง **Vetur** ใน VS Code และ **Git**  

---

## 2️⃣ ติดตั้ง **node_modules** ในโฟลเดอร์ `frontend`  
```cmd
npm i 
```
📌 **หมายเหตุ:** อย่าลืมติดตั้ง **Node.js** ก่อน  

---

## 3️⃣ ติดตั้ง **PgAdmin**  
📌 สำหรับใช้จัดการฐานข้อมูล PostgreSQL  

---

## 4️⃣ ตั้งค่า Role **'dev'**  
🔹 เปิด **PgAdmin** > เชื่อมต่อเซิร์ฟเวอร์  
🔹 คลิกขวาที่ **Login/Group Roles** > **Create** > **Login/Group Roles**  
🔹 ไปที่ **General** > ตั้งชื่อ **dev**  
🔹 ไปที่ **Definition** > ตั้งรหัสผ่านเป็น `1234`  
🔹 ไปที่ **Privileges** > ติ๊กถูกที่ **Can login?** > **Save**  

---

## 5️⃣ Restore Database  
🔹 คลิกขวาที่ **Database** > **Create** > **Database**  
🔹 ตั้งชื่อฐานข้อมูลเป็น **'NOVA_GALAXY'**  
🔹 คลิกขวาที่ฐานข้อมูลที่สร้าง > **Restore** ไฟล์จากโฟลเดอร์ `database`  

---

## 6️⃣ ตั้งค่า **Security**  
🔹 คลิกขวาที่ฐานข้อมูลที่สร้าง > **Properties**  
🔹 ไปที่ **Security** > คลิก **'+'** ที่ **Privileges**  
🔹 ตั้งค่า **Grantee** เป็น `dev`  
🔹 ตั้งค่า **Privileges** > ติ๊ก **✓** ที่ **Connect** > **Save**  

---

## 7️⃣ Grant Privileges (กำหนดสิทธิ์ให้ตาราง)  
🔹 คลิกขวาที่ **Table** ที่ restore มา  
🔹 เลือก **Grant Wizard**  
🔹 ดูตัวอย่างจากภาพด้านล่าง  
![image](https://github.com/user-attachments/assets/0ca173e6-9bcf-4a6a-916e-0a2d809456ba)  
![image](https://github.com/user-attachments/assets/bce7d7a6-a8c8-4d15-8220-e937a433678f)  

---

## 8️⃣ ติดตั้ง **HeidiSQL** (ถ้าต้องการแก้ไขฐานข้อมูล)  
![image](https://github.com/user-attachments/assets/da111da5-ab25-4bd3-925c-fa0a87b80885)  
![image](https://github.com/user-attachments/assets/07e20d0c-6ed8-49d5-b7aa-a509dc9f13fe)  

---

## ▶️ **Run โปรเจกต์**  

### 🎨 Run Frontend  
```cmd
npm run serve
```

### ⚙️ Run Backend  
```cmd
npm start
```

---
