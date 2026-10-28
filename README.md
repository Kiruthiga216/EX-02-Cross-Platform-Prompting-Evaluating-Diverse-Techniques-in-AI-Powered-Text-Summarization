# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## Name: Kiruthiga.B

## Reg.no : 212224040160

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm

Step 1: Select a 500-word technical article explaining blockchain technology, distributed ledgers, blocks, cryptographic hashing, consensus mechanisms, and applications.

Step 2: Select AI platforms such as ChatGPT, Gemini, Claude, and Microsoft Copilot for the experiment.

Step 3: Prepare zero-shot, few-shot, chain-of-thought-style, and role-based prompts for summarization.

Step 4: Submit the same article to each AI platform using each prompting technique.

Step 5: Generate summaries with consistent length, accuracy, and readability requirements.

Step 6: Evaluate each summary based on accuracy, coherence, simplicity, speed, and user experience.

Step 7: Record the evaluation scores and generation times in a comparison table.

Step 8: Compare the results to identify the most effective combination of AI platform and prompting technique.

## Prompt

```
Act as an AI research and educational experiment assistant. Prepare a detailed answer for the experiment titled “Cross-Platform Prompting — Evaluating Diverse Techniques in AI-Powered Text Summarization.”

Follow the given AIM and scenario: summarize a 500-word technical article on “The Basics of Blockchain Technology” for undergraduate students using ChatGPT, Gemini, Claude, and Microsoft Copilot. Compare zero-shot, few-shot, chain-of-thought-style, and role-based prompting techniques.

Write the answer with these sections:

1. Algorithm — provide numbered steps, with each step explained in one line.
2. Answer in Detail — explain the introduction, each prompting technique with examples, AI platforms, evaluation criteria, comparison table, and experimental analysis.


Use clear, student-friendly language, suitable for a college practical record. Include tables where useful. Do not invent experimental scores, generation times, or results that have not been measured. Distinguish expected observations from actual experimental findings.
```

## Output

### 1. Introduction

AI-powered text summarization uses artificial intelligence and natural language processing to shorten lengthy documents while preserving their important information. It helps students understand research papers and technical articles quickly without reading the entire document.

Prompting techniques influence how an AI model understands instructions and generates summaries. This experiment evaluates four prompting techniques across multiple AI platforms to determine which approach is most suitable for summarizing blockchain technology for undergraduate students.

### 2. Prompting Techniques

#### a) Zero-Shot Prompting

Zero-shot prompting asks the AI model to perform a task without providing examples. The model relies on its existing language capabilities and the instructions supplied by the user.

Example: “Summarize the following article about blockchain technology in 150 words using simple language. Include the main concepts, advantages, and applications.”

#### b) Few-Shot Prompting

Few-shot prompting provides one or more examples of the desired output before asking the model to perform the task. This helps the model follow a particular format and style.

Example: “Example: Input—Artificial intelligence enables machines to perform tasks that normally require human intelligence. Output—AI allows machines to perform human-like intelligent tasks. Now summarize the given blockchain article in the same concise style, covering its definition, working process, benefits, and applications.”

#### c) Chain-of-Thought-Style Prompting

This technique encourages the model to consider the important concepts and relationships in the article before producing a final summary. For this experiment, the prompt requests a careful analysis and a concise answer rather than asking the model to disclose private internal reasoning.

Example: “Carefully examine the article, identify its central idea and key supporting concepts, and check that the summary preserves the important technical facts. Then provide a clear 150-word summary of blockchain technology for undergraduate students.”

#### d) Role-Based Prompting

Role-based prompting assigns a specific role to the AI model to guide its tone, vocabulary, and presentation.

Example: “Act as an educational content editor who prepares technical summaries for undergraduate students. Summarize the given blockchain article in approximately 150 words using simple language, accurate technical terms, and relevant examples.”

### 3. AI Platforms Used

The experiment uses four AI platforms:

- ChatGPT: Generates summaries based on the instructions and article provided.
  
- Google Gemini: Produces summaries and explanations using the supplied prompt.

- Claude: Generates summaries with an emphasis on following the instructions and preserving context.

- Microsoft Copilot: Produces concise summaries and explanations based on the supplied text.

For a fair comparison, the same source article and equivalent summarization requirements should be used across all platforms. Feature availability and response speed may differ.

### 4. Evaluation Criteria

Each generated summary can be assessed using the following criteria.

Criterion	Description

Accuracy	Checks whether the summary correctly represents the article without adding false information.

Coherence	Measures whether the summary is logically organized and easy to follow.

Simplicity	Evaluates whether undergraduate students can understand the content easily.

Speed	Records the time taken to generate the summary.

User experience	Evaluates readability, instruction-following, and usefulness for students.

A rating scale from 1 to 5 can be used for the first four qualitative criteria and user experience, where 1 indicates poor performance and 5 indicates excellent performance. Speed should also be recorded in seconds for a more objective comparison.

### 5. Comparison of Prompting Techniques

Technique	Main advantage	Possible limitation

Zero-shot	Simple and quick to use	May not follow a specific format consistently

Few-shot	Helps produce a consistent style	Requires extra examples in the prompt

Chain-of-thought-style	Encourages careful coverage of key concepts	May increase prompt length or processing time

Role-based	Adapts language and tone to the target audience	Results depend on how clearly the role is defined

### 6. Experimental Analysis

The same article should be summarized using each of the four techniques on every selected platform. The resulting summaries can then be evaluated using the criteria above. A comparison table should record the scores, generation times, and observations for each platform-technique combination.

The experiment should also check whether the summary includes the essential blockchain concepts: distributed ledgers, blocks, cryptographic hashing, consensus mechanisms, and practical applications. A summary that is short but omits important concepts should not receive a high accuracy score.

Because no actual platform outputs or measured timings have been provided, the experiment cannot yet establish a numerical winner. The best combination should be selected only after testing and comparing the generated summaries.

## Result

The experiment establishes a method for comparing four prompting techniques across multiple AI platforms, with the best combination to be identified after evaluating actual summary quality and generation times.


