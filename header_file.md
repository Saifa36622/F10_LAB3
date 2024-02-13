# Header file หรือ file .h 

สำหรับ lab นี้ ไม่ถูกมุ่งเน้นไปทางการใช้ header file มาก เนื่องจากส่วนใหญ่ มีโค้ด template ที่อาจารย์ทำมาไไว้ให้แล้วส่วนหนึ่ง จึงจะอธิบายสั้นๆ โดยหากอยากรู้เพิ่มเติมสามารถกดเข้าไปที่ :[Github](https://github.com/Saifa36622/FIBO_LAB/blob/main/exlain_lab3/explain_basic_header_and_class.md) (อ่านแค่เรื่อง header พอๆ)

## อธิบายคร่าวๆ 

header file จะเป็นเหมือน libraly เราสามารถเขียน ไว้ที่ .h และ ดึงไปใช้ที่ file .cpp ได้
เช่น 

![code200](https://media.discordapp.net/attachments/784804366904590388/1073934615154278431/image.png)

จากรูปภาพ จะสังเกตได้ว่า code ทางซ้าย หรือ hi.h ได้มีการ สร้าง function ชื่อว่า yoloo และหากเรา include "hi.h"
เข้าไปที่ file .cpp ทางด้านขวา เราก็จะสามารถเรียกใช้ function ที่มีชื่อว่า yoloo ได้