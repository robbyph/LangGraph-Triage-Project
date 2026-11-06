# Sources

The alerts and approval records are fictional coursework examples, drafted with AI assistance and informed by the sources below. They are not copied from an employer's security console.

The sources establish the underlying event types and security behaviors. Host names, tickets, approvals, and observations are invented scenario context.

## MITRE ATT&CK T1486: Data Encrypted for Impact

Source: [MITRE ATT&CK T1486: Data Encrypted for Impact](https://attack.mitre.org/techniques/T1486/)

Related alerts: A01, A08

Use: Background on file encryption and ransomware behavior; the exercise and its authorization are fictional scenario context.

## MITRE ATT&CK T1190: Exploit Public-Facing Application

Source: [MITRE ATT&CK T1190: Exploit Public-Facing Application](https://attack.mitre.org/techniques/T1190/)

Related alerts: A02

Use: Background on exploitation of exposed applications; the correlated IDS and endpoint observations are synthetic.

## Microsoft: Event 4732, A member was added to a security-enabled local group

Source: [Microsoft: Event 4732, A member was added to a security-enabled local group](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-10/security/threat-protection/auditing/event-4732)

Related alerts: A03, A07

Use: Event meaning and the importance of monitoring privileged-group membership changes.

## MITRE ATT&CK T1003.001: OS Credential Dumping, LSASS Memory

Source: [MITRE ATT&CK T1003.001: OS Credential Dumping, LSASS Memory](https://attack.mitre.org/techniques/T1003/001/)

Related alerts: A04

Use: Why suspicious access to LSASS memory and dumping may indicate theft of authentication material.

## MITRE ATT&CK T1041: Exfiltration Over C2 Channel

Source: [MITRE ATT&CK T1041: Exfiltration Over C2 Channel](https://attack.mitre.org/techniques/T1041/)

Related alerts: A05

Use: Background on stolen data leaving through a command-and-control channel; the transfer and destination assessment are fictional.

## AWS CloudTrail API Reference: StopLogging

Source: [AWS CloudTrail API Reference: StopLogging](https://docs.aws.amazon.com/awscloudtrail/latest/APIReference/API_StopLogging.html)

Related alerts: A06, A12

Use: StopLogging suspends recording and delivery for the specified trail; it does not inherently disable every trail or all AWS logging.

## Microsoft: Event 4625, An account failed to log on

Source: [Microsoft: Event 4625, An account failed to log on](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-10/security/threat-protection/auditing/event-4625)

Related alerts: A09

Use: Event meaning; the employee confirmation and surrounding telemetry are fictional context supporting the label.

## Microsoft Entra: Reporting options for password management

Source: [Microsoft Entra: Reporting options for password management](https://learn.microsoft.com/en-us/entra/identity/authentication/howto-sspr-reporting)

Related alerts: A10

Use: Self-service password reset activity can be reviewed in audit reports; the identity checks and user confirmation are fictional scenario context.

## EICAR: Anti Malware Testfile

Source: [EICAR: Anti Malware Testfile](https://www.eicar.org/download-anti-malware-testfile/)

Related alerts: A11

Use: Purpose of the EICAR test file and why an authorized detection can be routine.

## Code and learning resources

- Course materials: MiniProject_Agent_Starter.ipynb, langgraph_state_nodes.ipynb, and langgraph_branch_tools.ipynb.
- [LangGraph streaming documentation](https://docs.langchain.com/oss/python/langgraph/streaming): node-update streaming used in the execution trace.
- ChatGPT/Codex assistance: scenario drafting, Python code, debugging, explanations, and source discovery.
