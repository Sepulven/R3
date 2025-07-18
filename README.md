# R3
Implementing a RayTracing algorithm in Java.

1º Commits - The smallest and the core of the versioning system
- One purpose commit.
- A brief but complete description of the changes. Not too long but with enough information.
 SOME RULES REFERENCE:  https://www.bairesdev.com/blog/git-best-practices-2/

- Tag the commit with its right label. (ADD, FIX, REPORT, DOC, PULL, MERGE) 
LABEL REFERENCES:   https://www.conventionalcommits.org/en/v1.0.0/#summary

2º Branching - Individual workspace within the same project
- The main branch is protected and needs a pull request reviews and pass the tests from CI/CD.
- Naming conventions: Lower case, hyphen, prefix with its category, use the ID of the issue in the branch name, if you don't want the branch to be changed by other users add the your name.
 SOME RULES REFERENCE:   https://tilburgsciencehub.com/topics/automation/version-control/advanced-git/naming-git-branches/

3º Testing - Your way to ensure your code works and will not break the whole application.
- All tests must explicitly test the covered domain of the feature as well as its documentation.
- Small internal versioning requires integration test with docker.

4º Documentation - God will not be the only one that understand your code.
- Standard Java Doc, if the class, function, enum, interface and so on requires a contract you must use requires and ensures.
- Be descriptive but brief in your documentation, don't write too much text whereas don't lack important information.

5º Lintering - Make up for your code
- Sonar Qube

6º Build and packages management - 

7º Rule of thumb - 
- This is not a poetry, be descriptive and clear with everything you do!
