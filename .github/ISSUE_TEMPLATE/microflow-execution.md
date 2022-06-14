---
name: Microflow execution
about: Execute the migrate workflow on a repository.
title: Microflow execution for the project user/projectname
labels: microflow-start
assignees: ''
body:
  - type: markdown
    attributes:
      value: |
        With this issue creation, you are going to execute the whole flow in the input project
  - type: input
    attributes:
      label: GitHub Repository
      description: |
        user/projectname of the GitHub repository.
      placeholder: |
        example-user/project-name
    validations:
      required: true
  - type: dropdown
    attributes:
      label: Java version used in the project
      options:
        - jdk-8
        - jdk-11
    validations:
      required: true
---


