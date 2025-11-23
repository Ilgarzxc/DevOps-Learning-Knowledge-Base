# Git Branching Strategies
## Main-Only Strategy
The main branch is the only branch used for development and deployment. 
All changes are commited directly to it.
![Main-Only Strategy](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Ffbrbhaga1k2218xj77bj.png)
## Feature Branching
Each feature or bug fix is developed in its own branch. Developers should follow the best practices such as regularly merging changes from the
main branch into the feature branch to keep it updated and prevent merge conflicts.
Once the feature or fix is complete and thoroughly tested, the branch is merged into the main branch.
![Feature Branching](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fmufdlg3q1xj9tbzv0geg.png)
## Gitflow
Gitflow is a structured branching strategy that uses multiple branches like main, develop, feature, release and hotfix.
Branch naming conventions play a crucial role in maintaining clarity and consistency.
![GitFlow](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Ff3xopzq3pjvrewt7thmq.png)
## GitHub Flow
GitHub flow is a simplified strategy focused on CD (Continuous Delivery). 
To maintain consistency, teams can adopt a branch naming convention such as /{{author}}/{{short-description}}.
This ensures clarity while keeping the approach straightforward. Developers create feature branches, merge them into the main branch, and deploy immediately.
![Github Flow](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Feq6kfa8nky3nbybdbwxp.png)
## Trunk-Based Development
In trunk-based development, all developers commit directly to the main branch or use short-lived branches that are merged quickly.
For short-lived branches, a naming convention like /fix/{{bug-id}} can help maintain clarity and traceability during rapid iterations.
![Trunk-Based Development](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2F3iun0sd72b8inc5sf22n.png)
## Release Branching
Separate brances are maintainted for each release version, often labeled with version numbers.
![Release Branching](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fhnez4qml7p3decx9209q.png)
