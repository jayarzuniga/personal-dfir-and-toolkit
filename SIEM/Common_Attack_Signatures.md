## Common Attack Signatures

Common Attack Signatures are patterns, strings, and indicators embedded within network traffic, log entries, or application requests that are characteristic of known attack techniques. Recognizing these signatures is a fundamental skill in threat detection, incident response, and security monitoring, enabling analysts to identify exploitation attempts, malicious payloads, and attacker tooling based on observable artifacts.

Security analysts and detection engineers reference curated payload libraries and encoding references to understand what malicious input looks like in practice, build detection rules, and validate whether observed activity in logs or traffic matches known attack patterns such as Cross-Site Scripting (XSS), SQL Injection, XML External Entity (XXE) Injection, Command Injection, and Local and Remote File Inclusion (LFI/RFI).

### Objectives of Common Attack Signature Analysis

* Recognize known attack patterns and malicious payloads in logs and traffic
* Develop and tune detection rules based on real-world attack signatures
* Identify injection attempts, encoding abuse, and bypass techniques
* Correlate observed indicators with known attack categories and techniques
* Support threat hunting, alert triage, and security control validation

### Common Information Analyzed

* URL-encoded and obfuscated attack strings in HTTP requests
* SQL injection syntax and database enumeration patterns
* XSS payloads embedded in input fields, headers, and parameters
* XXE injection markup targeting XML parsers
* OS command injection strings and shell metacharacters
* Path traversal and file inclusion patterns in request parameters

### Tools URLs

* [HTML URL Encoding Reference](https://www.w3schools.com/tags/ref_urlencode.asp)
* [PayloadsAllTheThings - GitHub](https://github.com/swisskyrepo/PayloadsAllTheThings)
* [XSS Payload List](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XSS%20Injection)
* [SQL Injection Payload List](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/SQL%20Injection)
* [XXE Injection Payload List](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XXE%20Injection)
* [Command Injection Payload List](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Command%20Injection)
* [LFI and RFI Payload List](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/File%20Inclusion)