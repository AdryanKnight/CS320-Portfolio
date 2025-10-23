# CS320-Portfolio
Reflection
How can I ensure that my code, program, or software is functional and secure?

I ensure functionality and security by writing unit tests that validate both normal and edge-case behavior before integrating new features. Each requirement from the client specification was translated into one or more JUnit 5 tests, ensuring traceability from rule to verification. Techniques such as equivalence partitioning, boundary-value analysis, and state-based testing were applied across all services to confirm that valid data succeeded and invalid inputs failed fast with clear exceptions.
I also measured code coverage using JaCoCo, achieving roughly 92 % line and 84 % branch coverage, which confirmed that most core paths and error conditions were exercised. This disciplined testing approach built confidence that the system remained functional and resistant to regression or input misuse

CS 320 Project Two

.

How do I interpret user needs and incorporate them into a program?

I translate user needs into clear, testable requirements before coding. For the contact, task, and appointment services, each functional rule—such as “IDs must be unique” or “descriptions cannot exceed 50 characters”—became a test name and acceptance criterion (for example, addContact_rejectsNullPhone() or updateTask_rejectsInvalidLength()).
This 1:1 mapping between user stories, acceptance criteria, and test cases ensured that my implementation directly satisfied the client’s expectations. When a test failed, it pointed immediately to an unmet requirement, allowing rapid correction and alignment with stakeholder goals.

How do I approach designing software?

I take a test-driven and modular design approach. Each class was built around small, cohesive responsibilities following object-oriented principles such as encapsulation and separation of concerns. I used arrange-act-assert patterns within tests to clarify intent and keep logic independent.
Design decisions emphasized maintainability—using parameterized tests to reduce duplication, defensive constructors to enforce invariants, and meaningful exception handling. This mindset treats testing as an integral part of design, resulting in readable, reliable code that can evolve safely through future iterations.

Professional Growth

This project reinforced that testing is not just verification but design validation. Building tests alongside implementation helped me think like both a developer and a quality engineer. The process improved my debugging efficiency, documentation clarity, and confidence in delivering secure, dependable software—skills directly applicable to professional software-engineering and QA roles.
