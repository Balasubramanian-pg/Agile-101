Acceptance Criteria are a set of predefined statements that specify the conditions that must be met for a User Story to be considered complete and accepted by the Product Owner or stakeholders. They provide a clear and measurable definition of "done" for each User Story, ensuring that the development team and stakeholders have a shared understanding of what needs to be delivered.

# **What are Acceptance Criteria?**

- **Definition:** Acceptance Criteria are a list of conditions that a User Story must satisfy to be considered complete and valuable. They are essentially the "tests" that a feature must pass to be accepted.
- **Purpose:**
    - **Clear Definition of "Done":** Acceptance Criteria provide a concrete and unambiguous definition of what "done" means for a User Story. This eliminates ambiguity and ensures everyone is on the same page.
    - **Shared Understanding:** They create a shared understanding of requirements between the Product Owner, development team, and stakeholders.
    - **Basis for Testing and Validation:** Acceptance Criteria serve as the foundation for creating test cases and validating that the implemented feature meets the intended functionality and quality standards.
    - **Development Guidance:** They guide the development team by clearly outlining the expected behavior and outcomes of the feature.
    - **Verification and Acceptance:** Acceptance Criteria are used by the Product Owner (and sometimes stakeholders) to verify that the implemented story meets the agreed-upon conditions before accepting it as complete.
    - **Reduce Rework and Misunderstandings:** By clearly defining expectations upfront, Acceptance Criteria help reduce rework due to misunderstandings or missed requirements.
    - **Focus on User Value:** Well-written Acceptance Criteria are derived from the User Story and directly relate to the user's goal and the benefit stated in the "so that" clause.

#### **Relationship to User Stories:**

Acceptance Criteria are directly linked to User Stories. For each User Story, there should be a corresponding set of Acceptance Criteria. They elaborate on the User Story and provide the detailed conditions that must be met to fulfill the user need described in the story.

- **User Story:** Describes _what_ the user wants and _why_.
- **Acceptance Criteria:** Describe _how_ we will know when the _what_ is done correctly. They specify the concrete, verifiable conditions.

## **Characteristics of Good Acceptance Criteria (SMART Criteria Adaptation):**

Similar to User Stories (INVEST), good Acceptance Criteria should also adhere to certain quality characteristics. We can adapt the **SMART** criteria (Specific, Measurable, Achievable, Relevant, Time-bound - often used for goals) to fit Acceptance Criteria:

- **Specific:**
    - **Meaning:** Acceptance Criteria should be clear, precise, and unambiguous. They should focus on a specific aspect of the User Story and avoid vague or general statements.
    - **Example (Specific):** Instead of "The search should work well," be specific: "When a user searches with a valid keyword, the system should display a list of products matching the keyword."
    - **Example (Not Specific):** "The system should be user-friendly." (Too vague)
- **Measurable:**
    - **Meaning:** Acceptance Criteria should be measurable or verifiable. It should be possible to objectively determine whether each criterion has been met.
    - **Example (Measurable):** "The page should load in under 2 seconds." (Measurable performance criterion). "The error message should be displayed in red color and should be clearly visible." (Measurable visual and functional criterion).
    - **Example (Not Measurable):** "The system should be fast." (Not measurable enough)
- **Achievable (or Attainable):**
    - **Meaning:** Acceptance Criteria should be realistic and achievable within the sprint and given the constraints of the project.
    - **Benefit:** Avoid setting unrealistic expectations that cannot be met within the sprint.
    - **Example:** Ensure that the performance criteria (e.g., page load time) is realistically achievable given the infrastructure and technology.
- **Relevant (or Valuable):**
    - **Meaning:** Acceptance Criteria should be directly relevant to the User Story and the user's need. They should focus on conditions that are important to the user and contribute to the value of the story.
    - **Benefit:** Ensure that the criteria are meaningful and not just arbitrary technical details. They should validate the user value described in the User Story.
    - **Example:** Acceptance Criteria should focus on aspects that directly impact the user's ability to achieve their goal as stated in the User Story.
- **Testable (or Time-bound, in some interpretations for AC):**
    - **Meaning:** Acceptance Criteria must be testable. It should be possible to design tests (manual or automated) to verify whether each criterion is met. In the context of Acceptance Criteria, "Testable" is crucial. Sometimes, "Time-bound" is loosely adapted in the sense that the scope of Acceptance Criteria should be reasonable for a sprint and not overly complex or time-consuming to verify.
    - **Benefit:** Testable criteria enable clear verification and acceptance of the story. They guide testing efforts and ensure quality.
    - **Example (Testable):** "Verify that when a user enters an invalid email format in the registration form, an appropriate error message is displayed." (Testable condition).
    - **Example (Not Easily Testable):** "The system should be robust." (Not directly testable without further specification of what "robust" means).

