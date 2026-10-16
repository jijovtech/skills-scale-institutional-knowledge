# OctoAcme Project Management Docs

OctoAcme follows a lightweight, iterative project management approach focused on delivering customer value through small, testable increments. Projects begin with a brief One-pager that clarifies the problem, success metrics, stakeholders, and an initial timeline. Planning turns approved initiatives into an actionable backlog with defined acceptance criteria, estimates, and a clear Definition of Done to keep work shippable and predictable.

The lifecycle progresses through Initiation, Planning, Execution, Release, and Close/Retrospective. Initiation confirms the business need and produces a Project One-pager; planning breaks work into prioritized backlog items with acceptance criteria and estimates; execution uses a project board and disciplined PR workflow with CI and approvals; releases follow a checklist with staging verification and rollback plans; retrospectives capture learnings and convert them into action items.

Operational workflows emphasize clear backlog management and small, reviewable changes. Teams use a project board with columns (Backlog → Ready → In Progress → In Review → QA → Done) and follow a PR workflow that encourages small PRs, links issues and acceptance criteria in PR descriptions, runs automated tests and security scans, and requires approvals per team policy. Planning uses timeboxed sessions, estimation (T-shirt or story points), and a Definition of Done to ensure work is ready for execution.

Roles are clearly defined: Project Manager (coordinates delivery, schedules, risks, and communication), Product Manager (owns outcomes and prioritization), Developers (implement and test), QA/Testing (validate acceptance criteria), and Stakeholders (provide inputs and approvals). Communication cadence includes daily standups for blockers, weekly delivery syncs for progress and risks, sprint demos, and regular PM↔PdM alignment. Quality practices layer unit and integration tests, end-to-end smoke tests, manual QA as needed, and security scanning in CI to maintain reliability and confidence in releases.

Usage and links
- Keep these process docs updated in docs/ and reference this README from onboarding materials and project templates.
- To make process-specific docs available to Copilot Spaces, add links or copies into `.copilot/` as needed.

Docs index
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md
