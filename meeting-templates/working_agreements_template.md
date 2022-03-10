
**Working Agreements Meeting Template**

Meeting purpose:


* Document a shared understanding of what we expect from each other on the team
* Consider how a new team member could quickly ramp up on our norms and expectations by documenting our unspoken rules / assumptions

Suggested topics:

* Planning, discovery and estimation
    * Who writes tickets?
    * What makes a well groomed ticket that’s ready for work?
        * Acceptance criteria
        * Testing instructions
        * Deployment instructions / rollback plan
        * Risk assessment
        * Estimation
            * Time? Complexity?
            * Do we estimate individually, or via consensus (e.g. planning poker)?
    * For larger initiatives
        * When do we use an epic?
        * What constitutes a ticket that should be split into smaller tickets?
        * When do we require additional planning/collaboration/documentation (e.g. design docs, RFC, etc)?
    * How do our tickets flow across the board (i.e. who moves them, when should a new ticket be taken, etc)?
    * Agile methodology
        * What will the team use (e.g. kanban vs sprints)?
        * If sprints:
            * How long is a sprint?
            * How is velocity measured/used?
            * What is the procedure / expectation for bringing in non-sprint work / additional sprint work?
            * How do we account for variance in team capacity (PTO, training, etc)?

* Writing and deploying code:
    * Code standards
        * Linting
        * File structure
        * Architectural considerations
        * Data modeling preferences / considerations
            * What are we optimizing for?
    * Code review expectations
        * Who reviews code?
        * How many approvals are required to merge?
        * What does review entail?
            * What are we looking for in a review besides style and readability (e.g. “includes tests”, “includes documentation”, etc)?
            * Should reviewers pull down the branch and test in certain circumstances?
            * Are reviewers expected to match functionality to acceptance criteria / ensure the PR sticks to the scope of the ticket?
            * When is documentation expected to be included?
    * Branching expectations
        * How should we name our branches?
        * What’s our branch workflow (e.g. gitflow, etc)?
        * How does our branch workflow affect our practices (e.g. long lived feature branches, etc)?
    * Deployment expectations
        * Who deploys code?
        * How do we deploy safely and reliably?
        * How do we handle failed deploys, bugs, etc?
        * How are releases handled, and what special considerations are there?
            * Are release tickets made for each deploy?
            * Do we use feature flags? Incremental rollout?
            * Are there forward/backward compatibility concerns?

* Daily workflow expectations (e.g. updating the team on progress, etc)
    * How is progress tracked (e.g. JIRA)?
        * If a board is used, what are the expectations on keeping it up to date / tracking progress?
        * Who handles tickets at different stages? (e.g. is a ticket assigned to a QA person when it reaches QA, then back to the author upon pass/fail?)
    * As we work through a ticket and encounter new information or challenges, what is our expected best practice?
        * Do we re-point when we realize a ticket is bigger than expected, or store expected vs actual?
        * Do we write a new ticket for added/newly discovered scope and link it?
    * What do we do when the build is broken?
    * When do we (and when do we not) make changes to an in-progress release (e.g. hotfixes, changes to an RC, rollbacks, etc)

* Team logistics
    * How do we prefer to communicate status updates outside of standup?
    * How is the team kept informed of time off?
    * Is there an oncall rotation?
    * What are the expectations for monitoring team chat channels (frequency, etc)?
    * How is work distributed
        * How can we expose team members to a variety of code and level of complexity?
        * How do we ensure we don’t create / perpetuate silos?
        * How do we ensure we challenge ourselves / don’t gravitate towards “familiar” work?
    * The team, not an individual, owns the code
        * We share in both our successes and our stumbles

* Handling bugs in production
    * How is triage handled by the team?
    * Who owns investigating a fix, and how is that determined?
        * E.g. oncall? Who owns the code?
    * How are bug fixes deployed, and when do we elect to rush something out vs wait for the next expected release?

* Working with other engineering teams
    * When should other teams know about changes we’re making (i.e. when can we break their stuff)
    * When should other teams know to communicate with us about their changes (i.e. when can they break our stuff?)
    * Are we expected to contribute code to codebases not “owned” by our team? How is this ideally executed?
    * Are other teams expected to contribute code to “our” codebase(s)? How is this ideally executed?

* Working with our peers in PM, UX, QA, etc
    * PM
        * How does prioritization happen?
        * How do we manage team capacity?
        * How do engineers contribute to the roadmap, both “expected” roadmap work, and “engineering focused” work such as tech debt or tooling?
    * UI/UX
        * How do we collaborate with UX during the planning process?
        * How can we best work together when we run into unexpected challenges, questions, etc?
        * What is the “source of truth” for the expected UI/UX?
    * QA
        * How can we best help QA succeed in their role / shift quality left in our process?
        * How do we engage with QA for creating test plans, automation, etc?