# task-3-
| Severity Level  | CVSS Score Range | Number of Vulnerabilities Found | Example Vulnerability                                 |
| --------------- | ---------------- | ------------------------------- | ----------------------------------------------------- |
| 🔴 **Critical** | 9.0 – 10.0       | 2                               | OpenSSH outdated version (Remote Code Execution risk) |
| 🟠 **High**     | 7.0 – 8.9        | 4                               | SMB signing not required (Man-in-the-Middle risk)     |
| 🟡 **Medium**   | 4.0 – 6.9        | 6                               | Weak TLS ciphers supported                            |
| 🔵 **Low**      | 0.1 – 3.9        | 3                               | Missing security headers (e.g., X-Frame-Options)      |

Interpretation
Critical Vulnerabilities should be patched immediately as they pose the highest risk of exploitation.

High Severity Issues require urgent attention but may have partial mitigations available.

Medium Issues often relate to configuration weaknesses that can be tightened.

Low Risks are minor but should still be addressed as part of good security hygiene.

🚀 Key Takeaways
CVSS helps prioritize remediation by providing a standardized severity score.

The highest risk items (Critical/High) should be fixed first to reduce attack surface.

Regular scans ensure that newly disclosed vulnerabilities are detected over time.

<img width="700" height="507" alt="image" src="https://github.com/user-attachments/assets/dfc9585e-e80a-47bb-931c-5f39e918f6e6" />
<img width="850" height="376" alt="image" src="https://github.com/user-attachments/assets/572ce6a0-160c-4430-9d16-6b60cba1cdcb" />



. What is vulnerability scanning?
Vulnerability scanning is the process of using automated tools to identify security weaknesses in systems, networks, or applications. It helps detect outdated software, misconfigurations, missing patches, or insecure settings that could be exploited by attackers.

2. Difference between vulnerability scanning and penetration testing?
Vulnerability Scanning: Automated, broad check for known security issues. Identifies what vulnerabilities exist.

Penetration Testing: Manual or semi-automated simulation of real-world attacks. Determines how vulnerabilities can be exploited and their real impact.

3. What are some common vulnerabilities in personal computers?
Outdated operating system or unpatched software

Weak or reused passwords

Insecure network services (e.g., open SMB, RDP)

Missing antivirus or endpoint protection

Misconfigured firewalls

Use of weak encryption (e.g., outdated SSL/TLS)

4. How do scanners detect vulnerabilities?
Scanners compare system information against a vulnerability database. They:

Collect details (open ports, running services, versions).

Match them against known vulnerabilities (CVEs).

Score and categorize the findings based on severity (e.g., CVSS).

5. What is CVSS?
CVSS (Common Vulnerability Scoring System) is an industry-standard framework for rating the severity of vulnerabilities.

Scores range from 0.0 (None) to 10.0 (Critical).

It considers exploitability, impact, and environmental factors.

Helps prioritize which issues to fix first.

6. How often should vulnerability scans be performed?
At least monthly for critical systems.

After every major change (new software, patching, or network updates).

In enterprise setups, continuous or weekly scanning is common.

7. What is a false positive in vulnerability scanning?
A false positive occurs when a scanner reports a vulnerability that doesn’t actually exist.
Example: A service might appear outdated, but it has been patched with a security backport by the vendor.

8. How do you prioritize vulnerabilities?
Use CVSS scores (Critical > High > Medium > Low).

Consider business impact (e.g., a vulnerability in a public-facing server is more urgent than one in an isolated system).

Focus first on exploitable vulnerabilities that attackers can use immediately.
