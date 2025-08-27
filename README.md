# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

## Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.

## Algorithm:

Select a test scenario: Write a Python program to check whether a number is prime.

Prepare prompts using different prompting strategies:

* **Unstructured**

* **Zero-Shot**

* **Few-Shot**

* **Chain-of-Thought**

* **Role-Based**

Generate responses from the model for each case.

Evaluate outputs on accuracy, detail, and clarity.

Summarize the findings and identify the most effective prompting style.

## Test Scenario & Prompts:
## Unstructured Prompt:
**Prompt:** “Prime program.”<br>
**Output:** Confusing/incomplete statement, no usable code.

## Zero-Shot Prompt:
**Prompt:** “Write a Python program to check if a number is prime or not.”<br>
**Output:** Correct code but no explanation.

## Few-Shot Prompt:
**Prompt:** “Python program to reverse a string:”<br>
**Output:** Learns from the pattern and produces a correct prime-checking program.

## Chain-of-Thought Prompt:
**Prompt:** “Explain step by step how to check prime numbers, then provide Python code.”<br>
**Output:** Gives a detailed explanation of the logic (divisibility test) followed by correct code.

## Role-Based Prompt:
**Prompt:** “You are a Python teacher. Explain and write a program to check prime numbers.”<br>
**Output:** Beginner-friendly explanation with stepwise logic and well-commented code.

## Output:

Unstructured prompts resulted in incomplete outputs, while zero-shot prompts generated correct code without detail. Few-shot prompting improved contextual correctness, chain-of-thought provided structured reasoning plus code, and role-based prompting gave a clear, educational explanation with proper code formatting.

## Result:

The analysis shows that structured prompting methods such as few-shot, chain-of-thought, and role-based approaches consistently deliver higher-quality responses compared to unstructured or plain zero-shot prompts. Prompt engineering therefore enhances both clarity and usefulness of AI-generated outputs.
