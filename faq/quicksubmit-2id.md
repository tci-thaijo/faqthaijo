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

# 13. วารสารไม่นำบทความที่ผู้แต่งส่งเข้ามาไปเผยแพร่ (Published) แต่ใช้ QuickSubmit เผยแพร่ (ซำ้ 2 ID)

### 🔷 <mark style="color:green;">การใช้ QuickSubmit ที่ถูกต้อง</mark>

* 📂 ใช้สำหรับ **บทความที่เก่า** ที่ต้องการนำมาเผยแพร่ในระบบ ThaiJO&#x20;

> เช่น บทความจากฉบับเก่าที่เคยเผยแพร่ในรูปเล่มหรือบนเว็บไซต์เดิม ก่อนย้ายมาใช้ระบบ ThaiJO

* 📝 ใช้สำหรับ **บทความที่ไม่ผ่านการ Peer Review**

> เช่น บทบรรณาธิการ บทความพิเศษ ที่กองบรรณาธิการจัดทำ และต้องการนำเข้าระบบโดยไม่ผ่านขั้นตอน Peer Review ใน ThaiJO

* 🔄 ใช้สำหรับ บทความที่ได้ดำเนินการจาก**นอกระบบ**เรียบร้อยแล้ว และต้องการนำมาเผยแพร่ในระบบร่วมกับบทความที่ดำเนินการผ่านระบบ ThaiJO

> เช่น บทความที่ผ่านการพิจารณาและตัดสินจากระบบอื่น หรือจากกระบวนการออฟไลน์ (เช่น ทางอีเมล/เอกสาร) แล้วต้องการนำมาเผยแพร่ใน ThaiJO

***

### 🚫 <mark style="color:green;">เหตุผลที่ไม่ควร QuickSubmit เผยแพร่แทนบทความที่ผู้แต่งส่งเข้ามาในระบบ</mark>

* ทำให้มี**บทความเรื่องเดียวกันซ้ำ 2 ID**
  * ID เดิม: ผู้แต่งส่งเข้ามาในระบบ → ผ่านการ Review (มีประวัติการรีวิว)
  * ID ใหม่: ใช้ QuickSubmit เพื่อนำเข้าระบบและเผยแพร่ (ไม่มีประวัติการรีวิว)
