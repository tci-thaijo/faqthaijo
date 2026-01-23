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

# 6. ไม่มีปุ่มตัดสินบทความ แสดงเฉพาะปุ่ม "ให้ข้อเสนอแนะ | Make Recomendation"

<figure><img src=".gitbook/assets/Screenshot 2568-09-08 at 10.08.47.png" alt="" width="395"><figcaption></figcaption></figure>

### <mark style="color:green;">**สาเหตุที่พบ**</mark>

### <mark style="color:red;background-color:yellow;">**1. ผู้ใช้มีตำแหน่งเป็น ผู้จัดการวารสาร (Journal Manager, JM)**</mark>

* Journal Manager ไม่สามารถดำเนินการกับบทความได้ จะสามารถดูข้อมูลได้เพียงอย่างเดียว

<mark style="color:green;">✅</mark> <mark style="color:green;"></mark><mark style="color:green;">**หากต้องการจัดการบทความ**</mark>

* แต่งตั้งผู้ใช้เป็นตำแหน่ง **บรรณาธิการ (Journal editor: JE)** หรือ **บรรณาธิการประจำบท/เรื่อง (Section editor: SE)**
  * 🔧 **ขั้นตอน:** [**การเพิ่ม/ลดตำแหน่งให้กับผู้ใช้ (User)**](editrole.md)
* จากนั้นไปที่หัวข้อ **ผู้มีส่วนเกี่ยวข้อง (Participants)** → มอบหมาย (Assign) เป็นผู้ดูแลบทความ

***

### <mark style="color:red;background-color:yellow;">**2. ผู้ใช้ไม่ได้ถูกมอบหมายเป็นผู้มีส่วนเกี่ยวข้อง (Participants)**</mark>

* หากผู้ใช้ไม่ได้รับมอบหมายให้เป็นผู้ดูแลบทความ ระบบจะไม่อนุญาตให้จัดการบทความและไม่แสดงปุ่มตัดสินบทความ

<mark style="color:green;">✅</mark> <mark style="color:green;"></mark><mark style="color:green;">**วิธีแก้ไข:**</mark>&#x20;

* ไปที่หัวข้อ **ผู้มีส่วนเกี่ยวข้อง (Participants)** → มอบหมาย (Assign) เป็นผู้ดูแลบทความ

<figure><img src=".gitbook/assets/Screenshot 2568-09-10 at 10.39.56.png" alt=""><figcaption></figcaption></figure>

📌 **ตัวอย่าง:**&#x20;

**Somchai Rakkhan** ได้รับมอบหมายเป็น ผู้ดูแลบทความในตำแหน่ง**บรรณาธิการ (Journal editor: JE)** ที่กำหนดสิทธิ์ให้สามารถจัดการและตัดสินบทความได้

***

### <mark style="color:red;background-color:yellow;">**3. การกำหนดสิทธิ์ของผู้ดูแลบทความ (Assign)**</mark>

* หากกำหนดสิทธิ์ผู้ดูแลบทความให้ <mark style="color:red;">**ไม่มีสิทธิ์ตัดสินบทความโดยตรง**</mark> ระบบก็จะไม่แสดงปุ่มตัดสินบทความให้กับผู้ดูแลท่านนั้น

<figure><img src=".gitbook/assets/Screenshot 2568-09-08 at 10.05.32.png" alt="" width="563"><figcaption></figcaption></figure>

<mark style="color:green;">✅</mark> <mark style="color:green;"></mark><mark style="color:green;">**วิธีแก้ไข:**</mark>

1. กระบวนการ (Workflow)  → **ผู้มีส่วนเกี่ยวข้อง (Participants)**
2. **คลิกลูกศรหน้าชื่อ**บรรณาธิการ (Journal editor: JE) → เลือก **แก้ไข (Edit)**
3. หัวข้อ **กำหนดสิทธิ์ (Assignment privileges)** → **เอาเครื่องหมายออก**
4. คลิก **ตกลง (OK)**

<div><figure><img src=".gitbook/assets/Screenshot 2568-09-08 at 10.16.03.png" alt=""><figcaption></figcaption></figure> <figure><img src=".gitbook/assets/Screenshot 2568-09-08 at 10.16.13.png" alt=""><figcaption></figcaption></figure></div>

ระบบจะแสดงปุ่ม **“ตัดสินบทความ”** ดังภาพ

<figure><img src=".gitbook/assets/Screenshot 2568-09-03 at 16.35.41.png" alt="" width="261"><figcaption></figcaption></figure>
