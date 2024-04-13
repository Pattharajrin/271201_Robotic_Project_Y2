# 271201_Robotic_Project_Y2

Project "หุ่นยนต์เก็บลูกเทนนิส"

เนื่องจากในสนามเทนนิสจะมีการใช้ลูกเทนนิสเยอะมาก และในสนามมีการตีลูกที่แรงมาก ซึ่งอาจทำให้เกินอันตรายได้หากไม่ระมัดระวัง
ดังนั้นจึงออกแบบเป็นหุ่นยนต์เก็บลูกเทนนิสที่มีรถเข็นเก็บลูกเทนนิสด้านหลังเพื่อให้สะดวกสบายต่อการนำไปใช้งาน และไม่เป็นอันตรายต่อบุคคลที่ต้องการเก็บลูกเทนนิส

ซึ่งในตัวหุ่นยนต์เก็บลูกเทนนิสจะประกอบไปด้วย 

1)ตัวหุ่นยนต์ติดล้อที่ทำหน้าที่รองรับแขนกล และเคลื่อนที่ และมีตะขอเกี่ยวกับตัวรถเข็นเพื่อให้รถเข็นสามารถเคลื่อนที่ไปด้วยได้

2)รถเข็น ทำหน้าที่เก็บรองรับลูกเทนนิสไว้ และสามารถนำออกไปใช้งานได้

3)แขนกล ทำหน้าที่หยิบลูกเทนนิสจากพื้นไปใส่ในรถเข็น ซึ่งประกอบด้วย arm 3 ส่วน และ grip 2 อัน โดยที่แบบควบคุมข้อต่อของ arm1 = "revolute" ,  arm2 = "revolute" , arm3 = "revolute" ,  grip1 = "revolute" ,  grip2 = "revolute"

4)ล้อ ทำหน้าที่เคลื่อนที่ไปตามพื้น โดยที่แบบควบคุมข้อต่อของทั้ง 4 ล้อ คือ "continuous"


ผลการทดลองล่าสุด "ยังไม่สามารถทำให้หุ่นใน gazebo อยู่จุดสมดุลได้ สันนิษฐานว่าน่าจะเป็นที่การตั้งค่า inertial"


https://drive.google.com/drive/folders/10vsJuEaWKvX-jsaSckTTFI855xokPK6a?usp=sharing
