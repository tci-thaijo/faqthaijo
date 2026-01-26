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

# 17. วารสารต้องการเปลี่ยนแปลง URL เว็บไซต์ในระบบ ThaiJO ต้องทำอย่างไร

> การเปลี่ยน URL เว็บไซต์ของวารสารจะทำให้ลิงก์การเข้าถึงเว็บไซต์และบทความ <mark style="color:red;">**เปลี่ยนทั้งหมด**</mark>

### <mark style="color:green;">ผลกระทบที่อาจเกิดขึ้น</mark>

1. <mark style="color:red;">**การสูญเสียการจดจำ URL**</mark>
   * ผู้ใช้ที่เคยบันทึกหรือบุ๊กมาร์ก URL เดิม จะไม่สามารถเข้าถึงเว็บไซต์ได้เมื่อมีการเปลี่ยนแปลง
2. <mark style="color:red;">**ปัญหา SEO (Search Engine Optimization)**</mark>
   * การเปลี่ยน URL อาจกระทบต่อการจัดอันดับการค้นหา (SEO) เพราะ search engines เช่น Google ใช้ URL เป็นตัวชี้วัดสำคัญ ส่งผลให้การค้นหาบทความหรือวารสารอาจตกอันดับ
3. <mark style="color:red;">**ลิงก์เสีย (Broken Links)**</mark>
   * ลิงก์ภายนอกที่อ้างอิง URL เดิม เช่น TCI, Google Scholar หรือระบบอื่น ๆ จะไม่สามารถเข้าถึงได้อีก หากบทความถูก Index ไว้ด้วย URL เดิม
4. <mark style="color:red;">**ปัญหาการแชร์ (Sharing Issues)**</mark>
   * ลิงก์ที่เคยถูกแชร์ผ่านโซเชียลมีเดียหรือช่องทางอื่น ๆ จะไม่สามารถใช้งานได้
5. <mark style="color:red;">**การสูญเสียสถิติการเข้าชม (Usage Statistics)**</mark>
   * สถิติการเข้าชมบทความและเว็บไซต์เดิมจะไม่ถูกนับรวมกับ URL ใหม่ ทำให้ข้อมูลสถิติไม่ต่อเนื่อง
6. <mark style="color:red;">**ปัญหากับระบบอ้างอิง (Citation Linking Systems)**</mark>
   * บทความที่ถูกเชื่อมโยงในฐานข้อมูลอ้างอิง เช่น Crossref, DOAJ, Scopus, หรือระบบจัดการบรรณานุกรม (Zotero, EndNote ฯลฯ) อาจไม่สามารถเข้าถึงได้ หาก DOI ชี้ไปที่ URL เดิมโดยตรง
   * แม้ DOI จะยังคงอยู่ แต่ถ้าไม่ได้อัปเดตการเชื่อมโยง (metadata) อาจเกิดปัญหาในการเข้าถึง
7. <mark style="color:red;">**การเข้าถึงจากระบบสืบค้นภายนอก (External Indexing Systems)**</mark>
   * ระบบอย่าง TCI, Google Scholar, BASE, Dimensions ฯลฯ จะยังคงมีข้อมูล URL เดิม หากไม่มีการอัปเดต อาจทำให้บทความไม่ถูกเข้าถึงหรือไม่ถูกดึงข้อมูลมาแสดง
   * ส่งผลต่อการมองเห็น (visibility) และการอ้างอิง (citation impact) ของวารสาร
8. <mark style="color:red;">**ภาระงานเพิ่มเติมในการสื่อสารกับผู้ใช้**</mark>
   * ต้องประชาสัมพันธ์และแจ้งผู้แต่ง, ผู้ประเมิน, ผู้อ่าน รวมถึงหน่วยงานต่าง ๆ ที่เกี่ยวข้อง ให้ทราบถึงการเปลี่ยน URL
   * หากไม่แจ้งให้ครบถ้วน อาจทำให้ผู้ใช้เกิดความสับสน

***

{% hint style="warning" %}
**ข้อแนะนำเพิ่มเติม:**

* ควรเปลี่ยน URL <mark style="color:red;">**เฉพาะกรณีจำเป็นจริง ๆ**</mark>
* หากต้องการเปลี่ยน ควรจัดทำ **แผนการย้าย (Migration Plan)** เช่น
  * **แจ้งผู้ใช้ล่วงหน้า** (บรรณาธิการ, ผู้ประเมิน, ผู้แต่ง, ผู้อ่าน) รวมถึงหน่วยงานต่าง ๆ ที่เกี่ยวข้อง
  * **การอัปเดต Metadata** และ **ฐานข้อมูลภายนอก**&#x20;
    * แจ้ง Crossref เพื่ออัปเดตลิงก์ DOI (ถ้ามี)
    * อัปเดตข้อมูลใน TCI, Google Scholar, DOAJ, Scopus ฯลฯ
    * ตรวจสอบการ Index ของ Search Engines
  * **การทดสอบระบบ (Testing)**
    * ตรวจสอบการเข้าถึงเว็บไซต์, การล็อกอิน, การส่งบทความ, การค้นหาบทความ
    * ตรวจสอบว่าไม่มี **broken links**
  * **การติดตามผลหลังย้าย**ว่าผู้ใช้ยังสามารถเข้าถึงบทความและระบบได้ตามปกติ
{% endhint %}

***

### <mark style="color:red;background-color:yellow;">📌 แจ้ง</mark><mark style="color:red;background-color:yellow;">**ยืนยันเปลี่ยนแปลง URL ของวารสาร**</mark>

1. **กรอกแบบฟอร์ม**📄 **:**&#x20;

> 🔗 [**การขอแก้ไข URL เว็บไซต์ของวารสารในระบบ ThaiJO**](https://forms.gle/KgPH6cvqc2NTtoNK6)

2. **แจ้งแอดมิน ThaiJO** (<mark style="color:red;">หลังจากกรอกแบบฟอร์มเรียบร้อยแล้ว</mark>)
   * 📫 **ช่องทางติดต่อ | Contact**
     * 📩 Facebook: [ThaiJO2.0](https://www.facebook.com/ThaiJo2.0)
     * 📩 Line ID: **@135rfmha**
