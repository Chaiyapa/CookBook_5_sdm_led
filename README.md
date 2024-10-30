# Example นี้แสดงวิธีการใช้ Sigma-Delta ไดรเวอร์เพื่อสร้างเอาต์พุตแบบมอดูเลตบนขา GPIO ซึ่งหากเชื่อมต่อ LED หรือตัวควบคุมแสงพื้นหลังของจอ LCD เข้ากับขา GPIO นี้ คุณจะสังเกตเห็นความสว่างของ LED ที่ค่อยๆ เพิ่มขึ้นและลดลง (สว่างขึ้นและหรี่ลง)

เริ่มจากการเลือกใน Show Example
![image](https://github.com/user-attachments/assets/b17e825a-3100-452b-9cad-0862885044e2)

กด Create project แล้วจะพบหน้าต่างนี้
![image](https://github.com/user-attachments/assets/80be8aca-d370-4cf8-8f43-6d4014e4c6cb)

ให้เราเลือก port ให้ตรงกับบอร์ด esp เสร็จแล้วให้ Build และ Flash ลงบอร์ด

เมื่อ Flash เสร็จแล้วจะพบข้อความประมาณนี้ดังนี้

![image](https://github.com/user-attachments/assets/e9db9bb6-35dc-437f-b034-5691828cfc92)


ต่อ gpio ที่ ขา 0 ที่led 
| gpio 0 |
|------- | 

![image](https://github.com/user-attachments/assets/f740e479-9bb8-4cb0-9101-0738fc976c0c)

สังเกตที่led ไฟจะค่อยๆสว่างขึ้นและค่อยดับลง

สามารถเปลี่ยน gpio ได้ที่ตรงนี้

![image](https://github.com/user-attachments/assets/f1ad9f57-2cb7-41ac-8479-853dc20a8d02)


