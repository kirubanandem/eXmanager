# eXmanager — Advanced Expense \& Data Management

A feature-rich Android application designed for professional expense tracking, financial planning, and personal data management. Powered by **Firebase** and **Material Design 3**, it offers a secure, cloud-synced, and highly customizable user experience.

\---

## 🌟 Key Features

### 🔐 Security \& Access

* **Multi-Factor Login:** Support for Username/Password and Direct Email login.
* **Biometric Security:** Fingerprint and Face Unlock integration for enhanced privacy.
* **Session Management:** Secure logout with "Switch User" capabilities directly from the lock screen.

### 💰 Financial Management

* **Expense Tracking:** Full CRUD operations for daily expenses with categories and payment methods.
* **Income Planner:** Manage multiple income sources with distributed value calculation over custom periods.
* **ATM / Cash Transfers:** Track money movement between bank accounts and physical cash.
* **Loans \& Debt Tracker:** Dedicated module for managing loans, debts, EMIs, and lending to others.
* **Repayment Schedules:** Automatically generate EMI plans and export them as professional PDFs.

### 📊 Advanced Analytics

* **Budgeting System:** Set monthly budgets per category with real-time cloud synchronization.
* **Visual Insights:** Bar charts and Pie charts for category breakdowns and payment method analysis.
* **Month-on-Month Comparison:** Compare spending trends across different months.
* **Budget vs Actual:** Dynamic reporting showing remaining balance or over-budget alerts.

### 📄 Professional Reporting

* **PDF Export:** Generate detailed reports for dashboard records, analytics, and budget performance.
* **Custom Ranges:** Filter and export data for specific dates or month ranges.
* **Share Directly:** Integrated Android share sheet to send reports via WhatsApp, Email, or Telegram.

### 🎨 Personalization \& UI

* **Dynamic Themes:** 5 beautiful built-in themes (Blue, Green, Purple, Pink, and Midnight Dark).
* **High-Contrast Support:** Specialized dark mode logic to ensure legibility on all device types.
* **Adaptive UI:** Fully responsive design using Material Design 3 components.

### 🏪 Developer App Store

* **App Ecosystem:** Browse and install other utility apps from the developer's ecosystem.
* **Smart Detection:** Automatically detects installed apps and switches from "Install" to "Open".
* **Community Links:** Direct access to the official Telegram channel and GitHub repository.

\---

## 📸 Screen Samples

|Login \& Security|Dashboard \& Records|Analytics \& Charts|
|:-:|:-:|:-:|
|<img src="screenshots/login\_theme.png" width="200" />|<img src="screenshots/main\_dashboard.png" width="200" />|<img src="screenshots/analytics\_charts.png" width="200" />|
|*Theme Selection at Login*|*Main Dashboard*|*Financial Charts*|

|Budget Reporting|Income Planner|App Store|
|:-:|:-:|:-:|
|<img src="screenshots/budget\_report.png" width="200" />|<img src="screenshots/income\_planner.png" width="200" />|<img src="screenshots/app\_store.png" width="200" />|
|*Budget vs Actual*|*Distributed Income*|*Utility Ecosystem*|

\---

## 🛠️ Technical Stack

* **Language:** Java / XML
* **Backend:** Firebase Authentication \& Realtime Database
* **UI Framework:** Material Design 3 (M3)
* **Charts:** MPAndroidChart
* **Image Processing:** Cloudinary (Profile Storage) \& Yalantis UCrop
* **Local Cache:** SQLite (Synced with Cloud)
* **Document Engine:** Android PdfDocument API

\---

## 🚀 Setup \& Installation

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
Apply the rules found in `firebase\_database\_rules.json` to your Firebase Console.
4. **Build:**
Open in Android Studio and sync Gradle. Ensure you are using JDK 17+.

\---

## 📞 Contact \& Support

Developed by **Kirubanandem.S**

* **Telegram:** [KcsDad App Store](https://t.me/KcsDadAppStore)
* **WhatsApp:** +91 9092041238
* **Email:** kirubas102@gmail.com

\---

## ⚖️ License

MIT License - Copyright (c) 2026 Kirubanandem.S

