# 📕 คู่มือการใช้งานระบบการตรวจสอบความคล้าย (Copycatch)

## รูปแบบการตรวจสอบความคล้าย (Copycatch)

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

การตรวจสอบความคล้ายระหว่าง

{% columns %}
{% column width="41.66666666666667%" valign="middle" %}
#### **1) สถานะ Submission**

<figure><img src=".gitbook/assets/submission.png" alt="" width="128"><figcaption></figcaption></figure>

<p align="center">บทความที่ส่งเข้าระบบใหม่</p>

<p align="center">ไฟล์ <mark style="background-color:yellow;"><strong>Article Text ล่าสุด</strong></mark><br>ในหัวข้อ <mark style="color:orange;"><strong>Submission Files</strong></mark></p>
{% endcolumn %}

{% column width="16.666666666666668%" %}
_**เทียบกับ**_
{% endcolumn %}

{% column width="41.66666666666664%" %}
<h4 align="center"><strong>สถานะ Unpublished</strong></h4>

<p align="center">บทความอื่น ๆ ที่ยังไม่เผยแพร่ในระบบ</p>
{% endcolumn %}
{% endcolumns %}

<figure><img src=".gitbook/assets/Screenshot 2568-12-16 at 11.50.18.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
* ระบบจะนำไฟล์ <mark style="background-color:yellow;">**Article Text ล่าสุด**</mark> ไปตรวจอัตโนมัติ ตั้งแต่ เวลา 03.00 น. ของทุกวัน และ<mark style="color:red;background-color:yellow;">**ทำครั้งเดียวเท่านั้น**</mark>
* <img src=".gitbook/assets/copycatch-grey.png" alt="C สีเทา" data-size="line"> C สีเทา หมายถึง ยังไม่มีผลการตรวจสอบความคล้าย เนื่องจาก
  * เกิดปัญหาในการตรวจไฟล์นั้น ๆ
  * บทความยังไม่อยู่ในสถานะที่สามารถนำไปตรวจได้
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

การตรวจสอบความคล้ายระหว่าง

{% columns %}
{% column width="41.66666666666667%" valign="middle" %}
#### **1) สถานะ Submission**

<figure><img src=".gitbook/assets/submission.png" alt="" width="128"><figcaption></figcaption></figure>

<p align="center">บทความที่ส่งเข้าระบบใหม่</p>

<p align="center">ไฟล์ <mark style="background-color:yellow;"><strong>Article Text ล่าสุด</strong></mark><br>ในหัวข้อ <mark style="color:orange;"><strong>Submission Files</strong></mark></p>
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

<figure><img src=".gitbook/assets/Screenshot 2568-12-16 at 11.50.18.png" alt=""><figcaption></figcaption></figure>

{% columns %}
{% column width="41.66666666666667%" valign="middle" %}
#### **2) สถานะ Review**

<figure><img src=".gitbook/assets/review.png" alt="" width="97"><figcaption></figcaption></figure>

<p align="center">บทความที่มีการแก้ไข</p>

<p align="center">ไฟล์ <mark style="background-color:yellow;"><strong>Article Text ล่าสุด</strong></mark><br>ในหัวข้อ <mark style="color:purple;"><strong>Revisions</strong></mark></p>
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

<figure><img src=".gitbook/assets/Screenshot 2568-12-16 at 14.20.04 (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
* ระบบจะนำไฟล์ <mark style="background-color:yellow;">**Article Text ล่าสุด**</mark> ไปตรวจอัตโนมัติ ตั้งแต่ เวลา 03.00 น. ของทุกวัน และ<mark style="color:red;background-color:yellow;">**ทำทุกครั้งที่มีการเปลี่ยนไฟล์**</mark>
* <img src=".gitbook/assets/copycatch-grey.png" alt="C สีเทา" data-size="line"> C สีเทา หมายถึง ยังไม่มีผลการตรวจสอบความคล้าย เนื่องจาก
  * เกิดปัญหาในการตรวจไฟล์นั้น ๆ
  * บทความยังไม่อยู่ในสถานะที่สามารถนำไปตรวจได้
{% endhint %}
