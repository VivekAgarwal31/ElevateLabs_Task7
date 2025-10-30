# 🔒 Browser Extension Security Analysis – Task 7  
**By:** Vivek Agrawal  
**Date:** October 30, 2025  
**Environment:** Google Chrome on Windows  

---

## 🎯 Objective
To identify, analyze, and remove potentially malicious or unnecessary browser extensions that may compromise **privacy, security, or performance**.  
This task focuses on recognizing risky permissions, verifying developer authenticity, and implementing safe extension management practices.

---

## 🧰 Tools and Resources
- **Google Chrome** — for managing and auditing extensions (`chrome://extensions/`)  
- **Chrome Web Store** — for checking developer authenticity and user reviews  
- **Online threat reputation sources** — to validate extension trustworthiness  

---

## 🧭 Methodology
1. Opened the **Chrome Extensions** page using `chrome://extensions/`.  
2. Reviewed all installed extensions, noting their permissions, update frequency, and developer credibility.  
3. Verified each extension’s authenticity through the **Chrome Web Store** and external reviews.  
4. Classified extensions into:  
   - ✅ Safe and necessary  
   - ⚠️ Medium risk or unnecessary  
   - 🚨 High risk or suspicious  
5. Removed or disabled high-risk and unverified extensions.  
6. Restarted the browser to monitor performance improvements.  
7. Documented all findings and created a summarized security report.

---

## 📋 Analysis of Installed Extensions

| Extension | Purpose | Risk Level | Notes / Reasoning | Action |
|------------|----------|-------------|--------------------|--------|
| **Always Active Window – Always Visible** | Keeps windows always active | ⚠️ Medium | Spoofs browser visibility; potential misuse | **Removed** |
| **Burp Suite Navigation Recorder** | Records navigation for web testing | ✅ Low | Legitimate for security testing | **Kept** |
| **CGPA Calculator** | Calculates GPA and charts | ⚠️ Medium | Unknown developer, redundant permissions | **Removed** |
| **Dark Mode – Night Eye** | Adds dark theme for websites | ✅ Low | Trusted and verified extension | **Kept** |
| **Enable Copy Anywhere** | Bypasses copy restrictions | 🚨 High | Injects scripts, violates site policies | **Removed** |
| **EPUBReader** | Reads EPUB files in-browser | ✅ Low | Safe and verified source | **Kept** |
| **Focus To-Do (Pomodoro Timer)** | Productivity and timer tool | ⚠️ Medium | Safe but not essential | **Disabled** |
| **Google Docs Offline** | Enables offline editing for Google Docs | ✅ Low | Official Google extension | **Kept** |
| **Google Scholar PDF Reader** | Improves academic PDF viewing | ✅ Low | Verified developer | **Kept** |
| **SEOquake** | Displays SEO metrics | ⚠️ Medium | Requires site access, but from verified source | **Kept** |
| **uBlock Origin Lite** | Blocks ads and trackers | ✅ Low | Trusted open-source blocker | **Kept** |

---

## 🔍 Findings
- A total of **11 extensions** were reviewed.  
- **2 high-risk** extensions were identified and **removed** (`Enable Copy Anywhere`, `Always Active Window`).  
- **1 medium-risk** extension was **disabled** due to unnecessary permissions.  
- Verified and essential extensions were retained to maintain functionality.  
- Browser performance and startup speed improved after cleanup.  

---

## 🧠 Learnings and Insights
- Extensions can access **sensitive data** (history, clipboard, tabs, passwords) when granted excessive permissions.  
- Always check **developer authenticity**, **user ratings**, and **update frequency** before installation.  
- Free or productivity-focused extensions often include hidden tracking components.  
- Conducting regular audits minimizes **privacy leakage** and **reduces attack surface**.  
- Removing unused or unverified extensions enhances **browser stability** and **security posture**.  

---

## 💡 Best Practices for Safe Browser Use
1. Install extensions **only from trusted developers** and verified sources.  
2. Regularly **audit and remove unused** extensions.  
3. Avoid granting unnecessary permissions such as "Read and change all your data".  
4. **Disable auto-updates** for unverified extensions to prevent malicious replacements.  
5. Use **ad blockers and privacy tools** like uBlock Origin.  
6. Keep the browser **up-to-date** for the latest security patches.  
7. Prefer **sandboxed or isolated browser profiles** for sensitive activities.  

---

## 📁 Deliverables
- `README.md` — Summary of findings and results.  
- `Report_Task7_Browser_Extension_Analysis.pdf` — Detailed report with screenshots and analysis.  
- `/screenshots/` — Evidence of removed and retained extensions.  

---

## 🏁 Conclusion
This analysis successfully identified and removed suspicious extensions, improving both the **security** and **performance** of the browser.  
The exercise enhanced understanding of **browser-level threats**, **permission management**, and **responsible extension auditing**.  
Routine checks and adherence to best practices are essential to maintaining a **secure and private browsing environment**.

---

> ✨ *Prepared by Vivek Agrawal as part of the Cybersecurity Internship — Task 7 (Browser Extension Security Analysis), October 2025.*
