# Threat Hunting

**Threat Hunting:**  Threat hunting is a technique designed to detect presence of threats that have not been discoverd by normal security monitoring
- Proactive vs Reactive
- Threat hunting is potentially less disruptive than a pentest
- Threat Hunting relies on the use of tools developed for regular security monitoring and incident response
- Assume existing rules have failed
- Consumes a lot of resources and time to conduct, but can yield a lot of benefits
    - Improve detection abilities
    - Integrate with intelligence
    - Reduce attack surface
    - Block attack vectors
    - Identify critical assets

## Process of Threat Hunting

- **Establish a Hypothesis**
    - A hypothesis is derived from the existing threat modeling data.  Hypotheisi is based on potential events with higher likelihood and higher impact
    - Who wants to harm us?
    - How are they going to do it?

 **Profiling Threat Actors and Activities**
 - Involves the creation of scenarios that show how a prospective attacker might attempt an intrusion and what their objectives might be

- Analyze logs, registery changes. process logs from different hosts
- Data is consolidated in a SIEM