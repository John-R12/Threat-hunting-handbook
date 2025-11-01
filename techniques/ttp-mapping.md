# 📊 TTP Mapping for Threat Hunting

Mapping observed activity to **MITRE ATT&CK TTPs** allows hunters to **understand adversary behavior** and detect campaigns effectively.

---

## 🧩 Purpose

- Align hunts with **standardized techniques**.  
- Prioritize detection based on **adversary goals**.  
- Facilitate **reporting, correlation, and intelligence sharing**.

---

## 📁 Example Table

| Observed Activity | MITRE ATT&CK TTP | Tactic | Notes |
|------------------|-----------------|--------|-------|
| Suspicious PowerShell execution | T1059.001 | Execution | Possible living-off-the-land activity |
| Unusual RDP session | T1021.001 | Lateral Movement | Check source & destination |
| Malicious registry modification | T1112 | Persistence | Investigate process and owner |
| Data exfiltration via HTTP | T1041 | Exfiltration | Monitor volume and destination |

---

## ⚙️ How to Use

1. Compare **endpoint, network, and cloud activity** with TTPs.  
2. Use mapping to **guide investigation and hunting steps**.  
3. Update and expand your **organization-specific hunting library**.  

---

## 📚 References

- MITRE ATT&CK – *Enterprise, ICS, Mobile*  
- SANS – *Threat Hunting Techniques*
