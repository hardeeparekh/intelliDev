# intelliDev

## Introduction

intelliDev is a comprehensive AI-driven developer productivity tool that continuously monitors a project's file system and terminal history. Integrated directly into the IDE (e.g., VS Code), it provides real-time, context-aware debugging support, code suggestions, and file diffs—all while safeguarding sensitive code via a customizable ignore file.

## Problem Tackled

Developers, especially those learning the ropes, often struggle with managing and debugging large, multi-file projects. Conventional chatbots and debugging tools do not work well for dynamic codebases because they require manual input of code context, making it infeasible to input all files every time a change occurs. intelliDev addresses this challenge by automatically tracking code changes and terminal commands, delivering accurate, context-sensitive insights to streamline debugging and boost productivity.

## Description and Key Ideas

- **Real-Time File Monitoring:**  
  intelliDev continuously tracks changes across the project’s file structure, ensuring the AI always has the most current context for analysis.

- **In-IDE Chatbot Interface:**  
  A built-in chatbot allows developers to query code changes, view file diffs, and receive intelligent debugging suggestions without leaving the IDE.

- **Terminal Assistance:**  
  The tool scans terminal command history to identify Git issues and file errors, providing corrective actions to resolve problems quickly.

- **Sensitive File Filtering:**  
  A customizable ignore file (e.g., `.aiignore`) lets developers exclude sensitive directories or files from AI processing, ensuring data privacy.

By dynamically updating its context with every modification, intelliDev simplifies the debugging process and accelerates development—making it especially valuable for new developers.
