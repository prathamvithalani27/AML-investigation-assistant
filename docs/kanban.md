# Our Kanban rules (Jira space: AML)

- Columns: To Do -> In Progress -> In Review -> Done
- WIP limit: max 2 cards in In Progress, max 2 in In Review
- Pull system: when free, pull the highest-priority card from To Do
- Review: the other member checks the work before it moves to Done
- Definition of Done: code on GitHub with card ID + reviewed by the other member
- Blocked card: add a flag in Jira + comment saying what it waits for
- Only modules (epics) have target dates; tasks flow by priority
- Weekly review every Sunday (15 min): what got done, what is stuck, what next
