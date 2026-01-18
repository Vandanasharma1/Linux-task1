# Linux-task1
Basics of Linux

project:
  name: Linux Basics Command Documentation
  description: >
    A hands-on Linux fundamentals project demonstrating
    terminal navigation, file management, permissions,
    system monitoring, and command logging on Ubuntu Linux.
  version: 1.0.0
  license: MIT

author:
  role: Intern / Learner
  platform: Linux (Ubuntu)
  access_methods:
    - Local Installation
    - Virtual Machine
    - WSL (Windows Subsystem for Linux)

environment:
  operating_system: Ubuntu Linux
  interface: Terminal
  shell: bash

objectives:
  - Learn basic Linux terminal commands
  - Understand Linux directory structure
  - Manage files and directories safely
  - Edit and view files using terminal editors
  - Understand file permissions and ownership
  - Monitor system resources
  - Maintain command execution logs

commands_covered:
  navigation:
    - pwd
    - ls
    - ls -l
    - cd

  directory_structure:
    - /
    - /home
    - /etc
    - /var

  file_management:
    - mkdir
    - touch
    - rm
    - rmdir

  file_viewing_and_editing:
    - cat
    - less
    - nano
    - vim

  permissions_and_ownership:
    - chmod
    - chown
    - ls -l

  system_monitoring:
    - top
    - htop
    - df -h
    - free -m

  logging:
    - history
    - history > command_log.txt

deliverables:
  documentation:
    - Linux_Basics_Documentation.pdf
  logs:
    - command_log.txt
  screenshots:
    description: Terminal execution proof
    location: screenshots/
  readme_formats:
    - README.md
    - README.yaml

expected_outcome:
  - Ability to navigate Linux systems confidently
  - Practical understanding of core Linux commands
  - Readiness for entry-level Linux or DevOps tasks

notes:
  warnings:
    - Avoid using rm -rf without understanding its impact
    - Practice commands before claiming proficiency
  recommendation:
    - Repeat commands daily for at least one week
    - Understand outputs instead of memorizing syntax

