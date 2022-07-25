# Robert Bosch GmbH (Tooling Software Engineer)

- Stuttgart, Germany
- Sep 2017 - Present

## Responsibilities:

As one of the very first team members that joined the team, I assumed these set of responsibilities.

- Train many new-comers
- Provide technical support for new and old team members
- Provide technical support for users of our tools/systems
- Contribute in archetictural decisions
- Reviewing Pull Requests from all team members
- Maintain DevOps infrastructure (Jenkins, BitBucket, Web-Hooks, REST API)
- Proxy for Team Lead
- Proxy for Product Owner
- Prepare and Conduct DEMOs for new potential users and to current users for newly added features

## Technologies:

### Python:

- Main programming language used, developed tools up to 7k lines of code each
- Developed many internal pip packages, some were used in our tools, and some by other departments
- Dependencies handling with PIPENV
- Versioning handling with commitizen
- Documentation using Sphinx (RST)
- Many Desktop UI apps using Qt for Python (PySide)

### React:

- Main JS Framework used for our Web Applications
- Used Zustand (previously Redux) to maintain internal app's state
- Used React-Query for handling/caching all communication with Server-Side (REST API)
- Used react-testing-library for unit-testing our apps
- All our apps using TypeScript (\*.ts) instead of plain JavaScript (\*.js)
- Used Material UI components (MUI)
- Used both "yarn" and "npm" packaging tools

### DevOps:

#### Jenkins:

- Developed/Maintained many complex pipelines in Groovy
- Built tools that communicate with Jenkins via REST API calls to create Jobs, trigger Builds, ..etc

#### Docker:

- Familiar with the concepts, watched many courses on LinkedIn Learning, but didn't use much in my daily work.

#### Chocolatey:

- Wrote a PowerShell script (ps1) to automate installing/un-installing necessary apps, and setting up Environment Variables for new nodes in our infrastructure.

#### BitBucket:

- Maintained Web-Hooks to automatically trigger Jenkins Builds to run unit-tests for any particular tool after a PR has been opened/modified.
- Developed many tools that communicate with our internal BitBucket installation to create PRs, query PRs with merge conflicts, add comments on PRs, approve/decline a PR based on successful/failing unit-testing (via a System User) via REST API calls.

### Software Industry Tools:

- Atlassian Jira
- Atlassian Bitbucket
- IBM RQM (Testing Management)
- IBM DOORS (Requirements Management)

## Major Projects:

### Tool Creator:

- An internal tool I developed, that creates all the necessary infrastructure changes for a new tool that we're going to develope, creates Jenkins Jobs & BitBucket Repository, configure Web-Hooks, configure SonarQube, initialize Sphinx Documentation, and the initial folder structure of the tool.
- It has been used to create all other tools that we started developing afterwards.
- Developed CI-CT-CR concepts, so that every merge to the master branch can only be done if all unit-tests pass and have at least 80% coverage, and SonarQube doesn't have any major findings.

### Project Metrics:

- Successfully automated a thorough Metrics generation Python script that extracts information from IBM DOORS, IBM RQM, and Atlassian Jira, and generates Excel/PowerBI Reports with a lot of numbers and graphs, that are of significant importance both to Management and Team members to monitor work progress across the whole project.
- Built and maintained Jenkins jobs to trigger Metrics generation multiple times per day, and converted the Jenkins Jobs into Pipelines for easier management.
- Conducted multiple trainings  to internal/external Test Centers on Project Metrics generation and Testing Process.
- This system is currently used by at least 10 projects, some of them for more than 4 years
