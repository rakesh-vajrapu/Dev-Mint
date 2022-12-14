---
name: Bug Report
about: This template will help in creating a bug report for the project
title: ''
labels: ''
assignees: ''

---

name: Bug Report
description: Report a bug you found
title: "[Bug Project Title here] "
labels: "bug"
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
        
Define You:

- [ ] Code Peak Participant 
- [ ] Contributor

Your Full Name : 
Category/Repo It Belongs To : 

  - type: textarea #description
    attributes:
      label: What happened?
      description: Also tell us, what did you expect to happen?
      placeholder: Tell us what you see!
    validations:
      required: true

  - type: textarea #reproduce
    attributes:
      label: How can we reproduce this bug?
      description: Are there any specific steps you had to take in order to trigger the bug, and what is the expected behaviour we should expect?
      placeholder: Kindly elaborate.
    validations:
      required: true

  - type: textarea #desktop info
    attributes:
      label: Desktop Information (Optional)
      description: Please provide the desktop configuration (OS,Browser, dependency version etc)
      placeholder: Type here.

  - type: dropdown #urgent
    attributes:
      label: Urgency (Optional)
      description: How urgent do you think it is to fix this bug?
      options:
        - Low priority
        - Medium priority
        - High priority