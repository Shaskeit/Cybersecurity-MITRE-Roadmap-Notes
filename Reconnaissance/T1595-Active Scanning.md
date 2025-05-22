
# T1595 – [Active Scanning]

## 📌 Tactic(s)
- Reconnaissance

## 🧠 Description
> Actuve scans are those where the adversary probes victim infrastructure via network traffic, as opposed to other forms of reconnaissance that do not involve direct interaction.

Example:
This technique targets specific safety Controllers within the enviroment.

## 🛠️ Real-World Examples
- **Triton Safety Instrumented System Attack, engaged in network reconnaissance againts targets of interest.

## 🔍 Detection Ideas
- Monitor and analyze traffic patterns and packet inpsection associated to protocols that do not follow the expected protocol standards and traffic flows(e.g extraneous packets that do not belong to established flows, gratuitous or anomalous traffic patterns, anomalous syntax, or structure).

## 🔐 Mitigation Strategies
- This technique cannot be easily mitigated with preventive controls since it is based on behaviors perfomed outside of the scope of enterprise defense controls.
- Effotrs should focus on minimizing the amount of sensitivity of data available to external parties.

## 🔗 External References
- https://attack.mitre.org/techniques/T1595/


## 🧪 Related Tools or Labs
- TryHackMe: [Room name or link]
- Atomic Red Team: [Link to atomic test]
- Detection Lab / ELK Stack setup (optional)

---

**Author**: Jose Luis  
**Date**: 2025-05-21  
