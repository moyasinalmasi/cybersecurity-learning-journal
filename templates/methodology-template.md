# [Vulnerability Name] Testing Methodology

## Overview

- **Category:** Client-side / Server-side / Access control / Authentication / Business logic
- **Current level:** Beginner / Intermediate / Advanced
- **Last updated:** YYYY-MM-DD
- **Labs completed:** 
- **Real-world practice hours:** 

## Vulnerability Summary

Explain the vulnerability in your own words:

- What is it?
- Why does it occur?
- What security assumption is broken?
- What could an attacker achieve?

## Required Knowledge

- 
- 
- 

## Important Terminology

| Term | Meaning |
|---|---|
|  |  |
|  |  |

## Potential Attack Surface

Identify application features that may be relevant:

- [ ] Authentication and registration
- [ ] User profile
- [ ] Search and filtering
- [ ] Forms and user input
- [ ] File uploads
- [ ] Comments or messaging
- [ ] Administrative functionality
- [ ] API endpoints
- [ ] Mobile API
- [ ] JavaScript files
- [ ] URL parameters
- [ ] HTTP headers
- [ ] Cookies and session data
- [ ] Other:

## Reconnaissance Questions

- Where does user-controlled input enter the application?
- Where is the input stored, processed, or displayed?
- Does behavior change between authenticated and unauthenticated users?
- Are multiple user roles available?
- Is the relevant functionality processed by the client or server?
- Which endpoints and parameters are related to this feature?
- Are there alternative HTTP methods or content types?
- Are there similar features on another subdomain or API version?

## Baseline Request

Before modifying anything:

- [ ] Capture the normal request.
- [ ] Save the normal response.
- [ ] Identify authentication and session requirements.
- [ ] Identify user-controlled values.
- [ ] Record the expected application behavior.

## Testing Workflow

### Phase 1 — Identify candidates

Describe how potentially vulnerable functionality is recognized.

- 
- 
- 

### Phase 2 — Build a hypothesis

```text
Observation:
Possible vulnerability:
Expected behavior:
Test:
Expected evidence:
```

### Phase 3 — Change one variable

- [ ] Modify only one relevant value at a time.
- [ ] Compare the response with the baseline.
- [ ] Record status code, response length, headers, and behavior.
- [ ] Repeat the test to confirm consistency.

### Phase 4 — Confirm safely

- [ ] Use the minimum proof required.
- [ ] Avoid accessing data belonging to real users.
- [ ] Use only personal test accounts where applicable.
- [ ] Stop if the test could affect availability or data integrity.
- [ ] Preserve sanitized evidence.

### Phase 5 — Evaluate impact

- What security boundary was crossed?
- What data or functionality could be affected?
- Is user interaction required?
- Which user roles are affected?
- Can the behavior be reproduced consistently?
- Does the program explicitly accept this vulnerability category?

## Method-Specific Test Cases

- [ ] 
- [ ] 
- [ ] 
- [ ] 
- [ ] 

## Bypass Ideas

Record conceptual variations only after understanding the normal behavior.

- Different input location:
- Different encoding:
- Different HTTP method:
- Different content type:
- Different user role:
- Different application state:
- Alternative endpoint:
- Alternative API version:

## Evidence to Preserve

- [ ] Original request
- [ ] Modified request
- [ ] Relevant response difference
- [ ] Screenshot if necessary
- [ ] Reproduction steps
- [ ] Impact explanation
- [ ] Environment and account roles
- [ ] Date and time
- [ ] Sensitive information removed

## Common False Positives

Document behaviors that may look vulnerable but do not demonstrate meaningful impact.

- 
- 
- 

## Common Mistakes

- 
- 
- 

## Reporting Checklist

- [ ] The affected asset is in scope.
- [ ] The behavior is reproducible.
- [ ] The report contains clear reproduction steps.
- [ ] The security impact is demonstrated.
- [ ] Unnecessary sensitive data is removed.
- [ ] The report does not exaggerate severity.
- [ ] Suggested remediation is included.
- [ ] Program-specific reporting requirements are followed.

## Labs and Practice

| Lab | Platform | Difficulty | Result | Main lesson |
|---|---|---|---|---|
|  |  |  |  |  |

## Real-World Practice Summary

Use anonymized names only.

| Program | Feature | Time | Result | Next step |
|---|---|---:|---|---|
| Program-A |  |  |  |  |

## Knowledge Gaps

- [ ] 
- [ ] 
- [ ] 

## Review History

| Date | Activity | Result |
|---|---|---|
|  | Initial study |  |
|  | Seven-day review |  |
|  | Thirty-day review |  |

## References

- PortSwigger Web Security Academy:
- OWASP:
- Additional reference:

## Ethical Testing Requirement

Use this methodology only in intentionally vulnerable labs or systems where explicit authorization has been granted. Always follow the program scope, rate limits, and testing restrictions.
