# Windows 10 STIG Full Remediation Lab  
**Author:** Dylan Leonard  
**GitHub Portfolio:** [https://github.com/dylanleonard-1](https://github.com/dylanleonard-1)  

---

## **Overview**  
This repository demonstrates the full remediation of Windows 10 DISA STIG vulnerabilities using custom-developed PowerShell scripts, with remediation steps executed and validated in a dedicated Windows 10 virtual machine.  

---

## **Tools Used**  
- Windows 10 Virtual Machine  
- PowerShell ISE  
- DISA STIG Benchmarks  
- Nessus Vulnerability Scanning  
- GitHub for version control and documentation  

---

## **STIG Remediations Completed**  

| STIG ID            | Description (from benchmark)                       | Script Link |
|--------------------|----------------------------------------------------|-------------|
| WN10-AU-000050     | Audit policy remediation using PowerShell          | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-AU-000050.ps1) |
| WN10-AU-000035     | Audit configuration remediation                    | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-AU-000035.ps1) |
| WN10-CC-000205     | Control Center hardening                           | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-CC-000205.ps1) |
| WN10-CC-000031     | Configuration fix                                  | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-CC-000031.ps1) |
| WN10-CC-000326     | Control Center remediation                         | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-CC-000326.ps1) |
| WN10-AU-000005     | Audit remediation script                           | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-AU-000005.ps1) |
| WN10-CC-000295     | Control Center setting remediation                 | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-CC-000295.ps1) |
| WN10-CC-000010     | Configuration script                               | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-CC-000010.ps1) |
| WN10-AU-000580     | Audit logging remediation                          | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-AU-000580.ps1) |
| WN10-CC-000310     | Control Center configuration                       | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-CC-000310.ps1) |
| WN10-CC-000085     | Config fix                                         | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-CC-000085.ps1) |
| WN10-AU-000100     | Audit configuration fix                            | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-AU-000100.ps1) |
| WN10-AU-000155     | Audit configuration remediation                    | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-AU-000155.ps1) |
| WN10-SO-000080     | Security Options remediation                       | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-SO-000080.ps1) |
| WN10-AC-000005     | Access Control remediation                         | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-AC-000005.ps1) |
| WN10-AU-000575     | Audit configuration remediation                    | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-AU-000575.ps1) |
| WN10-AU-000140     | Audit policy fix                                   | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-AU-000140.ps1) |
| WN10-CC-000066     | Control Center setting remediation                 | [View Script](https://github.com/dylanleonard-1/dylanleonard-1/blob/main/WN10-CC-000066.ps1) |

---

## **Execution Instructions**  
1. Clone this repository.  
2. Launch PowerShell ISE as Administrator.  
3. Navigate to the `Scripts/` directory.  
4. Execute each remediation script individually or batch run.  
5. Verify remediation using Nessus or DISA STIG scanning tools.  

---

## **Proof of Work**  
All before/after scans and evidence are located in the `/Evidence/` folder.  

---

## **Key Takeaways**  
- Mastery of PowerShell scripting for compliance remediation.  
- Strong understanding of Windows 10 STIG controls and mitigation steps.  
- Audit-ready documentation and remediation verification.  

---

## **Future Enhancements**  
- Automate remediation across multiple endpoints using Ansible or Azure Automation.  
- Expand project to Windows Server STIGs and hybrid cloud infrastructure.  
