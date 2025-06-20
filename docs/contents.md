| [Home](../README.md) |
 | -------------------------------------------- |

# Contents

The **Outbreak Response - TBK DVRs Botnet Attack** solution pack contains the following resources.

## Outbreak Alerts Record Set

| Name | Description |
|:-------------------------|:------------------|
| TBK DVRs Botnet Attack | Threat Actors are actively exploiting CVE-2024-3721, a command injection vulnerability in TBK DVR devices (Digital Video Recorders). This flaw allows unauthenticated remote code execution (RCE) via crafted HTTP requests to the endpoint. The compromised devices are conscripted into a botnet capable of conducting DDoS attacks. |

## Threat Hunt Rules Record set

| Name | Rule Type |
|:-------------------------|:------------------|
| FortiAnalyzer Threat Hunting - TBK DVRs Botnet Attack Event-Handler | Fortinet Fabric |
| FortiSIEM ContentUpdate - Outbreak: TBK DVR Authentication Bypass Attack Detected on Network | Fortinet Fabric |


 <table><th>NOTE</th><td>These SIGMA and Yara rules are sourced from public community repositories are not independently verified or validated by Fortinet. While community-contributed rules can be valuable for timely threat detection, they may vary in quality, accuracy, and relevance. Fortinet is not responsible for any inaccuracies, errors, or omissions in these rules, nor for any damage or loss that may result from their application. We encourage users to conduct their own validation and adapt these rules as necessary to meet specific security needs and contexts</td></table> 

# Next Steps
| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
| ----------------------------------------- | ------------------------------------------- | --------------------- |