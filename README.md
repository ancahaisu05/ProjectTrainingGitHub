# Simple README.md structure for VS Code Business Central projects
# Client Name
    ex: Millenium, Redoxim, NHR etx.
# Project Name
    Proiect Training Git
another example: Millenium Feature, MagnaPharmRoBuild etc
# Simple Description of the extension/project
    This project show how to use the standard Git Command and GitHub Repository.
    Commands in Git
        1. create repostories: git init
        2. make changes: git add
                         git commit
                         git status
        3. sync repository: git push
                            git pull
                            git add origin
        4. parallel development: git branch
                                 git merge
                                 git rebase
# Version and compatibility
-    **Business Central Version**: v0.0.0
-    **RunTime**: 0.0

# Implement Type: SaaS / On‑Premises

- **SaaS**: Da / Nu  
- **On‑Premises**: Da / Nu 

# Dependencies
    ex: Base Application vx.x.x
        Financial vx.x.x
        Operational vx.x.x
    etc.
# Project structure
    - .alpackages
    - .snapshots
    - .vscode - .alcache
              - launch.json
    - MainApp - .alpackages
              - .snapshots
              - .vscode - .alcache
                        - launch.json
                        - etc.
              - src - NewCustomizedObjects - Tables
                                           - Pages
                                           - Codeunits
                                           - Enums
                                           - Interfaces
                                           - Profiles
                                           - Queries
                                           - Reports - ReportsLayouts
                                           - XMLPorts
                                           
                    - ExtendedObject - Table
                                     - Pages
                                     - Reports
                                     - Enums
                                     - Codeunits etc.
    - TestApp - same structure as MainApp 
    - .gitignore
    - app.json
    - README.md

# Clone and Run
**GitHub URL for clone project**: https://github.com/ancahaisu05/ProjectTrainingGitHub.git
**Run**: Ctrl+F5 -> Run for dev
         Extension Management -> Install Extension -> Run for test


# Workflow
- New branches will be created only from branch **master**/ New branches will be created only with **go-task NoTask** command.
- Branch **uat** is used for test environment.
- Branch **release** is user for production environmnent.

- All the unnecessary branches will be deleted - locally with command **git -d branch NameBranch**
                                             - on remote with command **git push origin --delete Blr_Branch**

