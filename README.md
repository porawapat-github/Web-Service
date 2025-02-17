# Web Technology and Web Services Final Project 
- Subject : Web Technology and Web Services
- Detail : Room Reservation
- Type : Group Project<br>

- วิชาเรียน : เว็บเทคโนโลยีและเว็บบริการ
- รายละเอียด : การจองห้องพัก
- ประเภท : โครงการกลุ่ม<br>

# Objective
Learn about Front-end and Back-end How to connect database understand concept about Web Technology and Web Services.<br>

เรียนรู้เกี่ยวกับ Front-end และ Back-end วิธีการเชื่อมต่อฐานข้อมูล ทำความเข้าใจแนวคิดเกี่ยวกับเทคโนโลยีเว็บและบริการเว็บ<br>

# How to start
### requirement
  - Visual Studio Code
  - Install extensions ' vetur ' in visual studio code
  - Git
  - Node.js
  - PgAdmin
  - HeidiSQL (If you want to edit database)

## 1. Clone this repo
```cmd
git clone https://github.com/DevPeeramate/Web_Technology.git
```
Note : Don't forget Install extensions ' vetur ' in visual studio code and Install git<br>
หมายเหตุ : อย่าลืมติดตั้งส่วนขยาย ' vetur ' ใน Visual Studio Code และติดตั้ง git

<br>

## 2. Install node_modules in folder ' fontend '
```cmd
npm i 
```
Note : Don't forget Install Node.js<br>
หมายเหตุ : อย่าลืมติดตั้ง Node.js<br> 

## 3.Install PgAdmin

<br>

## 4.Set Role 'dev'
Open PgAdmin > Connect to server > Right Click at Login/Group Roles > Create > Login/Group Roles > General > Set Name : dev > Definition > Set Password : 1234 > Privileges > Set On Can login? > save<br>

เปิด PgAdmin > เชื่อมต่อกับเซิร์ฟเวอร์ > เข้าสู่ระบบ/กลุ่ม > สร้าง > เข้าสู่ระบบ/กลุ่ม > ทั่วไป > ตั้งชื่อ: dev > คำจำกัดความ > ตั้งรหัสผ่าน: 1234 > สิทธิ์ > ตั้งค่าเป็น สามารถเข้าสู่ระบบได้หรือไม่ > บันทึก<br>


## 5.Restore Database
Right Click at Database > Create > Database > Set Database ' NOVA_GALAXY ' > Right Click at Database or your databese > Restore file in folder ' database'<br> 
คลิกขวาที่ฐานข้อมูล > สร้าง > ฐานข้อมูล > ตั้งค่าฐานข้อมูล ' NOVA_GALAXY ' > คลิกขวาที่ฐานข้อมูลหรือฐานข้อมูลของคุณ > เรียกคืนไฟล์ในโฟลเดอร์ ' database'<br>

## 6.Set Security 
Right Click at your database that you create > Properties > Security > Click '+' at Privileges > Set Grantee 'dev' > Set Privileges '✓' at Connect > Save<br>
คลิกขวาที่ฐานข้อมูลที่คุณสร้าง > คุณสมบัติ > ความปลอดภัย > คลิก '+' ที่สิทธิ์ > ตั้งค่าผู้รับสิทธิ์ 'dev' > ตั้งค่าสิทธิ์ '✓' ที่เชื่อมต่อ > บันทึก<br>

## 7.Grant Privileges
Right Click at 'Table' that you restore > Grant Wizard > Use the image as a reference.<br>
คลิกขวาที่ 'ตาราง' ที่คุณคืนค่า > ตัวช่วยสร้างการอนุญาต > ใช้รูปภาพเป็นข้อมูลอ้างอิง
![image](https://github.com/user-attachments/assets/0ca173e6-9bcf-4a6a-916e-0a2d809456ba)
![image](https://github.com/user-attachments/assets/bce7d7a6-a8c8-4d15-8220-e937a433678f)

## 8.Install HeidiSQL (If you want to edit database)
![image](https://github.com/user-attachments/assets/da111da5-ab25-4bd3-925c-fa0a87b80885)
![image](https://github.com/user-attachments/assets/07e20d0c-6ed8-49d5-b7aa-a509dc9f13fe)

## 9. Run in folder ' frontend '
```cmd
npm run serve
```

## 10. Run in folder ' backend '
```cmd
npm start
```

 
