# GitHub Implementation Checklist

## Purpose

This checklist guides the setup of a GitHub repository for mapping the current-state SOPs of two CX functions:

1. Customer Data and Systems Support
2. Customer Focus Information Support

The purpose of the repository is to document how work is actually performed today, identify pain points and exceptions, and create a structured evidence base for future omnichannel service design, information reuse and operating model development.

---

## Phase 1: Repository setup

### 1. Create repository

* [ ] Create a new repository called `cx-current-state-sop-mapping`

* [ ] Set repository visibility according to current organisational requirements

* [ ] Add a short repository description:

  `Current-state SOP mapping for CX data, systems and information support functions.`

* [ ] Do not upload customer data, personal information, credentials, restricted operational material or sensitive examples

### 2. Add initial folder structure

* [ ] Create `00-project-control/`
* [ ] Create `01-customer-data-and-systems-support/`
* [ ] Create `02-customer-focus-information-support/`
* [ ] Create `03-cross-function-learning/`
* [ ] Create `04-templates/`
* [ ] Create `05-decisions/`

### 3. Add starter files

* [ ] Add `README.md`
* [ ] Add `00-project-control/purpose-and-scope.md`
* [ ] Add `00-project-control/working-principles.md`
* [ ] Add `00-project-control/co-design-session-guide.md`
* [ ] Add `00-project-control/role-intent-vs-actual-practice.md`
* [ ] Add `00-project-control/assumptions-log.md`
* [ ] Add `00-project-control/glossary.md`

---

## Phase 2: Establish mapping principles

### 4. Confirm current-state mapping rule

* [ ] Document that the repository maps actual current practice, not aspirational role descriptions
* [ ] Confirm that position descriptions are used as reference material only
* [ ] Capture any role responsibilities that exist in a PD but are not performed in practice as role-gap notes
* [ ] Avoid creating SOPs for work that is not currently performed

### 5. Add decision records

Create the following files in `05-decisions/`:

* [ ] `ADR-001-map-actual-practice-not-aspirational-pd.md`
* [ ] `ADR-002-keep-functions-separated-during-current-state-discovery.md`
* [ ] `ADR-003-use-github-for-sop-discovery.md`
* [ ] `ADR-004-design-for-future-enterprise-migration.md`

### 6. Confirm separation of functions

* [ ] Keep Customer Data and Systems Support separate from Customer Focus Information Support
* [ ] Do not merge workflows during current-state discovery
* [ ] Capture overlaps only in `03-cross-function-learning/`
* [ ] Review shared patterns after both functions have been mapped

---

## Phase 3: Create function folders

### 7. Customer Data and Systems Support

Create the following files in `01-customer-data-and-systems-support/`:

* [ ] `README.md`
* [ ] `role-context.md`
* [ ] `actual-practice-summary.md`
* [ ] `pd-intent-vs-current-reality.md`
* [ ] `sop-inventory.md`
* [ ] `current-state-process-map.md`
* [ ] `work-types.md`
* [ ] `systems-and-tools.md`
* [ ] `decision-points.md`
* [ ] `exception-pathways.md`
* [ ] `data-quality-controls.md`
* [ ] `pain-points-and-risks.md`
* [ ] `omnichannel-implications.md`

Create the SOP folder:

* [ ] `01-customer-data-and-systems-support/sops/`

Add starter SOP files:

* [ ] `CDSS-SOP-001-identify-duplicate-customer-records.md`
* [ ] `CDSS-SOP-002-cleanse-and-simplify-customer-records.md`
* [ ] `CDSS-SOP-003-manually-deduplicate-customer-records.md`
* [ ] `CDSS-SOP-004-monitor-customer-record-quality.md`
* [ ] `CDSS-SOP-005-correct-customer-data-quality-issues.md`
* [ ] `CDSS-SOP-006-record-progress-of-data-cleansing-work.md`
* [ ] `CDSS-SOP-007-escalate-data-quality-or-system-issues.md`
* [ ] `CDSS-SOP-008-support-basic-crm-data-maintenance-requests.md`

### 8. Customer Focus Information Support

Create the following files in `02-customer-focus-information-support/`:

