# InternCircle Cybersecurity Internship — Project 01
# Cyber Threat Landscape Brief: College Student Edition

**Author:** Yadhiksha M  
**Internship Role:** Cybersecurity Intern, InternCircle  
**Project Title:** Project 01 — Cyber Threat Landscape Brief  
**Target Audience:** College Students and Higher Education Campuses in India  
**Date of Submission:** November 2026  
**Project Status:** COMPLETE & VERIFIED  

---

## 📁 Project Deliverables Directory

All core project deliverables have been generated, formatted, and organized within this folder (`InternCircle_Cybersecurity_Project_01`):

| File Name | Format | Description | Rubric Alignment |
| :--- | :--- | :--- | :--- |
| **`Cyber_Threat_Landscape_Brief.pdf`** | PDF (Vector) | Official **Two-Page Executive Cybersecurity Brief** formatted with typography, structured threat cards, student defence matrix, and official citations. | Part 2: Two-Page Brief (Strictly 2 Pages) |
| **`Cyber_Security_Awareness_Poster.pdf`** | PDF (Print) | High-contrast, vector-quality **Awareness Poster** designed for campus boards, digital screens, and student newsletters. | Part 3: One-Page Poster (Print Ready) |
| **`Cyber_Security_Awareness_Poster.png`** | PNG (300 DPI) | High-resolution graphic poster (2480 × 3508 px) optimized for digital sharing on WhatsApp, Telegram, and social platforms. | Part 3: One-Page Poster (Digital Ready) |
| **`RESEARCH_AND_SOURCES.md`** | Markdown | Comprehensive research dossier detailing the technical background, incident reports, CERT-In advisories, CISA guidelines, and Verizon DBIR statistics. | Part 1: Research Dossier & References |
| **`report_page_1.png`** | PNG Preview | Visual rendering of Page 1 of the official report for quick inspection. | Visual Verification |
| **`report_page_2.png`** | PNG Preview | Visual rendering of Page 2 of the official report for quick inspection. | Visual Verification |
| **`README.md`** | Markdown | Comprehensive project documentation, rubric compliance audit, and evaluation guide. | Project Documentation |

---

## 🎯 Project Objective & Target Audience

### Objective
To research and analyze the most prevalent cybersecurity threats impacting college students and small businesses in India, producing:
1. A beginner-friendly, plain-language **Two-Page Cybersecurity Brief** that demystifies threat mechanisms and equips students with immediate defensive practices.
2. A high-impact, visual **Cyber Awareness Poster** distilling core security habits into actionable campus rules.
3. A fully verifiable **Research Dossier** grounded strictly in genuine public advisories from **CERT-In**, **CISA**, and the **Verizon DBIR**.

### Target Audience: College Students in India
Undergraduate and postgraduate students across Indian universities represent a distinct high-risk group:
- **Intense Digital Dependency:** Students perform high-frequency digital interactions across University Management Systems (UMS), fee portals, the National Scholarship Portal (NSP), DigiLocker, examination hall-ticket portals, and UPI payment apps.
- **Resource Constraints:** Financial pressures often prompt students to seek pirated academic software (AutoCAD, MATLAB, Photoshop), cracked game utilities, or unverified student tools.
- **Unsecured Shared Connectivity:** Frequent connection to unencrypted campus, cafeteria, hostel, and railway station Wi-Fi exposes students to session hijacking.
- **Susceptibility to Urgency-Based Social Engineering:** Impending deadlines (scholarship verifications, fee late fines, examination eligibility) make students vulnerable to smishing and phishing scams.

---

## 🛡️ Summary of the Five Researched Threats

In accordance with the project guidelines, each threat is articulated using plain language, a relatable student scenario, concrete red flags, verified real-world incident citations, and three actionable defences executable within the week.

