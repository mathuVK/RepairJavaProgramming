# Automated Program Repair with GPT-3.5 Turbo and Magicoder

This project is designed to automatically repair incorrect code solutions using two AI models: GPT-3.5 Turbo and Magicoder. The project was developed as part of a programming repair assignment, focusing on providing accurate and efficient bug fixes and suggestions.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project is an implementation of an automated program repair system using two models:
1. **GPT-3.5 Turbo** - This model is responsible for providing suggestions to resolve incorrect solutions. It takes the following inputs:
   - Error details
   - Trigger test cases
   - Incorrect code solution

2. **Magicoder (Hugging Face Open-Source Model)** - This model generates patches to fix the buggy code based on the inputs and suggestions provided by GPT-3.5 Turbo. The system uses a few-shot learning algorithm to repair the code effectively.

## Features
- **Automated Suggestions:** GPT-3.5 Turbo provides detailed suggestions for fixing bugs.
- **Patch Generation:** Magicoder generates code patches to repair buggy solutions.
- **Few-Shot Learning:** Employs few-shot algorithms to enhance repair accuracy.

## Installation
To use this project, clone the repository and install the necessary dependencies.

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
