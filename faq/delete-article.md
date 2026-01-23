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

# 12. ผู้แต่งส่งบทความเรื่องเดียวกันซ้ำหลาย ID

***

<mark style="color:red;background-color:yellow;">**บทความ 1 เรื่อง ควรมีเพียง 1 ID เท่านั้น**</mark> ต้องเลือกดำเนินการกับบทความหลักให้เสร็จสิ้น และลบบทความที่ซ้ำ (ไม่ได้ใช้งาน) ออกจากระบบ

### <mark style="color:green;">✅ วิธีการจัดการ</mark>

1. **ค้นหาบทความที่ซ้ำ**
   * **All Active (อยู่ระหว่างดำเนินการ)** → ค้นหาบทความด้วยชื่อเรื่องหรือชื่อผู้แต่ง
   * _บางกรณีบทความอาจจะอยู่ที่ Archives (คลังบทความ)_
2. **ตัดสินใจเลือกบทความหลักที่จะดำเนินการให้จบกระบวนการ**

📌 **ตัวอย่าง**

* ✅ ดำเนินการกับบทความ **ID: 240729** ให้จบกระบวนการ&#x20;
* ❌ ลบบทความ **ID: 241715** ออกจากระบบ

<figure><img src=".gitbook/assets/Screenshot 2568-09-15 at 09.26.37.png" alt=""><figcaption></figcaption></figure>

***

### ❌ <mark style="color:green;">ขั้นตอนการลบบทความที่ซ้ำ</mark>

1. เปิดบทความ **ID: 241715** (บทความที่ต้องการลบ)
2. **Workflow** → ตรวจสอบสถานะ **Submission**
3. หัวข้อ **Participants** ต้องมีผู้ดูแลบทความ
   * หากยังไม่มีผู้ดูแลบทความให้ **Assign** → **บรรณาธิการ (Journal editor)**
4. เมนูตัดสินบทความ → เลือก **Decline Submission**

<figure><img src=".gitbook/assets/Screenshot 2568-09-15 at 10.16.04.png" alt=""><figcaption></figcaption></figure>

5. 📧 การส่งอีเมลถึงผู้แต่ง:&#x20;
   * หากไม่ต้องการส่งอีเมล → เลือก **Do not send an email notification (ไม่ส่งอีเมล)**
   * _หรือ_ หากต้องการส่งอีเมล → แก้ไขข้อความในเนื้อหาอีเมล เช่น&#x20;

> ข้อความแจ้งในอีเมล
>
> “วารสารจะลบบทความ **ID: 241715** นี้ออกจากระบบ โปรดดำเนินการกับบทความ **ID: 240729** ให้แล้วเสร็จ”

6. กด **Record Editorial Decision**

<figure><img src=".gitbook/assets/Screenshot 2568-09-15 at 10.22.23.png" alt="" width="563"><figcaption></figcaption></figure>

7. ระบบจะย้ายบทความไปที่ **Archives**
   * คลิกไอคอน**ลูกศร** 🔽 **ท้ายชื่อบทความ** → **Delete**
   * **Yes** เพื่อยืนยันการลบบทความออกจากระบบ

{% hint style="danger" %}
**ข้อควรระวัง:**&#x20;

บทความที่ถูก <mark style="color:red;">**Delete**</mark> จะถูกลบอย่างถาวรและ<mark style="color:red;">**ไม่สามารถกู้คืนได้**</mark>
{% endhint %}

<div><figure><img src=".gitbook/assets/Screenshot 2568-09-15 at 10.25.28.png" alt=""><figcaption></figcaption></figure> <figure><img src=".gitbook/assets/Screenshot 2568-09-15 at 10.26.16.png" alt=""><figcaption></figcaption></figure></div>
