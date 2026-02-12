# GitHub Actions Lab

## Workflow 1 - Dependent Jobs (push to main)
**Purpose:** Demonstrates job dependencies using `needs`.
**Jobs:** build → test → deploy  
**Key concepts:** `on: push`, `runs-on`, `needs`

## Workflow 2 - Multi Platform (pull request to main)
**Purpose:** Runs jobs in parallel on 3 operating systems.
**Jobs:** ubuntu-job, windows-job, macos-job  
**Key concepts:** `on: pull_request`, `runs-on`, `actions/checkout@v4`

## Challenges
- YAML indentation issues: fixed by aligning spacing properly.
- Workflow not triggering: confirmed correct branch/event (push vs pull_request).
