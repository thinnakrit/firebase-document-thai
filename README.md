# คู่มือการใช้งาน Firebase ฉบับภาษาไทย
คู่มือการใช้งาน Firebase ฉบับภาษาไทย เรียบเรียงโดย ทินกฤต หนูอักษร

* Firebase คืออะไร
* ลักษะการทำงาน
* เริ่มต้นใช้งาน
* สร้างโปรเจค
* ใช้งาน Firebase ด้วย React
```
ใช้งาน Firebase ด้วย React
|---- อ่านข้อมูล
|---- เขียนข้อมูล
|---- อัพเดทข้อมูล
|---- ลบข้อมูล
|---- Authentication
|---- Storage
```

### Firebase คืออะไร
```
Firebase Realtime Database เป็น NoSQL cloud database ที่เก็บข้อมูลในรูปแบบของ JSON 
และมีการ sync ข้อมูลแบบ realtime กับทุก devices ที่เชื่อมต่อแบบอัตโนมัติในเสี้ยววินาที 
รองรับการทำงานเมื่อ offline(ข้อมูลจะถูกเก็บไว้ใน local จนกระทั่งกลับมา online ก็จะทำการ sync ข้อมูลให้อัตโนมัติ) 
รวมถึงมี Security Rules ให้เราสามารถออกแบบเงื่อนไขการเข้าถึงข้อมูลทั้งการ read และ write ได้ดังใจ 
ทั้ง Android, iOS และ Web
```
อ้างอิง 
https://developers.ascendcorp.com/รู้จัก-firebase-realtime-database-ตั้งแต่-zero-จนเป็น-hero-5d09210e6fd6#.va3kcmne8
http://www.poolsawat.com/firebase-tutorial/
