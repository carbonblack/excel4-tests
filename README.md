# excel4-tests


## Excel 4 Macro Forensics Tips

### Execution Techniques
Below are common execution techniques leveraged by malware inside of Excel4 macro documents.

Techniques | Description | Malicious Usage |
---------- | ----------- | --------------- |
EXEC | starts a process | Often used to execution second stage payload |

### Obfuscation Techniques
Common Evasion or Obfuscation techniques often used by malware inside of Excel4 macro documents.

Techniques | Description | Malicious Usage |
---------- | ----------- | --------------- |
Download via DCONN | | download additional excel4 macro content |

### Sandboxing Detection Techniques
Techniques used to check document execution environment

Function | Description | Malicious Usage |
---------- | ----------- | --------------- |
`GET.WORKSPACE` | Returns information about the workspace | Used to detect various information about windows environment to evade dynamic detonation |