### 1. Phishing and Social Engineering
- **What It Is:** Fraudulent communications (emails, SMS/smishing, WhatsApp messages) impersonating trusted authorities (colleges, scholarship bodies, banks, exam boards) to trick students into surrendering credentials, Aadhaar details, or OTPs.
- **Relatable Student Story:** An engineering student receives an SMS claiming their Central Sector Scholarship of ₹25,000 is on hold due to pending Aadhaar KYC. Panicked, the student clicks a shortened link to a cloned National Scholarship Portal and enters their credentials and OTP; attackers immediately execute an unauthorized UPI withdrawal.
- **Warning Signs:** Extreme urgency ("Verify within 24 hours or scholarship cancelled"); generic greetings ("Dear Student"); mismatched domains (e.g., `.site` or Gmail addresses instead of `.gov.in` / `.ac.in`); unsolicited requests for OTPs or UPI PINs.
- **Real-World Evidence:** **CERT-In Advisories (CIAD-2023 & CIAD-2024 series)** document recurring smishing campaigns cloning Indian government and banking portals (e-Challan, Income Tax, scholarship platforms). The **Verizon 2024 DBIR** confirms phishing is a primary breach vector with a median user click time under **60 seconds**.
- **Practical Defences (This Week):**
  1. *Never log in via links in messages:* Manually navigate to official websites (e.g., `scholarships.gov.in`).
  2. *Turn on Multi-Factor Authentication (MFA):* Use authenticator apps (Google/Microsoft Authenticator) across all academic and personal accounts.
  3. *Never disclose OTPs or UPI PINs:* Legitimate institutions will never ask for your authentication codes over chat or phone.

### 2. Malware and Ransomware
- **What It Is:** Malicious software (trojans, spyware, keyloggers, ransomware) covertly installed on laptops or smartphones to harvest files, spy on keystrokes, or use strong cryptographic ciphers (AES/RSA) to lock personal files and extort ransom payments.
- **Relatable Student Story:** Needing expensive CAD software for their final-year capstone project, a student downloads a "crack" installer from an unverified forum. The installer prompts them to disable Windows Defender. Upon execution, background ransomware quietly encrypts their thesis documents and source code with a `.enc` extension, leaving a desktop file `readme_now.txt` demanding ₹20,000 in cryptocurrency within 48 hours.
- **Warning Signs:** Installers requiring antivirus software to be turned off; sudden system sluggishness and high CPU usage; files displaying strange extensions and failing to open; sudden popup ransom demands.
- **Real-World Evidence:** **CERT-In Advisory on "Daam" Android Botnet/Ransomware** documented active malware distributed via untrusted downloads in India that uses AES encryption to lock files into `.enc` format and drops ransom extortion notes. The **Verizon 2024 DBIR** notes ransomware accounts for **32%** of all malware breaches.
- **Practical Defences (This Week):**
  1. *Enforce 3-2-1 offline backups:* Keep 3 copies of critical project work across 2 media, with at least 1 offline copy on a disconnected flash drive.
  2. *Adopt verified open-source software:* Replace pirated tools with official student licenses or free open-source software (LibreOffice, Blender, VS Code).
  3. *Keep real-time endpoint protection active:* Never disable Windows Defender or antivirus filters; enable automated OS patches.

### 3. Weak Passwords and Credential Attacks
- **What It Is:** Unauthorized account takeover through automated brute-force attacks, dictionary attacks, or "credential stuffing"—where attackers test username/password pairs leaked from one breached database across student portals, email, and cloud storage.
- **Relatable Student Story:** A student uses `Student@2024` for their university student portal, personal Gmail, Instagram, and a gaming forum. When the gaming forum suffers a database breach, automated bots spray those leaked credentials against university single sign-on (SSO) systems, locking the student out of their college email during exam week.
- **Warning Signs:** Automated alert emails stating "New sign-in from an unknown device/location"; unexpected 2FA push notifications when you are not logging in; sudden password reset notifications; inability to log in with known credentials.
- **Real-World Evidence:** **Verizon DBIR 2024** highlights stolen credentials as the **#1 entry vector** into web applications, featured in over **80%** of basic web application breaches. **CISA Authentication Standards** show that adopting multi-factor authentication (MFA) blocks up to **99%** of automated credential attacks.
- **Practical Defences (This Week):**
  1. *Install a password manager:* Use trusted tools like Bitwarden or KeePass to generate and store 16+ character unique passphrases.
  2. *Never reuse passwords:* Ensure college portals, primary email, and financial apps possess strictly unique passwords.
  3. *Audit public breach dumps:* Regularly check your email addresses on `haveibeenpwned.com` and change compromised passwords immediately.

