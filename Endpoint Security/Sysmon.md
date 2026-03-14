## Sysmon

Sysmon (System Monitor) is a Windows system service and device driver from the Microsoft Sysinternals suite that monitors and logs detailed system activity to the Windows Event Log. It provides granular visibility into process creation, network connections, file creation, registry modifications, and other endpoint behaviors that are not captured by standard Windows logging. Sysmon is widely deployed in enterprise environments as a foundational endpoint telemetry source for threat detection, incident response, and forensic investigations.

The effectiveness of Sysmon is largely determined by its configuration, and community-developed configuration templates provide high-quality, battle-tested baselines that analysts can deploy and customize to maximize detection coverage across their environment.

### Objectives of Sysmon Analysis

* Capture detailed endpoint telemetry beyond native Windows event logging
* Detect malicious process creation, injection, and execution behaviors
* Monitor network connections and correlate them with responsible processes
* Track file creation, registry changes, and driver loading activity
* Support threat hunting, detection engineering, and incident response operations

### Common Information Analyzed

* Process creation events including command-line arguments and parent processes
* Network connection events with associated process and binary information
* File creation and modification events with hash values
* Registry key creation, modification, and deletion activity
* Driver and image load events including unsigned or suspicious modules
* Pipe creation and WMI activity indicative of lateral movement or persistence

### Tools URLs

* [Sysmon](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon)
* [sysmon-config - GitHub](https://github.com/SwiftOnSecurity/sysmon-config)
* [sysmon-modular - GitHub](https://github.com/olafhartong/sysmon-modular)