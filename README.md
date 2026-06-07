# AI-Testcase-Generator
An intelligent web-based platform for generating, managing, and evaluating AI/LLM test cases across multiple testing categories.

## Overview

AI Testing Matrix Studio helps QA Engineers, SDETs, AI Testers, and Developers generate structured AI test cases using Large Language Models (LLMs) such as OpenAI GPT and Google Gemini.

The platform automatically creates high-quality test scenarios for different AI testing domains including:

* Prompt Robustness Testing
* Hallucination Testing
* Safety Testing
* Bias Testing
* Context Retention Testing
* Instruction Following Testing
* Adversarial Testing
* Logical Reasoning Testing
* Mathematical Reasoning Testing
* And many more

The generated test cases can be reviewed, executed, tracked, and exported for reporting purposes.

---

## Features

### AI-Powered Test Case Generation

* Generate dynamic test cases using OpenAI or Google Gemini APIs.
* Supports multiple AI testing categories.
* Automatically creates structured prompts and expected outcomes.

### Multi-Provider Support

* OpenAI Integration
* Google Gemini Integration

### Test Management Dashboard

* Total Test Cases Tracking
* Passed Test Cases Tracking
* Failed Test Cases Tracking
* Success Rate Calculation

### Test Case Evaluation

Each generated test case contains:

* Test Case ID
* Testing Type
* Prompt
* Expected Behaviour
* Severity
* Priority
* Actual Result
* Execution Status

### Real-Time Metrics

The dashboard automatically calculates:

* Total Tests
* Passed Tests
* Failed Tests
* Success Percentage

### Export Functionality

* Export generated test cases into CSV format.
* Easy sharing and reporting.

### Interactive Controls

* Category Selection
* Testing Type Selection
* Dynamic Test Count Selection
* API Configuration Panel

---

## Supported AI Testing Categories

| Category              | Examples                             |
| --------------------- | ------------------------------------ |
| Capability Testing    | QA, Summarization, Translation       |
| Quality Testing       | Accuracy, Relevance, Completeness    |
| Safety & Security     | Jailbreak, Prompt Injection, Privacy |
| Context & Memory      | Multi-Turn, Long Context             |
| Reasoning             | Logical and Mathematical Reasoning   |
| Fairness              | Bias and Toxicity Testing            |
| Robustness            | Adversarial and Edge Case Testing    |
| Grounding & Retrieval | Hallucination and Citation Testing   |
| Agent & Tool Use      | Workflow and Tool Testing            |

---

## Technology Stack

### Frontend

* HTML5
* Tailwind CSS
* JavaScript (Vanilla JS)

### APIs

* OpenAI API
* Google Gemini API

### Data Export

* CSV Export

---

## Project Structure

```text
AI-Testing-Matrix-Studio/
│
├── index.html
├── README.md
├── assets/
│   ├── screenshots/
│   └── icons/
│
└── docs/
```

---

## Getting Started

### Prerequisites

* OpenAI API Key OR
* Google Gemini API Key

### Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/AI-Testing-Matrix-Studio.git
```

2. Navigate to the project directory

```bash
cd AI-Testing-Matrix-Studio
```

3. Open the application

```bash
Open index.html in your browser
```

No backend setup is required.

---

## Usage

### Configure API

1. Select Provider

   * OpenAI
   * Google Gemini

2. Enter:

   * API Key
   * Model Name

### Generate Test Cases

1. Select AI Testing Category
2. Select Testing Type
3. Choose Number of Test Cases
4. Click **Generate with AI**

### Execute Tests

1. Run prompts against the target LLM.
2. Capture Actual Results.
3. Mark Status:

   * Pass
   * Fail
   * Blocked

### Export Results

Click **Export CSV** to download the complete test suite.

---

## Dashboard Metrics

The dashboard provides:

* Total Test Cases
* Passed Cases
* Failed Cases
* Success Rate %

These metrics update automatically based on execution status.

---

## Example Use Cases

### AI QA Teams

Generate and manage structured AI validation suites.

### SDET Engineers

Perform automated LLM quality assessments.

### Prompt Engineers

Stress test prompts against edge cases and adversarial inputs.

### AI Product Teams

Validate AI application behavior before release.

---

## Future Enhancements

* Test History Tracking
* Dark Mode
* PDF Export
* Database Integration
* Authentication & User Management
* Automated Execution Engine
* Multi-Model Comparison
* Result Analytics Dashboard
* React Version
* Cloud Deployment

---

## Screenshots

Add screenshots of the application here.

```markdown
![Dashboard](assets/screenshots/dashboard.png)
```

---

## Author

**Omkar Deshpande**

Senior Quality Analyst | Automation Tester | SDET

GitHub: https://github.com/your-username

LinkedIn: https://linkedin.com/in/your-profile

---

## License

This project is licensed under the MIT License.

Feel free to use, modify, and distribute this project.
