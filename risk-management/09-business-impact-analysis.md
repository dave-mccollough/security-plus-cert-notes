# Business Impact Analysis (BIA)

## Prioritize mission critical processes
- Payment Processing Systems
- Customer/Patient records

## Assess Risk
- Identify sensitive data and it's location
- Identify single points of failure
- Identify security controls and compliance that can reduce the impact of an event against business assets

## Business Impact
- Financial Impact
    - Fines
    - Loss of contracts
- Reputation loss
    - Customers
    - Shareholders
- Data loss
    - Breach notificaton
    - Escalation requirements
    - Exfiltration 
        - Sensitive data that has fallen into the hands of unauthorized users

- Recovery Point Objective (RPO)
    - Maximun tolerable amount of data loss
    - Directly related to backup frequency
        - If your RPO is 1 hour, you need to take backups at least once every hour

- Recovery Time Objective (RTO)
    - Maximum tolerable amount of downtime
    - Return systems and data back to useable state within RTO

## Failed Component Impact
- ### Mean Time Between Failures (MTBF)
    - Average time between failures of repairable components
        - Can be software or hardware components
            - Hardware repairs
            - Software patching

- ### Mean Time to Failure (MTTF)
    - Average time between **NON Repairable** component failure
        - Hard Disks, Switches, Routers

- ### Mean Time to Repair (MTTR)
    - Average time required to repair a failed component

## Location of Critical Resources
- ### Data discovery and classification
    - Where is our sensitive data?
    - Is the data classified?

- ### Impact on Sensitive Data
    - ### Privacy Threshold Assessment (PTA)
        - First step before implementing solutions related to sensitive data
        - Regulatory Compliance
