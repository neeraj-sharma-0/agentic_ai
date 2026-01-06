# Agentic AI: CVE + EPSS Prioritization leveraging Langchain
## Using Python Langchain, Langgraph, Langsmith


<img width="358" height="358" alt="image" src="https://github.com/user-attachments/assets/ec0fbdd3-d22e-4830-a1ed-fe5762b75547" />

### Building AI Agents over the weekend 
####  PacktPub / June 2025

### Glossary
| # | Abbreviation | Term                              | 
| - | ------------ | --------------------------------- | 
| 1 |  CVE         | Common Vulerability Exposure      |
| 2 |  EPSS        | Exploit Prediction Scoring System |


### Problem Statement
Automate the prioritization of the most recent vulnerabilities (CVEs) reported by NIST using the EPSS and enable Securitty teams to address the remediation of recent vulnerabilities with focused and timely remediation.

#### Notes
1. There may be recent CVEs whose status is `Awaiting Analysis` : Security teams can proatively watch the CVEs and remediate when the analysis is completed by NIST.
2. This prioritization helps timely remediation of CVEs which improves the overall compliance with Security Audits.

### AI Agent Function:
The AI agent conducts realtime data ingestion from NIST (with API key) and enriches the data from EPSS (Exploit Prediction Scoring System) followed by conducting `asset impact`  and finally `auto-prioritizes` in realtime the  CVes for efficient remediation downstream.

the AI agent begins by conducting real-time data ingestion from NIST, utilizing an API key. It then enriched the data from EPSS (Exploit Prediction Scoring System) before moving on to assess asset impact. 

The AI agent concludes by performing real-time auto-prioritization using langchain, leading to streamlined CVE remediation for enhancing cybersecurity efforts.

### Pydot AI-Agent Graph Visualization (Basic)

<img width="616" height="976" alt="ydot AI-Agent Graph Visualization" src="https://github.com/user-attachments/assets/c8b17860-76b5-4039-a19e-e3e33f4bd00f" />

### Code and Certification
Available on request.
