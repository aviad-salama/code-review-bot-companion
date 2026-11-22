# AI Code Review Companion Based on Quality Criteria

## Overview

Code review is an essential part of software development, but it is time-consuming and prone to human error. Traditional static analysis tools focus mainly on basic syntax and style rules, failing to evaluate deeper aspects such as business logic, modularity, security, and readability. Moreover, due to cognitive load and blind spots, human reviewers often miss subtle flaws during manual inspection. Therefore, there is a need for an AI code review bot that accompanies the reviewer, points out issues they might not have noticed on their own, and evaluates code changes according to 13 defined quality criteria with practical improvement suggestions.

## Evaluation Criteria

The review companion inspects pull requests and code changes across 13 software engineering criteria:

1. **Implementation:** Verifying that the code fulfills the functional requirements.
2. **Efficiency:** Identifying opportunities to improve algorithmic and resource efficiency.
3. **Simplicity:** Ensuring the code avoids unnecessary complexity.
4. **Modularity:** Checking for proper separation of concerns and reusable components.
5. **Bugs and Errors:** Detecting logical flaws and runtime defects.
6. **Error Handling:** Evaluating exception handling and edge-case resilience.
7. **Testing:** Assessing test coverage and testability of the changes.
8. **Usability:** Reviewing interface clarity and ease of integration.
9. **Documentation:** Checking comments, docstrings, and clarity of explanations.
10. **Ethics and Transparency:** Ensuring fair, transparent, and explainable review feedback.
11. **Security:** Identifying potential vulnerabilities and unsafe coding practices.
12. **Performance:** Evaluating execution speed and memory usage impact.
13. **Readability:** Checking naming conventions, formatting, and overall code clarity.

## Keywords

Code Review, LLMs, AI Agents, Software Quality, Human-in-the-Loop

## Project Status

Initial research, literature review, and system architecture design.

## Team

* **Students:** [Aviad Salama], [Michael Bonder]
* **Supervisor:** [Nataly Levi]
