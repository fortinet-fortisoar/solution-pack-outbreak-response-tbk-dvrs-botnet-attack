# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

Threat Actors are actively exploiting CVE-2024-3721, a command injection vulnerability in TBK DVR devices (Digital Video Recorders). This flaw allows unauthenticated remote code execution (RCE) via crafted HTTP requests to the endpoint. The compromised devices are conscripted into a botnet capable of conducting DDoS attacks. 

 The **Outbreak Response - TBK DVRs Botnet Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.1.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/tbk-dvrs-botnet-attack) contains information about the outbreak alert **Outbreak Response - TBK DVRs Botnet Attack**. 

## Background: 

FortiGuard Labs has detected a significant increase in malicious network activity exploiting CVE-2024-3721, a critical unauthenticated command injection vulnerability affecting TBK DVR devices. FortiGuard’s global network of intrusion prevention system (IPS) sensors recorded over 60,000 detection events, indicating widespread and coordinated exploitation attempts.

Our telemetry data reveals that multiple botnet operators are actively leveraging this vulnerability to expand their infrastructure. Notably, we have observed payloads and behaviors associated with Condi, Fodcha, Mirai, and Unstable botnet families- each known for targeting IoT devices to perform large-scale distributed denial-of-service (DDoS) attacks and establish persistent remote access. FortiGuard Labs continues to monitor this threat and will provide further intelligence as it becomes available. 

FortiGuard has previously released an Outbreak Alert for a different TBK vulnerability (CVE-2018-9995) exploited to spread Remote Access Trojan called HiatusRAT.  

## Announced: 

Currently, we are unaware of any vendor supplied patch or updates available for this issue. Immediate patching is recommended once available. Alternatively, we recommend isolating or replacing the TBK DVRs and Monitor for unusual traffic patterns or binary drops from DVRs.

Organizations with internet-facing DVR systems are strongly urged to take immediate mitigation steps, including:
-Blocking known indicators of compromise (IoCs) linked to these botnets.
-Applying firmware patches or security updates from the vendor, if and when available.
-Restricting remote access to DVR interfaces and placing them behind firewalls or VPNs. 

## Latest Developments: 

June 10, 2025: FortiGuard released a Threat Signal Report
https://www.fortiguard.com/threat-signal-report/6127/tbk-dvrs-botnet-attack

June 6, 2025: Analysis of the latest Mirai wave exploiting TBK DVR devices by Securelist
https://securelist.com/mirai-botnet-variant-targets-dvr-devices-with-cve-2024-3721/116742/ 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|
