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
* การตรวจสอบในกรณีนี้ <mark style="color:red;background-color:yellow;">**ดำเนินการเพียงครั้งเดียวเท่านั้น**</mark>\
  หากมีการอัปโหลดไฟล์ **Article Text** เพิ่มเติมในหัวข้อ **Submission Files** ระบบจะ **ไม่นำไฟล์ไปตรวจซ้ำ**
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
      * บทความยังไม่อยู่ในสถานะ **Submission / Review: Revision** ที่ระบบรองรับการตรวจ


{% endhint %}

***

### <mark style="color:green;">การอ่านค่าความคล้ายของบทความ</mark>

<figure><img src=".gitbook/assets/Screenshot 2568-12-17 at 09.03.37.png" alt=""><figcaption></figcaption></figure>

1. เมื่อคลิกที่สัญลักษณ์
