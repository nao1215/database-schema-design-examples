[[日本語]](./ja/README.md)

## Database Schema Design Examples
This repository aims to provide examples of database schema designs. By using realistic systems as subjects, it organizes the requirements to be considered in implementing those systems and presents examples of database schema designs based on those requirements. As part of the repository author's (@nao1215) database learning, we welcome Pull Requests and Issues.
  
Since the repository manager's first language is Japanese, the initial design will be created in Japanese and then translated into English using machine translation.

## List of Designs
| System Name | Design |
|:---|:---|
| TBD | TBD |

## Contributing
- We welcome your support through GitHub Star and GitHub Sponsors.
- If you have any comments on the designs presented in this repository, please create an Issue.
- If you would like to provide a new example of a database schema design, please create a Pull Request. Please follow the contents described below for the directory structure and README.md template.

### Directory Structure
Create a directory for each system you want to use as a subject and place the following files in it.

| File | Description |
|:---|:---|
| README.md | A file that describes the requirements and database design of the system. The ER diagram is described in mermaid. |
| schema.sql | A file that describes the DDL of the database schema (MySQL compliant) |
| *.drawio | Files created with draw.io that are necessary to describe the requirements of the system |
| *.png | Image files of the diagrams created with draw.io |

### README.md Template
```markdown
## System Overview

Describe an overview of the service

## Requirements

Describe the requirements for implementing the service

## ER Diagram

Describe the ER diagram described in mermaid

## Design Intent

Describe the design intent of the database schema design
```

