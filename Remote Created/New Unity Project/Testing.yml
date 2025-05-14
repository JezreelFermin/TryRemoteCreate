name: Test Case
description: Document a manual test case for a feature
title: "[TEST]: <Insert Test Case Title>"
labels: [test-case]
body:
  - type: input
    id: test-id
    attributes:
      label: Test Case ID
      placeholder: e.g. TC-001

  - type: input
    id: feature
    attributes:
      label: Feature/Module
      placeholder: e.g. Login System

  - type: textarea
    id: preconditions
    attributes:
      label: Preconditions
      placeholder: e.g. User must be registered and logged out

  - type: textarea
    id: steps
    attributes:
      label: Steps to Execute
      placeholder: |
        1. Navigate to login page
        2. Enter username and password
        3. Click login

  - type: textarea
    id: expected
    attributes:
      label: Expected Result
      placeholder: e.g. User should be redirected to the dashboard

  - type: dropdown
    id: status
    attributes:
      label: Execution Status
      options:
        - Pass
        - Fail
        - Blocked
        - Not Applicable

  - type: input
    id: actual-result
    attributes:
      label: Actual Result (fill after testing)
      placeholder: Describe what actually happened

  - type: input
    id: bug-reference
    attributes:
      label: Linked Bug ID (if any)
      placeholder: e.g. #42

  - type: input
    id: tester
    attributes:
      label: Tested By
      placeholder: e.g. Jane Doe

  - type: input
    id: date
    attributes:
      label: Test Date
      placeholder: YYYY-MM-DD
