# 🛡️ Phishing Email Analysis Report

## 📧 Email Overview

- **Sender:** eHealth Support (health-care@webnotifications[.]net)  
- **Recipient:** john.doe@mybusiness.com  
- **Subject:** Update your ID Badge  
- **Source:** Sample obtained from [CanIPhish](https://caniphish.com/templates)

---

## 🔍 Phishing Indicators Identified

### 1. Suspicious Sender Domain
- The domain `webnotifications.net` is not associated with any known healthcare provider.
- Likely a spoofed or lookalike domain used to deceive recipients.

### 2. Generic Greeting
- Uses “Hi John” — not personalized beyond the name.
- Phishing emails often use scraped or generic names to appear legitimate.

### 3. Urgent Call to Action
- “Make sure you have an up-to-date ID photo to complete our security validation.”
- Creates pressure to act quickly without verifying the source.

### 4. Emotional and Social Engineering Language
- Mentions “essential employee,” “doctor,” “nurse,” etc.
- Attempts to build trust and urgency by referencing healthcare roles and pandemic-related terms.

### 5. Suspicious Link
- The CTA “Update your ID badge” hides the actual URL.
- Hovering reveals a redirect to a **Google-style login page**, which is a credential harvesting site.

### 6. Fake Login Page
- Clicking the CTA leads to a **phishing website** mimicking Google’s sign-in interface.
- Designed to steal Google credentials by tricking users into entering their email and password.

### 7. Context Mismatch
- The recipient’s domain (`mybusiness.com`) is not healthcare-related.
- The message targets hospital personnel, which doesn’t align with the recipient’s role.

### 8. Lack of Contact Information
- No phone number, physical address, or verifiable contact person.
- Legitimate organizations usually include this for trust and traceability.

---

## ✅ Summary of Phishing Traits

| Indicator             | Description |
|----------------------|-------------|
| Spoofed domain        | `webnotifications.net` is not a healthcare domain |
| Urgent language       | Pushes user to act quickly |
| Suspicious CTA link   | Hidden destination leads to fake login page |
| Fake login interface  | Mimics Google sign-in to steal credentials |
| Context mismatch      | Recipient not in healthcare sector |
| No contact details    | No way to verify sender |
| Emotional appeal      | Uses “essential worker” language to gain trust |

---

## 🧠 Conclusion

This email is a **phishing attempt** designed to harvest personal data and Google credentials under the pretense of updating an ID badge. It uses urgency, emotional manipulation, and a spoofed domain to deceive recipients. The fake login page is a clear indicator of credential theft.

---

## 🔗 Tools Used

- Manual inspection of email body and sender
- Hover-check for link verification
- [Google Admin Toolbox](https://toolbox.googleapps.com/apps/messageheader/) – for header analysis
- [CanIPhish](https://caniphish.com/templates) – for sample sourcing

---

## 📷 Evidence

- Screenshot of phishing email content
- Screenshot of fake Google login page

---

## 📬 Recommendations

- Do not click or enter credentials on suspicious pages.
- Report phishing sites to [Google Safe Browsing](https://safebrowsing.google.com/safebrowsing/report_phish/)
- Educate users on how to hover-check links and spot spoofed domains.
- Enable 2FA on all critical accounts.
