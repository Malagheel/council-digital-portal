#  User Acceptance Testing (UAT) Test Plan

##  Project: Council Digital Services Portal

---

##  Objective
To validate that the Council Services Portal meets functional and non-functional requirements and is ready for use by residents and council staff.

---

##  Test Participants
| Role                    | Responsibility                    |
|-------------------------|------------------------------------|
| UAT Lead (Business Analyst) | Coordinate test cases and feedback |
| Resident Tester          | Simulate real-world resident use |
| Council Staff Tester     | Simulate back-office operations  |
| Developer (optional)     | Fix defects identified in UAT    |

---

##  UAT Test Cases

###  Test Case 1: Submit Service Request
| Field                 | Details                               |
|-----------------------|----------------------------------------|
| Test Case ID          | TC-001                                 |
| Scenario              | Submit a missed bin collection request |
| Input Data            | Request type: Waste, Address, Notes    |
| Expected Result       | Confirmation screen and request ID     |
| Status                |  Pass /  Fail                        |

---

###  Test Case 2: Track Request Status
| Test Case ID          | TC-002                           |
| Scenario              | Resident checks request progress |
| Input Data            | Request ID = 12345               |
| Expected Result       | Status is shown as "In Progress" |
| Status                |  Pass /  Fail                  |

---

###  Test Case 3: Make a Payment
| Test Case ID          | TC-003                        |
| Scenario              | Pay council fine via portal   |
| Input Data            | Card details, Amount = $200   |
| Expected Result       | Payment success message, email receipt |
| Status                |  Pass /  Fail              |

---

###  Test Case 4: View News & Events
| Test Case ID          | TC-004                              |
| Scenario              | Resident views council announcements |
| Expected Result       | List of news articles and dates     |
| Status                |  Pass /  Fail                    |

---

###  Test Case 5: Staff Resolves Request
| Test Case ID          | TC-005                        |
| Scenario              | Staff marks request as resolved |
| Expected Result       | Status updates to "Closed", resident notified |
| Status                |  Pass /  Fail              |

---

##  Acceptance Criteria
- 100% of critical test cases must pass
- Non-critical bugs logged and reviewed before go-live
- Stakeholders sign off post-testing

---

##  Notes
- Bugs will be tracked using GitHub Issues or JIRA
- Retesting required for failed cases

