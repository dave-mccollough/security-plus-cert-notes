# Threat Intelligence Sources

## You must consider the sources of your intelligence
- **Timeliness**
    - Property of an intelligence source that insures it's up to date
    - Over time intelligence loses its value

- **Relevancy**
    - Property of an intelligence source that ensures it matches the use-cases it was intended for
    - What intelligence affects me and my organization

- **Accuracy**
    - Property of an intelligence source that ensures it produces effective results
    - Information needs to be valid and true
    - Eliminate false positives

- **Confidence Level**
    - Property of an intelligence source that ensures it produces qualified statements about reliability
    - MISP Project codifies the use of the admiralty scale for grading data and estimative language
        - https://misp-project.org/
        - Evaluates based on:
            - Source reliabilty 
                - Graded on a scale of A-F
                - **Reliable** to **Cannot be Judged**
            - Source Content
                - Graded on a scale of 1-6
                - **Confirmed** to **Cannot be judged**



## Three Sources of Information
- **Propietary**
    - Threat intelligence is widely provided as a commercial service offering, where access to updates and research is subject to a subscription fee.

- **Closed Source**
    - Data that derived from the providers own research and analysis efforts, such as data from honeynet they operate, plus information mined from its customers systems(anonymized)
    - Fireeye

- **Open Source**
    - Data that is available to use without subscription, which may include threat feeds similar to commerical providers, and may contain reputation lists and malware signature databases
    - US-Cert
    - UK's NSCS
    - AT&T Security - Open Threat Exchange (OTX)
    - MISP - Malware Information Sharing Project
    - VirusTotal - Upload any file your not sure of - Public repo for malware
    - Spamhaus - Focused on spam email
    - SANS ISC Suspicious Domains

## Open-Source Intelligence (OSINT)
- Methods of obtaining information about a person or organization through public records, websites and social media

- **Threat feeds are a form of explicit knowledge, but implicit knowledge from experienced practitioners is also useful**