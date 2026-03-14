## Dynamic Attachment Analysis

Dynamic Attachment Analysis is the process of executing suspicious files in a controlled, isolated sandbox environment to observe their behavior in real time. Unlike static analysis, which examines file content without execution, dynamic analysis reveals how a file actually behaves when run — including process creation, network connections, file system modifications, registry changes, and command-and-control communications.

It is a vital technique in malware analysis and incident response, particularly for analyzing obfuscated or packed malware that may evade static detection methods.

### Objectives of Dynamic Attachment Analysis

* Observe real-time behavior of suspicious files in a safe, isolated environment
* Identify malicious processes, network connections, and system modifications
* Detect obfuscated or packed malware that evades static analysis
* Extract indicators of compromise generated during file execution
* Correlate behavioral patterns with known malware families and threat actors

### Common Information Analyzed

* Process creation and injection activity
* Network traffic and DNS queries generated during execution
* File system and registry modifications
* Dropped files and secondary payloads
* Command-and-control communication patterns
* Screenshots and behavioral timeline of execution

### Tools URLs

* [Hybrid Analysis](https://www.hybrid-analysis.com)
* [Joe Sandbox Cloud Basic](https://www.joesandbox.com)
* [ANY.RUN](https://any.run)
* [Cuckoo Sandbox](https://cuckoosandbox.org)