## **Formats for Writing Acceptance Criteria:**

There are several common formats for writing Acceptance Criteria:

1. **Checklist Format:**
    - **Description:** A simple list of statements, each representing a condition that must be checked or verified. Often uses bullet points or numbered lists.
    - **Example (User Story: As a customer, I want to search for products using keywords...):**
        - [ ] When a user enters a valid product keyword, the system displays a list of matching products.
        - [ ] When a user enters a keyword that does not match any products, a "No products found" message is displayed.
        - [ ] Search results should display product name, image, and price.
        - [ ] Search should be case-insensitive (e.g., "Laptop" and "laptop" should yield the same results).
2. **Rule-Based Format (Scenario-Based or Given-When-Then Format):**
    - **Description:** Uses a more structured format, often based on scenarios or rules. The "Given-When-Then" format is popular, especially when using Behavior-Driven Development (BDD).
    - **"Given-When-Then" Format:**
        - **Given:** Describes the initial context or precondition.
        - **When:** Specifies the event or action performed by the user or system.
        - **Then:** Describes the expected outcome or result.
    - **Example (User Story: As a customer, I want to search for products...):**
        - **Scenario 1: Successful Search:**
            - **Given** I am on the homepage
            - **When** I enter the keyword "Laptop" in the search bar and submit
            - **Then** I should see a list of products related to "Laptop".
        - **Scenario 2: No Results Found:**
            - **Given** I am on the homepage
            - **When** I enter the keyword "Unicorn" in the search bar and submit
            - **Then** I should see a "No products found" message.
        - **Scenario 3: Case-Insensitive Search:**
            - **Given** I am on the homepage
            - **When** I enter the keyword "laptop" (lowercase) in the search bar and submit
            - **Then** I should see the same search results as if I searched for "Laptop" (uppercase).
3. **Example-Based Format:**
    - **Description:** Uses concrete examples to illustrate the expected behavior and outcomes for different scenarios.
    - **Example (User Story: As a customer, I want to calculate the total cost in the shopping cart...):**
        - **Example 1: Single Item:** If I add 2 units of Product A (price $10 each) to the cart, the total should be $20.
        - **Example 2: Multiple Items:** If I add 1 unit of Product B ($20), 3 units of Product C ($5 each), and apply a discount coupon of $5, the total should be $20 + (3 * $5) - $5 = $30.
        - **Example 3: Zero Items:** If the cart is empty, the total should be $0.

### **Who Writes Acceptance Criteria and When?**

- **Collaboration:** Writing Acceptance Criteria is a collaborative effort. Typically, the Product Owner takes the lead, but input from the development team and sometimes testers and other stakeholders is crucial.
- **Timing:** Acceptance Criteria are ideally defined _before_ or during Sprint Planning, before the development team starts working on the User Story. This ensures clarity and alignment before development begins. They are often refined during backlog refinement or grooming sessions.

## **Benefits of Using Acceptance Criteria:**

- **Improved Communication and Alignment:** Fosters clear communication and shared understanding of requirements.
- **Reduced Ambiguity and Rework:** Minimizes misunderstandings and rework by clearly defining "done."
- **Enhanced Quality:** Guides development and testing towards delivering features that meet quality standards and user needs.
- **Efficient Testing and Verification:** Provides a clear basis for creating test cases and verifying implementation.
- **Clear Acceptance Process:** Facilitates a straightforward acceptance process by the Product Owner.
- **Focus on User Value:** Ensures that development is aligned with delivering user value.

## **Best Practices for Writing Acceptance Criteria:**

- **Keep them Concise and Clear:** Use simple, straightforward language. Avoid jargon or overly technical terms.
- **Focus on "What" and "Outcome," not "How":** Describe the expected outcome and behavior, not the implementation details.
- **Make them Testable and Verifiable:** Ensure each criterion is testable and can be objectively verified.
- **Use Examples Where Helpful:** Examples can clarify complex or nuanced requirements.
- **Collaborate and Discuss:** Involve the team in the process to get diverse perspectives and ensure shared understanding.
- **Review and Refine Regularly:** Acceptance Criteria can be reviewed and refined as understanding evolves, especially during backlog refinement or sprint planning.
- **Link to User Story Value:** Ensure that the criteria directly support the value proposition of the User Story.

> [!NOTE]
> In summary, Acceptance Criteria are a vital part of Agile development. They provide a precise definition of "done" for each User Story, facilitate clear communication, guide development and testing, and ultimately contribute to delivering high-quality software that meets user needs and business objectives.