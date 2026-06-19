# 🚫 การถอดถอนบทความ (Retraction)

**การถอดถอนบทความ (Retraction)** เป็นกระบวนการดำเนินการกับ<mark style="color:$danger;">**บทความที่พบปัญหาด้านความน่าเชื่อถือของผลการวิจัย**</mark> _หรือ_ <mark style="color:$danger;">**ประเด็นด้านจริยธรรมและจรรยาบรรณการตีพิมพ์**</mark> วารสารควรดำเนินการอย่างโปร่งใสและเป็นไปตามหลักจริยธรรม พร้อมแสดงสถานะการถอดถอนให้สามารถสืบค้นได้ในฐานข้อมูลและระบบดัชนีต่าง ๆ เพื่อให้ผู้อ่านรับทราบว่าบทความดังกล่าวถูกถอดถอนแล้ว

{% hint style="info" %}
หมายเหตุ

ห้ามลบบทความที่ถูกถอดถอออกจากระบบ แต่ยังคงบทควานไว้ในระบบ โดยแสดงสถานะ "**Retracted**" อย่างชัดเจน เพื่อรักษาความสมบูรณ์ของบันทึกทางวิชาการ และความต่อเนื่องของเลขหน้าในฉบับวารสาร
{% endhint %}

### ✅ <mark style="color:green;">แนวทางการดำเนินการ</mark>

#### <mark style="color:red;background-color:yellow;">**1. เพิ่มลายน้ำ (Watermark) ทุกหน้าของไฟล์ PDF**</mark>

* เพิ่มลายน้ำ (Watermark) คำว่า **"RETRACTED"** หรือ **"RETRACTED ARTICLE"** บนทุกหน้าของไฟล์ PDF เพื่อระบุว่าบทความถูกถอดถอน
* แทนที่ไฟล์ PDF ที่เพิ่มลายน้ำในระบบโดยใช้ **Change file** ใน **Galleys**

<div><figure><img src=".gitbook/assets/RETRACTED-1.png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src=".gitbook/assets/Screenshot 2568-09-09 at 14.06.07.png" alt="" width="563"><figcaption></figcaption></figure></div>

{% hint style="info" %}
**ตัวอย่าง**

