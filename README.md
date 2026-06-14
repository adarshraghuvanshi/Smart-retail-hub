# 🏪 Smart Retail Hub - Complete Project

> Digital Shop Management System | Firebase | Modern UI | Production Ready

## 📦 What's Inside?

```
smart-retail-hub-complete/
├── 📄 index.html              Home page
├── 📄 login.html              Login & signup
├── 📄 dashboard.html          Main dashboard
├── 📄 firebase-config.js      Firebase credentials
├── 📄 HOW_TO_USE_IN_VSCODE.md How to use in VS Code
├── 📄 run-windows.bat         Quick start for Windows
├── 📄 run-mac-linux.sh        Quick start for Mac/Linux
├── .gitignore                 Git ignore rules
├── .prettierrc                Code formatting
│
├── 📁 pages/                  Feature pages
│   ├── products.html
│   ├── customers.html
│   ├── billing.html
│   ├── inventory.html
│   ├── reports.html
│   └── settings.html
│
├── 📁 assets/
│   ├── css/
│   │   └── style.css          All styling
│   └── js/
│       ├── login.js
│       ├── dashboard.js
│       ├── products.js
│       ├── customers.js
│       ├── billing.js
│       ├── inventory.js
│       ├── reports.js
│       └── settings.js
│
├── 📁 components/             For future features
├── 📁 docs/                   Documentation
└── 📁 images/                 For product images
```

## ⚡ Quick Start (2 Minutes)

### Option 1: Windows Batch File
```bash
# Double-click:
run-windows.bat
```

### Option 2: Python Command
```bash
python -m http.server 8000
```

### Option 3: VS Code Live Server
1. Right-click on `login.html`
2. Select "Open with Live Server"
3. Browser opens automatically!

### Open in Browser
```
http://localhost:8000
```

## 🎯 Features

✅ 9 Complete HTML Pages
✅ Professional Responsive Design
✅ Dark/Light Mode
✅ Firebase Integration Ready
✅ Product Management
✅ Customer Database
✅ Invoice Generation with PDF
✅ QR Code Functionality
✅ Sales Analytics
✅ Inventory Tracking

## 📱 Pages

| Page | File | Features |
|------|------|----------|
| Home | `index.html` | Landing page |
| Login | `login.html` | Auth, Signup, Password reset |
| Dashboard | `dashboard.html` | Stats, Charts, Overview |
| Products | `pages/products.html` | CRUD, Image upload |
| Customers | `pages/customers.html` | Database, History |
| Billing | `pages/billing.html` | Invoice, PDF, QR |
| Inventory | `pages/inventory.html` | Stock tracking |
| Reports | `pages/reports.html` | Analytics |
| Settings | `pages/settings.html` | Profile, Password |

## 🔧 Setup Guide

### See Complete Setup:
```
Open: docs/SETUP.md
```

### Quick Firebase Setup:
1. Go to firebase.google.com
2. Create new project
3. Enable: Auth, Firestore, Storage
4. Copy credentials
5. Update `firebase-config.js`

## 🎨 Technology Stack

- **Frontend**: HTML5, CSS3, Bootstrap 5, JavaScript ES6+
- **Backend**: Firebase (Auth, Firestore, Storage)
- **Charts**: Chart.js
- **Export**: html2pdf.js, QRCode.js
- **Hosting**: Firebase Hosting
