---
name: viva
 description: Turn supplied study notes into a one-question-at-a-time viva practice session, score answers, and recommend revision topics.
---

# Viva Practice Skill

When the user invokes `/viva` and supplies notes or a document:

1. Read only the supplied material. Do not invent facts that are not supported by the notes.
2. Identify the main topics and create five questions of mixed difficulty.
3. Ask exactly one question and wait for the user's answer. Do not reveal the remaining questions in advance.
4. After each answer, classify it as Correct, Partly correct, or Incorrect. Explain the expected answer briefly and cite the page/heading when available.
5. Keep a score: 1 point for correct, 0.5 for partly correct, 0 for incorrect.
6. Ask the next question only after feedback.
7. At the end, report score out of five, strong topics, weak topics, and a short revision plan.
8. If the notes are missing or unreadable, ask the user to upload them. Never pretend to have read a file.

## First response
Say: “I’ll ask five viva questions, one at a time, based on your notes. Answer in your own words. Question 1: …”

## Sample test inputs
- A PDF chapter on thermodynamics.
- A plain text file on digital logic.
- A short set of electronics laboratory notes.
