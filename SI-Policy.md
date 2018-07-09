# System and Information Integrity Policy

CivicActions has a goal to ensure information integrity throughout its offerings. Services
to support this effort are available by contract and may be required by regulation or
law. When possible, support for this effort may cover one or more controls within these
families:

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

Ensures information systems have not been compromised through system errors, malicious
attacks, or unauthorized access during operation and transmission.

## Scope

See the [CivicActions Common Control Policy](CivicActions-Common-Control-Policy.md).

## Policy overlay

For information on roles and responsibilities, management commitment, coordination among
organizational entities, compliance, reviews, and updates please see the
[CivicActions Common Control Policy](CivicActions-Common-Control-Policy.md).

## Procedures

The CivicActions team identifies system flaws, tracks and reports them, and corrects them.

The CivicActions Operations team monitors upstream projects for new releases, implements
the new releases (including promptly installing newly-released security-relevant patches),
and tests patches for effectiveness and potential side effects on information systems
before installation. The testing takes place in development and test environments.

Flaws discovered during security assessments, continuous monitoring, incident response
activities, and information system error handling are addressed through the CivicActions
configuration management process.

See SI-2.

CivicActions employs tools at information system entry and exit points to detect and
eradicate malicious code with real-time scans. The CivicActions Operations team follows
the [Security Incident Response
Guide](https://github.com/NuCivic/healthdata/wiki/incident-response-plan) upon detection
of any potential security incident.

CivicActions-developed open source code that is used in the CivicActions products and
services is scanned using static analysis tools. When anyone proposes a change to the code
(a pull request), the static analysis tool automatically runs and displays results.

See SI-3.
