# 🛠 Runbook Example – Critical Service Outage

This runbook outlines the step-by-step response process for a major service outage involving a core application. It is designed to minimize downtime, ensure proper communication, and speed up recovery.

---

## 🔔 When to Use

- Full application outage or major degradation
- Multiple user reports
- SLA at risk or already breached

---

## 🚦 Severity Level

- Severity 1 (Critical)  
- Requires immediate response – 24/7 support

---

## 1. 🧭 Initial Response (0–10 min)

- [ ] Acknowledge alert
- [ ] Validate impact across services
- [ ] Inform on-call engineer or SRE
- [ ] Open incident ticket with high severity tag

---

## 2. 🔎 Diagnosis (10–30 min)

- [ ] Check logs, metrics, dashboards
- [ ] Identify pattern (e.g., recent deploy, spike)
- [ ] Check dependency health (DB, APIs, Auth)
- [ ] Reproduce issue if needed

---

## 3. 🔧 Recovery Actions (30–60 min)

- [ ] Restart affected services if safe
- [ ] Revert last deployment (if applicable)
- [ ] Switch to backup systems
- [ ] Inform users via status page or email

---

## 4. 🗣️ Communication Plan

| Audience        | Frequency         | Responsible       |
|-----------------|-------------------|-------------------|
| Internal teams  | Every 30 mins     | Incident Lead     |
| Stakeholders    | At T+1h or major update | IT Manager |
| Customers       | Via status page   | Comms / Support   |

---

## 5. ✅ Resolution & Follow-Up

- [ ] Document fix in ticket
- [ ] Close incident and notify stakeholders
- [ ] Start Root Cause Analysis within 24h
- [ ] Update runbook if applicable

---

## 📂 Related

- [Incident Escalation Guide](./incident-escalation-guide.md)  
- [Root Cause Analysis Template](./root-cause-analysis-template.md)

---

[🔙 Return to Main Index](./README.md)
