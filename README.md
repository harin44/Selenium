# Interview Cheat Sheet

## MANUAL TESTER / QA – FULL INTERVIEW QUESTION & ANSWER GUIDE

## SECTION 1: INTRODUCTION AND GENERAL QA

1. Introduce yourself in a professional QA context.
   Answer: Provide a concise summary of your experience, domains worked on, testing types performed, tools used, and strengths (attention to detail, analytical thinking, defect reporting quality).

2. What do you know about our company and how do we ensure product quality?
   Answer: Explain your research about the company’s products, customers, tech stack, and highlight how companies maintain quality using QA processes, automation, CI/CD, code reviews, and continuous testing.

3. What interests you most about working in quality assurance?
   Answer: Focus on improving software reliability, preventing defects, understanding user behavior, and contributing to product excellence.

4. What types of applications or systems have you tested in your previous roles?
   Answer: Mention web applications, mobile apps, backend APIs, banking systems, ERPs, POS, e-commerce, healthcare modules, etc.

5. Do you have previous experience working as a QA engineer? What has been your greatest achievement so far?
   Answer: Highlight a significant contribution such as reducing defects in production, improving test coverage, or implementing test processes.

---

## SECTION 2: TESTING BASICS

6. What is software testing and why is it essential?
   Answer: Testing is the process of evaluating software to detect defects and ensure it meets requirements. It is essential to ensure product reliability, performance, security, and user satisfaction.

7. Name the main testing levels and their purpose.
   Answer:

* Unit Testing: Validates individual components.
* Integration Testing: Validates combined modules.
* System Testing: Validates the complete application.
* Acceptance Testing: Validates readiness for release.

8. Difference between functional and non-functional testing.
   Answer:

* Functional Testing checks features, behavior, and requirements.
* Non-Functional Testing checks performance, security, usability, scalability.

9. How is verification different from validation?
   Answer:

* Verification: Are we building the product right? (Static checks)
* Validation: Are we building the right product? (Dynamic testing)

10. Explain the Software Testing Life Cycle (STLC).
    Answer: Requirement analysis, test planning, test design, test environment setup, test execution, defect reporting, test closure.

11. Test Case vs Test Scenario.
    Answer:

* Test Scenario: High-level functionality to be tested.
* Test Case: Detailed steps, inputs, and expected results.

12. What is regression testing and when do we perform it?
    Answer: Testing existing functionality after changes to ensure nothing is broken. Performed after builds, patches, enhancements.

13. Define smoke testing and sanity testing.
    Answer:

* Smoke Testing: Initial check to ensure build stability.
* Sanity Testing: Focused testing to verify a specific area after a minor fix.

14. What is exploratory testing and when do you use it?
    Answer: Unscripted testing based on tester intuition. Used when requirements are unclear or time is limited.

---

## SECTION 3: TEST DESIGN AND EXECUTION

15. How do you structure an effective test case?
    Answer: Clear title, preconditions, test steps, expected result, actual result, environment, severity, priority.

16. Key components of a test case document.
    Answer: Test ID, module, description, prerequisites, test data, steps, expected result, actual result, status, comments.

17. What is a use case and how do you verify it?
    Answer: Describes user interactions with the system. Verified by checking all user flows and alternate paths.

18. How do you ensure maximum test coverage?
    Answer: Use RTM, boundary value analysis, equivalence partitioning, requirement mapping, and scenario-based testing.

19. How do you decide which test cases to run first?
    Answer: Based on risk, business impact, critical functionality, customer usage frequency.

20. What is the significance of boundary value analysis?
    Answer: It detects defects at the edges of input ranges; most bugs occur at boundaries.

21. What is test case prioritization?
    Answer: Ranking test cases based on risk, usage frequency, defect-prone modules, and business importance.

---

## SECTION 4: DEFECT REPORTING AND TRACKING

22. Explain the defect life cycle.
    Answer: New → Assigned → Open → Fixed → Retest → Verified → Closed. Includes Reopen and Deferred.

23. What details must be included when logging a bug?
    Answer: Title, steps, expected result, actual result, severity, priority, screenshots/logs, environment details.

24. Difference between severity and priority.
    Answer:

* Severity: Impact on system functionality.
* Priority: Urgency to fix.

25. How do you react when a developer rejects your bug report?
    Answer: Provide evidence, clarify steps, discuss impact, and maintain professional communication.

26. How do you identify and report bugs?
    Answer: During execution, compare expected vs actual results, capture evidence, log detailed bugs in tools like JIRA or Azure DevOps.

