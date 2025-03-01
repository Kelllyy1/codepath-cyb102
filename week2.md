# Intrusion Detection Systems
  The focus this week was learning about Intrusion Detection and Prevention Systems.

<h3>Event Logs </h3>
<h4>Windows Event Viewer</h4>
- Common Windows Logs that are often inspected:
<!-- https://www.ultimatewindowssecurity.com/securitylog/encyclopedia/default.aspx -->
<br>-- Applications
<br>-- Security: timestamp, categories, IDs, severity level
<br>-- Systems
<br>- Each ID is associated with an action, so every time a particular action occurs, that ID is logged. For instance, Event ID 4625 is for Login attempts.

<h4>Linux Logs</h4>
 - /var/logs/ stores the log files here
 <br>- tail command - prints the last 10 lines of a file
  <br>- "auth.log" - shows recent failed login attempts
  <br>- "syslog" - lists all the actions that ocurred on the system
  <br>- "dmesg" - displayes messages from the kernel
  <br>- There are many options for log analysis

  <h3>Vulnerability Scanners</h3>
  Popular frameworks/websites for security analysis:
  <br>- CVE
  <br>- NVD
  <br>- NIST

<h3>Types of Intrusion Systems</h3>
- Host-based Intrusion Detection Systems: watch the events occur and sets off an alarm
<br>- Host-based Intrusion Prevention Systems: watch the events occur and do something about it


  
