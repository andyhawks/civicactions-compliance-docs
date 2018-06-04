# Incident response

See the [CivicActions Security Training](https://civicactions-handbook.readthedocs.io/en/latest/01-welcome-to-civicactions/training/security-training/) which covers:

* Awareness and Training (AT)
* Configuration Management (CM)
* Contingency Planning (CP)
* Incident Response (IR)
* Maintenance (MA)
* Media Protection (MP)
* Physical and Environmental Protection (PE)
* Personnel Security (PS)
* System and Information Integrity (SI)

## Purpose

Iteratively reduce both the number of incidents as a proportion of our total information system inventory, and reduce the mean time to recover from incidents.

## Scope

See the [CivicActions Common Control Policy](CivicActions-Common-Control-Policy.md).

## Policy overlay

For information on roles and responsibilities, management commitment, coordination among
organizational entities, compliance, reviews, and updates please see the
[CivicActions Common Control Policy](CivicActions-Common-Control-Policy.md).

## Procedures

The CivicActions Security Office organizes incident response training sessions, offered to the whole CivicActions team at least annually, and requires that all CivicActions Operations team members take the training. The training may be led by a Project Manager or a Security or Technology Operations team member.

The CivicActions team onboarding checklist (https://github.com/18F/cg-product/blob/master/OnboardingChecklist.md) requires that all team members take incident response training within 60 days of joining the team.

This training is a meeting reviewing and explaining the CivicActions IR Guide (https://docs.CivicActions/ops/security-ir/) and discussing questions and examples. The team takes notes on the training, stored in a Google Doc in the CivicActions team Google Drive folder. The team records attendance in that document.

If the CivicActions system changes in a radical way, the Program Manager adapts the incident response training to meet the needs of the new system. The Program Manager then requires Cloud Operations team members to take the training again.
The Program Manager requires all Cloud Operations team members to take the incident response training at least once a year.

See IR-2.

CivicActions implements processes to detect and analyze malicious activity within the system platforms. If these processes detect malicious activity, they report the activity to the Operations team.

CivicActions has an Incident Response Plan (https://civicactions-handbook.readthedocs.io/en/latest/09-security/incident-response-plan/) that documents the procedures that staff should take in the case of an incident.

See IR-4, IR-5, IR-6.

The Technology Operations team implements automated processes such as ClamAV and AIDE to detect anomalies. When these processes detect an anomaly, they escalate an alert to Security Operations team members, often automatically via Slack and/or OpsGenie.

CivicActions' systems automatically store logs so that Technology Operations can access relevant information when investigating a potential incident.

See IR-4 (1), IR-6 (1).

As described in the CivicActions security incident response guide and contingency plan, technology Operations will notify customers about incidents and potential incidents.

See IR-7.

The CivicActions team has developed an Incident Response Guide (https://civicactions-handbook.readthedocs.io/en/latest/09-security/incident-response-plan/) to implement incident response capabilities.

The Incident Response Guide is continually reviewed and updated by the CivicActions team. In addition, the CivicActions team updates the IR Guide after it tests the guide, which happens at least annually and after any major system/organizational changes.

The CivicActions team distributes changes to the Incident Response Guide to the whole CivicActions team.

See IR-8.

The CivicActions Incident Response directs CivicActions team members to watch out for and immediately report any potential security incident, which includes reporting suspected information spills (such as sensitive or classified information in the wrong places). In the event of a suspected information spill, CivicActions team members follow the reporting process in the CivicActions Incident Response Guide.

The System Owner, Program Manager, and CivicActions Information Security and Technology team members have primary responsibility for implementing the actual response to security incidents, including technical measures.

See IR-9.
