# Basoma Patrick

**PLP Students**  
**Software Engineering Program**

# PLP Software Engineering – Prompt Engineering for Software Engineering Tasks

## Exercise A: Explaining the SDLC

### Prompt 1: Zero-Shot

**Prompt:**

> Explain the Software Development Life Cycle (SDLC), including its main phases and their importance.

### AI Response

The **Software Development Life Cycle (SDLC)** is a systematic process used to develop software from the beginning of a project to its completion and maintenance.

The main phases are:

1. **Planning** – Identifying the project goals, resources, cost, and schedule.
2. **Requirements Analysis** – Understanding and documenting what users need from the software.
3. **System Design** – Designing the system architecture, database, interface, and other technical components.
4. **Implementation** – Writing and developing the software code.
5. **Testing** – Checking the software for errors and ensuring it meets requirements.
6. **Deployment** – Releasing the completed software for users.
7. **Maintenance** – Fixing problems, updating, and improving the software after release.

### Summary

The SDLC is a structured process for developing software. It contains seven main phases, from planning to maintenance. Each phase has a specific purpose and contributes to software quality. Following the SDLC helps software teams develop software in an organized way.

## Prompt 2: Role Prompting

**Prompt:**

> Act as an experienced software engineering teacher. Explain the Software Development Life Cycle (SDLC) to beginner software engineering students. Use simple English and organize the answer using headings and numbered points. Explain each phase and why it is important, then provide a short summary at the end.

### AI Response

# Software Development Life Cycle (SDLC)

The **Software Development Life Cycle (SDLC)** is a step-by-step process used by software engineers to plan, develop, test, deploy, and maintain software.

### 1. Planning

The team identifies the purpose of the project, required resources, estimated cost, and schedule.

**Importance:** Planning helps the team understand what needs to be done before development begins.

### 2. Requirements Analysis

The team collects information from users and identifies what the software should do.

**Importance:** Clear requirements help developers build software that meets users' needs.

### 3. System Design

The team decides how the software will be structured. This can include database design, user interface design, and system architecture.

**Importance:** Good design provides a clear plan for developers.

### 4. Implementation

Developers write the actual program code.

**Importance:** This is where the planned software is built.

### 5. Testing

The software is tested to find errors and confirm that it meets the requirements.

**Importance:** Testing helps improve software quality and reliability.

### 6. Deployment

The completed software is released and made available to users.

**Importance:** Users can now begin using the software.

### 7. Maintenance

Developers fix errors, provide updates, and improve the software.

**Importance:** Maintenance keeps the software useful and reliable after release.

### Summary

The SDLC gives software engineers an organized way to develop software. Each phase has a specific purpose, and completing the phases properly helps produce reliable and maintainable software.

### 3–5 Sentence Summary

The role-prompting response was more useful because it was written specifically for **beginner software engineering students**. I changed the prompt by giving the AI a role, identifying the audience, and requesting a specific format. The role made the response more like a teacher's explanation. Specifying the audience encouraged the AI to use simple language and clear examples.

### Comparison

The **Role Prompting response was more useful** for our learning because it was more organized and easier to understand. The main changes were adding the AI's role, the audience, and the desired format. The role helped the AI respond as a teacher, while the audience specification made the explanation suitable for beginners.

# Exercise B: Software Development Models

## Prompt

> Act as a software engineering consultant. For each of the following situations, recommend the most appropriate software development model:

1. A project with stable, clearly defined requirements.
2. A startup where requirements change frequently based on user feedback.
3. A large project with significant technical and security risks.
4. A project where testing and verification are extremely important.

> For each situation, recommend one development model, explain why it is appropriate, and briefly mention one limitation. Present the answer in a simple table.

## AI Response

| **Situation** | **Recommended Model** | **Why It Is Appropriate** | **One Limitation** |
|---|---|---|---|
| Stable, clearly defined requirements | **Waterfall** | Waterfall follows a structured sequence and works well when requirements are stable and unlikely to change. | Changes later in development can be difficult and costly. |
| Startup with frequently changing requirements | **Agile/Scrum** | Agile supports short development cycles and frequent feedback, allowing requirements to change during development. | It requires continuous communication and stakeholder involvement. |
| Large project with technical and security risks | **Spiral** | Spiral focuses on identifying and managing risks through repeated cycles of planning, development, and risk analysis. | It can be complex and expensive to manage. |
| Testing and verification are extremely important | **V-Model** | The V-Model connects development activities with corresponding testing activities and emphasizes verification and validation. | It is less flexible when requirements change significantly. |

### Reflection

I learned that the choice of a software development model depends on the **requirements, risks, flexibility, and testing needs** of a project. Waterfall can be suitable when requirements are stable, while Agile supports projects where requirements change frequently. Spiral places strong attention on risk management, while the V-Model emphasizes testing and verification. Therefore, software engineers should consider the characteristics of a project before selecting a development model.

# Exercise C: Requirements Extraction

## Prompt

> Act as a software requirements analyst. Analyze the following client brief for a local bookstore:

- Track books, quantities, and prices.
- Manage supplier payments.
- Alert staff when stock is low.
- Identify best-selling books.
- Allow customers to check availability online.
- Produce clear records for a part-time assistant.
- The owner has a limited budget.

> Produce the following:
>
> 1. Functional requirements.
> 2. Non-functional requirements.
> 3. Must Have requirements.
> 4. Should Have requirements.
> 5. Nice to Have requirements.
> 6. Questions or ambiguities that need clarification.
>
> Use simple English and explain the reason for your classifications.

## AI Response

### 1. Functional Requirements

The system should:

- Record books in the inventory.
- Record book quantities.
- Record book prices.
- Manage supplier payments.
- Alert staff when stock is low.
- Identify best-selling books.
- Allow customers to check book availability online.
- Produce clear records and reports.

### 2. Non-Functional Requirements

The system should:

- Be easy for the part-time assistant to use.
- Provide clear and understandable records.
- Protect business and payment information.
- Be reliable.
- Be affordable because the owner has a limited budget.

### 3. Must Have Requirements

- Book inventory management.
- Quantity and price tracking.
- Supplier payment management.
- Low-stock alerts.
- Basic records and reports.

### 4. Should Have Requirements

- Best-selling book reports.
- Online book availability.

### 5. Nice to Have Requirements

- Advanced sales charts.
- Mobile application.
- Automated supplier notifications.
- Advanced business analytics.

### 6. Questions or Ambiguities

1. How many books will the system need to manage?
2. What payment methods should be recorded?
3. What stock quantity should trigger an alert?
4. Should customers only check availability or also reserve books?
5. Who should be allowed to access supplier payment information?
6. What specific records does the part-time assistant need?
7. What is the available budget?

## Evaluation

### Two Things the AI Did Well

1. It correctly identified most of the **functional requirements** from the client brief.
2. It identified important non-functional requirements such as **usability, security, reliability, and affordability**.

### One Thing the AI Missed or Categorized Incorrectly

The AI placed **online book availability** under "Should Have." Since the client specifically requested this feature, it could reasonably be classified as a **Must Have**.

### One Improvement to the Prompt

I would ask the AI to **explain the reason for placing every requirement under Must Have, Should Have, or Nice to Have**.

# Exercise D: Prompt Iteration Challenge

## Version 1

### Prompt

> Create a project plan for a mobile application that allows university students to book campus study rooms.

### AI Response

A project plan for the application could include:

1. Planning
2. Requirements gathering
3. Design
4. Development
5. Testing
6. Deployment
7. Maintenance

### What Is Missing?

The response is too general. It does not provide **time estimates, deliverables, project risks, risk mitigation, team roles, or budget**.

# Version 2

### Prompt

> Create a project plan for a mobile application that allows university students to book campus study rooms. Include the main features of the application, project activities, users, and development stages.

### What I Changed

I added:

- Main application features.
- Users.
- Project activities.
- Development stages.

### Why?

These details provide the AI with more information about the application and its users. This should make the project plan more specific.

# Version 3

### Prompt

> Act as a software project manager. Create a project plan for a mobile application that allows university students to book campus study rooms. The application should allow students to view available rooms, check schedules, book rooms, cancel bookings, and receive booking confirmations. Consider students, university administrators, and technical staff as stakeholders. Organize the project according to the SDLC phases and identify possible project risks.

### What I Changed

I added:

- A specific **AI role**.
- Specific application features.
- Stakeholders.
- SDLC phases.
- Project risks.

### Why?

These additions give the AI more context and make the expected response clearer. The AI can now produce a more realistic software project plan.

# Version 4: Final Prompt

### Final Prompt

> Act as an experienced software project manager. Create a clear and practical project plan for a mobile application that allows university students to book campus study rooms.
>
> The application should allow students to:
>
> - View available study rooms.
> - Check room schedules.
> - Book a study room.
> - Cancel bookings.
> - Receive booking confirmations.
>
> The stakeholders are students, university administrators, and technical staff.
>
> Organize the project according to all **7 SDLC phases: Planning, Requirements Analysis, System Design, Implementation, Testing, Deployment, and Maintenance**.
>
> For each phase, provide:
>
> - Main activities.
> - Estimated time.
> - Key deliverables.
>
> Also include:
>
> - Project risks.
> - Risk mitigation strategies.
> - Team roles.
> - A rough budget.
>
> Use simple English and clear headings and tables. State any assumptions made about the timeline and budget.

## AI Response

### 1. Planning

**Estimated time:** 1–2 weeks

**Activities:**

- Define project objectives.
- Identify stakeholders.
- Estimate resources and budget.
- Identify initial risks.

**Deliverables:**

- Project proposal.
- Project schedule.
- Initial budget.

### 2. Requirements Analysis

**Estimated time:** 2 weeks

**Activities:**

- Collect requirements from students and administrators.
- Identify functional and non-functional requirements.
- Define booking rules.

**Deliverables:**

- Software Requirements Specification (SRS).
- User requirements.
- Use cases.

### 3. System Design

**Estimated time:** 2–3 weeks

**Activities:**

- Design the user interface.
- Design the database.
- Design system architecture.
- Plan authentication and security.

**Deliverables:**

- UI/UX designs.
- Database design.
- System architecture.

### 4. Implementation

**Estimated time:** 6–8 weeks

**Activities:**

- Develop the mobile application.
- Develop the backend.
- Create the database.
- Implement booking and cancellation.
- Implement notifications.

**Deliverables:**

- Working mobile application.
- Backend system.
- Database.

### 5. Testing

**Estimated time:** 3 weeks

**Activities:**

- Unit testing.
- Integration testing.
- System testing.
- Security testing.
- User acceptance testing.

**Deliverables:**

- Test plan.
- Test results.
- Bug reports.
- Tested application.

### 6. Deployment

**Estimated time:** 1–2 weeks

**Activities:**

- Prepare the production environment.
- Deploy the application.
- Train administrators.
- Release the application.

**Deliverables:**

- Deployed application.
- Deployment documentation.
- User guide.

### 7. Maintenance

**Estimated time:** Ongoing

**Activities:**

- Fix bugs.
- Monitor system performance.
- Apply security updates.
- Add improvements based on user feedback.

**Deliverables:**

- Maintenance reports.
- Software updates.
- New releases.

### Project Risks and Mitigation

| **Risk** | **Mitigation** |
|---|---|
| Users have difficulty using the application | Conduct user testing and provide training |
| Double booking of rooms | Implement booking validation |
| Security problems | Use authentication and security testing |
| Project delays | Monitor milestones and project progress |
| Limited budget | Prioritize essential features |

### Team Roles

- Project Manager
- Business/System Analyst
- UI/UX Designer
- Mobile Developer
- Backend Developer
- Database Administrator
- Software Tester/QA
- Security Specialist

### Rough Budget

An estimated budget could be **KES 1,000,000–2,500,000**, depending on the team size, technology, hosting, testing, and project duration.

## Final Reflection

Yes, the prompt improved from Version 1 to Version 4. The biggest difference was adding **specific context, requirements, output format, and constraints**. Adding the seven SDLC phases, deliverables, risks, team roles, timeline, and budget made the final response much more useful and practical.

# Overall Reflection

### 1. What Makes a Prompt Effective?

A good prompt is **clear, specific, and provides enough context**. It should tell the AI what task to perform and, when necessary, explain the expected format and audience.

### 2. Which Prompting Technique Did You Find Most Useful?

I found **role prompting** most useful because giving the AI a role, such as a software engineer or project manager, helps guide the type and style of response.

### 3. Why Is Context Important When Working With AI?

Context helps the AI understand the **problem, users, requirements, and expected outcome**. Without enough context, the response may be too general.

### 4. Why Should We Review AI-Generated Responses?

AI can make mistakes, misunderstand requirements, or provide incorrect information. Software engineers should **review, test, and verify** AI-generated responses before using them in real projects.

### 5. How Can AI Support Software Engineers Across the SDLC?

AI can support software engineers with **requirements analysis, documentation, system design, code generation, debugging, testing, project planning, security checks, and maintenance**. Human engineers still need to review the results and make important technical and ethical decisions.