# **EE495: Selected Topic in Electrical Engineering**
ผู้สอน รศ.ดร.ณัฐภพ นิ่มปิติวัน  ผศ.ดร.รุจิพรรณ สัมปันณา
## **📌 บรรยายรายวิชา**
รายวิชานี้มุ่งเน้นการพัฒนาทักษะทางวิศวกรรมไฟฟ้าและระบบควบคุม ผ่านการออกแบบและพัฒนาโดรน นักศึกษาจะได้เรียนรู้ตั้งแต่ **การออกแบบ PCB, การประกอบอุปกรณ์, การเขียนโปรแกรมควบคุมด้วย STM32F103C8 และ Arduino IDE, การสื่อสารระหว่างอุปกรณ์, ไปจนถึงการทดสอบการบิน** 

โดยเนื้อหาของรายวิชาจะช่วยให้นักศึกษาสามารถ **อธิบายความรู้เกี่ยวข้องกับการจัดการพลังงานของอุปกรณ์ (CLO1) เลือกใช้เทคโนโลยีที่เหมาะสม (CLO2), แก้ไขปัญหาที่เกิดขึ้นระหว่างพัฒนา (CLO3)** และสร้างโครงการต้นแบบที่สามารถทำงานได้จริง

---

## **📌 แผนการสอนและกิจกรรมการเรียนรู้**

| **สัปดาห์** | **หัวข้อ** | **กิจกรรมการเรียนรู้** | **CLO** |
|---|---|---|---|
| **1-2** | บทนำเกี่ยวกับการพัฒนาโดรนและการกำหนดแนวทางโครงงาน | 🔹 *Group Discussion*: วิเคราะห์โครงสร้างโดรนและระบบควบคุม <br> 🔹 *Workshop*: ติดตั้ง Arduino IDE และกำหนดค่า STM32F103C8 <br> 🔹 *Assignment*: ค้นคว้าเกี่ยวกับ STM32 และการใช้งานเบื้องต้น | CLO2 |
| **3-4** | การออกแบบ PCB และเตรียมไฟล์สำหรับการผลิต | 🔹 *Workshop*: ออกแบบวงจรและ PCB ด้วย Easyeda <br> 🔹 *Project*: ออกแบบและสร้างไฟล์ Gerber พร้อมส่งผลิต <br> 🔹 *Assignment*: วิเคราะห์ข้อดี-ข้อเสียของวงจร PCB ที่ออกแบบ |CLO1, CLO2 |
| **5** | พื้นฐานการเขียนโปรแกรม STM32 บน Arduino IDE | 🔹 *Coding Lab*: เขียนโปรแกรมควบคุม GPIO, PWM, ADC <br> 🔹 *ทดลอง*: ควบคุม LED และอ่านค่าจากปุ่มกดด้วย STM32 <br> 🔹 *Assignment*: แก้ปัญหาการเขียนโค้ดที่ผิดพลาดจากตัวอย่าง | CLO2 |
| **6** | การสื่อสารระหว่าง STM32 กับอุปกรณ์อื่น | 🔹 *Coding Lab*: ทดลองสื่อสารผ่าน UART, I2C, และ SPI <br> 🔹 *Project*: เชื่อมต่อ STM32 กับ IMU Sensor และอ่านค่าการเคลื่อนไหว <br> 🔹 *Discussion*: วิเคราะห์วิธีการสื่อสารที่เหมาะสมกับโดรน | CLO2 |
| **7** | การควบคุมมอเตอร์และ ESC | 🔹 *Lab Experiment*: ทดสอบการควบคุมมอเตอร์ผ่าน ESC โดยใช้ PWM <br> 🔹 *Project*: สร้างระบบควบคุมความเร็วของมอเตอร์ <br> 🔹 *Assignment*: วิเคราะห์พฤติกรรมของมอเตอร์เมื่อปรับค่า PWM | CLO1,CLO2 |
| **8-9** | การประกอบและทดสอบ PCB | 🔹 *Hands-on Activity*: นักศึกษาประกอบ PCB และบัดกรีอุปกรณ์ <br> 🔹 *Testing Lab*: ตรวจสอบสัญญาณไฟฟ้าและการทำงานของวงจร <br> 🔹 *Assignment*: รายงานผลการทดสอบ PCB และแนวทางแก้ไขปัญหา | CLO3 |
| **10** | การพัฒนา PID Controller สำหรับโดรน | 🔹 *Coding Lab*: ทดลองเขียนโค้ด PID Controller บน STM32 <br> 🔹 *Simulation*: ทดสอบ PID Tuning ผ่าน MATLAB หรือ Python <br> 🔹 *Project*: ปรับค่า PID ให้เหมาะสมกับการควบคุมเสถียรภาพโดรน | CLO2 |
| **11** | การเชื่อมต่อและสื่อสารไร้สายกับโดรน | 🔹 *Workshop*: เชื่อมต่อ STM32 กับ FS-i6 Receiver <br> 🔹 *Hands-on Activity*: ทดลองรับ-ส่งข้อมูลควบคุมโดรนผ่าน FS-i6 Remote Controller <br> 🔹 *Assignment*: วิเคราะห์ประสิทธิภาพของ FS-i6 ในการควบคุมโดรน | CLO2 |
| **12-13** | การทดสอบการบินและแก้ไขปัญหา | 🔹 *Testing & Debugging*: ทดลองบินโดรนแบบ Manual และ Assisted Mode <br> 🔹 *Project*: เก็บข้อมูลการบินและปรับปรุงเสถียรภาพ <br> 🔹 *Discussion*: วิเคราะห์ปัญหาที่เกิดขึ้นและแนวทางแก้ไข | CLO3 |
| **14** | การนำเสนอและสรุปผลโครงการ | 🔹 *Final Presentation*: นักศึกษาแต่ละกลุ่มนำเสนอผลงาน <br> 🔹 *Peer Review*: วิพากษ์วิจารณ์โครงการของกลุ่มอื่น <br> 🔹 *Final Report*: รายงานสรุปการพัฒนาและปัญหาที่พบ |CLO1, CLO2, CLO3 |

