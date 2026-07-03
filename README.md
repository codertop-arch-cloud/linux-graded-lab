# Linux Graded Lab Assignment (Modules 1–4)

This repository contains my submissions for the **Linux Graded Lab Assignment**. It is structured in strict compliance with the lab instructions, maintaining separate folders for all five questions and containing command records, outputs, explanations, and screenshot placeholders.

---

## ⚠️ Important Submission Policy
- **Public Visibility**: This repository must be kept **public** to be eligible for grading. Private repositories will not be graded (resulting in a score of 0).
- **conceptual Explanations**: Every Linux command executed in the reports includes a 1–2 sentence explanation detail explaining what the command does and what observations were made during execution.
- **Verification & Outputs**: All reports contain the actual command outputs and placeholders for step-by-step screenshots.

---

## 📂 Repository Structure

Below is the directory mapping of the repository:

```
linux-graded-lab/
├── README.md                           <- Root explanation (this file)
├── Question1/                          <- Linux Environment Verification
│   ├── Environment_Report.txt          <- System details, shell, directory, ping outputs
│   └── screenshots/                    <- Sequentially named screenshots (1.png - 6.png)
├── Question2/                          <- Secure Project Workspace Setup
│   ├── Project_Workspace_Report.txt    <- Workspace permissions, ownership, umask report
│   └── screenshots/                    <- Sequentially named screenshots (1.png - 8.png)
├── Question3/                          <- File System and Link Analysis
│   ├── Link_Analysis_Report.txt        <- Hard/soft links comparison and inode experiment
│   └── screenshots/                    <- Sequentially named screenshots (1.png - 9.png)
├── Question4/                          <- File Access and I/O Investigation
│   ├── IO_Investigation_Report.txt     <- Open files, descriptors, redirects, ulimit report
│   └── screenshots/                    <- Sequentially named screenshots (1.png - 8.png)
└── Question5/                          <- Storage Health Assessment and Documentation
    ├── Storage_Assessment_Report.txt   <- Disk usage, inodes, recommendations (via vi editor)
    └── screenshots/                    <- Sequentially named screenshots (1.png - 10.png)
```

---

## 📝 Folder Summary & Deliverables

### [Question 1: Linux Environment Verification](./Question1/Environment_Report.txt)
- **Objective**: Verify the current user account, groups, active shell, current working directory, workspace files, and network connectivity.
- **Main Deliverable**: `Environment_Report.txt`

### [Question 2: Secure Project Workspace Setup](./Question2/Project_Workspace_Report.txt)
- **Objective**: Set up a secure shared folder structure, configuring appropriate directory and file permissions, ownership settings, and explaining the security implications of `umask`.
- **Main Deliverable**: `Project_Workspace_Report.txt`

### [Question 3: File System and Link Analysis](./Question3/Link_Analysis_Report.txt)
- **Objective**: Create and compare hard links and symbolic (soft) links, analyze inode values, study deletion behaviors, and summarize link mechanics.
- **Main Deliverable**: `Link_Analysis_Report.txt`

### [Question 4: File Access and I/O Investigation](./Question4/IO_Investigation_Report.txt)
- **Objective**: Analyze active file descriptors, identify open files (`lsof`), practice command output/error redirection, check process resource limits (`ulimit`), and outline Linux I/O management.
- **Main Deliverable**: `IO_Investigation_Report.txt`

### [Question 5: Storage Health Assessment and Documentation](./Question5/Storage_Assessment_Report.txt)
- **Objective**: Check disk storage (`df`), inode levels (`df -i`), directory disk usage (`du`), and mounted systems. The report was composed in the `vi` editor to practice basic visual editor operations.
- **Main Deliverable**: `Storage_Assessment_Report.txt`

---

*Note: All screenshots have been successfully captured, sequentially organized, and linked within their respective question reports for final grading.*
