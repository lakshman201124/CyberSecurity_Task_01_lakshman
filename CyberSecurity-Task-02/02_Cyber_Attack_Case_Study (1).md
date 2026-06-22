# Part B: Real-World Case Study — SolarWinds Supply Chain Attack

## What Happened?

The SolarWinds attack, discovered in December 2020, is widely considered one of the most sophisticated and far-reaching cyberattacks in history. The attackers — believed to be a state-sponsored group — compromised the build process of SolarWinds' Orion software, a widely used IT monitoring platform. They inserted malicious code (nicknamed "SUNBURST") directly into a legitimate software update that was then distributed to around 18,000 customers, including US government agencies such as the Treasury Department, the Department of Homeland Security, and major private corporations like Microsoft and Intel.

Because the malware was embedded in a trusted, signed software update, it bypassed most traditional security defenses. Once installed, it lay dormant for up to two weeks before activating, giving it time to avoid detection. The attackers then used it to move silently through victim networks, stealing sensitive data and communications over a period of several months before being discovered.

## Which Part of the CIA Triad Was Affected?

**Confidentiality** was the primary casualty — the attackers' goal was silent, sustained access to steal sensitive government and corporate information without triggering alarms. They were not destroying or locking data, but reading it covertly over months. **Integrity** was also compromised — the software supply chain itself was corrupted, meaning organizations could no longer trust that the software they received from a vendor was legitimate and unmodified. **Availability** was less directly impacted since the attackers preferred to stay hidden rather than disrupt operations.

## What Was the Impact?

- Sensitive communications and data from multiple US federal agencies were accessed and potentially exfiltrated
- The breach went undetected for approximately 9 months, allowing extensive access
- It exposed a critical vulnerability in software supply chains — the trusted update mechanism itself became the attack vector
- It sparked a global rethinking of how organizations verify and trust third-party software
- Estimated remediation costs ran into hundreds of millions of dollars across affected organizations

## How Could It Have Been Prevented?

- **Software supply chain security:** Implementing stricter code integrity checks and build process security to detect unauthorized modifications before software is signed and distributed
- **Zero-trust architecture:** Rather than trusting software simply because it came from a known vendor, applying strict verification and least-privilege access to all systems regardless of the software's origin
- **Network traffic monitoring:** Unusual outbound communications from the Orion software — the SUNBURST backdoor communicated with external command servers — could have been caught earlier with robust network monitoring
- **Faster detection:** Enhanced threat detection tools focused on behavior (not just known signatures) might have flagged the dormant malware's activity sooner
- **Vendor security assessments:** Organizations relying on third-party software should periodically audit the security practices of their vendors, not just the software itself
