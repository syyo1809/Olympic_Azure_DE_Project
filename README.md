# Olympic_Azure_DE_Project
Dataset : [Olympic Dataset](https://github.com/darshilparmar/tokyo-olympic-azure-data-engineering-project/tree/main/data)<br>
&nbsp;<br>
&nbsp;<br>
Architecture
![Olympic Azure Architecture](https://github.com/syyo1809/Olympic_Azure_DE_Project/assets/83905993/6aaab565-18cb-480d-a47f-e36f3d0d7515)
&nbsp;<br>
&nbsp;<br>
สร้าง Storage Account เพื่อไว้เก็บข้อมูลดิบและรอเก็บข้อมูลที่จะต้องนำไปทำความสะอาด
![Storage account](https://github.com/syyo1809/Olympic_Azure_DE_Project/assets/83905993/ecd97875-68c8-41cf-8c2c-0b4d4b683cf3)
&nbsp;<br>
&nbsp;<br>
ใช้ Data Factory เก็บข้อมูลดิบมาจาก Github มาแล้วนำไปเก็บไว้ที่ โฟลเดอร์ raw data ที่สร้างไว้ใน Containers
![raw data](https://github.com/syyo1809/Olympic_Azure_DE_Project/assets/83905993/f9b18a6d-9099-4098-b7a0-c1fc18837c25)
&nbsp;<br>
&nbsp;<br>
สร้าง App registration ขึ้นมาเพื่อ ทำการเชื่อมต่อระหว่าง Databricks กับ Data lake ที่เก็บข้อมูลดิบไว้เพื่อเตรียมการแปลงข้อมูลต่อไป
![app01](https://github.com/syyo1809/Olympic_Azure_DE_Project/assets/83905993/faa38f81-9803-4247-ba3b-0f570140c33f)
&nbsp;<br>
&nbsp;<br>
หลังจากที่เชื่อมต่อได้แล้วก็ทำการแปลงข้อมูล และ นำข้อมูลที่แปลงแล้วไปเก็บไว้ในโฟลเดอร์ Transformed data ที่สร้างไว้แล้ว
![transform databrick](https://github.com/syyo1809/Olympic_Azure_DE_Project/assets/83905993/821bc33d-ed92-4252-b08f-cc10e36088be)
![transformed data](https://github.com/syyo1809/Olympic_Azure_DE_Project/assets/83905993/d676d5f2-1d0f-4635-a8bc-961a1663599e)
&nbsp;<br>
&nbsp;<br>
สร้าง Synapse Analytic เพื่อนำข้อมูลไปวิเคราะห์หรือนำไปสร้างแดชบอร์ดต่อไป
![analytic in synapse](https://github.com/syyo1809/Olympic_Azure_DE_Project/assets/83905993/3c69fefb-df06-4c43-b06e-e60a5b5ee1dd)
&nbsp;<br>
&nbsp;<br>
