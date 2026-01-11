# 📈 Interest Calculator Pro

A mobile-first, installable web app to calculate **simple monthly interest compounded yearly** with detailed monthly and yearly breakdowns.

Built for **personal finance tracking and projections**.

---

## 🚀 Features

- Simple monthly interest, **compounded yearly**
- Interest modes:
  - ₹ per month  
  - ₹ per month per ₹100  
  - % per month  
- Supports **date range or direct month input**
- Partial month calculation (days → fraction of month)
- 📅 Monthly breakdown table  
- 📆 Yearly summary table  
- 📊 Growth chart visualization  
- 🇮🇳 Indian number formatting (11,22,334.50)  
- 📋 Copy shareable summary text  
- 📸 Download screenshot of results  
- 🌗 Light / Dark theme (saved)  
- 📱 Mobile-first responsive UI  
- 📦 PWA support (installable, offline use)

---

## 🧠 Interest Logic

- Interest is calculated **every month**
- Interest is **not added immediately**
- After every **12 months**, accumulated interest is added to principal
- New principal is used for the next year
- Partial months are calculated as:

