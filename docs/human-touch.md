# Section 4: Human-Driven Testing

In the era of automation, AI, and machine learning, the human touch remains still needed in software testing. Various types of testing require human insight, creativity, and feedback to identify problems and enhance the overall user experience. This section will guide you through the importance of human-driven testing, its benefits, and how to incorporate it into your QA architecture.

## 4.1 From "Checkboxes" to "Exploration"

In traditional testing, the focus is often on following predefined test cases and checking off boxes. While this approach is essential for ensuring that the software meets the specified requirements, it may not be sufficient to uncover all potential issues. Human-driven testing, on the other hand, emphasizes exploration, creativity, and critical thinking to identify problems that may not be captured by automated tests or scripted scenarios.

### 4.1.1 Strengths of human-driven testing

- **Critical thinking & intuition**: We as humans can apply critical thinking, intuition, and domain knowledge to identify potential issues that automated tests may overlook.
- **Creativity & exploration**: As part of human-driven testing, testers can explore the software in ways that automated tests cannot, uncovering unexpected issues and edge cases.
- **Empathy & user perspective**: Bring your customer's perspective to the testing process, identifying usability issues, and ensuring that the software meets the end-users' needs and expectations.

### 4.1.2 Practical steps

#### 4.1.2.1 Exploratory testing

While automated tests are excellent at verifying known scenarios, exploratory testing is a powerful technique for uncovering unknown issues. Testers explore the software freely, following their intuition and creativity to identify potential problems. Here are some tips for effective exploratory testing:

- **Start early**: Begin exploratory testing as soon as new features are available, even before formal test cases are written.
- **Focus on risk**: Prioritize your testing efforts based on risk, focusing on critical areas and potential failure points.
- **Document your findings**: Keep detailed notes of your exploratory testing sessions, including steps taken, observations made, and issues identified.
- **Collaborate with the team**: Share your findings with developers, product managers, and other stakeholders to ensure that issues are addressed promptly.
- **Iterate and refine**: Continuously refine your exploratory testing approach based on feedback, lessons learned, and evolving requirements.
- **Automate where possible**: While human-driven testing is essential, look for opportunities to automate repetitive tasks and scenarios to increase efficiency and coverage.

#### 4.1.2.2 Usability testing

Usability testing focuses on evaluating the software from the end-user's perspective, identifying usability issues, and ensuring a seamless user experience. Here are some tips for effective usability testing:

- **Define clear objectives**: Establish specific goals and objectives for your usability testing sessions, focusing on key user interactions and workflows.
- **Recruit representative users**: Select participants who represent your target audience, ensuring that you receive relevant feedback and insights.
- **Create realistic scenarios**: Develop realistic scenarios and tasks that mimic real-world user interactions, allowing participants to provide meaningful feedback.
- **Observe and listen**: Pay attention to how users interact with the software, noting areas of confusion, frustration, or delight. Listen to their feedback and observe their behavior to identify usability issues.
- **Iterate and improve**: Use the insights gained from usability testing to refine the software, improve the user experience, and enhance overall satisfaction.
- **Incorporate feedback**: Share usability testing results with the development team, product managers, and designers, collaborating on solutions and enhancements based on user feedback.
- **Make usability testing a continuous practice**: Integrate usability testing into your development process, conducting regular sessions to gather feedback, validate assumptions, and drive improvements.
- **Leverage tools and techniques**: Use tools (with consent) to record user interactions, capture feedback, and analyze usability metrics to gain deeper insights into user behavior and preferences.

#### 4.1.2.3 Accessibility testing

Accessibility testing focuses on ensuring that the software is usable by individuals with disabilities, complying with accessibility standards and guidelines. Here are some tips for effective accessibility testing:

- **Understand accessibility requirements**: Familiarize yourself with accessibility standards, such as WCAG, and the needs of users with disabilities to guide your testing efforts.
- **Leverage assistive technologies**: Use screen readers, magnifiers, voice recognition software, and other assistive technologies to simulate the experience of users with disabilities.
- **Test with real users**: Involve individuals with disabilities in your testing process, seeking their feedback and insights to identify accessibility barriers and usability issues.
- **Conduct manual and automated tests**: Combine manual testing techniques with automated accessibility testing tools to ensure comprehensive coverage and compliance with accessibility standards.
- **Document issues and provide recommendations**: Record accessibility issues, provide detailed descriptions, and suggest remediation strategies to address usability barriers and improve accessibility.
- **Advocate for accessibility**: Promote accessibility awareness within your organization, educate team members on best practices, and advocate for inclusive design principles to create software that is accessible to all users.
- **Integrate accessibility into your development process**: Incorporate accessibility testing into your QA process, conduct regular audits, and ensure that accessibility is considered at every stage of the software development lifecycle.

### 4.1.3 Colaboration with automations

Human-driven testing and automated testing are not mutually exclusive; they complement each other to provide comprehensive test coverage and ensure software quality. By combining the strengths of human testers and automated tools, you can achieve a balance between creativity, exploration, and efficiency in your testing efforts. You can leverage automation to handle repetitive tasks, regression testing, and performance testing, while humans focus on exploratory testing, usability testing, and accessibility testing. Key points to consider:

- **Automations as foundation**: Use automated tests as a foundation for your testing strategy, covering critical paths, regression scenarios, and performance benchmarks.
- **Human insights**: Incorporate human-driven testing to bring creativity, intuition, and empathy to the testing process, identifying issues that automated tests may miss.
- **Continuous improvement**: Iterate on your testing approach, refining your automated tests and human-driven tests based on feedback, lessons learned, and evolving requirements.
