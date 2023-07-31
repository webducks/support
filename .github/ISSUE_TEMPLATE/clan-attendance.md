---
name: Clan Attendance
about: Clan Attendance request issue template
title: ''
labels: clan attendance
assignees: eymeen

---

name: Candidate Evaluation

about: Please answer the following questions to help us evaluate your qualifications.

title: "[Candidate Name]: Application"

labels:
  - Application

body:
  - type: input
    id: years_of_experience
    attributes:
      label: How many years of professional work experience do you have?
      description: Please provide the number of years of your professional experience.
      required: true

  - type: input
    id: role
    attributes:
      label: What is your role? (e.g., MEVN fullstack web developer)
      description: Please specify your current or desired role.
      required: true

  - type: input
    id: problem_solving_skills
    attributes:
      label: How do you rate your problem-solving skills? (1-10)
      description: Please rate your problem-solving abilities on a scale from 1 to 10.
      required: true

  - type: input
    id: scripting_algorithms_skills
    attributes:
      label: How do you rate your scripting and algorithms skills? (1-10)
      description: Please rate your scripting and algorithms skills on a scale from 1 to 10.
      required: true

  - type: input
    id: data_structures_skills
    attributes:
      label: How do you rate your data structures skills? (1-10)
      description: Please rate your data structures knowledge on a scale from 1 to 10.
      required: true

  - type: checkboxes
    id: programming_languages
    attributes:
      label: Do you know any of the following programming languages?
      description: Select all that apply.
      options:
        - JavaScript
        - Python
        - C
        - PHP
        - SQL
        - Scala
      required: true

  - type: radio
    id: cybersecurity_comfort
    attributes:
      label: Are you comfortable with hacking/cybersecurity?
      description: Please select the option that best represents your comfort level.
      options:
        - Yes
        - No
      required: true

  - type: textarea
    id: benefit_to_clan
    attributes:
      label: How do you think you can benefit this clan?
      description: Please describe how you believe you can contribute to the clan.
      required: true

  - type: input
    id: discord_username
    attributes:
      label: Your Discord Username
      description: Please provide your Discord username to contact you if necessary.
      required: true

  - type: textarea
    id: other_messages
    attributes:
      label: Any other messages? (optional)
      description: If you have any additional information or messages, feel free to include them here.
      required: false
