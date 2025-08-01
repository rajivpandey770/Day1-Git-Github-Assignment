# Day1 - Git & GitHub Assignment

## Project Overview
This is a practice project to learn Git and GitHub basics.

## Tasks Performed
- Created a new GitHub repository
- Added a README file with Markdown formatting
- Practiced Git commit messages
- Pushed changes using SSH

## Technical Scenario
**Category:** Cluster Management  
**Environment:** Kubernetes v1.23, On-prem bare metal, systemd cgroups  
**Scenario Summary:**  
Node drain stuck indefinitely due to an unresponsive terminating pod.

### What Happened?
A pod with a custom finalizer never completed termination, blocking `kubectl drain`.  
Even after marking the pod for deletion, the API server kept waiting because the finalizer wasn’t removed.

##  Commit Message Examples
- `Initial commit with project setup`
- `Added project description to README.md`
- `Renamed Readme.txt to README.md`
- `Updated scenario and environment section`
