
# Phishing Email Analysis Report

## Sample Email Analyzed

```
From: PayPal Security <support@paypa1.com>
Subject: Urgent: Your Account Has Been Limited

Dear Customer,

We have detected unusual activity on your PayPal account. For your protection, access to your account has been temporarily limited.

To restore access, please verify your account information by clicking the link below:

https://www.paypalsecurelogin.com/verify

Failure to verify your details within 24 hours will result in permanent suspension.

Thank you for your immediate attention.

Sincerely,  
PayPal Security Team

Attachment: PayPal_Statement.pdf.exe
```

---

## Identified Phishing Traits

### 1. Spoofed Sender Email
- Email address is `support@paypa1.com` — the domain includes a **“1” instead of “l”**.
- This is a classic **email spoofing technique** to trick users into trusting the sender.

### 2. Urgent and Threatening Language
- Phrases like **“Failure to verify... will result in permanent suspension”** are used to create panic.
- This is a form of **social engineering**.

### 3. Suspicious Link
- URL shown: `https://www.paypalsecurelogin.com/verify`
- Not an official PayPal domain. This is a **lookalike phishing site**.
- Hovering over the link (in real email) would reveal the mismatch.

### 4. Generic Greeting
- Uses “Dear Customer” instead of the user's actual name.
- Legitimate services usually personalize emails.

### 5. Dangerous Attachment
- `PayPal_Statement.pdf.exe` is a double extension file.
- Disguised as a PDF but is actually an **executable (.exe)** — likely malware.

### 6. Poor Grammar / Formal Tone
- Overly robotic or stiff phrases like “Thank you for your immediate attention” and awkward formatting are common in phishing attempts.

---

## Conclusion

This email is clearly a phishing attempt designed to:
- Steal user credentials
- Trick users into clicking malicious links
- Possibly install malware via an attachment

It demonstrates multiple phishing indicators including **spoofing**, **fake links**, **social engineering**, and **malicious files**.

Users should be trained to identify such signs and avoid interacting with suspicious emails.

