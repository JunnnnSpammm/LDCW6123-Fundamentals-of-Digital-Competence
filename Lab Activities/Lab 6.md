## Identify 3 challenges the company might face using only CVCS.

1. Since there is only one central repository that all developers commit to, if the central server goes down, no one can commit changes, update their code, view history, or collaborate.
2. Developers must be connected to the network, either local, via VPN or internet, to perform most common version control operations, such as committing, viewing full history, branching or merging.
3. The merging process can also be more cumbersome and prone to conflicts compared to DVCS, especially when merging long-lived branches, making continuous integration and rapid iteration more difficult.

## Suggest 3 solutions showing how DVCS could overcome these challenges.

1. In DVCS, every developer's local machine has a complete copy of the project's repository, including its full history. If the main remote server fails, developers can still commit locally, review history, and even exchange changes directly with a peer's repository until the central server is restored.
2. Because the entire repository, including the full history is local, developers can perform nearly all major version control operations without an internet connection, such as committing changes, viewing the complete project history, branching and merging features or reverting and inspecting past states.
3. In DVCS, a branch is simply a lightweight pointer to a commit, making it an instantaneous, local operation that requires minimal disk space. This encourages developers to use a "branch-per-feature" or "branch-per-fix" workflow, promoting feature isolation and eliminating the risk of breaking the main line of development.

## Create a comparison table showing advantages and disadvantages of CVCS vs DVCS.

|   Centralized Version Control Systems   (CVCS)            |   Distributed Version Control Systems   (DVCS)                 |
|-----------------------------------------------------------|----------------------------------------------------------------|
|   One central repository that all developers commit to    |   Every developer has a copy of the project’s repository       |
|   Cannot commit changes if central server is down         |   Able to commit changes without the need of central server    |
|   Need to be connected to the network                     |   Doesn’t need network connection                              |
|   Hard and costly branching and merging process           |   Easy branching and merging process                           |
|   Prone to main branch breaking                           |   Main branch won’t have risk of breaking                      |

## Write a short recommendation report on which system is better for the company and why.

Distributed Version Control Systems (DVCS) is better for the company. Firstly, every
developer has a copy of the project's repository. Developers can still commit locally, review history
without the need of a central server. This is a contrast to CVCS because it required a central server
to commit changes. Furthermore, DVCS doesn’t need network connection. Thus, allowing
developer to code while on-the-go. This cannot be done in CVCS because it requires a connection
to the network. Finally, DVCS provide easy branching and merging process, encouraging
developers to use a "branch-per-feature" or "branch-per-fix" workflow, promoting feature isolation
and eliminating the risk of breaking the main line of development. On the other hand, CVCS has
more cumbersome branching and merging process, and it is prone to conflicts.
