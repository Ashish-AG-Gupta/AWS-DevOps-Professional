# AWS-DevOps-Professional
# Code Commit


## Branching

Create branch -> git checkout -b <branch name>  
For Adding new feature, never make changes on the master branch. First create a new feature branch, develop the feature and then merge the feature into the master branch.

Switching to master --> git checkout master

### Security controls  
Don't give permissions to merge code to master brach to all.Create a policy which deny permissions to merge* the code to the master branch.

###  Notifications & Triggers
Notifications can be configured to send SNS Notifications on the different actions.  
Triggers can be used for automation such as invoking Lambda functions.  
CloudWatch events can be also be used for the orchestration of code commit events.
