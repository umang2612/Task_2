# Task_2
Analyze a Phishing Email Sample

## 🛠️ Tools Required
- Email client or `.eml` file viewer
- Online header analyzer:
  - [Google Header Analyzer](https://toolbox.googleapps.com/apps/messageheader/)

---

## 🧪 Analysis Steps

### 1. **Obtain a Sample**
Download a phishing email in plain text or `.eml` format.

### 2. **Check Sender Information**
- Inspect the "From" email address.
- Look for spoofed domains or generic names.

### 3. **Analyze Email Headers**
- Paste full headers into an online analyzer.
- Check SPF/DKIM/DMARC results.
- Review source IP location and server paths.

### 4. **Inspect Links**
- Hover over hyperlinks (do not click).
- Compare displayed vs. actual URLs.
- Watch for misspellings or suspicious domains.

### 5. **Review Attachments**
- Identify file types (.exe, .pdf, .doc).
- Never open attachments on a production machine.
- Consider using a virtual machine for testing.

### 6. **Look for Red Flags in Language**
- Threats, urgency, or time pressure.
- Generic greetings (e.g., “Dear User”).
- Spelling or grammar errors.

### 7. **Document Findings**
Write a report summarizing phishing indicators found, such as:
- Sender spoofing
- Authentication failures
- Malicious URLs or attachments
- Psychological manipulation tactics


---

## ✅ Best Practices
- Never interact with links or attachments in real phishing emails unless in a secure lab environment.
- Use anonymized data when sharing reports.
- Regularly update tools and phishing indicators based on new threats.
