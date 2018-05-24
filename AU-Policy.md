# Audit and accountability management policy

CivicActions develops, documents, and disseminates to all CivicActions staff the Audit and
Accountability Policy which addresses purpose, scope, roles, responsibilities, management
commitment, coordination among organizational entities, compliance, and procedures to
facilitate the implementation of the audit and accountability policy and associated audit
controls.  The CivicActions Audit and Accountability Policy is maintained in the
CivicActions compliance-docs Github repository is accessible to all CivicActions staff.

The CivicActions Audit and Accountability Policy covers:

* Access Control (AC)
* Audit and Accountability (AU)
* Identification and Authentication (IA)
* System and Communications Protection (SC)

## Purpose

Ensure all actions taken on the information system are transparent, valid, and prevent repudiation. 

## Scope

See the [CivicActions Common Control Policy](CivicActions-Common-Control-Policy.md).

## Policy overlay

For information on roles and responsibilities, management commitment, coordination among
organizational entities, compliance, reviews, and updates please see the
[CivicActions Common Control Policy](CivicActions-Common-Control-Policy.md).

In addition, the CivicActions Information Security will coordinate with CivicActions
client services as needed.

## Procedures

The procedures for auditing CivicActions and client services systems are specific to the
technology stack and as such are described - when needed - in client-specific
documentation.

Audit logs will be made available to client organizations and for mutual support in
response to security breaches, system and user access and incident reporting.

Client services and application system owners are responsible for making sure audit events
are captured based on AU-2(d) parameter requirements for their web applications.

See AU-2.

CivicActions Information Security updates the defined auditable events when changes in the
threat environment occur or are identified by risk assessment.

See AU-2(3).

The events monitored generally include but are not limited to successful and unsuccessful account logon events, account management events, policy change, privileged functions, and system events. These events are tracked for all administrator activity, authentication checks, authorization checks, and permission changes.

See AU-3.

The log management framework provides the capability to retain logs for 180 days online, with sufficient capacity as to mitigate the risk of exceeding storage space. In the event the threshold is exceeded, administrators can add additional storage capacity without impacting the system.

See AU-4.

CivicActions has the ability to implement alerting to notify of insufficient audit storage capacity or if no new logs have been written a logging facility within a defined time frame.

See AU-5.

Security vulnerabilities and system inconsistencies are reviewed by the CivicActions Operations team (notified by email, text message and voice phone call). Security vulnerabilities which are not classified as high are reviewed weekly and resolved by CivicActions Operations.

The CivicActions Operations team acts on findings that result from its regular audit process according to its [incident response guidelines](https://github.com/CivicActions/devops/blob/master/docs/incident-response-plan.md) including notifying CivicActions Information Security, the System Owner, and the ISSO.

See AU-6.

CivicActions pulls from multiple NTP sources including http://tf.nist.gov/tf-cgi/servers.cgi to generate timestamps for audit records. These timestamps can be mapped to Coordinated Universal Time (UTC) or Greenwich Mean Time (GMT).

See AU-8.

To maintain the integrity of log data, CivicActions manages access around the generation and storage of audit log files. The ability to view or modify log data is restricted to CivicActions Operations authorized users.

See AU-9.

Audit logs are retained to provide support for after-the-fact investigations of security incidents and to meet regulatory and organizational information retention requirements. Our logging systems referenced above retain logs for 180 days online, and for an additional year in an offline system.

See AU-11.

CivicActions provides audit record generation capability.

CivicActions Operations is responsible for maintaining the configuration that enforces the audit settings. 
CivicActions Operations team members select which auditable events are to be audited per system and client requirements.

See AU-12.
