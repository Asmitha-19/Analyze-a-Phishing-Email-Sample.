# Analyze-a-Phishing-Email-Sample.
1. Sample Phishing Email (Fake Example)

From: Security Alert <secure-update@paypal-support.com>
To: You
Subject: URGENT: Account Suspension Notice!

Dear Customer,

Your PayPal account has been temporarily suspended due to suspicious activity. Please click the link below to verify your information and restore account access:

[Verify Account Now](http://paypal-warnings.com/restore)

If no action is taken within 24 hours, your account will be permanently locked.

Thank you,
PayPal Security Team

Attachment: Account_Security_Update.exe
```
#### 2. Analysis of Phishing Indicators

- **Sender Address:**  
  - Looks suspicious and is not from official PayPal domain (uses “paypal-support.com” instead of “paypal.com”).
  - Spoofing attempt detected.

- **Header Analysis:**  
  - Email headers (checked with header analyzer) show routing from suspicious IP addresses and mismatched “From”/“Reply-To” fields.

- **Suspicious Links:**  
  - Hyperlink doesn’t go to official PayPal (actually links to “paypal-warnings.com”).
  - Mismatched visible link vs. actual URL.

- **Attachments:**  
  - Unsolicited executable file attached (“Account_Security_Update.exe”), which is uncommon and unsafe for trusted organizations.

- **Urgency & Threat:**  
  - Urgent tone (“restore access within 24 hours, or account will be locked”) creates panic and forces quick action.

- **Spelling/Grammar:**  
  - Multiple errors such as “Account_Security_Update.exe” and generic opening (“Dear Customer”).

- **Generic Greeting:**  
  - No personal identification; uses “Dear Customer.”

#### 3. Summary of Phishing Traits

- Sender domain spoofed/misspelled  
- Mismatched and suspicious URLs  
- Threatening and urgent language  
- Unsafe attachment file type  
- Poor grammar and generic greeting  
- Header inconsistencies found

#### 4. Conclusion

This email exhibits multiple signs of phishing:
- Spoofed sender address  
- Mismatched URLs and suspicious domain  
- Threats and urgency to induce panic  
- Unsolicited executable attachment  
- Technical header discrepancies  
- Poor attention to grammar and personalization

**Recommendation:** Do not click any links or download attachments. Report the email to IT/security, and block the sender.
