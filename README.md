# Cybersecurity-day-3

---
## Objective:
learn to  Use free tools to identify common vulnerabilities on your computer.

## Tools and Vulnerability Scan:
  - **Nessus Essentials** (Free for students and individuals)  
  🔗 "https://www.tenable.com/products/nessus/nessus-essentials"
    1.  Go to the link above.
    2.  Click "Get Started" and fill in your name and email.
    3.  You will receive a free activation code via email.
    4.  Download the installer for your OS: (I have for installed Windows (.exe))
    5.  Install Nessus and visit https://localhost:8834 in your browser. ( or it opens automatically)
    6.  Enter the activation code( received via mail) and complete the setup.
    7.  Create a scan → Choose “Basic Network Scan” → Set target IP as 127.0.0.1 or your local IP.
       
  - **Qualys Community Edition**
  🔗 https://www.qualys.com/community-edition/
    1. Go to the link above
    2. Click "Get Started" and sign up with your email.
    3. You'll receive login details for the Qualys Cloud Platform.
    4. After login: Download the Qualys Cloud Agent for Windows from your dashboard -> cloud agend ->activation key
    5. During setup, enter your Customer ID and Activation ID (available on dashboard).
    6. Go to Vulnerability Management -> assets tab in the Qualys portal.
    7. Your PC will automatically appear as a scanned asset after a few minutes.
    8. Click the hostname → View detailed vulnerability results.
    9. View:
          ~ Detected vulnerabilities
          ~ Their severity levels
          ~ Affected software
          ~ Suggested fixes

## Result
- No vulnerabilities were detected on my machine.
- System is considered secure based on this scan.
