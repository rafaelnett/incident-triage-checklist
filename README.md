# Motivation

```
Are we currently experiencing an incident?
```

Questions like these are sometimes difficult to answer. Nonetheless,
when asked, the urgency of an accurate and timely answer
is typically pretty high.

This checklist is designed based on the [InfoSec CIA triad](https://en.wikipedia.org/wiki/Information_security#Key_concepts).

## Confidentiality

 - [ ] Are authn/authz systems functioning as intended?
 - [ ] Is there evidence of improper information disclosure?
 - [ ] Are all physical devices (laptops, phones) accounted for?
 - [ ] Is there evidence of unauthorized access to data or systems?

## Integrity

 - [ ] Is there evidence of unauthorized data modification?
 - [ ] Is there evidence of data being inaccurate due to systemic error?
 - [ ] Is there evidence of data corruption?
 - [ ] Do logs exists for the relevant systems?
 - [ ] Have the logs been reviewed?

## Availability

 - [ ] Are systems available?
 - [ ] Are systems designed for resiliency and fault tolerance?
 - [ ] Is there a defined method/process for mitigating DOS?
 - [ ] Are backups maintained and usable?
 - [ ] Are backups stored in a logically separate environment?
 - [ ] Does adequate monitoring and alerting exist?
