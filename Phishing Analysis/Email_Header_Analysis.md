## Email Header Analysis

Email Header Analysis is the process of examining the metadata embedded in an email message to trace its origin, delivery path, and authenticity. It is a critical technique in cybersecurity investigations, phishing analysis, and incident response, as email headers contain technical details that are often hidden from end users but reveal important information about how a message was sent and routed.

By analyzing email headers, security analysts can identify spoofed sender addresses, trace the path of a message through mail servers, detect misconfigurations, and uncover indicators of compromise (IOCs) associated with malicious email campaigns.

### Objectives of Email Header Analysis

* Trace the origin and delivery path of an email message
* Identify spoofed or forged sender information
* Verify email authentication mechanisms (SPF, DKIM, DMARC)
* Extract indicators of compromise such as IPs, domains, and message IDs
* Support phishing investigations and incident response activities

### Common Information Analyzed

* Received headers and mail server relay chain
* From, Reply-To, and Return-Path fields
* SPF, DKIM, and DMARC authentication results
* X-Originating-IP and source IP addresses
* Message-ID and timestamp metadata
* User-Agent and mailer software information

### URLs

[Message Header Analyzer](https://mha.azurewebsites.net)
[MXToolbox](https://mxtoolbox.com)
[Google Apps Toolbox](https://toolbox.googleapps.com)
[13Cubed - GitHub](https://github.com/13Cubed/EmailHeader)
[Email IOC Extractor - GitHub](https://github.com/MalwareCube/Email-IOC-Extractor)