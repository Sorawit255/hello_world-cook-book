# แนวทางการทำงาน ESP32 hello_world cook book
## 1. ระบุตัวอย่างที่ใช้ ว่าเอามาจากตัวอย่างไหน
- เลือกโปรเจค hello_world จาก show examples แล้วกด create
![image](https://github.com/user-attachments/assets/87401d11-99bd-4d5f-94c0-a2b6c050997d)

## 2. ระบุว่า จะแก้ไขตรงไหนบ้าง เพื่ออะไร 
- สามารถแก้ไขที่ ฟังก์ชัน app_main ได้ printf("Hello world!\n"); หรือกำหนดฟังก์ชันให้แสดงข้อความแล้วเรียกใช้ผ่าน main ให้มาแสดงที่ terminal
![image](https://github.com/user-attachments/assets/bb9bbf76-6c16-4ea5-b12b-72b7300af98b)

## 3. แสดงขั้นตอนการทำ project
- เพิ่มฟังก์ชัน test ให้แสดงข้อความ hello world ที่ terminal ทุกๆ 1 วิและเรียกใช้งานฟังก์ชัน test ที่ main(จะลบออกให้หมดก็ได้เหลือแค่เรียกใช้งานฟังก์ชัน จะแสดงข้อความ ทุกๆ 1 วิ)
- แต่ของโปรเจคเดิมหลังจากแสดงแล้วจะให้รีสตาร์ททุกๆ10วิแล้วแสดง hello world ใหม่
![image](https://github.com/user-attachments/assets/5367c3b4-e6da-4f63-a270-a0754090563f)

## 4. แสดงผลการทำ project
- แสดงผลตามโค้ดด้านบน
![image](https://github.com/user-attachments/assets/11bbbfdc-d309-4c5f-a0be-7ddb040773c7)


## 5. สรุปผลการทำ project 
- โปรเจคนี้เป็นโปรเจคพื้นฐานสำหรับผู้เริ่มต้น เน้นการสร้าง Task พื้นฐาน โดยให้แสดงออกมาทาง terminal/ Serial Monitor
