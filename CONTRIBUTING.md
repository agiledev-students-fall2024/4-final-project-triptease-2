## CONTRIBUTING.md
## Team Members
- **Rena Wang**: [GitHub Profile](https://github.com/nomegustaexam)
- **Shay Butler**: [GitHub Profile](https://github.com/hawk-2414)
- **Chris Bobadilla**: [GitHub Profile](https://github.com/chrisbobadilla)
- **Makenzie Jones**: [GitHub Profile](https://github.com/m4kenziejones)

## Project Instructions
This repository includes several sets of instructions. Each set corresponds to a different phase of the project, with its own requirements and deadlines:

1. **App Map & Wireframes**: See the App Map & Wireframes and Prototyping instructions for the initial user experience design.
2. **Project Setup**: Replace the contents of this file with a proper README.md, as outlined in the Project Setup Instructions.
3. **Sprint Planning**: Follow the Sprint Planning Instructions for each sprint.
4. **Front-End Development**: Refer to the Front-End Development Instructions for implementing the initial UI components.
5. **Back-End Development**: See the Back-End Development Instructions for server-side implementation.
6. **Database Integration**: Follow the Database Integration Instructions for connecting and managing data.
7. **Deployment**: Use the Deployment Instructions to set up the app for release.

## Project Milestones and Schedule
- **Daily Standup**: Every Monday @3:30 PM , Tuesday @5:00 PM, and Thursday @ 9:00 PM
- **10/1**: Project Setup and Sprint 0 Planning
- **10/8**: Sprint 0 - App Map, Wireframe, and Prototype Deadline
- **10/10**: Sprint 0 Project Setup and Sprint 1 Planning
- **10/31**: Sprint 1 Completion, Stakeholder Demo, Sprint 1 Feedback, Sprint 2 Planning
- **11/14**: Sprint 2 Completion, Sprint 2 Feedback, Stakeholder Demo, Sprint 3 Planning
- **12/3**: Sprint 3 Completion, Sprint 3 Feedback, Stakeholder Demo, Sprint 4 Planning, Database Integration
- **12/12**: Sprint 4 Completion, Project Presentations, Sprint 4 Feedback

## Building and Testing Instructions
Instructions for building and testing the project will be provided once we reach the appropriate stages of development. Stay tuned for updates.



# CONTRIBUTING.md

## Team Members
1. Rena Wang: [GitHub Profile](https://github.com/nomegustaexam)
2. Shay Butler: [GitHub Profile](https://github.com/hawk-2414)
3. Chris Bobadilla: [GitHub Profile](https://github.com/chrisbobadilla)
4. Makenzie Jones: [GitHub Profile](https://github.com/m4kenziejones)

## Team Values & Team Norms

### Team Values
- **Collaboration**: We prioritize open communication and the sharing of ideas to achieve the best possible outcomes.
- **Communication**: We will communicate when we're working on a feature or if we encounter any blockers.
- **Respect**: Every team member's ideas and contributions are valued and considered with respect.
- **Accountability**: Each team member is responsible for their own tasks and deadlines. We hold ourselves and each other accountable.
- **Continuous Improvement**: We strive to learn from each sprint and continuously improve our processes and product.
- **Transparency**: We maintain clear and honest communication about our progress, challenges, and individual workloads.
- **Documentation**: We will document our code properly to ensure it's understandable for other contributors.


### Team Norms
- **Daily Standup and Sprint Meeting**: Meetings are held every Monday, Tuesday, and Thursday at 5 PM.
- **Role Rotation**: At the start of each sprint, the roles of Scrum Master and Product Owner rotate among team members to ensure balanced contributions.
    - **Scrum Master**: Leads daily standups, manages the progress of the project, and updates the task board.
    - **Product Owner**: Prioritizes and oversees tasks, prepares the Stakeholder Demo, and communicates the vision of the product.
    - **Developers**: Focus on building features, completing tasks, and preparing a functional product for demos.

- **Task Management**: Each team member updates the Sprint Task Board to communicate the current status of tasks. Meeting notes are documented for each standup to track workloads and task prioritization.
- **Commit Confirmation**: Before committing any changes, team members should consult with others to ensure the functionality is intact, minimize merge conflicts, and maintain code quality.

## Git Workflow
Our Git workflow follows these steps to maintain a structured and organized development process:

1. **Branching Strategy**: 
   - Create a new branch for each feature or bug fix (e.g., `feature/login-page` or `bugfix/fix-login-error`).
   - All work is done in feature branches, which are based on the `main` or `develop` branch.

2. **Commit Messages**:
   - Use clear and concise commit messages that describe the changes made (e.g., `Add login functionality` or `Fix issue with session timeout`).
   - Commits should be frequent and modular to make it easier to track changes.

3. **Pull Requests (PRs)**:
   - Before creating a PR, ensure your branch is up to date with the `develop` branch.
   - Submit a pull request when the feature is complete, and assign it to the Product Owner or a designated reviewer for approval.
   - Discuss any comments or changes required in the PR and make necessary adjustments.

4. **Merging Strategy**:
   - Only merge a branch into `develop` after it has been reviewed and approved by at least one other team member.
   - Avoid direct commits to the `main` or `develop` branches; only merge using pull requests.

5. **Conflict Resolution**:
   - In case of merge conflicts, resolve them locally before pushing the changes.
   - Communicate with the team if conflicts are complex or affect multiple areas of the code.

## Instructions for Setting Up the Local Development Environment

To get started with setting up the development environment for TripTease, follow these steps:

1. **Clone the Repository**:
git clone https://github.com/agiledev-students-fall2024/4-final-project-triptease-2/tree/master 
2.  **Install Dependencies:**:
npm install
3.  **Starting the Development Server:**:
npm start
4. **Building the Project**
npm run build
4. **Testing the Project**
npm test
