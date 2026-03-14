## Windows Event Logs

Windows Event Logs are a centralized record of system, security, and application activity maintained by the Windows operating system. They capture a wide range of events including user logons, process creation, privilege escalation, service installations, and policy changes, making them an essential data source for security monitoring, incident response, and forensic investigations.

Security analysts use tools such as `wevtutil` and PowerShell's `Get-WinEvent` cmdlet to query, filter, and extract relevant events from local and remote systems during threat hunting and incident response operations. Combined with curated event monitoring lists and autorun artifact enumeration, Windows Event Logs provide deep visibility into attacker activity across the endpoint.

### Objectives of Windows Event Log Analysis

* Identify malicious or suspicious activity recorded across Windows event channels
* Detect persistence mechanisms, privilege escalation, and lateral movement
* Correlate logon events, process creation, and network activity across endpoints
* Query and filter events efficiently using wevtutil and PowerShell cmdlets
* Support live incident response and post-incident forensic investigations

### Common Information Analyzed

* Security event logs including logon, logoff, and privilege use events
* System and application logs for service installations and crashes
* Process creation events with command-line arguments (Event ID 4688)
* PowerShell script block and module logging events
* Autorun and persistence artifact enumeration from live systems
* Scheduled task and cron expression analysis for persistence detection

### Tools URLs

* [wevtutil](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/wevtutil)
* [Get-WinEvent](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.diagnostics/get-winevent)
* [Creating Get-WinEvent queries with FilterHashtable](https://learn.microsoft.com/en-us/powershell/scripting/samples/creating-get-winevent-queries-with-filterhashtable)
* [Appendix L - Events to Monitor](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/plan/appendix-l--events-to-monitor)
* [AutoRuns PowerShell Module - GitHub](https://github.com/p0w3rsh3ll/AutoRuns)
* [Crontab Guru](https://crontab.guru)
* [LimaCharlie](https://limacharlie.io)
* [Hunt Evil - SANS Poster](https://www.sans.org/posters/hunt-evil)