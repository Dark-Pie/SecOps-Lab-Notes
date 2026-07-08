# TryHackMe Room: SOC Fundamentals 🛡️

* **Date Completed:** July 5, 2026
* **Difficulty:** Easy
* **Category:** Blue Team / SecOps Fundamentals

---

## 1. Objective & Core Concepts
The objective of this room was to understand the primary functions, technologies, and workflow models within a modern Security Operations Center (SOC).

### Key Takeaways:
* **The 3 Pillars of a SOC:** People, Process, and Technology must align to filter false alerts and handle legitimate threats effectively.
* **Triage Analysis:** Learned how to evaluate an alert by identifying the **5 Ws**: *What* triggered the alert, *When* it occurred, *Where* it originated/targeted, *Who* was the source, and *Why* it happened.

---

## 2. Practical Lab Component
During the practical exercise, I triaged a simulated network alert involving a suspicious host interaction.

### Investigation Steps:
1. Identified the source host name as `Nessus` executing a port scan.
2. Determined the destination host IP to be `10.0.0.3`.
3. Concluded that the activity was an *Intended* vulnerability scan rather than a malicious breach attempt.

---

## 3. Defensive Mitigations
To maintain zero-trust integrity during regular operations, vulnerability scanning tools like Nessus should be explicitly whitelisted within internal asset inventories, ensuring security teams can differentiate scheduled scans from active adversarial reconnaissance.
