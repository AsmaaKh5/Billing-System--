> 🇸🇦 [اقرأ التوثيق بالعربي](README.ar.md)

# 📄 Invoice Management System

A complete and lightweight invoice management system built entirely with **HTML + CSS + JavaScript** — no external libraries or frameworks required. Runs directly in the browser and stores all data locally using `localStorage`.

---

## 🎯 Demo

Simply open `index.html` in any modern browser to start using the system.

---

## ✨ Features

### 📊 Dashboard
- Real-time statistics (total invoices, revenue, paid, pending)
- Quick view of the latest 5 invoices

### 📄 Invoice Management
- Create invoices with multiple line items
- Automatic subtotal, VAT (15%), and grand total calculation
- Toggle invoice status (Paid / Pending / Overdue)
- Professional print-ready invoice view
- Search by invoice number or customer name
- Delete invoices

### 👥 Customer Management
- Add customers (name, phone, email, company, address)
- Search and filter customers
- Delete customers

### 📦 Products & Services
- Add products with price and description
- Delete products

### 🖨️ Print Support
- Clean print layout for invoices
- Auto-hides UI elements during printing

### 📱 Responsive Design
- Fully responsive on desktop, tablet, and mobile
- Collapsible sidebar on small screens

---

## 🛠️ Technologies

| Technology | Usage |
|------------|-------|
| **HTML5** | Page structure and semantic markup |
| **CSS3** | Styling — Grid, Flexbox, CSS Variables, Media Queries |
| **JavaScript (Vanilla)** | Business logic, DOM manipulation, data management |
| **localStorage** | Client-side data persistence |

---

## 🚀 Getting Started

1. Clone the repository: `git clone https://github.com/AsmaaKh5/invoice-system.git`
2. Navigate to the project: `cd invoice-system`
3. Open `index.html` in any modern browser or use VS Code Live Server extension
4. Start using:
   - Add customers from the **Customers** section
   - Add products from the **Products** section
   - Create invoices from the **Dashboard** or **Invoices** section

> ⚠️ **Note:** All data is stored in `localStorage`. Clearing browser data will delete all records.

---

## 📁 Project Structure
📂 invoice-system/
├── 📄 index.html ← Main file (HTML + CSS + JS all-in-one)
├── 📄 README.md ← English documentation
├── 📄 README.ar.md ← Arabic documentation

---

## 📸 System Sections

| Section | Description |
|---------|-------------|
| 📊 **Dashboard** | Overview statistics and recent invoices |
| 📄 **Invoices** | Create, view, manage, and print invoices |
| 👥 **Customers** | Manage customer database |
| 📦 **Products** | Manage products and services catalog |

---

## 🔧 Customization

### Change Tax Rate
Find the line `const tax = subtotal * 0.15;` and change `0.15` to your desired rate.

### Change Currency
Search for `ر.س` (SAR) in the code and replace it with your currency like `$` or `€`.

### Change Theme Colors
Modify CSS variables in `:root`:

| Variable | Description | Default |
|----------|-------------|---------|
| `--primary` | Main brand color | `#6366f1` |
| `--primary-dark` | Hover state | `#4f46e5` |
| `--success` | Paid status | `#22c55e` |
| `--warning` | Pending status | `#f59e0b` |
| `--danger` | Overdue / Delete | `#ef4444` |
| `--dark` | Sidebar / Text | `#1e293b` |

### Change Language Direction
The system is built RTL for Arabic. To switch to LTR change `<html lang="ar" dir="rtl">` to `<html lang="en" dir="ltr">`.

---

## 📋 Feature Roadmap

- [ ] Export invoices as PDF
- [ ] Email invoices to customers
- [ ] Multi-currency support
- [ ] Backend integration (Node.js / PHP)
- [ ] Database support (MySQL / MongoDB)
- [ ] User authentication
- [ ] Invoice templates
- [ ] Dashboard charts and graphs
- [ ] Recurring invoices
- [ ] Payment gateway integration

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/new-feature`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature/new-feature`
5. Open a Pull Request

---

## 📝 Notes

- No server or database required
- Zero dependencies — pure HTML, CSS, and JavaScript
- Suitable for personal use and small businesses
- Can be extended with a backend and real database
- Full Arabic RTL interface

---
 

 
