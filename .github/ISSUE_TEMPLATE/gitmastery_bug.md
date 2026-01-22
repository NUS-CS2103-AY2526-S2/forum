---
name: "\U0001F41D Git-Mastery Bug report"
description: File a bug report with the Git-Mastery team
title: "[Git-Mastery] "
labels:
  - 'type-Bug :bee:'
assignees:
  - NUS-CS2103-AY2526-S2/git-mastery-team
type: Bug
body:
  - type: markdown
    attributes:
      value: |
        # Git-Mastery Bug report

        You are currently filing a bug report with Git-Mastery. (Team: @NUS-CS2103-AY2526-S2/git-mastery-team)
  - type: textarea
    attributes:
      label: Describe the bug
      description: Provide a clear and concise description of what the bug is. If applicable, share screenshots and the error message to help explain your problem.
      placeholder: |
        Include any errors as text as well.
    validations:
      required: true
  - type: textarea
    attributes:
      label: Steps to reproduce
      description: What are the steps to reproduce the bug?
      placeholder: |
        1. Go to '...'
        2. Click on '....'
        3. Scroll down to '....'
        4. See error
    validations:
      required: true
  - type: textarea
    attributes:
      label: Expected behavior
      description: A clear and concise description of what you expected to happen. Omit if unknown
    validations:
      required: false
  - type: textarea
    attributes:
      label: Upload log file
      description: |
        Please upload the `.gitmastery.log` file found in the root of your Git-Mastery exercises folder.

        Use `ls -la` to show hidden files.
    validations:
      required: false
  - type: dropdown
    attributes:
      label: Operating system
      options:
        - Windows
        - MacOS
        - Linux (specify below under Version)
    validations:
      required: true
  - type: input
    attributes:
      label: Operating system version
      description: Name of your operating system version. If you are using Linux, include the name of your distro here as well.
    validations:
      required: true
  - type: dropdown
    attributes:
      label: System architecture
      options:
        - amd64/x86_64
        - arm64
    validations:
      required: true
  - type: textarea
    attributes:
      label: Additional information
      description: Additional questions that can help speed up the triaging process.
      value: |
        - Terminal (e.g. Git Bash/WSL/Alacritty): 
        - Git version (using `git --version`): 
        - Github CLI version (if installed, `gh --version`): 
        - Git-Mastery CLI version (using `gitmastery version`):
        - Are you using SSH or HTTPS (if you have setup Github CLI):
        - Any other comments?
  - type: markdown
    attributes:
      value: |
        # Next steps

        The Git-Mastery team will review the issue and respond accordingly.
---