[https://www.thelancet.com/action/showPdf?pii=S0140-6736%2897%2911096-0](https://www.thelancet.com/action/showPdf?pii=S0140-6736%2897%2911096-0)
{% endhint %}

***

#### <mark style="color:red;background-color:yellow;">**2. แก้ไขชื่อบทความใน Metadata**</mark>&#x20;

เพิ่มคำว่า "**\[RETRACTED ARTICLE]"** หรือ **"RETRACTED ARTICLE"** หรือ **"RETRACTED"** หน้า **ชื่อบทความ**

> เช่น
>
> * **\[RETRACTED ARTICLE]** Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua
> * **RETRACTED:** Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua

{% hint style="info" %}
**ตัวอย่าง**

* [https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(97)11096-0/fulltext](https://www.thelancet.com/journals/lancet/article/PIIS0140-6736\(97\)11096-0/fulltext)
* [https://link.springer.com/article/10.1007%2Fs13277-012-0340-4](https://link.springer.com/article/10.1007%2Fs13277-012-0340-4)
{% endhint %}

***

#### <mark style="color:red;background-color:yellow;">**3. ระบุเหตุผลการถอดถอนบทความ**</mark>

* เพิ่มข้อความแจ้งการถอดถอนและเหตุผลการถอดถอนในส่วนเนื้อหาของบทคัดย่อ ทั้งภาษาไทยและภาษาอังกฤษ

{% hint style="info" %}
การระบุเหตุผลควรใช้ถ้อยคำที่เป็นข้อเท็จจริง มีความเป็นกลาง และหลีกเลี่ยงการกล่าวหาหรือใช้ถ้อยคำที่อาจก่อให้เกิดความเสียหายแก่บุคคล
{% endhint %}

<figure><img src=".gitbook/assets/RETRACTED-2.png" alt=""><figcaption></figcaption></figure>

***

#### <mark style="color:red;background-color:yellow;">**4. เผยแพร่ประกาศการถอดถอน (Retraction) (ถ้ามี)**</mark>

วารสารอาจเผยแพร่ประกาศการถอดถอนในรูปแบบบทความแยกต่างหาก โดยจัดอยู่ในประเภทบทความ (Section) ที่กำหนดขึ้นสำหรับการถอดถอน เช่น Retraction Note, Retraction Notice หรือ บทบรรณาธิการ (Editor's Note)

<mark style="color:green;">**ขั้นตอนการดำเนินการ**</mark>

1. สร้างประเภทบทความ (Section) สำหรับการถอดถอน เช่น Retraction Notice หรือ Retraction Note
2. สร้างบทความใหม่เพื่อใช้เป็นประกาศการถอดถอน และเผยแพร่ในฉบับปัจจุบันหรือฉบับที่วารสารกำหนด (วารสารที่ใช้ระบบ OJS หรือ ThaiJO สามารถนำเข้าบทความประกาศถอดถอนด้วยใช้วิธี Quick Submit)
3. จัดทำเนื้อหาประกาศการถอดถอน โดยระบุข้อมูลของบทความที่ถูกถอดถอนให้ครบถ้วน ได้แก่

* ชื่อบทความ
* ชื่อผู้เขียน
* ปีที่ (Volume)
* ฉบับที่ (Issue)
* เลขหน้า
* DOI (ถ้ามี)
* เหตุผลในการถอดถอน

ทั้งนี้ ควรใช้ถ้อยคำเชิงข้อเท็จจริง เป็นกลาง และหลีกเลี่ยงการกล่าวหา

4. เพิ่มรายการอ้างอิง (References) ในประกาศการถอดถอน โดยอ้างอิงถึงบทความที่ถูกถอดถอน และในกรณีที่เกี่ยวข้องกับการละเมิดจริยธรรมการวิจัยหรือการตีพิมพ์ อาจอ้างอิงเอกสารหรือแนวปฏิบัติที่เกี่ยวข้อง เช่น COPE Retraction Guidelines หรือหลักจริยธรรมการตีพิมพ์ของวารสาร
5. เชื่อมโยง (Link) ระหว่างประกาศการถอดถอนและบทความที่ถูกถอดถอน เช่น

* เพิ่ม URL ของบทความที่ถูกถอดถอนในประกาศการถอดถอน
* เพิ่ม URL ของประกาศการถอดถอนในบทความที่ถูกถอดถอน
* เพิ่มข้อมูลการเชื่อมโยงใน Metadata ของทั้งสองรายการ
* ตรวจสอบการแสดงผลบนเว็บไซต์วารสาร เพื่อให้ผู้อ่านสามารถเข้าถึงทั้งบทความที่ถูกถอดถอนและประกาศการถอดถอนได้อย่างถูกต้อง

{% hint style="info" %}
**ตัวอย่าง**

* [https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(10)60175-4/fulltext](https://www.thelancet.com/journals/lancet/article/PIIS0140-6736\(10\)60175-4/fulltext)
{% endhint %}

***

#### <mark style="color:red;background-color:yellow;">**5. แจ้งฐานข้อมูลดัชนีและการสืบค้น**</mark>

เมื่อดำเนินการถอดถอนบทความเรียบร้อยแล้ว วารสารควรแจ้งและอัปเดตสถานะ **“Retracted”** ไปยังฐานข้อมูลและหน่วยงานที่เกี่ยวข้อง เช่น TCI, Scopus, DOAJ และ Crossref เพื่อให้สถานะการถอดถอนของบทความเป็นปัจจุบัน และแสดงผลสอดคล้องกันในทุกระบบสืบค้น

***

### 📝 <mark style="color:green;">**แนวทางการปฏิบัติที่เกี่ยวข้องกับ TCI**</mark>

เมื่อวารสารดำเนินการถอดถอนบทความแล้ว ขอให้วารสารทำหนังสือแจ้งกลับมายังศูนย์ TCI ทางอีเมล [tci.thai@gmail.com](mailto:tci.thai@gmail.com) เพื่อที่ทางศูนย์ TCI ดำเนินการแก้ไขข้อมูลบทความดังกล่าวในฐานข้อมูล TCI ต่อไป

{% hint style="danger" %}
**หมายเหตุ**

* วารสารอาจพิจารณาทำหนังสือแจ้งผู้บังคับบัญชาสูงสุดของหน่วยงานต้นสังกัดของผู้เขียน
* วารสารอาจพิจารณางดรับพิจารณาบทความจากผู้เขียนรายดังกล่าวเป็นระยะเวลาหนึ่งตามที่เห็นสมควร

แนวทางดังกล่าวเป็นเพียงข้อแนะนำจากศูนย์ TCI ซึ่งท่านสามารถปรับใช้ได้ตามสมควร
{% endhint %}

{% hint style="info" %}
⚠️ **กรณีลบบทความออกจากเว็บไซต์ไปแล้ว**

ศูนย์ TCI ขอความกรุณานำบทความดังกล่าวกลับขึ้นเผยแพร่ในระบบอีกครั้ง โดยดำเนินการดังนี้

* เพิ่มข้อความ **\[RETRACTED ARTICLE]** หน้าชื่อบทความ
* เพิ่มลายน้ำ (Watermark) คำว่า **RETRACTED** บนทุกหน้าของไฟล์ PDF
* แสดงสถานะการถอดถอนบนหน้าเว็บไซต์บทความอย่างชัดเจน

แนวทางดังกล่าวจะช่วยรักษาความต่อเนื่องของเลขหน้า ความสมบูรณ์ของฉบับวารสาร และความถูกต้องของบันทึกทางวิชาการ
{% endhint %}

***

### <mark style="color:$success;">🔗</mark> <mark style="color:green;">**แหล่งข้อมูลอื่น ๆ ที่เกี่ยวข้อง**</mark>

* **เว็บไซต์สำหรับค้นหาบทความที่ถูกถอน:** [http://retractiondatabase.org/RetractionSearch.aspx?](http://retractiondatabase.org/RetractionSearch.aspx?)
* **COPE’s Retraction Guidelines:** [https://publicationethics.org/guidance/guideline/retraction-guidelines](https://publicationethics.org/guidance/guideline/retraction-guidelines)
