# link ส่ง อ.จีระวรรณ
https://drive.google.com/drive/folders/1jRMFS1XR94FbqeBwpmKtLuFjNt2D6XZV?usp=sharing วีดีโอ


# 🏢 LuxeDorm — Apartment Management System

ระบบจัดการหอพัก (Apartment / Dormitory Management System) พัฒนาด้วย Django  
รองรับการจัดการผู้เช่า ห้องพัก บิลค่าเช่า มิเตอร์ การชำระเงิน และงานแจ้งซ่อม

---

## 🚀 Features

- 👤 ระบบผู้ใช้งาน (Admin / Staff / Tenant)
- 🏠 จัดการห้องพัก (Rooms Management)
- 🧾 ออกใบแจ้งหนี้ (Invoice System)
- 💡 จัดการมิเตอร์น้ำ-ไฟ (Meter Reading)
- 💰 ระบบชำระเงิน (Payment Tracking)
- 🔧 แจ้งซ่อม (Repair Requests)
- 📦 จัดการพัสดุ (Parcel Management)
- 📊 Dashboard แสดงภาพรวมระบบ

---

## 🧑‍💻 Tech Stack

- **Backend:** Django 6
- **Frontend:** Bootstrap 5, HTML, CSS
- **Database:** SQLite / PostgreSQL
- **Language:** Python 3.13

---

## 📸 Screenshots

> (ใส่ภาพหน้าจอระบบตรงนี้ เช่น Dashboard, Tenant Page)

---

## ⚙️ Installation

```bash
# Clone project
git clone https://github.com/your-username/luxedorm.git

cd luxedorm

# Create virtual environment
python -m venv venv

# Activate
venv\Scripts\activate   # Windows
source venv/bin/activate  # Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Run server
python manage.py runserver


System Flow


<img width="1619" height="328" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/02431081-2264-4ae2-90c9-3fa53bce567d" />

