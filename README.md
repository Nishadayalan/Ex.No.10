# EXP 10: CAPSTONE MINI PROJECT – PROMPT ENGINEERING FOR REAL-WORLD ENGINEERING APPLICATION

## Title

AI Research Assistant Using Prompt Engineering for Engineering Students

## Domain

Artificial Intelligence / AI Engineering

## 1. Aim

To design and develop a prompt engineering solution that uses structured prompts to assist engineering students in research activities such as topic exploration, literature summarization, idea generation, technical writing, comparison of methods, and preparation of research reports.

## 2. Problem Statement

Engineering students spend considerable time searching for information, understanding technical concepts, summarizing research papers, comparing different approaches, and preparing technical documentation.

Traditional search methods often provide large amounts of information without organizing it according to the student's specific requirement.

The proposed system uses prompt engineering to create an AI Research Assistant that can generate structured and relevant responses based on the user's research objective.

The system is designed to support students while keeping human verification as an important part of the research process.

## 3. Objectives

* To design structured prompts for engineering research tasks.
* To generate clear and organized technical responses.
* To summarize technical information using AI.
* To compare different engineering methods or technologies.
* To improve prompts through iterative refinement.
* To evaluate AI-generated outputs for relevance and accuracy.
* To identify ethical issues related to AI-assisted research.
* To demonstrate a practical prompt engineering workflow.

## 4. Proposed Solution

The proposed AI Research Assistant accepts a research requirement from the user and processes it using specially designed prompts.

The workflow consists of:

User Research Requirement
↓
Task Identification
↓
Structured Prompt
↓
AI Processing
↓
Output Generation
↓
Output Evaluation
↓
Prompt Refinement
↓
Final Response

The system can perform tasks such as:

1. Research topic generation
2. Technical concept explanation
3. Literature summarization
4. Technology comparison
5. Research gap identification
6. Report section generation
7. Question generation
8. Research idea evaluation

## 5. Prompt Design

A structured prompt is created using the following components:

* Role
* Context
* Task
* Input
* Constraints
* Output format

### General Prompt Template

```text
Role:
Act as an engineering research assistant.

Context:
The user is an engineering student working on a technical research project.

Task:
Analyze the given research topic and provide useful technical information.

Input:
[Research Topic]

Constraints:
- Use simple technical language.
- Avoid unnecessary information.
- Organize the response using headings.
- Clearly identify assumptions.
- Do not invent research findings or references.

Output Format:
1. Topic Overview
2. Key Concepts
3. Existing Approaches
4. Advantages
5. Limitations
6. Possible Research Directions
```

## 6. Prompt 1 – Research Topic Generation

### Prompt

```text
Act as an AI research assistant for engineering students.

Generate 5 innovative research topics in Artificial Intelligence that can be implemented as student projects.

For each topic provide:
1. Title
2. Problem being addressed
3. Proposed AI approach
4. Expected outcome
5. Possible application

Keep the ideas practical and suitable for an engineering project.
```

### Sample Output

| Topic                                  | AI Approach      | Application          |
| -------------------------------------- | ---------------- | -------------------- |
| AI-Based Energy Consumption Prediction | Machine Learning | Smart Buildings      |
| Predictive Maintenance Assistant       | ML + Sensor Data | Manufacturing        |
| Intelligent Traffic Prediction         | Time-Series ML   | Smart Cities         |
| AI-Based Crop Disease Detection        | Computer Vision  | Agriculture          |
| Automated Technical Document Analyzer  | NLP              | Engineering Research |

## 7. Prompt 2 – Technical Explanation

### Prompt

```text
Act as an AI engineering tutor.

Explain the concept of Transformer Architecture to a final-year engineering student.

Include:
1. Definition
2. Basic architecture
3. Self-attention mechanism
4. Encoder and decoder
5. Applications
6. Advantages
7. Limitations

Use simple technical language and one practical example.
```

### Expected Output

The AI should provide a structured explanation of Transformer architecture with suitable examples instead of producing an unorganized paragraph.

## 8. Prompt 3 – Research Paper Summarization

### Prompt

```text
Act as a research assistant.

Summarize the following technical paper.

Provide:
- Research problem
- Objective
- Methodology
- Dataset or input
- Main findings
- Advantages
- Limitations
- Future work

Do not add information that is not present in the provided paper.

Paper:
[Insert paper content]
```

This prompt reduces unnecessary information and keeps the summary focused on research-related information.

## 9. Prompt 4 – Technology Comparison

### Prompt

```text
Compare Machine Learning and Deep Learning for an engineering application.

Create a table containing:
- Definition
- Data requirement
- Computational requirement
- Training complexity
- Accuracy
- Advantages
- Limitations
- Suitable applications

End with a recommendation explaining when each approach should be preferred.
```

### Expected Output

The AI generates a structured comparison instead of a general explanation.

