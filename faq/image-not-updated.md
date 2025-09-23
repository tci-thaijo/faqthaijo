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

# 15. ทำไมอัปโหลดรูปภาพหน้าแรกใหม่แล้ว แต่หน้าเว็บไซต์จึงยังคงแสดงรูปภาพเดิม?

### <mark style="color:$success;">**สาเหตุที่พบบ่อย**</mark> <a href="#undefined" id="undefined"></a>

มี 2 กรณี ดังนี้

### **1. Cache ของ Browser (เช่น Chrome, Microsoft Edge, Safari, Mozilla Firefox)**

* Browser มักจะเก็บรูปภาพไว้ในเครื่องเพื่อให้โหลดเว็บเร็วขึ้น ทำให้ยังเห็นเป็นรูปเดิม
* <mark style="color:blue;">**วิธีตรวจสอบ:**</mark> ลองเปิดจากมือถือ ถ้าในมือถือเห็นเป็นรูปใหม่ แสดงว่าเป็นปัญหาจาก Cache ของ Browser
* <mark style="color:red;">**วิธีแก้ไข:**</mark> กด **Shift + F5** หรือ **Ctrl + Shift + R** (Mac ใช้ **Command + Shift + R**) หรือ **เคลียร์ Cache ของ Browser**

### **2. Cache ของ Server**

* หากทดสอบในมือถือแล้วยังเห็นเป็นรูปเดิม แสดงว่าระบบยังเก็บ Cache ของไฟล์ภาพไว้ที่ Server
* โดยทั่วไประบบจะอัปเดตภายใน **2–3 วัน**
* หากเกินเวลานี้แล้วยังไม่เปลี่ยน โปรดแจ้งผู้ดูแลระบบ
