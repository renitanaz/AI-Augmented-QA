# Setup + First AI Output

## GOAL
-  Create GITHUB REPO
-  Setup teh folder structure
-  First AI-generated QA test cases
-  First entries into md files created
-  First GITHUB commit

## Setting up 

### 1. Create repo in github
```
qa-ai-playground
```


### 2. Create structure
```
/phase-1-ui-ai/
  claude.md
  prompts.md
  learning-log.md
  agents.md
```
### claude.md : Controls AI behavior
-  Our "system prompt" for Claude — how we want Claude to behave when helping with QA tasks.
-  Why? It reduces inconsistency and standardizes output quality.

Add the below into the md file:
```
# Role
You are a senior QA engineer with strong experience in test design.

# Expectations
- Generate practical, real-world test cases
- Avoid generic answers
- Include edge cases and negative scenarios

# QA Mindset
- Think like a tester
- Focus on failure scenarios
- Be specific
```

### prompts.md : Improves AI output over time
-  Actual prompts we will use for test case generation, with observations on what worked/didn't.
```
## Test Case Generation v1

Prompt:
You are a senior QA engineer.

Generate:
1. Functional test cases
2. Negative test cases
3. Edge cases

For:
Login feature with username and password

Observation:
- Covers basic scenarios
- Missing deep edge cases
- Some steps are generic
```

### learning-log : 
-  We are using this to track our learning. i.e. Skills we are developing (both QA and AI skills).

```
## Day 1

### QA Skills
- Writing basic test cases
- Understanding functional scenarios

### AI (Claude)
- Generated test cases using AI
- Observed generic outputs
```

### agents.md :Reusable QA workflows

-   Simple reusable “mini-systems   
```
## Agent: Test Case Generator (Initial)

Input:
Requirement

Prompt:
Generate functional, negative, and edge test cases

Output:
List of test cases

Note:
Needs improvement for edge cases
```
