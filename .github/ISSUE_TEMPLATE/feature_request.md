---
name: Feature request
about: Suggest a new feature
title: ''
labels: ''
assignees: ''

---

---
name: Feature Request
description: Suggest a new idea
title: "Feature: "
labels: ["enhancement"]
body:
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: What is your name?
      placeholder: ex. Sertha Taweewattana
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: dropdown
    id: request_type
    attributes:
      label: Type of request?
      description: Select the type of your request
      options:
        - New Feature
        - Improvement
  - type: dropdown
    id: os_type
    attributes:
      label: What is the OS which you want to suggest?
      options:
        - Windows
        - Linux
        - MacOS
  - type: textarea
    id: suggestions
    attributes:
      label: What are the details of your suggestion?
      description: Explain what do you want
      placeholder: Feature details!
---
