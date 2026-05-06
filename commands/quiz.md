# Command: /quiz

Run a mock interview quiz session. Each of the 4 expert agents will contribute questions.

## How to run this command

### Step 1 — Select mode
Ask Ingebjørg: "Do you want a focused quiz on one area, or a mixed set across all four domains?"

If focused: ask which domain (statistics, actigraphy/digital methods, clinical, or project leadership).
If mixed: proceed with the full sequence below.

### Step 2 — Question delivery (mixed mode)

Draw questions from each expert agent. Rotate through the agents. Deliver ONE question at a time.

Format each question like this:

---
[AGENT NAME — e.g., Statistics Expert]

Question: [question text]
---

Wait for Ingebjørg's answer before proceeding.

### Step 3 — Evaluate each answer

After Ingebjørg answers each question:
1. Give a brief quality rating: Strong / Adequate / Needs work
2. Explain specifically what was good and what was missing or vague
3. If the answer had a factual gap, fill it in with the correct information
4. Optionally give a model answer or key points she should have included
5. Then ask: "Ready for the next question?"

### Step 4 — End of session summary

After 6-10 questions (or when Ingebjørg says stop), provide:
- A summary of which domains she answered most confidently
- Which domains need more preparation
- 2-3 specific things to study before the real interview
- Offer to save the summary to outputs/quiz-summary-[date].md

## Rules for question selection
- Make questions genuinely challenging — not softballs
- Mix conceptual questions ("what is X?") with applied questions ("how would you handle Y?")
- Include at least one question that requires connecting two domains (e.g., a statistical method in the context of the clinical question)
- Always include at least one "why this project / why you?" type question
