# 📈 Interest Calculator Pro

A modern, mobile-first web app to calculate **Simple Interest** or **Yearly Compound Interest** with detailed visualizations and breakdowns. 

Built for precise **personal finance tracking**, allowing users to project growth over customized durations.

---

## 🚀 Key Features

### 🧮 Flexible Calculation Logic
- **Two Calculation Modes:**
  - **Simple Interest:** Interest accumulates separately and is not added to the principal.
  - **Yearly Compound:** Accumulated interest is added to the principal every 12 months.
- **Three Interest Rate Types:**
  - ₹ Fixed amount per month
  - ₹ Per month per ₹100 (Traditional Indian method)
  - % Per month

### ⚡ Smart Inputs & Validation
- **Smart Duration Sync:** Automatically syncs "Date Range" with "Month Count" input.
- **Quick Presets:** One-tap buttons for 1, 3, 5, and 10-year durations.
- **Input Validation:** The "Calculate" button remains disabled until all required fields are valid (marked with red asterisks).

### 📊 Visuals & Reporting
- **Interactive Growth Chart:** Visualize principal vs. total value over time.
- **Detailed Breakdowns:**
  - 📅 **Monthly Table:** Month-by-month accrual history.
  - 📆 **Yearly Table:** Annual summary of opening/closing balances.
- **Shareable Results:**
  - 📋 **Copy Summary:** Copies a formatted text summary to the clipboard.
  - 📸 **Screenshot:** Generates and downloads a clean PNG image of the results.

### 🎨 UI & Accessibility
- **Modern "Card" Layout:** Sectioned interface for better readability on all devices.
- **Mobile-First Design:** Optimized touch targets, spacing, and responsive grids.
- **Animated Theme:** Smooth toggle between **Light** 🌞 and **Dark** 🌙 modes (preference saved).
- **🇮🇳 Indian Formatting:** Numbers formatted as 1,12,345.00 for local relevance.
- **PWA Support:** Installable as an app on Android/iOS/Desktop.

---

## 🧠 Calculation Logic

The app calculates interest on a **monthly basis** using the selected rate. It handles partial months (days) as a fraction of a 30-day month.

### 1. Simple Interest Mode
- Interest is calculated every month based on the **initial principal**.
- Total Interest is stored separately.
- **Final Amount = Principal + Total Accumulated Interest.**

### 2. Yearly Compound Mode
- Interest is calculated every month but **held in a temporary accrual**.
- At the end of every **12th month**, the accrued interest is added to the Principal.
- The **New Principal** is used for the next year's calculation.

---

## 🛠️ Tech Stack

- **Core:** HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Libraries:**
  - `Chart.js` (Data Visualization)
  - `html2canvas` (Screenshot generation)
- **Deployment:** Vercel / GitHub Pages

---

## 📸 Screenshots

| Light Mode | Dark Mode |
|:---:|:---:|
| *(Add screenshot here)* | *(Add screenshot here)* |