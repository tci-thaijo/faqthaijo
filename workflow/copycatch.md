# 📕 คู่มือการใช้งานระบบการตรวจสอบความคล้าย (Copycatch)

### <mark style="color:$warning;">รูปแบบการตรวจสอบความคล้าย (Copycatch)</mark>

มี 2 รูปแบบ ดังนี้

{% columns %}
{% column width="16.666666666666664%" %}
<h4 align="center"><mark style="color:blue;"><strong>แบบที่ 1</strong></mark></h4>
{% endcolumn %}

{% column width="16.666666666666664%" %}
<figure><img src=".gitbook/assets/copycatch-1.png" alt="C สีน้ำเงิน" width="32"><figcaption><p>C สีน้ำเงิน</p></figcaption></figure>
{% endcolumn %}

{% column width="66.66666666666667%" %}
#### <mark style="color:blue;">**ตรวจเทียบกับบทความที่ยังไม่เผยแพร่**</mark>
{% endcolumn %}
{% endcolumns %}

{% columns %}
{% column width="41.66666666666667%" valign="middle" %}
<h4 align="center"><strong>สถานะ Submission</strong></h4>

<figure><img src=".gitbook/assets/submission.png" alt="" width="128"><figcaption></figcaption></figure>

<p align="center">บทความที่ส่งเข้าระบบใหม่</p>

<figure><img src=".gitbook/assets/Screenshot 2568-12-16 at 11.50.18.png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column width="16.666666666666668%" %}
_**เทียบกับ**_
{% endcolumn %}

{% column width="41.66666666666664%" %}
<h4 align="center"><strong>สถานะ Unpublished</strong></h4>

<p align="center">บทความอื่น ๆ ที่ยังไม่เผยแพร่ในระบบ</p>
{% endcolumn %}
{% endcolumns %}

{% hint style="info" %}
## ข้อควรทราบ

* ระบบจะนำไฟล์ <mark style="color:red;background-color:yellow;">**Article Text**</mark> ที่อัปโหลด<mark style="color:red;background-color:yellow;">**ล่าสุด**</mark>ในหัวข้อ <mark style="color:red;background-color:yellow;">**Submission Files**</mark> ไปตรวจสอบความคล้าย<mark style="color:red;background-color:yellow;">**อัตโนมัติ**</mark>
* การตรวจสอบในกรณีนี้ ระบบจะ<mark style="color:red;background-color:yellow;">**ดำเนินการเพียงครั้งเดียวเท่านั้น**</mark>\
  หากมีการอัปโหลดไฟล์ **Article Text** เพิ่มเติมในหัวข้อ **Submission Files ภายหลัง** ระบบจะ**ไม่นำไฟล์ไปตรวจซ้ำ**
{% endhint %}

***

{% columns %}
{% column width="16.666666666666664%" %}
<h4 align="center"><mark style="color:red;"><strong>แบบที่ 2</strong></mark></h4>
{% endcolumn %}

{% column width="16.666666666666664%" %}
<figure><img src=".gitbook/assets/copycatch-2.png" alt="C สีน้ำเงิน" width="32"><figcaption><p>C สีแดง</p></figcaption></figure>
{% endcolumn %}

{% column width="66.66666666666667%" %}
#### <mark style="color:red;">**ตรวจเทียบกับบทความที่เผยแพร่แล้ว**</mark>
{% endcolumn %}
{% endcolumns %}

{% columns %}
{% column width="41.66666666666667%" valign="middle" %}
#### **1) สถานะ Submission**

<figure><img src=".gitbook/assets/submission.png" alt="" width="128"><figcaption></figcaption></figure>

<p align="center">บทความที่ส่งเข้าระบบใหม่</p>

<figure><img src=".gitbook/assets/Screenshot 2568-12-16 at 11.50.18.png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column width="16.666666666666668%" %}
_**เทียบกับ**_
{% endcolumn %}

{% column width="41.66666666666664%" %}
<h4 align="center"><strong>สถานะ Published</strong></h4>

<figure><img src=".gitbook/assets/published.png" alt="" width="101"><figcaption></figcaption></figure>

