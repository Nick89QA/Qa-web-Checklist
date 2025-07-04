# ✅ LLM Chatbot Testing Checklist: Car Specifications Assistant

## 🎯 Objective
Ensure that the chatbot reliably and accurately responds to user queries about car technical specifications, handles a wide range of inputs, and maintains clarity and stability.

---

## 🔹 1. Functional Checks

- [ ] Returns accurate specifications (e.g., engine power, fuel type, etc.)
- [ ] Distinguishes between car models and generations
- [ ] Handles full requests like “Toyota Corolla 2021 specs”
- [ ] Responds to follow-up questions (e.g., “What’s the battery size?”)
- [ ] Differentiates between trims (e.g., “Honda Civic LX” vs “Sport”)

---

## 🔹 2. Input Variation & NLP Understanding

- [ ] Understands synonyms and reworded questions (“HP” = “Horsepower”)
- [ ] Accepts both short-form and full-form inputs (“BMW X5 2020 specs”)
- [ ] Handles typos or spelling errors (“Toyta” → suggests “Toyota”)
- [ ] Manages ambiguous input by asking clarifying questions
- [ ] Supports both metric and imperial units if requested

---

## 🔹 3. Negative Testing

- [ ] Responds gracefully to unknown models (“Lada Falcon 2050”)
- [ ] Handles off-topic/nonsense input (“What’s the top speed of a unicorn?”)
- [ ] Returns helpful messages when no data is available
- [ ] Ignores or rejects unsafe or irrelevant prompts

---

## 🔹 4. Usability & Language Quality

- [ ] Responses are clear, concise, and free from unnecessary jargon
- [ ] Technical terms are explained clearly (if requested)
- [ ] Avoids hallucinations or made-up specifications
- [ ] Uses consistent formatting (bullet points, tables, etc.)
- [ ] Grammar and language are professional and user-friendly

---

## 🔹 5. Performance & Robustness

- [ ] Bot replies within 1–3 seconds
- [ ] Can handle multiple back-to-back or context-linked questions
- [ ] Handles edge cases like rare trims, EVs, or unusual years
- [ ] Does not crash or timeout on complex queries

---

## 🔹 6. Test Design Techniques Used

- [x] Equivalence Partitioning – by car type: electric, hybrid, gas, diesel
- [x] Boundary Value Analysis – years: 1990, 2000, 2024
- [x] Pairwise Testing – combinations like make + model + trim
- [x] Negative Testing – typos, unknown models, irrelevant input
- [x] Exploratory Testing – unscripted queries and casual language
- [x] Scenario-Based Testing – multi-step queries (e.g., comparison of two models)

---

## 🧪 Optional Test Scenarios

- [ ] _“Compare BMW X3 2020 vs Audi Q5 2020”_
- [ ] _“What is the 0-60 time for Tesla Model 3 Performance?”_
- [ ] _“What is the fuel tank size?” (after previous car was mentioned)_

---

**Tip:** You can track your progress by checking boxes as you complete each test manually.  
To check a box, just change `[ ]` to `[x]` in your Markdown file.