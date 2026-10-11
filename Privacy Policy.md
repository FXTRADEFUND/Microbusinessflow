# Privacy Policy for MicrobusinessFlow

**Effective Date:** October 2026  
**Application Name:** MicrobusinessFlow  
**Package Name:** `com.studios.microbusinessflow`  
**Developer Contact:** easymobileng@gmail.com  

---

## 1. Overview & Core Privacy Commitment
MicrobusinessFlow is an **offline-first** expense tracking, budgeting, and bookkeeping application engineered for sole proprietors, microbusiness owners, and freelancers. 

**We do not collect, upload, share, or store your private financial transactions, expenses, revenue numbers, or budget targets on our servers.** All financial bookkeeping records remain 100% locally on your Android device.

---

## 2. Information We Do NOT Collect
Unlike cloud-based accounting platforms, MicrobusinessFlow has zero server-side bookkeeping infrastructure:
- **No Personal Financial Data:** Your transactions, custom categories, expense notes, and monetary limits are stored in a private, encrypted local SQLite database (Android Room) on your physical device.
- **No Mandatory Accounts or Passwords:** You do not need to register, provide your email, or link bank credentials to use the application.
- **No Location or Contact Access:** The app does not request or access GPS location, contacts, phone calls, or SMS.

---

## 3. Device Permissions & Specific Usage Disclosures

MicrobusinessFlow requests only the minimum set of permissions necessary to deliver its core features, complying strictly with Google Play User Data policies:

### A. Microphone Access (`android.permission.RECORD_AUDIO`)
- **Feature:** Hands-Free Voice Expense Logging.
- **How It Works:** When you tap the microphone button to dictate an expense (e.g., *"Spent forty dollars on inventory"*), speech audio is processed into text via the Android operating system’s Speech Recognition service.
- **Privacy Assurance:** Raw audio files are **never recorded, stored to disk, or sent to any private servers**. Audio data is processed ephemerally and discarded immediately after transcription.

### B. Biometric Authentication (`android.permission.USE_BIOMETRIC`, `android.permission.USE_FINGERPRINT`)
- **Feature:** Biometric App Lock & Privacy Overlay.
- **How It Works:** Prevents unauthorized individuals from viewing your sensitive business finances when holding your device.
- **Privacy Assurance:** Biometric verification is processed entirely by the Android system's hardware-backed Trusted Execution Environment (TEE). MicrobusinessFlow **never has access to your actual fingerprint, facial biometric data, or cryptographic keys**.

### C. File Export & Sharing (`FileProvider` / Storage Access Framework)
- **Feature:** One-Tap CSV Spreadsheet Export.
- **How It Works:** Allows you to generate standard `.csv` spreadsheet files of your expense history for tax preparation, accounting, or import into Google Sheets / Microsoft Excel.
- **Privacy Assurance:** Files are created locally and shared strictly through Android's secure `FileProvider` mechanism only when you explicitly press the export button.

### D. Internet & Network State (`android.permission.INTERNET`, `android.permission.ACCESS_NETWORK_STATE`)
- **Feature:** Network connectivity for Google Mobile Ads banner rendering and network state checks.

---

## 4. Third-Party Services & Advertising
MicrobusinessFlow integrates **Google Mobile Ads (AdMob)** to display non-intrusive banner advertisements:
- **Data Processed by Google Mobile Ads:** Google may automatically process diagnostic data, device identifiers (such as the Google Advertising ID / GAID), and IP addresses to serve advertisements, limit impression fraud, and diagnose SDK performance.
- **Opt-Out & Personalization:** You can reset or delete your Advertising ID at any time in your device's settings under `Settings > Google > Ads`.
- Review Google’s Advertising Privacy Policy: [https://policies.google.com/technologies/ads](https://policies.google.com/technologies/ads)

---

## 5. Data Retention, Portability & Deletion
- **Full User Ownership:** You have unilateral control over all your bookkeeping data.
- **Individual Deletion:** You can delete individual transactions or categories anytime within the app.
- **Full Erasure:** Clearing the app’s storage data in your Android settings or uninstalling the app permanently purges all stored transactions from the device.
- **Data Export:** You can export your entire bookkeeping ledger anytime using the CSV export tool.

---

## 6. Children's Privacy (COPPA)
MicrobusinessFlow is a commercial productivity utility designed for business owners and adult professionals. It is not intended for or marketed to children under 13 years of age. We do not knowingly collect personal information from children.

---

## 7. Security Best Practices
We adhere to Google Play security guidelines:
- Sandboxed application storage protected by Android's UID isolation.
- Zero external transmissions of bookkeeping data.
- Strict adherence to scoped storage and secure Android `FileProvider` paths.

---

## 8. GDPR & CCPA Compliance Summary
- **No Sale of Personal Data:** We do not sell or monetize personal or financial user data.
- **Right to Portability:** Fulfilled via the built-in CSV export functionality.
- **Right to Erasure:** Fulfilled immediately upon deleting transactions or clearing application data.

---

## 9. Contact Information
For any questions regarding this Privacy Policy or data safety practices, please contact:

* **Developer Email:** [easymobileng@gmail.com](mailto:easymobileng@gmail.com)  
* **Application:** MicrobusinessFlow (`com.studios.microbusinessflow`)  