### 4. Public Wi-Fi and Man-in-the-Middle (MitM) Attacks
- **What It Is:** Eavesdropping on unencrypted public Wi-Fi networks (cafes, bus terminals, railway stations, campus libraries) or deploying "Evil Twin" rogue access points with identical SSIDs to intercept network traffic, harvest session cookies, and steal plaintext login credentials.
- **Relatable Student Story:** Studying at a cafe near campus, a student connects their laptop to an open Wi-Fi network named `Campus_Cafe_FreeWiFi`. In reality, an attacker at a nearby table deployed a rogue hotspot broadcasting that exact SSID. When the student logs into an unencrypted college portal, the attacker captures session tokens and hijacks their active session without needing their password.
- **Warning Signs:** Open Wi-Fi networks requiring zero password or captive login; duplicate Wi-Fi networks with nearly identical names; browser warnings stating "Your connection is not private" (SSL/TLS certificate errors); sluggish connection accompanied by security bypass prompts.
- **Real-World Evidence:** **CISA Security Tip (ST05-003: Securing Wireless Networks)** warns that unencrypted public Wi-Fi hotspots transmit data in the clear, allowing nearby adversaries to monitor sessions. **CERT-In Wi-Fi Guidelines** recommend against conducting financial or academic transactions over open public Wi-Fi.
- **Practical Defences (This Week):**
  1. *Use cellular hotspot for sensitive work:* Prefer 4G/5G mobile data over public Wi-Fi for banking, academic submissions, and email logins.
  2. *Always tunnel via a trusted VPN:* If public Wi-Fi is unavoidable, connect through a trusted Virtual Private Network (VPN) to encrypt all traffic.
  3. *Disable auto-connect:* Turn off "Connect automatically to open Wi-Fi networks" in phone/laptop settings, and never bypass browser SSL certificate warnings.

### 5. Fake Applications and Malicious Downloads
- **What It Is:** Counterfeit Android APKs, trojanized mobile apps, or modified apps (e.g., GB WhatsApp, cracked utility tools) distributed outside official app stores that masquerade as helpful student tools while secretly harvesting SMS OTPs, contact lists, and personal files.
- **Relatable Student Story:** Seeking an internal marks predictor, a student downloads an APK named `College_GPA_Attendance_Pro.apk` shared in a student Telegram channel. After enabling "Install from Unknown Sources", the app requests permissions for SMS, contacts, and accessibility services. Once installed, the trojan silently intercepts incoming banking OTPs, enabling fraudulent transactions while displaying a fake error screen to the student.
- **Warning Signs:** Applications distributed as standalone `.apk` files on WhatsApp, Telegram, or cloud download links rather than Google Play Store; intrusive permission requests (e.g., a calculator app requesting SMS access); zero developer history or lack of digital signatures.
- **Real-World Evidence:** **CERT-In Advisories** continuously warn against malicious Android APK campaigns (such as fake e-Challan APKs, banking trojans like SOVA, and malicious APK droppers) that intercept 2FA SMS codes. The **Ministry of Home Affairs (I4C)** actively cracks down on predatory rogue apps that harvest student contact books for extortion.
- **Practical Defences (This Week):**
  1. *Install strictly from official app stores:* Download applications only from Google Play Store (with Google Play Protect enabled) or Apple App Store.
  2. *Strictly audit permissions:* Deny SMS, call logs, contacts, and accessibility permissions to utility apps that have no legitimate need for them.
  3. *Disable APK sideloading:* Ensure "Install Unknown Apps" remains disabled in Android settings across all browsers and file management apps.

