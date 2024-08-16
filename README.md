# 🚨 XSS Payload Collection

This repository contains a collection of unique XSS (Cross-Site Scripting) payloads that can be used for security testing purposes. These payloads help in identifying and mitigating XSS vulnerabilities in web applications.

## 📂 File Description

- **[XSS_all_payloads_unique](./XSS_all_payloads_unique)**  
  This file contains a carefully curated list of unique XSS payloads, free from duplicates. You can use these payloads in penetration testing tools, scripts, or manually test your web applications for XSS vulnerabilities.

## 🛠️ How to Use

To use the XSS payloads from this repository, follow these steps:

1. Clone or download this repository:
   \`\`\`bash
   git clone https://github.com/$GITHUB_USERNAME/$REPO_NAME.git
   \`\`\`
2. Navigate to the folder containing the $FILE_NAME file:
   \`\`\`bash
   cd $REPO_NAME
   \`\`\`
3. Open the file and choose a payload for testing:
   \`\`\`bash
   cat $FILE_NAME
   \`\`\`

4. Copy the desired payload and inject it into form fields, URL parameters, or other user input areas of the application under test.

### Example of a Basic XSS Payload

Here's an example of an XSS payload from the file:

\`\`\`html
<script>alert('XSS');</script>
\`\`\`

This payload can be inserted into form fields, URL parameters, or comment sections to check for possible XSS vulnerabilities.

## 🔄 Example of Automated Testing

You can also automate the testing of XSS payloads using tools such as:

- **Burp Suite**
- **OWASP ZAP**
- **Fuzzers**

For example, in **Burp Suite**, you can import this payload list as a custom wordlist for active scanning:

\`\`\`bash
# Example to show how to load wordlist into Burp Suite Intruder

# 1. Open Burp Suite.
# 2. Go to Intruder > Positions.
# 3. Highlight the parameter where you want to test for XSS.
# 4. Select Payloads tab > Load your custom wordlist.
# 5. Choose "$FILE_NAME" and start the attack.
\`\`\`

## 💡 Contribution Guidelines

We welcome contributions to expand the collection of XSS payloads. If you would like to contribute:

1. Fork the repository.
2. Add your unique payloads to \`$FILE_NAME\`.
3. Submit a pull request with a brief explanation of the changes.

### Example Contribution:

\`\`\`html
<svg onload=alert(1)>
\`\`\`

## ⚠️ Disclaimer

This collection is for **educational purposes** and **ethical hacking** only. Please use it responsibly and ensure you have permission before testing any application. Unauthorized testing is illegal and unethical. Always follow legal and ethical guidelines when performing security tests.
EOT
