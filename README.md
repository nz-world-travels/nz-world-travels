# NZ World Trous &amp; Travels Sdn Bhd

## Development

We will maintain a consistent structure across all repositories, following these guidelines:

**Branches:**
- **main** branch: Used for production-ready code.
- **dev** branch: Used for staging and development purposes.

**Workflow Steps:**

Step 0: Create a JIRA story to track the task.

Step 1: Create a branch from the **dev** branch with a descriptive name, prefixing it with the JIRA story ID.

Step 2: Move the JIRA story to the **In Progress** status.

Step 3: Make the necessary code changes and push your commits to your branch.

Step 4: Create a pull request from your branch to the **dev** branch after completing your work.

Step 5: Move the JIRA story to the **In Review** status.

- Reviewers will review the code in the pull request and provide comments if necessary. The developer is responsible for addressing these comments and making the required changes.
- Once the code is reviewed and approved, either the reviewer or the project manager can merge the code into the **dev** branch.
- When ready, notify the **DevOps** team to deploy the code on the staging environment.
- After deployment on staging, thorough testing will be conducted. Upon completion of testing, the project manager will move the JIRA story to the **Done** status.

These guidelines ensure a standardized process for repository management, code review, and deployment, promoting collaboration and efficiency within the development team.
