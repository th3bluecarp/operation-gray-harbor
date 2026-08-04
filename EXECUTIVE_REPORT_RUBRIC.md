# Operation Gray Harbor v5: Executive Report Rubric

## Scenario-specific required conclusions

Correlate identity, SaaS, source-control, endpoint, and network records before assigning one actor. Confirmed findings are only events with both an authenticated principal and matching endpoint/network evidence. Contractor/archive workflow activity and the prior purple-team residue are false signals unless independently corroborated. Preserve timezone normalization and report unresolved links explicitly.

## Scoring

- 30% accurate, normalized timeline with artifact citations
- 25% complete entry, pivot, persistence, privilege, and impact analysis
- 20% correct clustering of related, unrelated, benign, and false-signal activity
- 15% disciplined confidence labels and treatment of telemetry gaps
- 10% executive-quality remediation, ownership, and sequencing

## Automatic deductions

- Unsupported attribution or invented observables
- Collapsing every suspicious event into a single incident
- Treating attempted access as successful access
- Treating access as exfiltration without transfer or receipt evidence
- Treating missing logs as proof that activity did not occur
- Omitting material contradictory or benign evidence

Every high-impact conclusion should cite two independent artifacts where available and preserve exact identities, hosts, IP addresses, object names, and timestamps.
