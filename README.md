# 🌐 Computer Networks Final Exam Mastery Suite (Ch 4–8)

> **เว็บแอปพลิเคชันสื่อการเรียนรู้และระบบจำลองข้อสอบวิชา Computer Networks (Final Exam)**  
> รวมแนวข้อสอบ สรุปเข้มเนื้อหา ตัวแก้โจทย์คำนวณ Part B แสดงวิธีทำทีละสเต็ป และคลังคลิปบรรยาย อ.วรา (Vara Varavithya)

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-0e7c7b?style=for-the-badge&logo=github)](https://kong19565.github.io/network-final-mastery/)
[![Offline First](https://img.shields.io/badge/Offline-100%25%20Supported-10b981?style=for-the-badge)](https://kong19565.github.io/network-final-mastery/)
[![Exam Score](https://img.shields.io/badge/Total%20Score-130%20Points-f59e0b?style=for-the-badge)](#โครงสร้างข้อสอบ)

---

## 🚀 ลิงก์เข้าใช้งานบนมือถือ / แท็บเล็ต / ทุกอุปกรณ์
เข้าใช้งานผ่านเบราว์เซอร์ได้ทันที ไม่ต้องติดตั้งโปรแกรมเพิ่มเติม:
👉 **[https://kong19565.github.io/network-final-mastery/](https://kong19565.github.io/network-final-mastery/)**

---

## 📋 โครงสร้างข้อสอบ (130 คะแนนเต็ม)

| ส่วน | รูปแบบ | เนื้อหา / สัดส่วนคะแนน | คำแนะนำสำคัญ |
| :--- | :--- | :--- | :--- |
| **Part A** (Moodle) | ปรนัย (MCQ, T/F, จับคู่) | ครอบคลุมบทที่ 4 – 8 (70 คะแนน) | เน้นความเข้าใจแม่นยำ ระวังโจทย์หลอกนิยาม (CSMA/CD vs CSMA/CA, Checksum vs CRC) |
| **Part B** (Paper) | **ข้อเขียนแสดงวิธีทำ 5 ข้อ** | รวม **60 คะแนน**<br>• RIP: 15 คะแนน<br>• OSPF/Dijkstra: 15 คะแนน<br>• Virtual-Circuit Table: 12 คะแนน<br>• STP: 12 คะแนน<br>• Security & Ethics Case: 6 คะแนน | **เขียนวิธีทำทุกขั้นตอน** ตอบแต่ตัวเลข/ผลลัพธ์จะได้แค่คะแนนบางส่วน (Partial Credit) |

---

## ✨ ฟีเจอร์หลักในระบบ (Core Features)

1. **📋 โครงสร้างข้อสอบ & ยุทธศาสตร์ (Exam Blueprint):** แจกแจงสัดส่วนคะแนน เกณฑ์การให้คะแนน และเทคนิคเก็บคะแนน Part B ให้ครบ
2. **🧠 สรุปเข้ม Ch 4–8 (Concept Mastery):**
   - **Ch 4 Data Plane:** Subnetting (CIDR, /24 → four /26, $2^n-2$ hosts), NAT, DHCP (DORA), VLANs (802.1Q), Datagram vs Virtual Circuit
   - **Ch 5 Control Plane:** RIP vs OSPF, Distance-Vector vs Link-State, Count-to-Infinity, Poison Reverse, BGP, ICMP
   - **Ch 6 Link Layer:** CRC vs Checksum vs FEC, CSMA/CD, Switch Self-Learning, STP, Ethernet Frame
   - **Ch 7 Wireless:** 802.11 Infrastructure, CSMA/CA, Hidden Terminal & RTS/CTS Handshake, 4G vs 5G
   - **Ch 8 Security & Ethics:** CIA Triad, Encryption vs Integrity, ARP Spoofing (MitM), DAI & DHCP Snooping, จริยธรรมวิศวกร (Data Minimisation)
3. **🧮 5 ตัวช่วยแก้โจทย์แสดงวิธีทำ Part B (Step-by-Step Solvers):**
   - **ข้อ 1 (RIP):** แสดงตาราง Round 0, Round 1, Round 2 พร้อมตรวจ Convergence และจำลอง Poison Reverse
   - **ข้อ 2 (OSPF / Dijkstra):** แสดงตาราง $N', D(v), p(v)$ ทีละขั้นตอน พร้อมสรุป Routing Table (Destination, Cost, Next Hop)
   - **ข้อ 3 (Virtual Circuit):** ตาราง Forwarding Table ขาไป ($H_1 \to H_2$) และขากลับ ($H_2 \to H_1$ สลับ In/Out)
   - **ข้อ 4 (Spanning Tree):** ลำดับการเลือก Root Bridge, Root Port, Designated Port, Blocking Port ตามค่า Cost มาตรฐาน (10M=100, 100M=19, 1G=4)
   - **ข้อ 5 (Security & Ethics):** วิเคราะห์เคส ARP Spoofing ตามสามเหลี่ยม CIA + มาตรการ DAI/DHCP Snooping + จริยธรรม 4 ข้อ
4. **🎯 ระบบสอบจำลองเสมือนจริง (Interactive Mock Exam):** แบบฝึกหัดปรนัย 20 ข้อ ตรวจคำตอบทันที คำนวณคะแนนเป็นเปอร์เซ็นต์ พร้อมคำอธิบายเหตุผลทางเทคนิคทุกข้อ
5. **📑 สูตรลัดและตารางเทียบจำด่วน (Cheat Sheet):** รวมตาราง Subnet Mask, ค่า STP Port Cost, ตารางเทียบ Protocol, และจุดดักคำหลอกยอดฮิต
6. **📺 คลังคลิปบรรยาย อ.วรา (Vara Varavithya Vault):** รวมลิงก์คลิปจริงและแอนิเมชันจำลองจากช่อง `@varavithya` ตรงตามหัวข้อสอบ 1:1
7. **🖨️ รองรับ Print to PDF (A4):** จัดเลย์เอาต์เฉพาะการพิมพ์ หน้าไม่ขาดตอน ตารางไม่ถูกตัดแยกหน้า

---

## 📱 การใช้งานบนอุปกรณ์พกพา (Mobile Friendly)
- Responsive Design ปรับขนาดเลย์เอาต์อัตโนมัติบนมือถือทุกรุ่น
- ตัวหนังสืออ่านง่าย คอนทราสต์สูง ไม่ล้าสายตา
- รองรับการเปิดใช้งานแบบ Offline (บันทึกเป็น Web App หรือ Add to Home Screen ได้)
