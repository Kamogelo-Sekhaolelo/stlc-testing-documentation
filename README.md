# STLC Testing Documentation

Manual QA work following the full **Software Testing Life Cycle (STLC)**, done during my QA learnership on public demo applications.

## 1. [parabank-stlc](parabank-stlc): ParaBank (online banking demo)

A complete STLC project from requirements to release decision:

| Phase | Document |
|---|---|
| 1. Requirement analysis | Discovery and requirements, **Requirements Traceability Matrix (RTM)** |
| 2. Test planning | Test plan with scope, approach, entry and exit criteria |
| 3. Test design | Test cases and coverage |
| 4. Environment and preparation | Quality preparation |
| 5. Execution and defects | Quality investigation and defect reports, with screenshot evidence |
| 6. Closure | **Go / No-Go release decision**, executive presentation |

The release was a **No-Go**: even with an 82% pass rate, one open **critical** defect (a loan approval logic error) broke the exit criteria. `Presentation_QA_Prep.md` explains the reasoning.

## 2. [orangehrm-stlc](orangehrm-stlc): OrangeHRM (HR system demo)

My own part of a team STLC project:

- Environment validation and **automation readiness** check
- **Master test data sheet** (valid, invalid and edge-case data)
- Phase 5 test execution work
- A sample Selenium automation script for the login module

## Skills shown

Test planning, test case design (positive, negative, data-driven, boundary), requirements traceability, defect reporting and severity, entry and exit criteria, release decisions.
