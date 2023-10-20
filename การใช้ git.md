git init 
/ตั้งค่าโครงสร้างข้อมูลและไฟล์การกำหนดค่าที่จำเป็นเพื่อเริ่มใช้ Git เพื่อติดตามการเปลี่ยนแปลงในโปรเจ็กต์
นิยาม
1. นำทางไปยังไดเร็กทอรีโปรเจ็กต์ของคุณ:เปิดบรรทัดคำสั่งหรือเทอร์มินัลของคุณแล้วนำทางไปยังไดเร็กทอรีที่คุณต้องการเริ่มการควบคุมเวอร์ชันด้วย Git
2. เมื่อคุณอยู่ในไดเร็กทอรีโปรเจ็กต์แล้ว ให้รัน git initคำสั่ง สิ่งนี้จะสร้างไดเร็กทอรีย่อยที่ซ่อนอยู่ชื่อ ".git"
ในไดเร็กทอรีปัจจุบัน ไดเร็กทอรีนี้มีข้อมูลและไฟล์ที่จำเป็นทั้งหมดสำหรับพื้นที่เก็บข้อมูล
3. เตรียมใช้งานพื้นที่เก็บข้อมูล Git

git add .
/ แสดงไฟล์ทั้งหมด หรือ แสดงบางส่วน เช่น git add index.html
นิยาม
1. git add คือการนำของใส่กล่อง
   
git commit บันทึกการเปลี่ยนแปลงเหล่านั้นไปยังพื้นที่เก็บข้อมูล
git commit -m "first commit" บันทึกการเปลี่ยนแปลงและคอมเมนต์ first commit
/ 
นิยาม
1. คือการปิดกล่องเมื่อของในกล่องครบตามที่ต้องการ

git branch แสดงรายการ สร้าง ลบ และจัดการสาขาภายในที่เก็บ Git
git branch -M main
/ 

git remote add origin https://github.com/supachaiB/git.git
/ คำสั่งนี้จะใช้เพิ่ม Location ของ Remote Repository ของคุณ ตอนนี้ทุกอย่างอยู่ใน Local Repository บน Computer ของคุณ 
คุณจะต้องไปที่ GitHub Account ของคุณ และสร้าง Remote Repository ใหม่ที่ซึ่งคุณจะสามารถ Push Local Repository ของคุณได้ หลังจากที่คุณสร้าง Remote Repository 
คุณจะได้รับ Link ซึ่ง Link นั้นจะเป็น Location

git push สำหรับส่งการเปลี่ยนแปลงหรือ commit ที่ local repository ไปยัง remote repository
git push -u origin main


ขั้นตอน อัพขึ้น github
git init 
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/supachaiB/git.git
git push -u origin main
