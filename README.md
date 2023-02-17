# cs_gitflow-workflow
This is to demonstrate the GITFLOW workflow for a case study.

Gitflow Architecture:
The overall flow of Gitflow is: -
•	A develop branch is created from main
•	Feature branches are created from develop
•	When a feature is complete it is merged into the develop branch
•	A release branch is created from develop
•	When the release branch is done it is merged into develop and main
•	If an issue in main is detected, a hotfix branch is created from main
•	Once the hotfix is complete it is merged to both develop and main
