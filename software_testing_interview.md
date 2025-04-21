
# Software Testing Interview Questions and Answers

## 1. Explain the defect life cycle
The **Defect Life Cycle** (also called Bug Life Cycle) defines the various states a defect goes through from identification to closure:
- **New**: Defect is logged and awaits review.
- **Assigned**: Assigned to a developer for fixing.
- **Open**: Developer starts analyzing and working on the defect.
- **Fixed**: Developer resolves the issue and marks it fixed.
- **Retest**: QA retests the issue.
- **Verified**: QA confirms the fix.
- **Closed**: Defect is closed after successful verification.
- **Reopen**: If the issue persists, it’s reopened.
- **Rejected/Not a Bug/Duplicate**: Bug is invalid, already logged, or not reproducible.

## 2. What is alpha testing?
**Alpha Testing** is a type of acceptance testing performed **in-house by the QA team** before releasing the software to external users or beta testers.

## 3. Can automation testing replace manual testing?
**No**, automation testing **cannot completely replace manual testing**. Manual testing is essential for exploratory, usability, and ad-hoc testing, where human intuition plays a role.

## 4. What is a test plan?
A **Test Plan** outlines the strategy, scope, objectives, resources, schedule, and deliverables of the testing process.

## 5. What is boundary value analysis?
**Boundary Value Analysis (BVA)** is a black-box testing technique where tests are created based on boundary values rather than all possible inputs.

## 6. What is manual testing?
**Manual Testing** involves executing test cases **without automation tools**, where testers manually check software for defects.

## 7. What is software testing?
**Software Testing** is the process of evaluating software to detect differences between existing and required conditions (i.e., bugs).

## 8. What is test harness?
A **Test Harness** is a collection of software and test data configured to test a program under different conditions and monitor outputs.

## 9. Describe functional testing
**Functional Testing** is a black-box testing type that validates the software against the functional requirements/specifications.

## 10. What is test coverage?
**Test Coverage** measures the amount of testing performed by tests and how much of the code is covered.

## 11. Differentiate between Positive and Negative Testing
| Aspect              | Positive Testing                      | Negative Testing                     |
|---------------------|----------------------------------------|--------------------------------------|
| Purpose             | Ensure the app works as expected       | Ensure app handles invalid input     |
| Input Type          | Valid input                            | Invalid/malformed input              |
| Outcome             | System functions normally              | System handles errors gracefully     |

## 12. Explain equivalence class partitioning
**Equivalence Class Partitioning** divides input data into partitions of valid and invalid values. Only one value from each class is tested.

## 13. Explain monkey testing and performance testing
- **Monkey Testing**: Random input testing to see if the system crashes.
- **Performance Testing**: Measures the system's behavior under load. Includes load, stress, and spike testing.

## 14. Explain what SDLC is
**SDLC (Software Development Life Cycle)** is a structured approach to software development, including requirement analysis, design, development, testing, deployment, and maintenance.

## 15. What is a stub?
A **Stub** is a dummy module used in **top-down integration testing** to simulate the behavior of actual modules.

## 16. What is a test case?
A **Test Case** contains:
- Test Case ID
- Preconditions
- Test steps
- Expected result
- Actual result
- Status (Pass/Fail)

## 17. What is a test scenario?
A **Test Scenario** is a high-level description of what to test. It may have multiple test cases associated with it.

## 18. What is API testing?
**API Testing** tests the interfaces (APIs) to ensure correct functionality, reliability, performance, and security.

## 19. What is defect triage?
**Defect Triage** involves prioritizing defects, assigning severity, and determining the timeline for fixes.

## 20. What is exploratory testing?
**Exploratory Testing** is unscripted testing where testers explore the application and design test cases on the fly.

## 21. What is regression testing?
**Regression Testing** ensures that new code changes do not adversely affect existing functionalities.

## 22. What is test closure?
**Test Closure** includes wrapping up testing activities, reporting results, closing defects, and documenting lessons learned.

## 23. What is test data?
**Test Data** is the input data used to execute test cases. It includes valid, invalid, boundary, and backend data.

## 24. Why is software testing required?
Software testing ensures:
- Quality assurance
- Bug detection
- Customer satisfaction
- Better performance
- Compliance with requirements

## 25. What is Adhoc Testing?
**Adhoc Testing** is an informal and unstructured type of testing performed without any planning or documentation. Testers aim to find defects by randomly checking functionality, often using their experience and intuition. It’s useful in the early stages or when time is limited.

## 26. What is Black Box Testing?
**Black Box Testing** is a software testing method where the internal structure/design/code is not known to the tester. Testing is based solely on requirements and functionality. It focuses on:
- Input/output validation
- Functional testing
- Boundary value analysis
- Equivalence partitioning

## 27. What is White Box Testing?
**White Box Testing** involves testing the internal logic and structure of the code. The tester needs knowledge of the code and works closely with developers. Common techniques:
- Unit testing
- Code coverage analysis
- Path testing
- Loop testing

## 28. What is Regression Testing?
**Regression Testing** ensures that new code changes have not adversely affected the existing functionality. It is performed after:
- Bug fixes
- Enhancements
- Configuration changes
It helps maintain software stability.

## 29. What is Functional Testing?
**Functional Testing** verifies that the software performs according to specified functional requirements. It includes:
- Unit testing
- Integration testing
- System testing
- Acceptance testing

## 30. What is Non-Functional Testing?
**Non-Functional Testing** checks aspects not related to specific behaviors or functions, such as:
- Performance
- Usability
- Reliability
- Scalability
- Security
It ensures the software's quality attributes are met.

## 31. What is Monkey Testing?
**Monkey Testing** is a type of random testing where testers (or automated tools) input random data to check system behavior. It aims to crash the system and expose unexpected failures. It is useful for:
- Stress testing
- Stability checks

## 32. What is Gorilla Testing?
**Gorilla Testing** is an intense testing technique where one module or functionality is tested thoroughly and repeatedly with varied inputs to ensure robustness. It is a type of manual testing done to break the application through brute force testing.


