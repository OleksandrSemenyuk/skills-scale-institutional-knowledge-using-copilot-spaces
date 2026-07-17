# Process templates & checklists

This file collects practical templates and checklists to reduce friction and ensure consistent execution. Copy these into project READMEs or daily workflows as needed.

## Risk Register (table)
| ID | Description | Impact | Likelihood | Owner | Mitigation | Status |
|----|-------------|--------|------------|-------|------------|--------|
| R-001 | Short description | High/Med/Low | High/Med/Low | @owner | Steps to reduce impact | Open/Closed |

## PR Checklist (to include in PR template)
- [ ] Ticket/issue linked
- [ ] Acceptance criteria included in PR description
- [ ] Tests added / updated
- [ ] Linting passed
- [ ] CI green
- [ ] Small scope and clear change list
- [ ] At least one approval (per repo policy)

## Release Checklist (pre-deploy)
- [ ] Acceptance criteria for all items met
- [ ] All PRs merged and CI green
- [ ] Security scans completed
- [ ] Release notes drafted
- [ ] Rollback plan documented
- [ ] Stakeholders notified

## Smoke test quick list (post-deploy)
- [ ] Core user login succeeds
- [ ] Key API endpoints respond within expected latency
- [ ] Basic end-to-end happy path succeeds
- [ ] No critical errors in logs

## Incident communication template
- Summary:
- Time discovered:
- Impact:
- Immediate actions taken:
- Next steps / owner:
- Post-incident retrospective planned (date):

## Where to add these
- Copy the items you need into project-specific docs in docs/ or project README for discoverability.
