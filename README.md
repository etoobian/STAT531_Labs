# STAT 531 — Ethics & Practice of Data Science  
## Team Labs Repository: **TECK Squad**

This repository contains:

- Lab assignments
- Team documents (Charter, Workflow, PR checklist, Check-in log template)    

**Important:**  
This repo does **NOT** contain datasets, nor should any data files be committed.  
All data must be stored **locally** by team members following the structure described below.

---

# Repository Structure
```
README.md                       # Currently document

Lab01_Collab/
│
└── Lab01_TeamCollabSetup.md    # Lab 1

Lab02_Collab/
│
└── Lab01_DataMinipVis.md       # Lab 2

TeamDocuments/
│
├── TeamCharter.md              # Copy of team charter for reference
│
├── GitWorkflow.md              # Detailed instructions & notes on Git Workflow
│
├── PR_Checklist.md             # List of checks prior to each pull request
│
└── TeamCheckInTeamplate.md     # Template for team check-in meeeting notetaker
```

# Expected Local Structure

**DO NOT COMMIT DATA TO THIS REPO**

Instead, create a local directory. Rather than use our project's `data_io.R` scripts, we will simply add the appropriate lines of code to each lab which needs to access the data. Please add the data from the class's Canvas page into a local directory as shown below:

```
README.md                       # Currently document

Lab01_Collab/
│
└── Lab01_TeamCollabSetup.md    # Lab 1

Lab02_Collab/
│
└── Lab01_DataMinipVis.md       # Lab 2

Data/
│
├── bids_data_vDTR.parquet      # Project data .parquet file
│
└── data_dictionary.md          # Data dictionary for project data

TeamDocuments/
│
├── TeamCharter.md              # Copy of team charter for reference
│
├── GitWorkflow.md              # Detailed instructions & notes on Git Workflow
│
├── PR_Checklist.md             # List of checks prior to each pull request
│
└── TeamCheckInTeamplate.md     # Template for team check-in meeeting notetaker
```