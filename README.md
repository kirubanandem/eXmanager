# eXmanager — Advanced Expense & Data Management

A feature-rich Android application designed for professional expense tracking, financial planning, and personal data management. Powered by **Firebase** and **Material Design 3**, it offers a secure, cloud-synced, and highly customizable user experience with full offline support.

---

## 🌟 Key Features

### 💼 Business Mode (Pro Enhancements!)
* **Business Health Monitoring:** Real-time **Asset Measurement (Net)** calculation: `[Total Cash] + [Current Asset Value] - [Outstanding Loan Debt]`.
* **Equity & Investor Tracking:** Professional partner management. Track **Equity Share (%)** instead of interest for investors, treated as capital inflow rather than debt.
* **Asset Portfolio:** Dedicated module to track business-owned investments and physical assets. Automatically treats acquisition as expense and returns/payouts as income.
* **Entity Status Control:** Manage your business lifecycle by toggling status between **Active** and **Closed**. Closed businesses are archived with a distinct visual state.
* **Integrated Financials:** Seamlessly link specific Loans, Investors, and Assets to individual business profiles for segregated bookkeeping.
* **Virtual Transaction Logic:** Loans and Assets are automatically injected into the business dashboard summary as virtual income/expense entries for a true cash-flow picture.
* **Advanced Filtering:** Range-based filters and instant search to audit years of transactions in seconds.
* **Business Analytics:** Specialized charts (MPAndroidChart) visualizing P&L and category-wise capital allocation.

### 💰 Comprehensive Financial Suite
* **Loans & Debt Tracker:** Full lifecycle management for Loans, Debts, EMIs, and Lending. Features automated repayment schedules and revised plans based on current balances.
* **Account Hierarchy:** Organize finances using **Parent Source Accounts** (e.g., HDFC Bank) and linked **Payment Channels** (e.g., UPI, Debit Card). Balances consolidate automatically at the parent level.
* **Income Planner:** Distributed income tracking. Plan your monthly fixed inflows and monitor remaining balances across custom periods.
* **Transfers & ATM Logs:** Track movement between accounts (ATM withdrawals, bank transfers) with double-entry correction to ensure account balances stay perfect.
* **Insurance Manager:** Centralized vault for insurance policies with status tracking.
* **Billing Cycle Support:** Configure statement and due days for credit cards to automate billing period calculations.

### 📋 Master Data Management
* **Centralized Categories:** Standardize your expense tagging across the entire app.
* **Investor Master List:** Manage a global list of partners and shareholders. Quickly view which businesses an investor is currently active in.
* **Channel Management:** Configure your payment instruments (Wallets, Cards, Apps) and link them to their physical money sources.

### 📊 Professional Analytics & Reporting
* **Range-Based Totals:** Instant dashboard updates for custom date ranges, showing weekly and monthly spending velocity.
* **Detailed Period Reports:** Generate on-the-fly source-wise summaries showing every inflow and outflow for a selected period.
* **Budgeting Engine:** Set monthly targets per category. View "Budget vs Actual" reports with visual "Over-budget" alerts.
* **PDF Export System:** Professional-grade PDF generation for Account Balances, Financial Records, and Budget reports. Includes built-in sharing via WhatsApp, Email, etc.

### 🔐 Security & Sync
* **Offline-First Architecture:** Full CRUD capability without internet. All data is cached in a versioned SQLite database (v23).
* **Firebase Realtime Sync:** High-speed cloud synchronization with data isolation per user (`auth.uid`).
* **Biometric Protection:** Secure your sensitive financial data with Fingerprint or Face Unlock.
* **OCR Receipt Scanning:** Extract amounts from physical receipts using Google ML Kit's on-device text recognition.

### 🎨 Personalization & UI
* **Global Navigation Drawer:** Unified sidebar for seamless jumping between Personal, Business, and Financial modules.
* **Dynamic Theme Engine:** 5 premium Material 3 themes (Blue, Green, Purple, Pink, and Midnight Dark).
* **Accessibility:** High-contrast support and localized currency formatting.

---

## 📸 Screen Samples

|Login & Security|Dashboard & Records|Analytics & Charts|
|:-:|:-:|:-:|
|<img src="screenshots/login_theme.png" width="200" />|<img src="screenshots/main_dashboard.png" width="200" />|<img src="screenshots/analytics_charts.png" width="200" />|
|*Theme Selection at Login*|*Main Dashboard*|*Financial Charts*|

|Business Mode|Income Planner|Budget Report|
|:-:|:-:|:-:|
|<img src="screenshots/business_dashboard.png" width="200" />|<img src="screenshots/income_planner.png" width="200" />|<img src="screenshots/budget_report.png" width="200" />|
|*Net Asset Measurement*|*Distributed Income*|*Budget vs Actual*|

---

## 🛠️ Technical Stack

* **Language:** Java / XML (Android SDK)
* **Backend:** Firebase Authentication & Realtime Database
* **Local Database:** SQLite with automated migrations (Version 23)
* **ML Features:** Google ML Kit (Text Recognition/OCR)
* **UI Framework:** Material Design 3 (M3) with Custom View Binding
* **Charts:** MPAndroidChart (Bar, Pie, Line)
* **Document Engine:** Android PdfDocument API

---

## 🚀 Setup & Installation

1. **Clone the Repo:**
   ```bash
   git clone https://github.com/kirubanandem/AndroidFirebaseApp.git
   ```

2. **Firebase Setup:**
   * Create a project in the [Firebase Console](https://console.firebase.google.com/).
   * Add your Android app with package name `com.firebaseapp`.
   * Download `google-services.json` and place it in the `app/` folder.
   * Enable **Email/Password** Auth and **Realtime Database**.

3. **Database Rules:**
   Apply the rules found in `firebase_database_rules.json` to your Firebase Console to enable investor and business logic validation.

4. **Build:**
   Open in Android Studio and sync Gradle. Minimum SDK: 26, Recommended SDK: 34.

---

## 📞 Contact & Support

Developed by **Kirubanandem.S**

* **Telegram:** [KcsDad App Store](https://t.me/KcsDadAppStore)
* **WhatsApp:** +91 9092041238
* **Email:** kirubas102@gmail.com

---

## ⚖️ License

MIT License - Copyright (c) 2026 Kirubanandem.S
