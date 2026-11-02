# 📚 ByteBooks — ร้านหนังสือคอมพิวเตอร์และเทคโนโลยี (Clean & Minimalist Tech Bookstore)

> เว็บไซต์ร้านหนังสือคอมพิวเตอร์และเทคโนโลยี ออกแบบด้วยแนวคิด **Minimalist & Clean UX/UI** เรียบง่าย สบายตา ใช้งานง่าย ค้นหาหนังสือได้รวดเร็ว พร้อมข้อมูลสารบัญและเนื้อหาย่อครบถ้วน

---

## 🌐 ตัวอย่างเว็บไซต์ออนไลน์ (Live Demo)
สามารถเข้าชมเว็บไซต์จริงผ่าน GitHub Pages:  
🔗 **[https://kannikacxkthxng-cpu.github.io/Lab1_1/](https://kannikacxkthxng-cpu.github.io/Lab1_1/)**

---

## ✨ จุดเด่นและการออกแบบ (Key Highlights & Features)

### 1. การออกแบบที่เน้นความเรียบง่าย สบายตา (Minimalist UX/UI)
- **Palette โทนสีเทคโนโลยี:** ใช้สีขาวและเทาอ่อนสว่าง (`Slate-50`) เพื่อความสบายตาเวลาอ่านชื่อหนังสือ ตัดด้วยสีน้ำเงินเทคโนโลยี (`Royal Blue #2563EB`)
- **Typography:** ใช้ตัวอักษร **Prompt** และ **Inter** จาก Google Fonts ที่ทันสมัย ชัดเจน และอ่านง่ายทุกหน้าจอ
- **Responsive 100%:** รองรับการแสดงผลทั้งบนสมาร์ตโฟน แท็บเล็ต และคอมพิวเตอร์เดสก์ท็อป

### 2. ระบบค้นหาและตัวกรองที่ใช้งานง่าย (Search & Filtering)
- 🔍 **Real-time Instant Search:** พิมพ์ค้นหาตามชื่อหนังสือ ผู้แต่ง หรือภาษาเขียนโค้ดได้ทันทีแบบไม่ต้องรีเฟรชหน้าเว็บ
- 🏷️ **Category Filter Tabs:** กรองหนังสือตามหมวดหมู่ได้ในคลิกเดียว:
  - 💻 **การเขียนโปรแกรม (Programming):** Python, React & Node.js, JavaScript
  - 🤖 **AI & Data Science:** Machine Learning, SQL & Database Design
  - 🔒 **ความมั่นคงปลอดภัยไซเบอร์ (Cybersecurity):** Cybersecurity 101
  - ☁️ **Cloud & DevOps:** Docker & Kubernetes
  - 🖥️ **พื้นฐานคอมพิวเตอร์ (Computer Basics & Network):** Computer Architecture, Network Fundamentals
- 🔃 **Sort By:** จัดเรียงหนังสือตามยอดนิยม, มาใหม่ล่าสุด หรือเรียงตามราคา (ต่ำ-สูง / สูง-ต่ำ)

### 3. ฟังก์ชันเสริมเพื่อประสบการณ์การซื้อที่ลื่นไหล
- 📖 **Book Detail Modal:** คลิกดูรายละเอียดเนื้อหาโดยย่อ สารบัญเด่น จำนวนหน้า และระดับความเหมาะสมของผู้เรียน (Zero to Hero / Intermediate)
- 🛒 **Slide-over Cart Drawer:** ตะกร้าสินค้าด้านข้างพร้อมระบบคำนวณยอดเงินรวมและค่าจัดส่งฟรี
- ❤️ **Wishlist:** บันทึกหนังสือเล่มที่ถูกใจไว้ดูย้อนหลัง
- 🧭 **Learning Guide for Beginners:** ส่วนแนะนำเส้นทางการเริ่มต้นศึกษาสำหรับมือใหม่ (สายโปรแกรมมิ่ง, สายข้อมูล & AI, สายระบบ & เน็ตเวิร์ก)

---

## 🛠️ เทคโนโลยีที่ใช้ (Tech Stack)

- **HTML5:** Semantic Web Elements โครงสร้างมาตรฐาน สะอาดและถูกต้อง
- **CSS Framework:** [Tailwind CSS (v3 CDN)](https://tailwindcss.com/)
- **Typography:** [Google Fonts](https://fonts.google.com/) (`Prompt` & `Inter`)
- **Icons:** [Lucide Icons](https://lucide.dev/) (Minimalist SVG Icons)
- **JavaScript (Vanilla JS):** จัดการ State ค้นหา, กรองหมวดหมู่, ป๊อปอัป Modal, ตะกร้าสินค้า และ Toast Notification

---

## 📂 โครงสร้างโฟลเดอร์ (Project Structure)

```text
├── index.html               # หน้าแรกของเว็บไซต์ ByteBooks (Main Landing Page)
├── README.md                # เอกสารประกอบโปรเจกต์
├── ร้านหนังสือ/              # โฟลเดอร์สำรองข้อมูลและไฟล์ต้นฉบับ
│   └── index.html           # ไฟล์หน้าเว็บ ByteBooks
├── ระบบของหาย/              # โปรเจกต์ระบบของหาย (Lost & Found Infographic)
└── images/                  # ไฟล์รูปภาพและสื่อประกอบ
```

---

## 🚀 วิธีการเปิดใช้งานบนเครื่องของคุณ (Getting Started)

1. Clone หรือ Download Repository นี้:
   ```bash
   git clone https://github.com/kannikacxkthxng-cpu/Lab1_1.git
   ```
2. ดับเบิลคลิกเปิดไฟล์ `index.html` ผ่านเว็บเบราว์เซอร์ใดก็ได้ (Chrome, Edge, Safari, Firefox) ใช้งานได้ทันทีโดยไม่ต้องติดตั้งหรือรันเซิร์ฟเวอร์

---

© 2026 ByteBooks. Designed with Clean & Minimalist UX/UI for Tech Learners.