---

## ✅ Rubric Compliance Audit

Every requirement from the official InternCircle Project 1 Learner Guide (`project-1-guide.pdf`) has been checked and verified:

| Rubric Requirement | Verification Status | Implementation Details |
| :--- | :---: | :--- |
| **Five threats explained simply** | ✅ **PASSED** | Phishing, Malware/Ransomware, Weak Passwords, Public Wi-Fi, and Fake Apps are each articulated with "What it is", relatable student stories, warning signs, and defenses. |
| **Real, sourced examples from public reports** | ✅ **PASSED** | Sourced directly from **CERT-In** (CIAD advisories, Daam malware), **CISA** (Secure Our World, ST05-003), and **Verizon DBIR 2024** (68% human element, 80%+ stolen credentials). |
| **No private individuals named** | ✅ **PASSED** | All examples use generalized student scenarios or public institutional advisories; zero private individuals are named. |
| **Each threat has three practical defences** | ✅ **PASSED** | Each of the 5 threats provides exactly 3 practical, actionable defenses students can implement this week. |
| **Clear and readable poster** | ✅ **PASSED** | High-contrast, 300-DPI A4 poster (`Cyber_Security_Awareness_Poster.png` & `.pdf`) featuring 5 distinct rule cards, emergency helpline (1930), and professional branding. |
| **The brief is strictly two pages** | ✅ **PASSED** | Verified via PyMuPDF: `Cyber_Threat_Landscape_Brief.pdf` is **exactly 2 pages** with zero overflow, balanced headers, executive summary, and footers. |
| **Target audience relevance** | ✅ **PASSED** | Specifically customized for college students in India navigating UPI, scholarships, LMS portals, and campus Wi-Fi. |
| **Emergency reporting information** | ✅ **PASSED** | Prominently highlights the **National Cyber Crime Helpline (1930)**, **cybercrime.gov.in**, and CERT-In reporting channels. |

---

## 🏛️ Authoritative Reference Directory

1. **Indian Computer Emergency Response Team (CERT-In)**
   - Official Portal: [https://www.cert-in.org.in/](https://www.cert-in.org.in/)
   - Cyber Swachhta Kendra (Botnet Cleaning & Malware Analysis): [https://www.csk.gov.in/](https://www.csk.gov.in/)
   - Incident Reporting Email: `incident@cert-in.org.in`
2. **Cybersecurity and Infrastructure Security Agency (CISA)**
   - Official Portal: [https://www.cisa.gov/](https://www.cisa.gov/)
   - "Secure Our World" 4 Core Habits: [https://www.cisa.gov/secure-our-world](https://www.cisa.gov/secure-our-world)
   - CISA Security Tip ST05-003 (Wireless Security): [https://www.cisa.gov/news-events/news/securing-wireless-networks](https://www.cisa.gov/news-events/news/securing-wireless-networks)
3. **Verizon Business Security Solutions**
   - Verizon Data Breach Investigations Report (DBIR) 2024: [https://www.verizon.com/business/resources/reports/dbir/](https://www.verizon.com/business/resources/reports/dbir/)
4. **National Cyber Crime Reporting Portal (I4C, Ministry of Home Affairs, India)**
   - Official Portal: [https://cybercrime.gov.in/](https://cybercrime.gov.in/)
   - **National Cyber Emergency Helpline:** **Dial 1930** (Toll-Free, 24x7 Support — Act within the Golden Hour)

---
*Created with dedication by **Yadhiksha M** for the InternCircle Cybersecurity Internship Program.*
