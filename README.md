# 💸 Refundly - Money & Refund Tracker PWA

**Refundly** is a privacy-first Progressive Web Application (PWA) designed to track expected refunds, reimbursements, security deposits, and card returns worldwide. 

Built as a lightweight, zero-dependency single page app, Refundly works completely offline, stores all data locally in the browser, and provides follow-up message templates to help users recover pending payments.

---

## 🚀 Features

* **Global Currency Support:** Switch instantly between USD, EUR, GBP, KES, CAD, AUD, JPY, INR, NGN, and ZAR.
* **4-Step Visual Timeline:** Track statuses through *Requested*, *Processing*, *Approved*, and *Paid*.
* **Automated Overdue Alerts:** Automatically flags returns that pass their expected disbursement date.
* **Follow-Up Message Generator:** Create customizable friendly, professional, or firm email templates for merchants with a single tap.
* **Partial Refund & Math Calculator:** Calculate fees, percentage refunds, and overdue day metrics instantly.
* **Complete History Log:** Separate active pending refunds from completed and recovered funds.
* **Offline-First & Local Storage:** No server, login, or database required. Financial data remains 100% private to your device.
* **PWA & Mobile Ready:** Fully responsive UI with a native-feeling mobile navigation bar and Service Worker support.

---

## 🛠️ Installation & Setup

Because Refundly consists of standard, framework-free web technology, setting it up requires no build tools, Node.js, or npm commands.

### Local Development / Acode
1. Create a project directory on your device.
2. Place `index.html`, `sw.js`, and `manifest.json` into the same root folder.
3. Open `index.html` in any modern web browser or mobile browser editor (e.g., Acode).

### GitHub Pages Deployment
1. Create a public repository on GitHub.
2. Commit and push the 3 core files (`index.html`, `sw.js`, `manifest.json`) to the `main` branch.
3. Navigate to **Settings > Pages**.
4. Set the source branch to **main** / **root** and click **Save**.
5. Your app will be live at `https://<username>.github.io/<repository-name>/`.

---

## 📁 File Structure

```text
├── index.html       # Complete application HTML, CSS, and JS logic
├── sw.js            # Service Worker for offline asset caching
└── manifest.json    # PWA configuration for installation on iOS/Android
