# Operation Gray Harbor v5: Executive Report Rubric

## Scenario-specific required conclusions

The campaign begins with session/OAuth compromise of `l.price`. `Calendar Hub Service` receives `Files.Read.All`, `Mail.Read`, and `offline_access` from `45.83.64.201`, after which the actor downloads BlueRidge partner terms and accesses mailbox/board material.

In the engineering track, `n.kade` is compromised on the macOS endpoint. The actor creates a deploy key from `203.0.113.211`, pushes `refs/heads/reconcile-hotfix`, and removes the key. `j.ortiz` approves the workflow believing it is an operational backlog fix. GitHub Actions obtains OIDC credentials for `gha-partner-role`; AWS/EKS activity decrypts the Box integration token, creates/uses the bundle exporter, stages `blueridge_recon_bundle_2026-03-25.tgz`, and uploads it to Box. External download from `45.83.64.201` links this delivery to the identity/SaaS actor and confirms receipt.

The approved reconciliation workflow explains why Box export and bundle compression are not inherently malicious; the malicious conclusion comes from the unauthorized ref, role path, credential use, and linked external download. The DS-JUP-05 XMRig incident associated with contractor activity is real but separate. `office-calendar-check.lab` and `runner-health.mesh.invalid` are old exercise residue. Signing parameters were reachable, but the KMS summary shows no observed Sign operation.

Containment must revoke `l.price` sessions and OAuth consent, rotate `n.kade` and GitHub credentials, remove malicious refs/keys, constrain GitHub OIDC, rotate Box/SSM secrets, isolate the exporter/EKS workload, disable the shared link, preserve the contractor miner as a separate case, and validate that no regulated partner data beyond the named bundle was received.

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