27. How would you handle conflicting test results?
    Answer: Reproduce in a clean environment, compare logs, verify test data, and collaborate with developers.

---

## SECTION 5: AGILE PROCESS AND COLLABORATION

28. What is your role during an Agile sprint?
    Answer: Participate in planning, review user stories, create test cases, execute tests, attend standups, perform regression, report defects.

29. What is a user story?
    Answer: A short requirement expressed from user perspective. Example: As a user, I want to log in so that I can access my account.

30. What do acceptance criteria define?
    Answer: The conditions that must be met for a user story to be accepted.

31. What happens in daily stand-ups and what do you report?
    Answer: Report what you did yesterday, what you will do today, and blockers.

32. How do you handle unclear or vague requirements in Agile sprints?
    Answer: Ask clarifying questions, collaborate with Product Owner, create assumptions and validate them, and document discussions.

33. How do you handle changes in the test scope during testing?
    Answer: Re-evaluate effort, update test cases, adjust priorities, and communicate time impact.

---

## SECTION 6: BANKING / FINANCE DOMAIN

34. Have you worked on any finance/banking systems?
    Answer: Mention modules like account management, fund transfer, loan processing, payment gateways.

35. What difficulties did you face while testing financial modules?
    Answer: High security, strict validations, complex calculations, audit trails, zero tolerance for errors.

36. Explain security testing in banking applications.
    Answer: Includes authentication testing, authorization testing, encryption, session handling, input validation, and penetration testing.

37. Which areas of a banking web app need the most attention?
    Answer: Login, transactions, payment flows, encryption, audit logs, statements, account summary, concurrency handling.

---

## SECTION 7: SCENARIO-BASED QA THINKING

38. What do you do if the requirements are incomplete?
    Answer: Communicate with stakeholders, ask questions, use exploratory testing, and document assumptions.

39. How do you approach testing with strict time constraints?
    Answer: Risk-based testing, prioritize critical flows, run sanity tests, avoid low-risk areas.

40. What is your response if a defect appears in production?
    Answer: Acknowledge, reproduce, identify root cause, update test coverage, and improve regression suites.

41. How would you test a login functionality end-to-end?
    Answer:

* Valid credentials
* Invalid username
* Invalid password
* Empty fields
* Locked user
* SQL injection
* UI validations
* Password masking
* Session timeout

42. If you were given a new application to test with no documentation, how would you approach it?
    Answer: Exploratory testing, understanding UI flow, analyzing similar products, interviewing team members, building test scenarios.

---

## SECTION 8: TEST ENVIRONMENT AND SDLC

43. Describe the SDLC and where testing fits.
    Answer: SDLC includes requirement gathering, design, development, testing, deployment, maintenance. Testing occurs after development but QA participates from day one.

44. What is a test environment?
    Answer: The setup where testing occurs, including hardware, software, database, network, test data.

45. Can you describe test closure activities?
    Answer: Test summary reports, metrics, defect analysis, lessons learned, archiving test artifacts.

---

## SECTION 9: AUTOMATION & MODERN QA CONCEPTS

46. Explain the benefits of automation.
    Answer: Faster execution, better coverage, repeatability, reduces human error, supports CI/CD.

47. Selenium Page Object Model (POM) structure.
    Answer: Separates page locators from test logic. Improves reusability and maintainability.

48. What is Maven?
    Answer: A build and dependency management tool for Java automation frameworks.

49. CI/CD explanation.
    Answer: Continuous Integration and Continuous Deployment; ensures automated builds, testing, and quick release cycles.

50. Selenium new features (latest versions).
    Answer: Relative locators, Chrome DevTools protocol support, better handling of iframes, improved wait strategies.

51. BDD tools you know (SpecFlow, NUnit, ReqAndRoll).
    Answer: Explain Gherkin, feature files, step definitions, and collaborative testing approach.

52. Mobile testing with Appium.
    Answer: Automates iOS/Android applications using WebDriver protocol.

53. TestNG explanation.
    Answer: Test framework for test grouping, annotations, data providers, parallel testing.

---

## SECTION 10: ADDITIONAL QA CONCEPTS

54. UI testing.
    Answer: Verifies layout, alignment, fonts, colors, controls, responsiveness.

55. Usability testing.
    Answer: Ensures ease of use, navigation clarity, user experience.

56. Integration testing.
    Answer: Validates data flow and interactions between components.

57. Performance testing tools.
    Answer: JMeter, LoadRunner, Locust, Gatling.

58. Quality Assurance vs Quality Engineering.
    Answer:

* QA focuses on preventing defects.
* QE focuses on continuous quality improvement using automation and engineering practices.





