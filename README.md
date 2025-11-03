# GitHub Actions Lab – Bassam Husam

## Workflow1: dependent-jobs.yml

**purpose**
to use needs to run jobs in a spesific order

key concepts:
- needs: makes jobs run in a order rather than in parralell. 
- runs on: sets the runnner enviornment eg. ubuntu-latest
- steps: defines the order of actions in the jobs

description: 
each job prints progress messages and simulates work with sleep comands, this shows dependent workflows and sequential order of jobs. 


## Workflow1: env-and-secrets.yml

**purpose**
to show how enviroment variables are used on the workflow, job, and step levels. also to show how secrets are managed.

key concepts: 
- env: defines enviornment variables with different scopes.
- secrets: stores sensitive information secrely, doesnt show the information in logs.
- workflow_dispatch: manual trigger

description:
this workflow is used to show inheritance and scoping. it prints masked AWS credientials and shows the different workflow, job, and step level variables.

## Workflow1: multi-os-test.yml

**purpose**
this workflow was made to demonstrate running jobs on multipe OS's using different runners.

key concepts:
- runs-on: specifies the operating system eg. ubuntu-latest, windows-latest
- parallel execution: job run at the same time on multiple operating system enviornments

description: 
the workflow runs some echo commands and operations on ubuntu and windows. confirming cross-platform compatibility.


## challenges and resolutions
i ran into a few issues with navigating git's website to spesific information in the workflows for the screen shots. besides that the lab went smoothly.