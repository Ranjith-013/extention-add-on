# Browser Extension Security Review

## Objective
To identify and remove potentially harmful or unnecessary browser extensions in order to improve browser performance, maintain user privacy, and reduce security risks.

---

## Tools Used
- **Mozilla Firefox** – Add-ons & Permissions Manager
- **Google Chrome** – Extensions Manager (`chrome://extensions/`)

---

## ✅ Steps Performed

### 1. Accessed Extension Manager
- **Firefox:** `Menu → Add-ons and Themes → Extensions`
- **Chrome:** `chrome://extensions/`

### 2. Reviewed Installed Extensions
- **FoxyProxy**
- **Weather Forecast**

### 3. Checked Permissions & User Reviews
- **FoxyProxy:** Needed permissions for proxy setup. Trusted and actively used.
- **Weather Forecast:** Poor rating (2.7/5), access permissions concerning, multiple user complaints.

### 4. Removed Unused/Suspicious Extensions
- ❌ **Removed:** `Weather Forecast` (Firefox)
- ✅ **Kept:** `FoxyProxy` (for proxy management tasks)

### 5. Restarted Browser & Checked Performance
- Observed smoother and faster browsing experience after removing unused extensions.

---

## Research on Malicious Extensions

**Potential Risks of Malicious Add-ons:**
- Data theft (credentials, personal info)
- Browser hijacking (ads, redirects)
- Activity tracking
- Malware injection

🔗 Sources:
- OWASP
- Mozilla Developer Docs
- Kaspersky Blog

---

## Summary of Actions
- Reviewed all extensions
- Audited permissions and user ratings
- Removed a suspicious add-on
- Enhanced awareness of browser extension security

---

## Screenshots
Screenshots showing:
- Installed extensions
- Permissions panel
- User reviews
- Wireshark network monitoring setup

📁 See `/screenshots` folder in this repo.

---

## Conclusion
This review exercise highlights the importance of regularly auditing your browser extensions. Only install what you trust, monitor permissions carefully, and remove anything unused or poorly rated.

> “Digital hygiene is as essential as physical hygiene in today’s connected world.”


