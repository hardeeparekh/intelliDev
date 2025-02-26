# intelliDev

## Introduction

intelliDev is a comprehensive AI-driven developer productivity tool that continuously monitors a project's file system and terminal history. Integrated directly into your IDE (e.g., VS Code), it offers real-time, context-aware debugging support, code suggestions, and file diffs—all while safeguarding sensitive code via a customizable ignore file.

## Core Challenges Addressed

- **Complexity in Large Projects:**  
  Developers, especially those in the learning phase, struggle to manage and debug projects with many files.

- **Manual Context Input:**  
  Conventional debugging tools require manual input of code context, which is impractical for dynamic codebases.

- **Tracking Modifications:**  
  Keeping track of changes across multiple files is challenging and error-prone.

- **Need for Automation:**  
  There is a need for a solution that automatically monitors file changes and terminal commands to provide accurate, context-sensitive debugging insights.

## Description and Key Ideas

- **Real-Time File Monitoring:**  
  intelliDev continuously tracks changes across the project’s file structure, ensuring the AI has up-to-date context.

- **In-IDE Chatbot Interface:**  
  A built-in chatbot allows developers to query code changes, view file diffs, and receive intelligent debugging suggestions directly within the IDE.

- **Terminal Assistance:**  
  The tool analyzes terminal command history to detect Git issues and code errors, offering corrective suggestions.

- **Sensitive File Filtering:**  
  A customizable ignore file (e.g., `.aiignore`) lets developers exclude sensitive directories or files from processing, ensuring data privacy.

By dynamically updating its context with every modification, intelliDev simplifies the debugging process and accelerates development, making it especially beneficial for new developers.

## Technologies

- **Frontend (VS Code Extension):**  
  - **Languages:** TypeScript, JavaScript  
  - **APIs/Libraries:** VS Code Extension API, Chokidar (for real-time file monitoring)

- **Backend (AI & Terminal Assistant):**  
  - **Language:** Python  
  - **Libraries:** Python-based AI and NLP frameworks, logging libraries

- **Sensitive File Filtering:**  
  - Utilizes a customizable ignore file (`.aiignore`) to exclude specified files and ensure data privacy.

## Conclusion

intelliDev is designed to enhance developer productivity by delivering real-time, context-sensitive debugging support and code insights while maintaining data security. This streamlined approach to code management is a valuable asset for developers of all skill levels.