<p align="center">บทความที่เผยแพร่แล้วในระบบ</p>
{% endcolumn %}
{% endcolumns %}

{% hint style="info" %}
## ข้อควรทราบ

* ระบบจะนำไฟล์ <mark style="color:red;background-color:yellow;">**Article Text**</mark> ที่อัปโหลด<mark style="color:red;background-color:yellow;">**ล่าสุด**</mark>ในหัวข้อ <mark style="color:red;background-color:yellow;">**Submission Files**</mark> ไปตรวจสอบความคล้าย<mark style="color:red;background-color:yellow;">**อัตโนมัติ**</mark>
* ระบบจะดำเนินการตรวจสอบ <mark style="color:red;background-color:yellow;">**ทุกครั้งที่มีการอัปโหลด**</mark>ไฟล์ **Article Text** เพิ่มเติมในหัวข้อ <mark style="color:red;background-color:yellow;">**Submission Files**</mark>
{% endhint %}

{% columns %}
{% column width="41.66666666666667%" valign="middle" %}
#### **2) สถานะ Review**

<figure><img src=".gitbook/assets/review.png" alt="" width="97"><figcaption></figcaption></figure>

<p align="center">บทความที่มีการแก้ไข</p>

<figure><img src=".gitbook/assets/Screenshot 2568-12-16 at 14.20.04 (1).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column width="16.666666666666668%" %}
_**เทียบกับ**_
{% endcolumn %}

{% column width="41.66666666666664%" %}
<h4 align="center"><strong>สถานะ Published</strong></h4>

<figure><img src=".gitbook/assets/published.png" alt="" width="101"><figcaption></figcaption></figure>

<p align="center">บทความที่เผยแพร่แล้วในระบบ</p>
{% endcolumn %}
{% endcolumns %}

{% hint style="info" %}
## ข้อควรทราบ

* ระบบจะดำเนินการตรวจสอบอีกครั้ง <mark style="color:purple;background-color:red;">**เมื่อมีการแก้ไขบทความ**</mark> โดยจะนำไฟล์ <mark style="color:purple;background-color:red;">**Article Text**</mark> ที่อัปโหลด<mark style="color:purple;background-color:red;">**ล่าสุด**</mark>ในหัวข้อ <mark style="color:purple;background-color:red;">**Revisions**</mark> ไปตรวจสอบความคล้าย<mark style="color:purple;background-color:red;">**อัตโนมัติ**</mark>
* ระบบจะดำเนินการตรวจสอบ <mark style="color:red;background-color:yellow;">**ทุกครั้งที่มีการอัปโหลด**</mark>ไฟล์ **Article Text** เพิ่มเติมในหัวข้อ <mark style="color:purple;background-color:red;">**Revisions**</mark>
{% endhint %}

***

{% hint style="warning" %}
## ⚠️ หมายเหตุ

* ระบบ**ไม่ได้**นำบทความไป**ตรวจ**ความคล้าย**ทันที** โดยจะเริ่มดำเนินการตรวจสอบ**อัตโนมัติ** ตั้งแต่เวลา **03.00 น.** (เวลาประเทศไทย GMT+7) **ของทุกวัน**
* <img src=".gitbook/assets/copycatch-grey.png" alt="C สีเทา" data-size="line"> **C สีเทา** หมายถึง ระบบยังไม่มีผลการตรวจสอบความคล้าย เนื่องจากเกิดปัญหาในการตรวจไฟล์ หรือบทความยังไม่อยู่ในสถานะที่สามารถนำไปตรวจได้
  *   ตัวอย่างสาเหตุที่พบบ่อย ได้แก่

      * อัปโหลดไฟล์ผิดประเภท\
        (เลือก Component ไม่ใช่ **Article Text**)
      * ไฟล์บทความเป็นไฟล์สแกน หรือไฟล์ PDF ที่ไม่สามารถคัดลอกข้อความได้
      * ไฟล์ถูกสร้างจากโปรแกรมเวอร์ชันเก่ามาก ทำให้ระบบไม่สามารถอ่านไฟล์ได้
      * เพิ่งอัปโหลดไฟล์ แต่ยังไม่ถึงรอบเวลาการตรวจ (ก่อนเวลา 03.00 น.)
      * บทความยังไม่อยู่ในสถานะ **Submission** หรือ **Review (Revision)** ที่ระบบรองรับการตรวจ


