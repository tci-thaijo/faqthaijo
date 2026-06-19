# 🚫 การถอดถอนบทความ (Retraction)

**การถอดถอนบทความ (Retraction)** เป็นกระบวนการดำเนินการกับ<mark style="color:$danger;">**บทความที่พบปัญหาด้านความน่าเชื่อถือของผลการวิจัย**</mark> _หรือ_ <mark style="color:$danger;">**ประเด็นด้านจริยธรรมและจรรยาบรรณการตีพิมพ์**</mark> วารสารควรดำเนินการอย่างโปร่งใสและเป็นไปตามหลักจริยธรรม พร้อมแสดงสถานะการถอดถอนให้สามารถสืบค้นได้ในฐานข้อมูลและระบบดัชนีต่าง ๆ เพื่อให้ผู้อ่านรับทราบว่าบทความดังกล่าวถูกถอดถอนแล้ว

### ✅ <mark style="color:green;">**วิธีการดำเนินการ**</mark>

#### <mark style="color:red;background-color:yellow;">**1. เพิ่มลายน้ำ (Watermark) บททุกหน้าของไฟล์ PDF**</mark>

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

* เพิ่มข้อความแจ้งการถอดถอนและเหตุผลในการถอดถอนในส่วนเนื้อหาของบทคัดย่อ ทั้งภาษาไทยและภาษาอังกฤษ
* ใช้ถ้อยคำเชิงข้อเท็จจริง เป็นกลาง และหลีกเลี่ยงการกล่าวหา

<figure><img src=".gitbook/assets/RETRACTED-2.png" alt=""><figcaption></figcaption></figure>

***

#### <mark style="color:red;background-color:yellow;">**4. เผยแพร่ประกาศการถอดถอน (Retraction) (ถ้ามี)**</mark>

วารสารอาจเผยแพร่ประกาศการถอดถอนในรูปแบบบทความแยกต่างหาก โดยจัดอยู่ในประเภทบทความ (Section) ที่กำหนดขึ้นสำหรับการถอดถอน เช่น Retraction Note, Retraction Notice หรือ บทบรรณาธิการ (Editor's Note)

ขั้นตอนการดำเนินการ

1. สร้างประเภทบทความ (Section) สำหรับการถอดถอน เช่น Retraction Notice หรือ Retraction Note
2. สร้างบทความใหม่เพื่อใช้เป็นประกาศการถอดถอน และเผยแพร่ในฉบับปัจจุบันหรือฉบับที่วารสารกำหนด (วารสารที่ใช้ระบบ OJS หรือ ThaiJO สามารถนำบทความประกาศถอดถอนเข้าสู่ระบบด้วยใช้วิธี Quick Submit)
3. จัดทำเนื้อหาประกาศการถอดถอน โดยระบุข้อมูลของบทความที่ถูกถอดถอนให้ครบถ้วน ได้แก่

* ชื่อบทความ
* ชื่อผู้เขียน
* ปีที่ (Volume)
* ฉบับที่ (Issue)
* เลขหน้า
* DOI (ถ้ามี)
* เหตุผลในการถอดถอน

ทั้งนี้ ควรใช้ถ้อยคำเชิงข้อเท็จจริง เป็นกลาง และหลีกเลี่ยงการกล่าวหา

* เพิ่มเอกสารอ้างอิง (References) ในประกาศการถอดถอน โดยอ้างอิงถึงบทความที่ถูกถอดถอน และในกรณีที่เกี่ยวข้องกับการละเมิดจริยธรรมการวิจัยหรือการตีพิมพ์ อาจอ้างอิงเอกสารหรือแนวปฏิบัติที่เกี่ยวข้อง เช่น COPE Retraction Guidelines หรือหลักจริยธรรมการตีพิมพ์ของวารสาร
* เชื่อมโยง (Link) ระหว่างประกาศการถอดถอนและบทความที่ถูกถอดถอน เช่น
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

* แจ้งและอัปเดตสถานะ “Retracted” ไปยังฐานข้อมูลดัชนีที่เกี่ยวข้อง เช่น TCI, Scopus, DOAJ, Crossref เป็นต้น เพื่อให้แสดงผลสถานะการถอดถอนอย่างถูกต้องและสอดคล้องกันในทุกระบบสืบค้น

***

### 📝 <mark style="color:green;">**แนวทางการปฏิบัติที่เกี่ยวข้องกับ TCI**</mark>

1\. หากวารสารได้ดำเนินการไปแล้วอย่างไร ขอให้วารสารทำหนังสือแจ้งกลับมายังศูนย์ TCI ทางอีเมล [tci.thai@gmail.com](mailto:tci.thai@gmail.com) เพื่อที่ทางศูนย์ TCI ดำเนินการแก้ไขข้อมูลบทความดังกล่าวในฐานข้อมูล TCI ต่อไป

2\. ทำหนังสืออย่างเป็นทางการแจ้งผู้บังคับบัญชาสูงสุดของหน่วยงานของเจ้าของบทความ

3\. อาจงดรับพิจารณาบทความของผู้เขียนคนดังกล่าวเป็นระยะเวลา 5 ปี

{% hint style="danger" %}
**หมายเหตุ**

แนวทางดังกล่าวเป็นเพียงข้อแนะนำจากศูนย์ TCI ซึ่งท่านสามารถปรับใช้ได้ตามสมควร
{% endhint %}

⚠️ นอกจากนี้ ในกรณีที่ท่านดำเนินการ**ลบบทความออกจากฉบับที่เผยแพร่**ไปแล้วนั้น ศูนย์ TCI ขอความกรุณาจากท่าน นำบทความดังกล่าว (ที่คงคำว่า “**\[RETRACTED ARTICLE]**” **หน้าชื่อของบทความ**และ**คาดลายน้ำ (Watermark)** คำว่า “**RETRACTED**” ลงบนทุกหน้าของบทความแล้วนั้น) **นำกลับขึ้นเผยแพร่ดังเดิม** เพื่อคงไว้ซึ่งความต่อเนื่องของเลขหน้าและรักษาความสมบูรณ์ของฉบับ

***

### <mark style="color:$success;">🔗</mark> <mark style="color:green;">**แหล่งข้อมูลอื่น ๆ ที่เกี่ยวข้อง**</mark>

* **เว็บไซต์สำหรับค้นหาบทความที่ถูกถอน:** [http://retractiondatabase.org/RetractionSearch.aspx?](http://retractiondatabase.org/RetractionSearch.aspx?)
* **COPE’s Retraction Guidelines:** [https://publicationethics.org/guidance/guideline/retraction-guidelines](https://publicationethics.org/guidance/guideline/retraction-guidelines)
