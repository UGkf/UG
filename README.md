<div align="center">
<!-- logo -->
<p align="center">
  <img src="docs/image/UG-logo.png" width="100px" style="vertical-align:middle;">
</p>

<!-- language -->
[English](README.md) | [简体中文](README_zh-CN.md)
<br>
<br>
🚀<a href="http://ughelper.huiqi-service.cn/#/login">Mold Development Platform → ✅ Online Demo ✅ Full Client ✅ UG Dev Community, Try Now! </a>
</div>

# 📋 Update Log

  2025/07/25 1.1.1 Released
  
- This is the first version update of the mold development platform. The platform has undergone the following updates to improve user experience.:
- Intelligent Question and Answer: 
  - Users can ask questions and seek answers from the full-power Deepseek model on the intelligent question and answer page.
  - Multi-round dialogue: the large model will remember some of your questions.
  - Historical dialogue query: users can also query past records on the intelligent question and answer page.
- Video Upload:
  - Supports users uploading videos for analysis to derive coding ideas.

<details>
  <summary>📚 History Log</summary>
  <details>
    <summary>2025/07/25 1.1.1 Released</summary>
    <ul>
      <li>The intelligent question-and-answer page is now live.</li>
      <li>Update video analysis function.</li>
    </ul>
  </details>
  <details>
    <summary>2025/07/11 1.1.0 Released</summary>
    <ul>
      <li>UG Mold Development Platform officially goes live. </li>
    </ul>
  </details>
</details>

<!-- TABLE OF CONTENT -->
<details open="open">
  <summary><h2 style="display: inline-block">📋 Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#mold-design-development-platform">Mold Design Development Platform</a>
      <ul>
        <li><a href="#project-introduction">Project Introduction</a></li>
        <li><a href="#main-features">Main Features</a></li>
        <li><a href="#quick-start">Quick Start</a>
        </li>
      </ul>
    </li>
    <li><a href="#todo">TODO</a></li>
    <li><a href="#known-issues">Known Issues</a></li>
  </ol>
</details>

# Mold Design Development Platform
## Project Introduction
The Mold Development and Design Platform is an integrated platform that combines UG secondary development code plugin design (generating UG code and performing code compilation) with a UG secondary development community for mold functionality.
<br>
The UG Mold Development Platform was created primarily to enable mechanical engineers, process engineers, and other non-professional programmers to complete simple automation tasks through natural language, while also freeing experienced development engineers from tedious API queries and basic code writing, allowing them to focus on core algorithms and complex logic implementation to improve their work efficiency. The platform combines UG secondary development with large model applications, aiming to streamline UG secondary development engineering tasks.

https://github.com/user-attachments/assets/fb4915f3-fff2-457c-857f-124868948fe0



## Main Features
- Supports user input of requirements, the platform will generate UG secondary development C++ coding ideas that can fulfill user needs based on the requirements (users can modify them).
- Supports generating required UF functions for each step based on the generated coding ideas (users can modify them).
- Supports function information query, users input function names and the platform can retrieve corresponding parameters, function descriptions, and related header files.
- Supports UG secondary development C++ code generation, the platform can generate code that fulfills user requirements based on user-confirmed coding ideas and function information.
- Supports UG secondary development C++ code compilation, users can select their desired NX version for compilation to obtain DLL files.
- Supports users viewing history records, allowing direct navigation to corresponding historical records for coding design.
- Supports users viewing past DLL files, users can directly download previous DLL files.

## Quick Start
[![UG_Demo](https://img.shields.io/badge/UG_Demo-Quick_Start-2196F3?style=flat&logo=desktop&logoColor=white)](http://ughelper.huiqi-service.cn/#/login)

# TODO
- [x] Requirement-to-code generation
- [x] Code compilation with DLL output
- [x] History & DLL library
- [x] Multi-NX version support
- [ ] Video input support
- [ ] NX OPEN-based UG development
- [ ] Intent recognition
- [ ] Plugin requirement parsing

# Known Issues
- **Early Stage Limitations**: Knowledge base is limited, generated coding solutions may be incomplete. Users can modify ideas and functions as needed.
- **Complex Plugin Limitations**: Poor performance on complex plugin designs, generated code may fail to complete certain functional steps.
- **Version Compatibility**: Currently supports only NX10, NX12, NX2306, and NX2406 compilation. DLL files may not work with other NX versions.
