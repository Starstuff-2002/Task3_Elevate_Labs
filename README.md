# Task3_Elevate_Labs
# Basic Vulnerability Scan Report using Nessus Essentials

## Tool Used
- Nessus Essentials by Tenable
- Scan Target: Localhost (this PC)

## Objective
To perform a basic vulnerability scan on a personal computer using Nessus Essentials in order to identify common security vulnerabilities and explore possible remediation strategies.

## Scan Summary
- **Scan Policy:** Basic Network Scan
- **Scanner Type:** Local Scanner
- **Scan Status:** Completed
- **Scan Duration:** Approximately 1 hour
- **Vulnerabilities Identified:** 27 total

## Most Critical Finding

### SMB Signing Not Required
- **Severity Level:** Medium
- **CVSS Base Score:** 5.3
- **Description:** The scan identified that SMB (Server Message Block) signing is not required on the system. This misconfiguration may allow an attacker to perform man-in-the-middle (MITM) attacks, potentially intercepting or altering SMB traffic between systems.
- **Affected Component:** SMB protocol configuration
- **Risk Implications:** Without mandatory signing, SMB communications can be tampered with or intercepted without detection, especially in environments with shared networks.

## Vulnerability Summary
- Medium Severity: 1
- Mixed Severity: 1
- Informational: 25+

## Supporting Material
- Screenshots of the scan dashboard and vulnerability list are included in this repository.

## Key Takeaways
- Gained hands-on experience with a vulnerability scanner.
- Learned to identify and interpret various common vulnerabilities affecting personal computers.
- Understood the importance of securing default services such as SMB and TLS.
- Developed a basic remediation workflow for identified issues.



