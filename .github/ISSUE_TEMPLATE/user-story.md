---
name: User story
about: Create a new user story based on product requirements.
title: ''
labels: ''
assignees: ''

---

name: User Story
description: Create a new user story based on product requirements.
title: "[User Story] "
labels: ["user story"]
assignees: []

body:
  - type: textarea
    id: description
    attributes:
      label: Description
      description: "Provide a clear and concise description of the feature."
    validations:
      required: true

  - type: textarea
    id: user-story
    attributes:
      label: User Story
      description: "Use the format: 'As a [user], I want to [action], so that [benefit].'"
      placeholder: "As a user, I want to..."
    validations:
      required: true

  - type: textarea
    id: acceptance-criteria
    attributes:
      label: Acceptance Criteria
      description: "Define the conditions under which this story is considered complete."
      placeholder: |
        Given [initial context],
        When [action is taken],
        Then [expected outcome].
    validations:
      required: true

  - type: dropdown
    id: priority
    attributes:
      label: Priority
      description: "Select the priority level for this story."
      options:
        - High
        - Medium
        - Low
    validations:
      required: true

  - type: textarea
    id: additional-notes
    attributes:
      label: Additional Notes
      description: "Add any additional context or information."
