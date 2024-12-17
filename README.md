# project-request-app-KU
## วิธีการติดตั้งและรันโปรแกรม
- กดที่ Tags แล้วกด Releases
- เลือกไฟล์ tysm-release.zip ที่ tysm release
- หลังdownloadเสร็จ แตกไฟล์ไปไว้ในที่ที่ต้องการ
- เปิดterminalแล้วเข้าไปที่ path.../tysm-release
- จากนั้นพิมพ์คำสั่ง ```java -jar cs211-671-project-1.0-shaded.jar```

**ที่อยู่ของไฟล์ pdf**
- เปิดterminalแล้วเข้าไปที่ path.../tysm-release/instruction ไฟล์pdfจะอยู่ในนั้น

## ตัวอย่างข้อมูลผู้ใช้ระบบ (username, password)
### ผู้ดูแลระบบ

Username : admin
Password : admin

### นิสิต

Username : mon
Password : 111

Username : amorntep_a
Password : 111

Username : kittipob_k
Password : 111

### อาจารย์ที่ปรึกษา

Username : sand
Password : 222

Username : nopadol_s
Password : 222

Username : thanapat_c
Password : 222

Username : warintorn_p
Password : 000 (รหัสเริ่มต้น)

### เจ้าหน้าที่ภาควิชา

Username : yok
Password : 333

Username : waranya_t
Password : 333

Username : ekachai_c
Password : 333

Username : siriporn_m
Password : 000 (รหัสเริ่มต้น)

### เจ้าหน้าที่คณะ

Username : tiew
Password : 444

Username : woramet_k
Password : 444

Username : chanoknan_p
Password : 444

Username : thanakorn_s
Password : 000 (รหัสเริ่มต้น)

## การวางโครงสร้างไฟล์ของโครงงาน
**directory data**
- เก็บ file csv ทั้งหมด และในdataมี directory 2 directory คือ images ใช้เก็บรูปโปลไฟล์ของผู้ใช้ระบบ และ signature ใช้เก็บลายเซ็นของอาจารย์ที่ปรึกษา เจ้าหน้าที่ภาควิชา และ เจ้าหน้าที่คณะ

**directory scr**
- เก็บ 1 directory คือ directory main
- ซึ่ง directory main เก็บการทำงานของโปรแกรม(controllers ,models, services)และหน้าuiของโปรแกรม(ไฟล์css, รูป, ไฟล์fxml)
