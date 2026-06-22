# Part A: Understanding the CIA Triad

The CIA Triad stands for Confidentiality, Integrity, and Availability. It is the core model that every cybersecurity decision is built around — every threat, every control, and every policy maps back to protecting one or more of these three principles. Together they define what "secure information" actually means.

## 1. Confidentiality

**Definition:** Confidentiality is the principle that information should only be seen or accessed by people who are explicitly authorized to do so. It ensures that sensitive data is kept private and shielded from unauthorized disclosure.

**Why it is important:** In a world where personal, financial, and organizational data is constantly being transmitted and stored digitally, maintaining confidentiality is essential. A failure of confidentiality — whether through a hack, a misconfigured database, or a careless employee — can expose private data to competitors, criminals, or the public, resulting in legal penalties, financial losses, and loss of user trust.

**Real-world Example:** When an employee sends a confidential company document to their personal email to work from home, and that personal account gets breached, confidentiality is violated — even though no external hacker directly targeted the company's systems.

## 2. Integrity

**Definition:** Integrity means ensuring that data remains accurate, complete, and unaltered from its original state unless changed by an authorized process. It is about trusting that the information you're looking at is true and untampered.

**Why it is important:** Decisions made on corrupted or manipulated data can have serious consequences — whether it's a bank processing incorrect transaction amounts, a hospital working from altered medication records, or a college showing incorrect attendance. Integrity controls ensure that what is stored is what actually happened.

**Real-world Example:** During the 2016 Bangladesh Bank cyber heist, attackers manipulated SWIFT transaction messages to authorize fraudulent transfers of $81 million. The integrity of the financial messages was compromised — the data was altered to appear legitimate while actually being fraudulent.

## 3. Availability

**Definition:** Availability means ensuring that systems, networks, and data are accessible and operational for authorized users whenever they need them. A system that is secure but constantly down is not fulfilling its purpose.

**Why it is important:** Downtime has real-world costs — for hospitals it can mean delayed treatment, for businesses it means lost revenue, and for governments it can disrupt critical services. Ensuring availability means building resilience: redundancy, backups, and protection against attacks designed to overwhelm or crash systems.

**Real-world Example:** In 2016, the Mirai botnet launched a massive DDoS attack on Dyn, a DNS provider, taking down major websites including Twitter, Netflix, and Reddit for hours. Availability was completely broken — even though none of the data was stolen or modified.

## Comparison Table

| Principle | Definition | Importance | Real-World Example |
|---|---|---|---|
| **Confidentiality** | Only authorized users can access information | Prevents unauthorized disclosure and privacy violations | Employee emailing confidential data to a personal account that gets breached |
| **Integrity** | Information stays accurate and unaltered | Ensures data can be trusted for decision-making | Bangladesh Bank heist — SWIFT messages manipulated to authorize fraudulent transfers |
| **Availability** | Systems are accessible when needed | Prevents downtime that disrupts operations and services | Mirai botnet DDoS attack bringing down major websites for hours |