{% endhint %}

***

### <mark style="color:green;">การอ่านค่าความคล้ายของบทความ</mark>

1. จากรูประบบนำบทความไปตรวจความคล้ายเรียบร้อยแล้ว
2. คลิกที่สัญลักษณ์  <mark style="color:blue;">C สีน้ำเงิน</mark> หรือ <mark style="color:red;">C สีแดง</mark>

<figure><img src=".gitbook/assets/Screenshot 2568-12-17 at 09.03.37.png" alt=""><figcaption></figcaption></figure>

ระบบจะแสดงค่าความคล้าย ดังนี้

<figure><img src=".gitbook/assets/Screenshot 2569-01-22 at 14.59.58.png" alt=""><figcaption></figcaption></figure>

1.  **โลโก้ CopyCatch**&#x20;

    แสดงแหล่งข้อมูลที่นำไปตรวจ

    🔵 สีน้ำเงิน = ตรวจเทียบกับบทความที่ยังไม่เผยแพร่

    🔴 สีแดง = ตรวจเทียบกับบทความที่เผยแพร่แล้ว
2. **ชื่อไฟล์บทความที่นำมาตรวจ** \
   เช่น “บทความวิจัย.docx” \
   ซึ่งเป็นไฟล์ Article Text ล่าสุดจากหัว Submission Files หรือ Revision\
   ทั้งนี้ขึ้นอยู่กับสถานะของบทความ
3. **เนื้อหาของบทความ (ฝั่งซ้าย)**
   * ข้อความที่ถูกไฮไลต์สี คือ ส่วนที่ระบบตรวจพบว่ามีความคล้าย
   * ข้อความไฮไลต์สีเดียวกัน หมายถึง ข้อความในบทความ (ฝั่งซ้าย) ซ้ำกับ แหล่งที่พบหมายเลขเดียวกัน (ฝั่งขวา)
4. **เปอร์เซ็นต์ความคล้ายทั้งเอกสาร** \
   เช่น 26.31%\
   แสดงสัดส่วนจำนวนคำที่ซ้ำทั้งหมด (ไฮไลต์สีต่าง ๆ) เทียบกับ จำนวนคำทั้งหมดของบทความ
5. **รายการบทความแหล่งที่พบความคล้าย (ฝั่งขวา)** \
   แสดงรายชื่อบทความต้นทางที่ตรวจพบความคล้าย พร้อมเปอร์เซ็นต์รายแหล่ง \
   เมื่อคลิกชื่อบทความแหล่งที่พบ ระบบจะลิงก์ไปยังบทความต้นทาง\
   ตัวอย่างการอ่าน\
   ข้อความสีแดงในบทความ (ฝั่งซ้าย) ซ้ำกับ แหล่งที่พบลำดับที่ 1 คิดเป็น 27.56% (ฝั่งขวา)

**สรุปง่าย ๆ**

26.31% = บทความที่นำไปตรวจซ้ำกี่เปอร์เซ็นต์

27.56%, 2.94%, 2.74% = ซ้ำกี่เปอร์เซ็นต์ของ “บทความต้นทางแต่ละเรื่อง”

***

### <mark style="color:green;">การตีความค่าเปอร์เซ็นต์</mark>

* แหล่งที่มีจำนวนคำมาก → เปอร์เซ็นต์ความคล้ายจะมีค่าน้อย
* แหล่งที่มีจำนวนคำน้อย → เปอร์เซ็นต์ความคล้ายจะมีค่าสูง
* ค่าตัวเลขเปอร์เซ็นต์เป็นเพียงตัวบ่งชี้เบื้องต้น บรรณาธิการควรพิจารณา “ลักษณะของความซ้ำ” ประกอบด้วย เช่น
  * การซ้ำคำอธิบายทั่วไปหรือข้อความเชิงทฤษฎีที่ใช้ร่วมกันทั่วไป
  * การซ้ำโครงสร้างประโยคหรือรูปแบบการเขียน
  * การคัดลอกเนื้อหาสาระสำคัญโดยตรง
