# homework
► คำสั่งที่ใช้
# mkdir homework
  ✿ สร้างโฟลเดอร์
# cd homework
  ✿เพื่อเปลี่ยนไปยัง dir อื่น
# echo "# homework" >> README.md
  ✿คำสั่งที่ใช้ในการแสดงผล
# git init
  ✿ใช้สร้าง local repo ขึ้นมา
# git add README.md
  ✿ใช้ stage เพื่อติดตามตามความเปลี่ยนแปลงของไฟล์
# git status
  ✿ตรวจสอบสถานะ
# git config --global user.email "ausukanya@hotmail.com"
# git config --global user.name "sukanya068"
  ✿การระบุตัวตน
# git commit -m "first commit"
  ✿ใช้เพื่อบันทึกความเปลี่ยนแปลงที่เกิดขึ้นสู่ local repo
# git remote add origin https://github.com/Sukanya068/homework.git
  ✿เมื่อยังไม่มี remote repo เราก็จะเพิ่มมันเข้าไป โดยใช้ url ที่ก็อปปี้ไว้เมื่อกี้
# git remote -v
  ✿เช็คว่า local repo นี้มี remote repo รึยัง
# git push -u origin master
  ✿แล้วก็ push to origin (remote repo) แล้วก็ให้ป้อนชื่อผู้ใช้กับรหัสผ่าน