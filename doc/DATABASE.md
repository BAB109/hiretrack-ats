# Database Design

## Tables

### Users

- id
- name
- email
- password

### Jobs

- id
- title
- department
- location
- salary
- description
- status

### Candidates

- id
- name
- email
- phone
- experience
- skills
- resumeUrl

### Applications

- id
- candidateId
- jobId
- status
- appliedDate

## Relationships

User

├── Jobs

├── Candidates

└── Applications

Candidate

↓

Application

↓

Job