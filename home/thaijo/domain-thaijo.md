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
    visible: false
  pagination:
    visible: true
  metadata:
    visible: true
---

# 📡 โดเมน (Domain) ในระบบ ThaiJO

## ระบบ ThaiJO แบ่งโดเมน (Domain) ตามสาขาหลักของวารสาร ดังนี้

<table data-full-width="true"><thead><tr><th width="389.711181640625" align="center">สาขาหลักของวารสาร</th><th align="center">จำนวนโดเมน</th></tr></thead><tbody><tr><td align="center"><mark style="color:blue;"><strong>Health Sciences (he)</strong></mark></td><td align="center"><p><mark style="color:blue;"><strong>5</strong></mark></p><p><mark style="color:blue;">https://he01.tci-thaijo.org</mark></p><p><mark style="color:blue;">…</mark></p><p><mark style="color:blue;">https://he05.tci-thaijo.org</mark></p></td></tr><tr><td align="center"><mark style="color:$success;"><strong>Life Sciences (li)</strong></mark></td><td align="center"><p><mark style="color:$success;"><strong>5</strong></mark><br><mark style="color:$success;">https://li01.tci-thaijo.org</mark></p><p><mark style="color:$success;">…</mark></p><p><mark style="color:$success;">https://li05.tci-thaijo.org</mark></p></td></tr><tr><td align="center"><mark style="color:orange;"><strong>Physical Sciences (ph)</strong></mark></td><td align="center"><p><mark style="color:orange;"><strong>5</strong></mark><br><mark style="color:orange;">https://ph01.tci-thaijo.org</mark></p><p><mark style="color:orange;">…</mark></p><p><mark style="color:orange;">https://ph05.tci-thaijo.org</mark></p></td></tr><tr><td align="center"><mark style="color:red;"><strong>Social Sciences &#x26; Humanities (so)</strong></mark></td><td align="center"><p><mark style="color:red;"><strong>20</strong></mark><br><mark style="color:red;">https://so01.tci-thaijo.org</mark></p><p><mark style="color:red;">…</mark></p><p><mark style="color:red;">https://so20.tci-thaijo.org</mark></p></td></tr><tr><td align="center"><strong>รวม</strong></td><td align="center"><strong>35</strong></td></tr></tbody></table>

<p align="right"><em>ข้อมูล ณ วันที่ 9 ม.ค. 66</em></p>

## 📍**โครงสร้างโดเมนและวารสาร**

<figure><img src="../.gitbook/assets/Pic-Domain.png" alt="โดเมนในระบบ ThaiJO"><figcaption><p align="center">โดเมนในระบบ ThaiJO</p></figcaption></figure>

* แต่ละโดเมนมีวารสารอยู่ภายใน **(\~100 วารสาร/โดเมน)**
* การเข้าสู่ระบบจะใช้บัญชี **SSO** (Email + Password เดียว) ได้ทุกโดเมน&#x20;

{% hint style="danger" %}
<mark style="color:red;">**ข้อจำกัด**</mark>❗️ การค้นหาผู้ใช้เพื่อนำไป**มอบหมายบทบาท** เช่น ผู้ประเมิน หรือบรรณาธิการ ผู้ใช้นั้น<mark style="color:red;">**ต้องมีบัญชีอยู่ในโดเมนเดียวกัน**</mark> หากยังไม่มีบัญชี ผู้ใช้สามารถเข้าสู่เว็บไซต์วารสารของโดเมนอื่นโดยใช้ <mark style="color:purple;">**อีเมลเดิม**</mark> เพื่อเพิ่มบทบาทในวารสาร หรือวารสารสามารถสร้างบัญชีให้กับผู้ใช้โดยใช้ <mark style="color:purple;">**อีเมลเดิม**</mark>**&#x20;**<mark style="color:green;">**เพื่อเชื่อมโยงกับ SSO**</mark>
{% endhint %}

## 🔷 ตัวอย่าง

#### <mark style="color:blue;">**1. Health Sciences (he) - 5 โดเมน**</mark>

* **โดเมน he01.tci-thaijo.org**
  * `https://`**`he01`**`.tci-thaijo.org/index.php/`**`nah`**
  * `https://`**`he01`**`.tci-thaijo.org/index.php/`**`JHematolTransfusMed`**

* **โดเมน he02.tci-thaijo.org**
  * `https://`**`he02`**`.tci-thaijo.org/index.php/`**`jnphr`**
  * `https://`**`he02`**`.tci-thaijo.org/index.php/`**`jaas_muvs`**

* <kbd>...</kbd>

***

#### <mark style="color:$success;">**2. Life Sciences (li) - 5 โดเมน**</mark>

* **โดเมน li01.tci-thaijo.org**
  * `https://`**`li01`**`.tci-thaijo.org/index.php/`**`anres`**
  * `https://`**`li01`**`.tci-thaijo.org/index.php/`**`tnh`**

* **โดเมน li02.tci-thaijo.org**
  * `https://`**`li02`**`.tci-thaijo.org/index.php/`**`ssstj`**
  * `https://`**`li02`**`.tci-thaijo.org/index.php/`**`JASM`**

* <kbd>...</kbd>

***

#### <mark style="color:orange;">**3. Physical Sciences (ph) - 5 โดเมน**</mark>

* **โดเมน ph01.tci-thaijo.org**
  * `https://`**`ph01`**`.tci-thaijo.org/index.php/`**`JIE`**
  * `https://`**`ph01`**`.tci-thaijo.org/index.php/`**`easr`**

* **โดเมน ph02.tci-thaijo.org**
  * `https://`**`ph02`**`.tci-thaijo.org/index.php/`**`swujournal`**
  * `https://`**`ph02`**`.tci-thaijo.org/index.php/`**`gskku`**

* <kbd>...</kbd>

***

#### <mark style="color:red;">**4. Social Sciences & Humanities (so) – 20 โดเมน**</mark>

* **โดเมน so01.tci-thaijo.org**
  * `https://`**`so01`**`.tci-thaijo.org/index.php/`**`NUR_YIU`**
  * `https://`**`so01`**`.tci-thaijo.org/index.php/`**`CBSReview`**

* **โดเมน so02.tci-thaijo.org**
  * `https://`**`so02`**`.tci-thaijo.org/index.php/`**`jica`**
  * `https://`**`so02`**`.tci-thaijo.org/index.php/`**`SNGSJ`**

* <kbd>...</kbd>

***