* [ ] `README.md`
* [ ] `role-context.md`
* [ ] `actual-practice-summary.md`
* [ ] `sop-inventory.md`
* [ ] `current-state-process-map.md`
* [ ] `knowledge-and-work-types.md`
* [ ] `systems-and-tools.md`
* [ ] `decision-points.md`
* [ ] `exception-pathways.md`
* [ ] `content-quality-controls.md`
* [ ] `pain-points-and-risks.md`
* [ ] `omnichannel-implications.md`

Create the SOP folder:

* [ ] `02-customer-focus-information-support/sops/`

Add starter SOP files:

* [ ] `CFIS-SOP-001-update-service-directory-content.md`
* [ ] `CFIS-SOP-002-maintain-customer-service-tools.md`
* [ ] `CFIS-SOP-003-support-crm-user-issues-and-requests.md`
* [ ] `CFIS-SOP-004-maintain-telephone-messages-on-hold.md`
* [ ] `CFIS-SOP-005-coordinate-hot-topic-customer-responses.md`
* [ ] `CFIS-SOP-006-communicate-urgent-updates-to-branch-staff.md`
* [ ] `CFIS-SOP-007-support-service-directory-editors.md`
* [ ] `CFIS-SOP-008-improve-first-contact-resolution-content.md`

---

## Phase 4: Add reusable templates

Create the following files in `04-templates/`:

* [ ] `sop-discovery-template.md`
* [ ] `current-state-sop-template.md`
* [ ] `interview-guide-template.md`
* [ ] `process-observation-template.md`
* [ ] `decision-table-template.md`
* [ ] `exception-log-template.md`
* [ ] `pain-point-log-template.md`
* [ ] `omnichannel-implication-template.md`

---

## Phase 5: Co-design preparation

### 9. Prepare officer mapping sessions

* [ ] Schedule one mapping session with the Customer Data and Systems Support officer
* [ ] Schedule one mapping session with the Customer Focus Information Support officer
* [ ] Use the same discovery structure for both sessions
* [ ] Begin each session by asking what work actually lands on the officer’s desk in a normal week
* [ ] Do not start with the PD accountabilities
* [ ] Use the PD only as a reference check after actual work has been mapped

### 10. Use a consistent mapping structure

For each function, capture:

* [ ] Work types
* [ ] Triggers
* [ ] Inputs
* [ ] Systems and tools
* [ ] Process steps
* [ ] Decision points
* [ ] Handoffs
* [ ] Exceptions
* [ ] Workarounds
* [ ] Controls
* [ ] Pain points
* [ ] Risks
* [ ] Improvement opportunities
* [ ] Omnichannel implications

---

## Phase 6: Map Customer Data and Systems Support

### 11. Confirm actual work types

* [ ] Identify recurring weekly work
* [ ] Identify ad hoc requests
* [ ] Identify system or data maintenance activities
* [ ] Identify customer record quality activities
* [ ] Identify work that exists in the PD but is not performed in practice
* [ ] Add non-performed PD responsibilities to `pd-intent-vs-current-reality.md`

### 12. Draft first SOPs

Prioritise SOPs that are real, recurring and operationally important:

* [ ] Identify duplicate customer records
* [ ] Cleanse and simplify customer records
* [ ] Manually de-duplicate customer records
* [ ] Monitor customer record quality
* [ ] Correct customer data quality issues
* [ ] Escalate data quality or system issues

### 13. Capture future signals

* [ ] Note what customer data issues affect channel continuity
* [ ] Note what customer identity or account context issues create rework
* [ ] Note what data quality issues could block automation
* [ ] Note what system constraints affect staff or customers

---

## Phase 7: Map Customer Focus Information Support

### 14. Confirm actual work types

* [ ] Identify recurring content and information maintenance work
* [ ] Identify urgent information update work
* [ ] Identify CRM or user support work
* [ ] Identify Service Directory editor support work
* [ ] Identify customer service tool update work
* [ ] Identify work that is informal, undocumented or dependent on individual knowledge

### 15. Draft first SOPs

Prioritise SOPs that are real, recurring and operationally important:

* [ ] Update Service Directory content
* [ ] Maintain customer service tools
* [ ] Support CRM user issues and requests
* [ ] Maintain telephone messages on hold
* [ ] Coordinate hot topic customer responses
* [ ] Communicate urgent updates to branch staff
* [ ] Support Service Directory editors

### 16. Capture future signals

