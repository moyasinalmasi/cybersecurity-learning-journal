# Weekly Learning Logs

This directory contains sanitized weekly summaries from my six-month web security and bug bounty learning journey.

Each weekly log documents:

- The main vulnerability topic
- Important prerequisites
- Class and methodology analysis
- Labs and legal training boxes
- Authorized real-world practice
- Key lessons and mistakes
- Time spent on different activities
- Remaining knowledge gaps
- The plan for the following week

## Directory Structure

Weekly logs are organized by month:

```text
weekly-logs/
├── month-01/
│   ├── week-01-[topic].md
│   ├── week-02-[topic].md
│   ├── week-03-[topic].md
│   └── week-04-[topic].md
├── month-02/
├── month-03/
├── month-04/
├── month-05/
└── month-06/
```

Example:

```text
weekly-logs/month-01/week-01-xss.md
weekly-logs/month-01/week-02-sqli.md
```

## Weekly Workflow

At the beginning of each week:

1. Copy `templates/weekly-log-template.md`.
2. Create a new file in the appropriate monthly directory.
3. Add the weekly topic to the filename.
4. Complete the document gradually during the week.
5. Review and finalize it at the end of the week.

## Publication Rules

Published weekly logs must not contain:

- Real authentication tokens or cookies
- Personal or customer information
- Private program assets
- Undisclosed endpoints
- Active vulnerability details
- Unredacted HTTP requests
- Confidential screenshots
- Information prohibited by a program’s disclosure policy

Real programs should be anonymized using names such as:

```text
Program-A
Program-B
```

## Documentation Standard

Weekly logs should focus on:

- Understanding the vulnerability’s root cause
- Explaining the testing methodology
- Recording mistakes and improvements
- Measuring practical progress
- Demonstrating ethical testing practices

The purpose of these logs is to show consistent, structured skill development rather than simply listing completed activities.