## 10. Prompt 5 – Research Gap Identification

### Prompt

```text
Act as an engineering research analyst.

Analyze the following research topic:

"AI-based predictive maintenance in manufacturing."

Identify:
1. Existing approaches
2. Common limitations
3. Possible unexplored areas
4. Technical challenges
5. Potential research gaps
6. Possible project ideas

Clearly distinguish between established information and possible research directions.
```

## 11. Prompt 6 – Technical Report Generation

### Prompt

```text
Act as a technical report writing assistant.

Prepare the Introduction section for an engineering project titled:

"AI-Based Predictive Maintenance System."

The section should include:
- Background
- Existing problem
- Need for the system
- Role of AI
- Motivation
- Project objective

Use formal academic language and approximately 300 words.
```

## 12. Prompt Iteration

Prompt iteration is the process of improving a prompt based on the quality of the generated output.

### Initial Prompt

```text
Explain AI in manufacturing.
```

### Problem with Output

The response may be too broad and may include unnecessary information.

### Improved Prompt

```text
Explain the role of Artificial Intelligence in manufacturing for a final-year engineering student.

Cover:
1. Predictive maintenance
2. Quality inspection
3. Production optimization
4. Defect detection

For each application provide one practical example.

Use simple technical language and organize the answer using headings.
```

### Final Prompt

```text
Act as an AI engineering consultant.

Explain how Artificial Intelligence can improve manufacturing operations.

Focus only on:
- Predictive maintenance
- Automated quality inspection
- Production optimization
- Defect detection

For each application provide:
1. Problem
2. AI technique
3. Working principle
4. Practical example
5. Main benefit
6. Limitation

Present the result in a table followed by a short conclusion.

Avoid unsupported claims and clearly mention when an example is illustrative.
```

### Iteration Summary

| Version  | Prompt Quality                     | Result                          |
| -------- | ---------------------------------- | ------------------------------- |
| Prompt 1 | Very general                       | Broad response                  |
| Prompt 2 | Added context                      | More relevant                   |
| Prompt 3 | Added role, constraints and format | Structured and focused response |

## 13. AI Output Evaluation

The generated output is evaluated using the following criteria.

| Evaluation Criteria | Description                                         |
| ------------------- | --------------------------------------------------- |
| Relevance           | Does the answer address the requested task?         |
| Accuracy            | Is the technical information correct?               |
| Completeness        | Are all requested points covered?                   |
| Clarity             | Is the explanation easy to understand?              |
| Structure           | Is the information properly organized?              |
| Consistency         | Does the response follow the prompt?                |
| Hallucination       | Does the AI introduce unsupported information?      |
| Practicality        | Is the information useful for the engineering task? |

### Evaluation Method

Each criterion can be scored from 1 to 5.

1 – Poor
2 – Needs Improvement
3 – Average
4 – Good
5 – Excellent

Example:

| Criterion             | Score |
| --------------------- | ----: |
| Relevance             |     5 |
| Accuracy              |     4 |
| Completeness          |     5 |
| Clarity               |     5 |
| Structure             |     5 |
| Consistency           |     5 |
| Hallucination Control |     4 |
| Practicality          |     5 |

Total Score = 38/40

## 14. Prompt Engineering Techniques Used

### 14.1 Role Prompting

The AI is given a specific role such as:

```text
Act as an engineering research assistant.
```

This helps establish the expected perspective.

### 14.2 Context Setting

Relevant background information is provided before the task.

### 14.3 Task Decomposition

Complex tasks are divided into smaller steps.

### 14.4 Output Formatting

The expected format is explicitly specified.

Examples:

* Table
* Bullet points
* Headings
* Step-by-step explanation

### 14.5 Constraints

Restrictions are added to control the response.

Example:

```text
Do not invent references or research findings.
```

### 14.6 Iterative Refinement

The prompt is improved after evaluating the initial response.

### 14.7 Few-Shot Prompting

Examples can be provided to demonstrate the expected response style.

## 15. Ethical Considerations

AI-assisted engineering research must be used responsibly.

### Accuracy

AI-generated information should be verified using reliable technical sources.

### Academic Integrity

Students should not submit AI-generated work as completely original without proper review and acknowledgement when required.

### Hallucination

AI may generate incorrect technical information or fictional references. Important information must therefore be verified.

### Data Privacy

Confidential project data, personal information, or sensitive institutional information should not be entered into public AI systems without authorization.

### Human Responsibility

AI should assist the researcher rather than completely replace human judgment.

### Bias

AI-generated responses may contain biases based on the data used to train the model.

## 16. Complete Prompt Repository

The project maintains a collection of reusable prompts.

