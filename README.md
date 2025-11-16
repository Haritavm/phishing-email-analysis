# 🛡️ Phishing Email Analysis – Credential Harvesting Case

## 📌 Overview
This repository documents the analysis of a phishing email sample obtained from [CanIPhish](https://caniphish.com/templates). The email impersonates a healthcare credentialing service and redirects users to a fake Google login page to steal credentials.

## 🎯 Objective
To identify phishing indicators and demonstrate how attackers use social engineering and spoofed websites to harvest sensitive information.

## 📂 Repository Structure
```phishing-email-analysis/ ├── README.md ├── Phishing_Report.md ├── samples/ │   └── sample_email.txt ├── screenshots/ │   ├── alert_screenshot.png │   ├── fake_login_page.png │   └── phishing_collage.png```

## 🔍 Key Findings
- Spoofed sender domain (`webnotifications.net`)
- Urgent and emotional language targeting healthcare workers
- CTA link redirects to a fake Google login page
- No contact information or verification
- Clear signs of credential harvesting

## 🧪 Tools Used
- Manual inspection of email content and sender domain
- Hover-check for link verification
- [Google Admin Toolbox](https://toolbox.googleapps.com/apps/messageheader/) – for header analysis
- [CanIPhish](https://caniphish.com/templates) – for sample sourcing

## 📄 Report Summary
The phishing email uses urgency and emotional appeal to lure recipients into clicking a link that leads to a fake Google login page. This is a credential harvesting attempt disguised as a healthcare ID badge update.

See [`Phishing_Report.md`](Phishing_Report.md) for full details.

## 🧠 Outcome
This analysis reinforces key skills in phishing detection, including:
- Spotting spoofed domains
- Identifying social engineering tactics
- Recognizing fake login interfaces
- Documenting findings for awareness and training





