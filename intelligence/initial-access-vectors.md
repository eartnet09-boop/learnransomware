# Initial Access Vectors

## Executive Focus

- Exposure of business services and credentials as pathways to operational disruption.
- Prioritization by exploitability, business criticality, and external reachability.
- Validation of access paths using internal telemetry and trusted intelligence.

## Priority Access Patterns

### Exposed VPN and Remote Access

- Unpatched or misconfigured gateways and edge services.
- Weak, reused, or compromised credentials.
- Gaps in authentication telemetry and device posture enforcement.
- Administrative access exposed beyond business need.

### Remote Monitoring and Management (RMM) Abuse

- Misuse of legitimate remote administration tools.
- Unauthorized tool installation or unexpected changes in usage patterns.
- Excessive privileges and insufficient separation of administrative identities.
- Detection based on anomalous behavior, not tool presence alone.

### Infostealer-Derived Credentials

- Stolen credentials, session tokens, and browser data entering criminal markets.
- Password reuse and weak credential revocation practices.
- Exposure of privileged and third-party identities.
- Credential rotation, session invalidation, and user-risk monitoring.

### AI-Assisted Phishing

- Highly tailored lures and impersonation of trusted business relationships.
- Increased scale and localization of social-engineering content.
- Abuse of email, collaboration, and identity workflows.
- Verification procedures for payment, access, and sensitive-data requests.

## Defensive Priorities

- Maintain an inventory of internet-facing assets, owners, and business criticality.
- Reduce unnecessary exposure and remediate unsupported or vulnerable edge devices.
- Enforce phishing-resistant authentication for privileged and high-risk access.
- Monitor identity, endpoint, email, and remote-access events as a correlated signal.
- Establish secure vendor access, time-bound privileges, and rapid revocation procedures.

## Intelligence Collection and Validation

- Record source, timestamp, confidence, and relevance for each threat claim.
- Distinguish observed indicators from inferred attribution and unverified reporting.
- Map validated behaviors to internal detection and response coverage.
- Reassess exposure after material changes to vendors, infrastructure, or threat activity.