| Prompt ID | Task                  | Purpose                          |
| --------- | --------------------- | -------------------------------- |
| P01       | Topic Generation      | Generate research ideas          |
| P02       | Technical Explanation | Explain engineering concepts     |
| P03       | Paper Summarization   | Summarize research papers        |
| P04       | Comparison            | Compare technologies             |
| P05       | Research Gap          | Identify possible research gaps  |
| P06       | Report Writing        | Generate report sections         |
| P07       | Question Generation   | Generate viva/research questions |
| P08       | Project Evaluation    | Evaluate proposed project ideas  |

## 17. Demonstration

The project can be demonstrated using the following example.

### Input

```text
I want to develop an AI project for manufacturing.
Suggest a practical project idea.
```

### Step 1 – Initial AI Response

The AI provides a general list of manufacturing AI applications.

### Step 2 – Refined Prompt

```text
Act as an AI project mentor.

Suggest one practical AI project for manufacturing that can be completed by final-year engineering students.

Include:
- Problem statement
- Proposed solution
- AI technique
- Required input data
- System workflow
- Expected output
- Advantages
- Limitations

The project should be affordable and suitable for a student-level prototype.
```

### Step 3 – Final Output

Example project:

AI-Based Predictive Maintenance System

Problem:
Unexpected machine failures can interrupt production.

Solution:
Use sensor data such as temperature, vibration and operating time to predict possible machine failures.

AI Technique:
Machine Learning classification or anomaly detection.

Input:
Machine sensor readings.

Output:
Machine condition and possible maintenance alert.

## 18. System Workflow

```text
             USER
               |
               v
      Research Requirement
               |
               v
        Task Identification
               |
               v
       Structured Prompt
               |
               v
          AI MODEL
               |
               v
        Generated Output
               |
               v
        Output Evaluation
          /          \
      Satisfactory   Unsatisfactory
          |               |
          v               v
    Final Output     Prompt Refinement
                          |
                          └──────> AI MODEL
```

## 19. Advantages

* Reduces time spent on initial research.
* Produces structured technical information.
* Supports engineering students during project development.
* Makes complex information easier to understand.
* Provides reusable prompts for different tasks.
* Improves productivity.
* Helps organize technical documentation.

## 20. Limitations

* AI output may contain incorrect information.
* Generated references may require verification.
* AI cannot replace expert engineering judgment.
* Output quality depends heavily on prompt quality.
* Domain-specific information may require additional validation.
* Sensitive information should not be entered into public AI tools.

## 21. Expected Results

The proposed prompt engineering solution successfully demonstrates how structured prompts can improve AI-generated responses for engineering research activities.

Prompt iteration improves the relevance, organization, and completeness of the generated output.

The evaluation process also helps identify inaccurate or unsupported information before the final output is used.

## 22. Future Scope

The AI Research Assistant can be extended to:

* Analyze complete research papers.
* Connect with verified academic databases.
* Generate citation-supported research summaries.
* Create project proposals automatically.
* Assist with literature review.
* Generate experiment plans.
* Support multiple engineering domains.
* Integrate with academic document management systems.
* Provide domain-specific prompt templates.

## 2 Final Presentation Structure

### Slide 1 – Title

AI Research Assistant Using Prompt Engineering

### Slide 2 – Introduction

* What is Prompt Engineering?
* Need for structured AI interaction

### Slide 3 – Problem Statement

* Difficulty in engineering research
* Time-consuming information processing

### Slide 4 – Objectives

* Research assistance
* Structured information generation
* Prompt refinement
* Output evaluation

### Slide 5 – Proposed Solution

AI-powered research assistant using structured prompts.

### Slide 6 – System Workflow

User → Prompt → AI → Evaluation → Refinement → Final Output

### Slide 7 – Prompt Design

Role + Context + Task + Constraints + Output Format

### Slide 8 – Prompt Examples

Show P01, P03 and P05.

### Slide 9 – Prompt Iteration

Initial prompt → Improved prompt → Final prompt

### Slide 10 – Output Evaluation

Relevance, accuracy, completeness, clarity and hallucination control.

### Slide 11 – Ethical Considerations

* Accuracy
* Privacy
* Academic integrity
* Bias
* Human verification

### Slide 12 – Demonstration

Show an actual prompt and AI-generated response.

### Slide 13 – Results

* Better structured responses
* Reduced manual effort
* Improved consistency

### Slide 14 – Advantages and Limitations

### Slide 15 – Future Scope

### Slide 16 – Conclusion

## Conclusion

Prompt engineering provides an effective method for using AI in real-world engineering applications.

The AI Research Assistant developed in this project demonstrates how role definition, context, task instructions, constraints, output formatting and prompt iteration can improve the quality of AI-generated results.

The project also shows that AI outputs should be evaluated for accuracy, relevance and reliability before they are used in engineering or academic work.

Therefore, prompt engineering can act as a practical bridge between generative AI and engineering problem-solving while keeping human verification and ethical use at the center of the process.