---

## **📌 การประเมินผล**

| **องค์ประกอบ** | **CLO** | **น้ำหนัก (%)** | **รายละเอียด** |
|---|---|---|---|
| **แบบทดสอบความรู้พื้นฐาน** | CLO1, CLO2 | 15% | แบบทดสอบสั้น ๆ ในช่วงสัปดาห์ที่ 1-7 |
| **โครงงานออกแบบและสร้าง PCB** | CLO1, CLO2 | 20% | การออกแบบและประกอบ PCB |
| **การเขียนโค้ดควบคุมมอเตอร์และ PID Controller** | CLO3 | 30% | ทดสอบและปรับค่า PID, ควบคุม ESC |
| **การทดสอบการบินและการแก้ไขปัญหา** | CLO3 | 20% | ทดสอบโดรนในสนามบินจริง |
| **การนำเสนอและสรุปโครงการ** | CLO1, CLO2, CLO3 | 15% | Final Presentation & Report |

---

## **📌 ความสอดคล้องกับ CLO ทั้งหมด**
✅ **CLO1 (เลือกใช้วิธีการ)** → มีระดับความสำคัญสูงใน **การออกแบบ เลือกใช้อุปกรณ์ และแบตเตอรี่ ** (สัปดาห์ 3-4, 8-11)   
✅ **CLO2 (เลือกใช้วิธีการ)** → มีระดับความสำคัญสูงใน **การออกแบบระบบ, การเขียนโปรแกรม, และการเลือกอุปกรณ์** (สัปดาห์ 1-7, 10-11)  
✅ **CLO3 (แก้ปัญหาขณะพัฒนา)** → มีระดับความสำคัญสูงใน **การประกอบ PCB, ทดสอบบิน, และแก้ปัญหาระหว่างการพัฒนา** (สัปดาห์ 8-9, 12-13)  

📌 รายวิชานี้ช่วยให้ **นักศึกษาสามารถเลือกใช้เทคโนโลยีที่เหมาะสมและแก้ไขปัญหาระหว่างการพัฒนาโดรนได้อย่างเป็นระบบ** 🎯