* [ ] Note what information is duplicated across systems
* [ ] Note what information lacks clear ownership
* [ ] Note what knowledge could be reused across channels
* [ ] Note what information quality issues affect first contact resolution
* [ ] Note what knowledge gaps could block automation or self-service

---

## Phase 8: Compare without merging

### 17. Populate cross-function learning folder

Create or update:

* [ ] `03-cross-function-learning/common-patterns.md`
* [ ] `03-cross-function-learning/shared-systems.md`
* [ ] `03-cross-function-learning/shared-governance-gaps.md`
* [ ] `03-cross-function-learning/shared-data-and-knowledge-dependencies.md`
* [ ] `03-cross-function-learning/role-gap-and-capability-signals.md`
* [ ] `03-cross-function-learning/automation-candidates.md`
* [ ] `03-cross-function-learning/future-operating-model-signals.md`

### 18. Look for patterns

Capture shared patterns across both functions:

* [ ] Shared systems
* [ ] Shared handoffs
* [ ] Shared unclear ownership
* [ ] Shared manual workarounds
* [ ] Shared quality risks
* [ ] Shared dependency on individual knowledge
* [ ] Shared automation opportunities
* [ ] Shared omnichannel readiness gaps

---

## Phase 9: GitHub working practices

### 19. Use simple version control

* [ ] Use clear commit messages
* [ ] Commit small logical changes
* [ ] Avoid large mixed-purpose commits
* [ ] Keep draft files marked as draft
* [ ] Use version numbers inside SOP files

Example commit messages:

* `Add initial repo structure`
* `Add current-state mapping principles`
* `Add Customer Data and Systems Support SOP inventory`
* `Draft CFIS Service Directory update SOP`
* `Add role intent vs actual practice note`

### 20. Use issues for open questions

Create GitHub issues for:

* [ ] Missing process information
* [ ] Unclear ownership
* [ ] Policy or approval questions
* [ ] System constraints
* [ ] Data quality risks
* [ ] Content governance gaps
* [ ] Automation candidates
* [ ] Enterprise migration questions

### 21. Use labels

Suggested labels:

* [ ] `current-state`
* [ ] `sop`
* [ ] `data-quality`
* [ ] `service-knowledge`
* [ ] `systems`
* [ ] `decision-point`
* [ ] `exception`
* [ ] `pain-point`
* [ ] `risk`
* [ ] `omnichannel`
* [ ] `automation-candidate`
* [ ] `role-gap`
* [ ] `enterprise-migration`

---

## Phase 10: Enterprise migration readiness

### 22. Keep the prototype enterprise-safe

* [ ] Do not include customer records
* [ ] Do not include screenshots with personal information
* [ ] Do not include system credentials
* [ ] Do not include restricted operational material
* [ ] Do not include confidential staff information
* [ ] Use fictional or anonymised examples only

### 23. Prepare for future migration

Create `05-decisions/ADR-004-design-for-future-enterprise-migration.md` and capture:

* [ ] Potential enterprise owner
* [ ] Repository access model
* [ ] Review and approval process
* [ ] Information classification requirements
* [ ] Records management considerations
* [ ] Long-term source of truth
* [ ] Integration with CRM, Service Directory, intranet, web, chatbot or reporting platforms

---

## Definition of done for V0.1

The V0.1 repository is complete when:

* [ ] Repository structure is created
* [ ] README is added
* [ ] Mapping principles are documented
* [ ] Both functions have separate folders
* [ ] Each function has a draft SOP inventory
* [ ] At least two current-state SOPs are drafted for each function
* [ ] Role intent vs actual practice is documented
* [ ] Cross-function learning folder is created
* [ ] Key shared patterns are captured
* [ ] Enterprise migration considerations are documented
* [ ] No sensitive customer or operational data is stored in the repository

---

## Definition of done for V1

The V1 repository is complete when:

* [ ] Each function has a validated SOP inventory
* [ ] Priority SOPs have been mapped with the officers who perform the work
* [ ] Decision points and exceptions are documented
* [ ] Pain points and risks are documented
* [ ] Omnichannel implications are captured
* [ ] Role gaps are identified
* [ ] Automation candidates are listed
* [ ] Shared governance gaps are visible
* [ ] Future operating model signals are synthesised
* [ ] The repository can support a business case for a more mature CX operating capability
