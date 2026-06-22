# Part D: Threat Identification

## 1. Insider Threat

**Description:** An insider threat comes from someone within the organization — a current or former staff member, student, or contractor — who misuses their authorized access to cause harm. This can be intentional (disgruntled employee leaking data) or accidental (staff member falling for phishing and unknowingly giving attackers a foothold). What makes insider threats particularly dangerous is that traditional perimeter defenses like firewalls don't help — the attacker is already inside.

**Possible Impact:** Theft or leakage of sensitive data such as payroll records, student information, or exam papers; deliberate sabotage of systems before leaving; accidental exposure of confidential data through careless sharing or poor security habits. Insider incidents often go undetected for long periods because the activity looks like normal authorized use.

**Prevention Methods:**
- Apply the principle of least privilege — staff should only have access to what they genuinely need for their role
- Monitor user activity logs, especially for sensitive data and systems
- Establish a clear offboarding procedure that immediately revokes access when someone leaves
- Create a culture where security concerns can be reported without fear

## 2. Malware

**Description:** Malware is a broad term for any software designed to cause harm to a system, steal data, or provide unauthorized access. It includes viruses (which attach to files and self-replicate), worms (which spread across networks automatically), trojans (disguised as legitimate software), spyware (which silently monitors activity), and ransomware (which encrypts files and demands payment).

**Possible Impact:** Loss of critical data, system downtime, financial cost of remediation or ransom, reputational damage if a college's systems are found to be compromised, and potential exposure of student or staff personal data.

**Prevention Methods:**
- Maintain up-to-date antivirus and endpoint protection on all devices
- Educate users to avoid downloading software from unofficial or unverified sources
- Disable AutoRun features on USB ports to prevent infected drives from executing automatically
- Use application whitelisting to only allow approved software to run on college systems

## 3. Phishing

**Description:** Phishing is a social engineering attack that uses deceptive messages — most commonly emails — crafted to look as though they come from a trusted source. The goal is to trick the recipient into revealing credentials, clicking a link that installs malware, or transferring money or data. Spear phishing is a more targeted version directed at specific individuals using personalized information.

**Possible Impact:** Compromised staff or student accounts, unauthorized access to internal systems, financial fraud if payment-related credentials are stolen, and a potential entry point for much larger attacks within the college network.

**Prevention Methods:**
- Run regular phishing simulations and security awareness training for all staff and students
- Implement email filtering and anti-spoofing measures (SPF, DKIM, DMARC)
- Enforce MFA so that stolen passwords alone are not sufficient for account access
- Establish a clear process for reporting suspicious emails to the IT team

## 4. Weak Passwords

**Description:** Weak passwords — those that are too short, too simple, or reused across multiple accounts — are one of the most common and preventable causes of account compromise. Attackers use automated tools to try thousands of common passwords (brute force) or test known leaked credentials against new targets (credential stuffing).

**Possible Impact:** Unauthorized access to student portals, staff systems, or administrative platforms; account takeover leading to data theft or misuse; and cascading breaches if the same password protects multiple linked systems.

**Prevention Methods:**
- Enforce a minimum password length of at least 12 characters with complexity requirements
- Implement account lockout policies after a set number of failed login attempts
- Encourage or mandate the use of password managers across the institution
- Require MFA as an additional layer on top of passwords for all critical systems

## 5. Unpatched Systems

**Description:** Every piece of software — operating systems, browsers, applications, server software — occasionally has vulnerabilities discovered in it. Vendors release patches to fix these. Unpatched systems are those where these fixes haven't been applied, leaving known vulnerabilities open for attackers to exploit. Attackers actively scan for and target these known weaknesses because the exploit is already understood and tested.

**Possible Impact:** Full system compromise through known, publicly documented exploits; malware infection including ransomware; unauthorized access to college databases; and in networked environments, rapid lateral spread to other connected systems.

**Prevention Methods:**
- Set up automated patch management for operating systems and common applications
- Prioritize critical security patches — especially for internet-facing systems — and apply them within 24–48 hours of release
- Maintain an up-to-date inventory of all software in use so nothing is overlooked
- Isolate or retire systems that can no longer receive vendor security support
