## การทดลอง
# Ex1
เขียนโปรแกรมแกรม platform io ลง microcontroller ใช้โปรแกรม 01 การทำงานแบ่งเป็น set กับ loop
เมื่อโหลดเสร็จดูผลลัพธ์ได้โดยใช้ pio device monitor

# Ex2
Run program บน microcontroller esp 01
เสียบ esp01 ใส่ usb port และอัพโหลดโปรแกรมลง  
  
# Ex3 run
Run program ทดลองการ output สัญญาณออกไปภายนอก
Output port - ที่ port0
Input port - ที่ port 1
ใช้ adapter คั่นและค่อยเสียบ microcontroller ลงไป
คี่ on 1
คู่ off 0
ผลลัพธ์ดูที่หลอดไฟทดลอง

# Ex4 run
นำสัญญาณ input เข้ามาใน microcontroller
• set up - port 0 input สีขาว
- port 2 output สีเหลือง
• loop 1 ไฟดับ
0 ไฟติด
อัพโหลดและดูผล monitor  
  
# Ex 5
สร้าง web server ผ่าน ไวไฟ
โดยใส่ชื่อไวไฟและที่อยู่
จากนั้นกดอัพโหลด และเสียบ microcontroller กับ USB port
ใช้เว็บบราวเซอร์ทดลองโปรแกรม

# Ex 6
การทดลองที่6ต่างจากการทดลองที่5ตรงที่เราไม่ต้องสร้างขึ้นมาเองแต่เชื่อมกับไวไฟที่มีอยู่แล้ว
โดย กำหนดชื่อไวไฟเอง กำหนดIP address เอง เกทเวย์ และ subnet
เตรียม web serve
สร้างที่อยู่ไอพีกำหนดรหัสผ่านให้เรียบร้อย และrun program อัพลง microcontroller อัพเสร็จสามารถทดสอบโปรแกรมได้โดยใช้คอมเชค
