# Motivation

```
Are we currently experiencing an incident?
```

Questions like these are sometimes difficult to answer. Nonetheless,
when asked, the urgency of an accurate and timely answer
is typically pretty high.

This checklist is designed based on the [InfoSec CIA triad](https://en.wikipedia.org/wiki/Information_security#Key_concepts).

An affirmative check below indicates there's a strong possibility an incident is occurring.

## Confidentiality

 - [ ] Is there evidence of compromise in authn/authz system integrity?
 - [ ] Are any physical devices (laptops, phones) missing?
 - [ ] Is there evidence of unauthorized access to data or systems?
 - [ ] Is there evidence of unintended disclosure of private information (regardless of access)?

## Integrity

 - [ ] Is there evidence of unauthorized data modification?
 - [ ] Is there evidence of data being inaccurate due to systemic error?
 - [ ] Is there evidence of data corruption?
 - [ ] Are logs missing?
 - [ ] Do the logs indicate an anomaly?

## Availability

 - [ ] Is system availability in question?
 - [ ] Is system performance degraded to a point of unacceptable usability loss?
 - [ ] Is there evidence of DOS or other inappropriate access requests?
 - [ ] Were backups affected?
 - [ ] Did monitoring and alerting identify an issue?
 - [ ] Was monitoring and alerting inadequate in identifying an availability issue?
