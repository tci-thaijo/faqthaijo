---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# 7. สร้างรอบการประเมินใหม่ (New Review Round) สามารถลบรอบประเมินนั้นได้หรือไม่

<figure><img src=".gitbook/assets/Screenshot 2568-09-05 at 11.32.40.png" alt=""><figcaption></figcaption></figure>

### <mark style="color:$success;">คำตอบ</mark>

<mark style="color:red;">**ไม่สามารถลบรอบการประเมินที่สร้างขึ้นได้**</mark> เนื่องจาก<mark style="color:red;">**สถานะบทความ**</mark>ได้ถูกกำหนดให้<mark style="color:red;">**เป็นรอบใหม่**</mark>แล้ว เช่น หากสร้าง Round 2 ระบบจะถือว่าสถานะปัจจุบันอยู่ที่ Round 2 และ<mark style="color:red;">**ปุ่มตัดสินบทความจะอยู่ในรอบปัจจุบัน**</mark>

### <mark style="color:green;">✅</mark> <mark style="color:$success;">วิธีการจัดการ</mark>

* รอให้ผู้ประเมินในรอบก่อนหน้า (เช่น Round 1) ส่งผลการประเมินครบทุกท่าน → รวบรวมผลประเมินจากทุกท่าน
* ตัดสินบทความในรอบปัจจุบัน (เช่น Round 2) เพื่อแจ้งผู้แต่งแก้ไขบทความ (Request Revisions) → กด Record Editorial Decision&#x20;
* หากจำเป็นต้องสื่อสารกับผู้แต่ง ให้ใช้ช่องทางกระทู้สนทนา Review Discussion

{% hint style="warning" %}
การแจ้งผู้แต่งแก้ไขบทความ (Request Revisions) ระบบจะ **+ดึงข้อมูลจากแบบประเมิน (+Add Reviews to Email) จากรอบปัจจุบันได้เท่านั้น** ไม่สามารถดึงข้อมูลจากรอบก่อนหน้าได้
{% endhint %}