* พิจารณาเจตนาและบริบททางวิชาการ ว่าเป็นการอ้างอิงตามหลักวิชาการที่ถูกต้อง หรือเป็นการนำผลงานผู้อื่นมาใช้โดยไม่เหมาะสม
* <mark style="color:$danger;">**ระบบ Copycatch เป็นเพียงเครื่องมือช่วยตรวจสอบความคล้าย**</mark>\ <mark style="color:$danger;">**การตัดสินความเหมาะสมของบทความยังคงขึ้นอยู่กับดุลยพินิจของบรรณาธิการเป็นสำคัญ**</mark>

***

{% hint style="warning" %}
## ⚠️ หมายเหตุ

1.  **การแสดงผลไฮไลต์สีและแหล่งที่พบความซ้ำ**\
    \- ระบบจะแสดงแหล่งที่พบความซ้ำสูงสุดไม่เกิน 10 แหล่ง\
    \- ข้อความที่ถูกไฮไลต์ด้วยสีเดียวกัน หมายถึง ข้อความในบทความ (ฝั่งซ้าย) ซ้ำกับแหล่งที่พบหมายเลขเดียวกัน (ฝั่งขวา)\
    \- หากในบทความไม่ปรากฏการไฮไลต์สี อาจเกิดได้ 2 กรณี ดังนี้\
    กรณีที่ 1: บทความ**ไม่ซ้ำกับบทความใด ๆ** ระบบจึงไม่แสดงการไฮไลต์สี

    กรณีที่ 2: บทความ**มีข้อความซ้ำ** แต่ข้อความที่ซ้ำทั้งหมดถูกจัดกลุ่มและแสดงอยู่ในรายการแหล่งที่พบครบถ้วนแล้ว จึงไม่ปรากฏการไฮไลต์สีเพิ่มเติมในเนื้อหา
2. **เปอร์เซ็นต์ความคล้าย (ทั้งเอกสาร)**\
   หมายถึง สัดส่วนจำนวนคำที่ซ้ำ เทียบกับ จำนวนคำทั้งหมดของบทความที่นำไปตรวจ\
   **วิธีคำนวณ**\
   จำนวนคำที่ซ้ำ ÷ จำนวนคำทั้งหมดของบทความ × 100
3.  **เปอร์เซ็นต์ความคล้ายกับแหล่งที่พบ (รายแหล่ง)**

    หมายถึง สัดส่วนจำนวนคำที่ซ้ำ เทียบกับ จำนวนคำทั้งหมดของบทความต้นทางแต่ละเรื่อง\
    **วิธีคำนวณ**\
    จำนวนคำที่ซ้ำกับแหล่งนั้น ÷ จำนวนคำทั้งหมดของบทความแหล่งนั้น × 100
4. **ผลรวมของเปอร์เซ็นต์ความคล้ายกับแหล่งที่พบ (รายแหล่ง)&#x20;**<mark style="color:$danger;">**ไม่เท่ากับ**</mark>**&#x20;เปอร์เซ็นต์ความคล้าย (ทั้งเอกสาร)** เนื่องจากใช้ตัวเทียบในการการคำนวณต่างกัน จึงไม่สามารถนำเปอร์เซ็นต์รายแหล่งมารวมให้เท่ากับเปอร์เซ็นต์ทั้งเอกสารได้ โดย\
   \- เปอร์เซ็นต์ความคล้าย (ทั้งเอกสาร) คำนวณจากจำนวนคำของบทความที่นำไปตรวจ\
   \- เปอร์เซ็นต์ความคล้าย (รายแหล่ง) คำนวณจากจำนวนคำของบทความต้นทางแต่ละเรื่อง
5. **กรณีเปอร์เซ็นต์ไม่แสดงผล**\
   ให้ทำการรีเฟรชแบบ Hard Reload\
   \- Windows / Linux : กด Shift + F5\
   \- Mac : กด Cmd + Shift + R
{% endhint %}
