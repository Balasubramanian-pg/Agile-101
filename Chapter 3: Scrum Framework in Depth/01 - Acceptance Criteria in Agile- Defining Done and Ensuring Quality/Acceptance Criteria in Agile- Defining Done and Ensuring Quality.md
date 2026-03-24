# Acceptance Criteria: Defining "Done"

> [!INFO]
> **What are Acceptance Criteria?**
>
> Acceptance Criteria (AC) are a set of predefined conditions that a User Story must meet to be considered complete. They are the "tests" a feature must pass to be accepted by the Product Owner and stakeholders.
>
> **Purpose:**
> -   Provide a clear and unambiguous **Definition of "Done"** for a story.
> -   Create a **shared understanding** of requirements across the team.
> -   Serve as the **basis for testing** and validation.
> -   **Guide development** by outlining expected behavior.
> -   **Reduce rework** by clarifying expectations upfront.

> [!TIP]
> **User Story vs. Acceptance Criteria**
>
> -   **User Story:** Describes *what* the user wants and *why*.
> -   **Acceptance Criteria:** Describe *how* we will know when the *what* is done correctly.

### Characteristics of Good Acceptance Criteria

Good Acceptance Criteria are often described as being **SMART**: Specific, Measurable, Achievable, Relevant, and Testable.

> [!NOTE]
> ### The SMART Framework for Acceptance Criteria
>
> -   **Specific:** Be precise and unambiguous. Avoid vague terms.
>     -   *Bad:* "The search should work well."
>     -   *Good:* "When a user searches with a valid keyword, the system displays a list of matching products."
>
> -   **Measurable:** The outcome must be verifiable.
>     -   *Bad:* "The system should be fast."
>     -   *Good:* "The product page must load in under 2 seconds on a standard connection."
>
> -   **Achievable:** The criteria must be realistic to meet within the sprint's constraints.
>
> -   **Relevant:** The criteria must directly relate to the user's goal in the User Story.
>
> -   **Testable:** It must be possible to write a test (manual or automated) to confirm if the criterion has been met.
>     -   *Bad:* "The system should be robust."
>     -   *Good:* "Verify that entering an invalid email format displays the 'Invalid email' error message."

### Formats for Writing Acceptance Criteria

> [!NOTE]
> ### 1. Checklist Format
>
> A simple list of conditions to be verified.
>
> **User Story:** *As a customer, I want to search for products using a keyword...*
> -   [ ] When a valid keyword is entered, matching products are displayed.
> -   [ ] When no products match, a "No products found" message is displayed.
> -   [ ] Search results include the product name, image, and price.
> -   [ ] Search is case-insensitive (e.g., "Laptop" and "laptop" return the same results).

> [!NOTE]
> ### 2. Rule-Based Format (Given-When-Then)
>
> A structured format that describes a scenario, popular in Behavior-Driven Development (BDD).
>
> -   **Given:** The initial context or precondition.
> -   **When:** The action performed by the user.
> -   **Then:** The expected outcome.
>
> **Scenario: Successful Search**
> -   **Given** I am on the homepage
> -   **When** I enter "Laptop" in the search bar
> -   **Then** I should see a list of products related to "Laptop"

> [!NOTE]
> ### 3. Example-Based Format
>
> Uses concrete examples to illustrate expected behavior, especially for complex rules.
>
> **User Story:** *As a customer, I want to calculate the total cost in my shopping cart...*
> -   **Example 1:** If I add 2 units of Product A ($10 each), the total is $20.
> -   **Example 2:** If I add 1 unit of Product B ($20) and apply a $5 coupon, the total is $15.
> -   **Example 3:** If the cart is empty, the total is $0.

> [!TIP]
> **Who Writes Acceptance Criteria and When?**
>
> -   **Who:** This is a collaborative effort, typically led by the **Product Owner** with crucial input from the **Development Team** and **QA**.
> -   **When:** AC should be defined *before* development begins, often during backlog refinement or sprint planning sessions.

> [!IMPORTANT]
> ### Best Practices for Writing Acceptance Criteria
>
> -   **Keep them clear and concise.** Use simple language.
> -   **Focus on "what," not "how."** Describe the outcome, not the implementation details.
> -   **Make every criterion testable.**
> -   **Collaborate with the entire team** to ensure a shared understanding.
> -   **Ensure AC supports the value** described in the User Story.

> [!NOTE]
> In summary, Acceptance Criteria are a vital part of Agile development. They provide a precise definition of "done" for each User Story, facilitate clear communication, guide development and testing, and ultimately contribute to delivering high-quality software that meets user needs and business objectives.
