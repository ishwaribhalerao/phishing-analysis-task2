# 🛡️ Phishing Email Analysis: Fake PayPal Alert

## 📌 Objective

The goal of this task is to analyze a suspicious email claiming to be from PayPal and identify phishing indicators using email header analysis tools. The task focuses on recognizing email spoofing, social engineering techniques, and threat detection.

---

## 📥 Email Sample Overview

**Subject:** `[PayPal]: Your account access has been limited`  
**From:** `"PayPal" <support@paypal-accounts.com>`  
**To:** `<aarav.mehta42@gmail.com>`  
**Date:** `June 25, 2025, 9:32 AM IST`  
**Tool Used:** [Google Admin Toolbox - Messageheader](https://toolbox.googleapps.com/apps/messageheader/)

---

## 🔍 Phishing Indicators Identified

| Indicator              | Description |
|------------------------|-------------|
| **📛 Spoofed Sender**   | The email claims to be from PayPal but uses a fake domain: `paypal-accounts.com`. |
| **📉 SPF Check Failed** | SPF (Sender Policy Framework) failed, meaning the sending IP is not authorized to send emails on behalf of the domain. |
| **🔐 DKIM Failed**      | DKIM (DomainKeys Identified Mail) failed with an unknown domain signature. |
| **❌ DMARC Failed**     | DMARC (Domain-based Message Authentication, Reporting & Conformance) failed, indicating the email doesn’t meet authentication standards. |
| **⚠️ Urgent Language**  | The email urges the user to act within 24 hours or face account suspension. |
| **🧠 Social Engineering** | Uses fear and urgency to manipulate the user into clicking a malicious link. |
| **🚫 Suspicious Link**  | Includes a "Confirm Your Information" CTA likely pointing to a phishing page. |
| **📝 Grammar Issues**   | Contains errors like "permanetly" and unprofessional formatting. |
| **🧩 Email Sent via Script** | The email was sent using PHPMailer, often used in bulk or spoofed email campaigns. |

---


---

## 🧰 Tools Used

- **Google Admin Toolbox: Messageheader**  
  👉 [https://toolbox.googleapps.com/apps/messageheader/](https://toolbox.googleapps.com/apps/messageheader/)

---

## 📸 Screenshots

- `email_header_analysis.png` — Screenshot of Google Admin Toolbox result

---

## 📚 Key Concepts Demonstrated

- Email Spoofing
- Header Analysis (SPF, DKIM, DMARC)
- Social Engineering Awareness
- Threat Detection & Phishing Indicators

---

## ✅ Conclusion

This phishing email is a clear example of email spoofing and social engineering. Through this exercise, I gained practical experience in email header analysis and improved my awareness of common phishing tactics and email-based threats.

---