* บทความที่เผยแพร่โดยใช้ QuickSubmit จะ **ไม่มีประวัติการรีวิวในระบบ** → ส่งผลต่อคะแนนประเมินคุณภาพวารสาร
* บทความ ID เดิม ที่ผู้แต่งส่งเข้ามาในระบบยัง**คงค้าง**อยู่ใน **All Active (อยู่ระหว่างดำเนินการ)** เนื่องจากกระบวนการพิจารณายังไม่สิ้นสุด
* ระบบตรวจสอบการคัดลอก (<mark style="color:red;">**©**</mark>**&#x20;CopyCatch**) อาจฟ้องว่า **ซ้ำ** เนื่องจากเป็นเรื่องเดียวกัน

***

### <mark style="color:green;">✅</mark> <mark style="color:green;"></mark><mark style="color:green;">**วิธีการจัดการ**</mark>

### <mark style="color:red;background-color:yellow;">**1️⃣ ดำเนินการกับ บทความ ID เดิม (ผู้แต่งส่งเข้ามาในระบบ) ให้จบกระบวนการ**</mark>

1. **ค้นหาบทความ**
   * ค้นหาบทความที่ **All Active (อยู่ระหว่างดำเนินการ)** → **เข้าไปที่บทความ**
   * _บางกรณีบทความอาจจะอยู่ที่ Archives (คลังบทความ)_
2. **Workflow ของบทความ**
   * บทความต้องอยู่ที่ สถานะ **Production**
   * หากยังไม่อยู่ที่ Production ทำตามขั้นตอน:
   * ขั้นตอนการตัดสินบทความ:
     * Submission **(Sent to Review)**
     * Review **(Accept Submission)**
     * Copyediting **(Send To Production)**
     * Production (บทความเข้าสู่สถานะ **Production** ✅)

<figure><img src=".gitbook/assets/Screenshot 2568-09-11 at 14.20.05.png" alt="" width="563"><figcaption></figcaption></figure>

{% hint style="warning" %}
**หมายเหตุ**

* ❌ **ไม่เลือกไฟล์ใด ๆ** ในการเปลี่ยนสถานะของบทความ
* 📧 การส่งอีเมลถึงผู้แต่ง: เลือก **Do not send an email notification (ไม่ส่งอีเมล)** → **Record Editorial Decision**
{% endhint %}

<div><figure><img src=".gitbook/assets/Screenshot 2568-09-11 at 13.10.34.png" alt=""><figcaption></figcaption></figure> <figure><img src=".gitbook/assets/Screenshot 2568-09-11 at 11.32.59.png" alt=""><figcaption></figcaption></figure></div>

3. **Publication ของบทความ**
   * **Metadata** → แก้ไขข้อมูลบทความ: Title, Abstract, Contributors, Keyword, Reference (ถ้ามี)ให้ตรงกับไฟล์ PDF
   * **Galleys** → อัปโหลดไฟล์ Galley (PDF)
   * **Issue** →
     * _Pages_: กรอกเลขหน้า
     * _Date Published_: กรอกวันที่นำเข้าฉบับ (วันที่นำเข้าฉบับในระบบ (รูปแบบ: ปี(ค.ศ.)-เดือน-วัน) ซึ่งอาจตรงกับหรือแตกต่างจากวันที่เผยแพร่ฉบับก็ได้)
     * Save
   * กด **Schedule For Publication** → **เลือกฉบับ (Issue)** → กด **Publish**
   * ✅ บทความเข้าสู่ฉบับ (Issue) และเผยแพร่เรียบร้อยแล้ว (Published)

<div><figure><img src=".gitbook/assets/Screenshot 2568-09-11 at 13.38.21.png" alt=""><figcaption></figcaption></figure> <figure><img src=".gitbook/assets/Screenshot 2568-09-11 at 13.54.43.png" alt=""><figcaption></figcaption></figure></div>

4. **Archives:**

* บทความย้ายจาก **All Active (อยู่ระหว่างดำเนินการ)** ไปที่ **Archives (คลังบทความ)**
* สถานะบทความเปลี่ยนเป็น **Published (เผยแพร่แล้ว)** ✅

<figure><img src=".gitbook/assets/Screenshot 2568-09-11 at 14.30.32.png" alt="" width="563"><figcaption></figcaption></figure>

### <mark style="color:red;background-color:yellow;">**2️⃣ ลบบทความ ID ใหม่ (วารสารนำเข้าบทความด้วย QuickSubmit)**</mark>

1. **ค้นหาบทความ**
   * ค้นหาบทความที่ **Archives (คลังบทความ)** → **เข้าไปที่บทความ**

<figure><img src=".gitbook/assets/Screenshot 2568-09-11 at 14.35.00.png" alt="" width="563"><figcaption></figcaption></figure>

2. **Publication ของบทความ**
   * กด **Unpublish** เพื่อนำบทความออกจากฉบับ (Issue) และยกเลิกการเผยแพร่

<figure><img src=".gitbook/assets/Screenshot 2568-09-11 at 10.41.09.png" alt="" width="375"><figcaption></figcaption></figure>

3. **Workflow ของบทความ**
   * Participants → หากยังไม่มีผู้ดูแลบทความให้ **Assign: Journal editor**
   * สถานะ Submission → **Change decision** → **Decline Submission**
   * 📧 การส่งอีเมลถึงผู้แต่ง: เลือก **Do not send an email notification (ไม่ส่งอีเมล)** → **Record Editorial Decision**

<div><figure><img src=".gitbook/assets/Screenshot 2568-09-11 at 10.43.22.png" alt=""><figcaption></figcaption></figure> <figure><img src=".gitbook/assets/Screenshot 2568-09-11 at 10.43.48.png" alt=""><figcaption></figcaption></figure></div>

4. **Archives**
   * สถานะบทความเปลี่ยนเป็น **Declined** → **Delete เพื่อลบบทความออกจากระบบ**

{% hint style="danger" %}
**ข้อควรระวัง:**&#x20;

บทความที่ถูก <mark style="color:red;">**Delete**</mark> จะถูกลบอย่างถาวรและ<mark style="color:red;">**ไม่สามารถกู้คืนได้**</mark>
{% endhint %}

<div><figure><img src=".gitbook/assets/Screenshot 2568-09-11 at 10.45.11 (1).png" alt=""><figcaption></figcaption></figure> <figure><img src=".gitbook/assets/Screenshot 2568-09-15 at 10.26.16.png" alt=""><figcaption></figcaption></figure></div>

