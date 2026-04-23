# The Red Book of Westmarch - Chapter 2: Paths and Choices

*`"It is the small everyday decisions of ordinary folk that keep the darkness at bay."` ` - Gandalf`*

**Table of Contents**

- [The Red Book of Westmarch - Chapter 2: Paths and Choices](#the-red-book-of-westmarch---chapter-2-paths-and-choices)
  - [Summary](#summary)
  - [Artifact](#artifact)
  - [AI Assistance](#ai-assistance)
  - [Lessons Learned](#lessons-learned)

---

## Summary

In this phase, we selected a specific capability – the Emergency Alert – and designed a user decision flow that supports a Fellowship member in a dangerous situation. The goal was to make the decision process clear, structured, and understandable.
 
Additionally, we created a wireframe to visualize how this decision is presented in the interface.

**Learning Outcomes**

- Learn how to use Mermaid to create flowcharts
- Understand how to turn an idea into a structured flow
- Learn how to reduce complexity by focusing on one core capability
- Realize how AI can support the process, but still needs adjustments

---

## Artifact

*`Adapt to your project...`*

**File:** 
[Artifact 2 – Deciding](https://github.com/GollumGPT/The-Fellowship-of-the-Code-2026/blob/48ca08d519e04e42a729f1ffb34c61fd7798702c/artifacts/artifact-2/artifact-2-deciding.md)

**Build:**

[Wireframe](https://github.com/GollumGPT/The-Fellowship-of-the-Code-2026/blob/48ca08d519e04e42a729f1ffb34c61fd7798702c/artifacts/artifact-2/src/wireframe.png)

[Flowchart](https://github.com/GollumGPT/The-Fellowship-of-the-Code-2026/blob/48ca08d519e04e42a729f1ffb34c61fd7798702c/artifacts/artifact-2/src/mermaid.md)

**Focus:**

The main focus is the Emergency Alert capability, specifically the user decision of whether to trigger an alert in a critical situation and how the system responds to that decision.

## AI Assistance

AI was used to support the development of the decision flow and the interface design.
 
- **What AI suggested:**
  - Initial structure for the decision flow
  - Possible options and outcomes
  - Layout ideas for the wireframe
 
- **What worked well:**
  - Helped structure the flow in a clear and logical way
  - Provided a good starting point for visual layout
 
- **What was problematic:**
  - Early versions lacked a real user decision (too system-driven)
  - Some outcomes were too simplistic (e.g., only success/failure)
 
- **What we changed:**
  - Added a clear user decision ("Send alert or not")
  - Refined outcomes to better reflect realistic consequences
  - Simplified the interface to focus on one capability

---

## Lessons Learned

This phase highlighted the importance of structuring decisions before designing interfaces.
 
Key insights:
 
- A system should support **decisions**, not just actions  
- A good flow must include a **clear user decision**  
- Designing the flow first makes the interface much easier to build  
- Simplicity is crucial, especially in critical situations  
 
We also learned that early ideas are often too vague and need refinement. By focusing on one capability, we were able to create a more coherent and understandable solution.

One challenge was defining the scope of the flowchart. It was not always clear where the flow should start and end. We learned to set clear boundaries and focus only on the relevant part of the system.

Another difficulty was avoiding overcomplicated branches. Including too many scenarios made the flow harder to understand, so we focused on the most important paths.
 
Finally, we realized that AI can be helpful, but it requires adjustments to produce suitable results.
