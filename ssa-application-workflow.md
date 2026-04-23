# SSA Application Workflow

## Metadata
- **Status:** Active
- **Priority:** P1
- **Work Type:** Application Workflow
- **Output Type:** Process Guide
- **Launch Critical:** Yes
- **Last Updated:** 2026-04-23
- **Related Files:** medical-documentation-checklist.md, work-history.md, symptom-function-summary.md, provider-list.md, master-deadline-and-contact-tracker.md, README.md

---

## Purpose
Create a step-by-step workflow for preparing and submitting an SSI and/or SSDI disability application and tracking what happens next.

---

## Definition of Done
- application path is identified: SSI, SSDI, or both
- required information is assembled
- application is submitted
- supporting forms are saved
- all notices and deadlines are logged
- follow-up actions are tracked

---

## Working Goal
Reduce avoidable delays by preparing the application as a document-driven workflow rather than a one-time form submission.

---

## Workflow Overview

### Phase 1: Determine Readiness
**Goal:** confirm whether enough information is available to begin.

#### Tasks
- review current ability to gather documents and answer questions
- create or confirm SSA account access if applying online
- identify whether the likely path is SSI, SSDI, or both
- verify that basic identity, treatment, and work history information can be assembled

#### Exit Criteria
- enough information exists to begin pre-application prep
- missing items are known and logged

---

### Phase 2: Gather Application Inputs
**Goal:** assemble the information needed before starting the application.

#### Required Information Categories
- legal name and identifying information
- contact information
- bank information if applicable
- work history
- education or training history if relevant
- provider list
- treatment dates
- medication list
- medical records already in hand
- onset timeline for when symptoms became work-limiting

#### Pre-Application Checklist
- [ ] ID information available
- [ ] mailing address confirmed
- [ ] provider list prepared
- [ ] medication list prepared
- [ ] work history drafted
- [ ] symptom/function summary drafted
- [ ] existing records stored in `/02-ssa` or linked from `/01-medical`

#### Exit Criteria
- all available supporting information is assembled
- missing items are listed and not hidden

---

### Phase 3: Draft Application Packet
**Goal:** prepare answers before entering them into the SSA system or presenting them in an appointment.

#### Packet Components
- application notes
- symptom/function summary
- provider list
- treatment dates
- medication list
- job history for relevant years
- questions to ask if applying by phone or in person

#### Internal Prep Questions
- when did symptoms begin to interfere with work?
- when did work become unsustainable?
- what treatment has been attempted?
- what are the most consistent limitations?
- what happens on a bad day?
- what happens on a typical day?

#### Exit Criteria
- answers are drafted in plain language
- packet is ready for submission session

---

### Phase 4: Submit Application
**Goal:** complete and submit the application.

#### Submission Paths
- online
- phone appointment
- in-person appointment

#### Submission Tasks
- complete application
- complete supporting disability report or similar forms
- review entries before submission
- submit application
- save or print confirmation
- save copies of completed answers if possible

#### Immediate Post-Submission Tasks
- write down submission date
- log confirmation number if provided
- create claim status entry in tracker
- store copies in `/02-ssa`

#### Exit Criteria
- application has been submitted
- confirmation is saved
- tracker has been updated

---

### Phase 5: Follow-Up and Case Maintenance
**Goal:** prevent missed requests and keep the case active and organized.

#### Tasks
- check mail regularly
- log all SSA notices
- respond to requests for additional information
- attend consultative exams if scheduled
- store every letter and notice
- document all calls with SSA
- update the tracker after each contact

#### Ongoing Watch Items
- deadlines on mailed notices
- exam scheduling
- additional records requests
- appeal deadlines if denied

#### Exit Criteria
- all notices are logged
- pending actions are visible and dated

---

## Application Materials Tracker

| Item | Status | Location | Notes |
|---|---|---|---|
| SSA account access |  |  |  |
| Provider list |  |  |  |
| Medication list |  |  |  |
| Work history |  |  |  |
| Symptom/function summary |  |  |  |
| Records packet |  |  |  |
| Application submitted |  |  |  |
| Confirmation saved |  |  |  |

---

## SSA Contact Log

| Date | Method | Contact / Office | Reason | Outcome | Next Step | Deadline |
|---|---|---|---|---|---|---|
|  |  |  |  |  |  |  |

---

## Common Risks
- starting the application before key details are organized
- inconsistent dates across forms
- forgetting providers or medication history
- missing mailed follow-up requests
- losing confirmation details
- becoming overwhelmed after submission and not tracking the case

---

## Mitigation
- draft answers before filing
- use one provider list and one timeline as source-of-truth documents
- save every form and notice immediately
- log every contact the same day
- use the master tracker for deadlines and next actions

---

## Minimal Folder Structure
```text
/02-ssa
  application-notes.md
  provider-list.md
  medication-list.md
  work-history.md
  symptom-function-summary.md
  confirmations
  notices
```

---

## Notes
Verify current eligibility, form requirements, and submission options directly with SSA before filing. This file is meant to support readiness and organization, not replace official instructions.
