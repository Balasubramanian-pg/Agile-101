# User Stories

> [!INFO]
> **What is a User Story?**
>
> A User Story is a short, simple description of a feature told from the perspective of the person who desires it—usually a user or customer. In Agile, User Stories are the primary way to capture requirements and define what needs to be built.
>
> **Purpose:**
> -   **Capture User Needs:** Focus on *what* the user needs, not *how* to implement it.
> -   **Foster Collaboration:** Act as a placeholder for conversations between the team and stakeholders.
> -   **Enable Planning:** Serve as the primary unit of work for planning, estimation, and prioritization.

### The User Story Template

> [!TIP]
> A common and highly effective template for writing User Stories is:
>
> **"As a [user role], I want to [goal/desire] so that [benefit/reason]."**

-   **"As a" [User Role]:** Defines **who** wants the feature (e.g., *a customer*, *an administrator*). This keeps the focus on the user's perspective.
-   **"I want to" [Goal/Desire]:** Describes **what** the user wants to do (e.g., *view my order history*, *reset my password*). This clearly states the desired functionality.
-   **"So that" [Benefit/Reason]:** Explains **why** the user wants this feature (e.g., *so that I can track my past purchases*). This clarifies the value and helps with prioritization.

> [!NOTE]
> ### Example User Stories
>
> -   **E-commerce:** "As a **customer**, I want to **search for products using keywords** so that **I can quickly find what I'm interested in buying**."
> -   **Online Banking:** "As a **registered user**, I want to **view my recent transaction history** so that **I can track my spending**."
> -   **Admin Panel:** "As an **administrator**, I want to **generate a monthly sales report** so that **I can analyze sales data**."

### Characteristics of Good User Stories (The INVEST Criteria)

> [!IMPORTANT]
> To be effective, User Stories should ideally adhere to the **INVEST** criteria. This acronym helps ensure stories are well-formed and ready for development.

> [!NOTE]
> -   **I - Independent:** The story should be self-contained and not dependent on other stories. This allows for flexible prioritization.
> -   **N - Negotiable:** A story is not a rigid contract but a starting point for a conversation. Details are fleshed out through collaboration.
> -   **V - Valuable:** The story must deliver tangible value to the user or customer. The "so that" clause helps articulate this value.
> -   **E - Estimable:** The team must have enough information to provide a reasonable estimate of the effort required. If a story is too vague to estimate, it needs refinement.
> -   **S - Small:** The story should be small enough to be completed within a single sprint. Large stories (Epics) should be broken down.
> -   **T - Testable:** The story must have clear, verifiable conditions for completion (Acceptance Criteria).

### Splitting Large User Stories

> [!TIP]
> Large user stories (often called Epics) must be split into smaller, manageable stories that can fit into a sprint. Common splitting techniques include:
>
> -   **By Workflow Steps:** Break down a process into individual steps.
> -   **By Business Rules:** Create separate stories for different rules or scenarios.
> -   **By User Roles:** Create different stories for different types of users.
> -   **By Operations (CRUD):** Split based on Create, Read, Update, and Delete actions.

### User Stories and Acceptance Criteria

> [!NOTE]
> Acceptance Criteria are the conditions that a User Story must satisfy to be considered "done." They provide the testable details that bring a story to life.
>
> -   **User Story:** "As a customer, I want to search for products using keywords so that I can quickly find items I am interested in buying."
>
> -   **Acceptance Criteria:**
>     -   **Given** I am on the homepage, **when** I enter a valid keyword, **then** I should see a list of matching products.
>     -   **Given** I am on the homepage, **when** I enter a keyword with no matches, **then** I should see a "No products found" message.

> [!NOTE]
> In summary, User Stories are a powerful and user-centric way to capture requirements in Agile development. By understanding the User Story template, INVEST criteria, and techniques for splitting stories, Agile teams can effectively define, plan, and deliver valuable software features that meet user needs.
