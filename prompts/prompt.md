---
title: "Initial Story Prompts & o1 Prompting Guidelines"
description: "Prompts to guide the AI or collaborator in establishing foundational world and story elements, with best practices from o1 Prompting Guidelines."
tags: [prompt, story, initialization, guidelines]
---

# Initial Story Prompts & Guidance

This document combines:
1. **o1 Prompting Guidelines** – Best practices for constructing clear, context-rich, and focused prompts.  
2. **Sample Prompts** – Specific suggestions for kicking off worldbuilding and major story elements.

---

## o1 Prompting Guidelines

### Status
[Draft / In Progress / Complete — choose your current status]

### Purpose
Provide step-by-step guidance on writing effective prompts for the o1 AI model (or any similar AI).  

### Best Practices

1. **Context Pushing**  
   - Whenever possible, give the AI all relevant documents or code snippets.  
   - Don’t rely on back-and-forth chat to gather context.  
   - *Be opinionated:* If certain .md files (like `world-building.md` or `narrative-rules.md`) are crucial for the AI’s understanding, explicitly include them in your prompt or attach them in your AI workflow.

2. **Focus on Output Format**  
   - Be explicit about what you want the AI to produce. For instance:  
     > “Output a single markdown file labeled `01-chapter-title.md` with fully drafted narrative text.”  
   - This helps the AI structure its response correctly.

3. **Use Clear Headers & Bullet Points**  
   - Structure your prompt with clear headings (e.g., “Context,” “Task,” “Output Requirements”) and bullet points.  
   - This reduces ambiguity and makes it easier for the AI to parse your instructions.

4. **One Deliverable Per Prompt**  
   - Avoid requesting multiple, unrelated deliverables in a single query.  
   - If you need two separate pieces of output, consider two separate prompts so the AI can maintain focus.

### Examples
- A short example of a *well-structured* prompt:
  > **Context**: “Here is our `world-building.md` describing the major events and magic rules.”  
  > **Task**: “Draft a two-page summary focusing on how magic shaped the first empire.”  
  > **Output Requirements**: “Return a single `.md` file with a top-level heading ‘Magic & The First Empire’ and at least three subheadings on culture, warfare, and commerce.”

### Common Pitfalls
- **Insufficient Context**: Only providing a few lines of background where the AI needs entire `.md` documents to remain consistent.  
- **Mixing Multiple Requests**: e.g., “Also rewrite these docs *and* generate a brand-new short story,” can confuse the AI.  
- **Not Specifying Format**: If you fail to say “Output a `.md` file” or provide heading guidelines, the AI might produce text that’s harder to integrate back into your project.

### Next Steps
- **Incorporate these guidelines into your daily prompts**: Each time you add or revise a `.md` document, consider how to unify the AI instructions with your existing structure.  
- **Maintain a Prompt Library**: Keep a small library of tried-and-tested prompts for reference when new collaborators join.

---

## Sample Prompts for Worldbuilding & Story Setup

Below are a few example prompts tailored for **initial worldbuilding** and **global rule-setting**. Each prompt follows the best practices above: they specify context, the request, and how we want the output structured.

### Prompt 1: Establishing the World’s Identity

**Context**  
- Provide the AI with a link or attachment to `world-building.md` (even if it’s partially filled).  
- Include any relevant docs like `narrative-rules.md` if tone/voice is already defined.

**Task**  
“Using the partial `world-building.md` provided, expand the general setting. Specifically, detail 3–5 major cultural traits, the world’s overall technology/magic level, and at least two main themes (e.g., rebellion vs. authority).”

**Output Requirements**  
- Output one `.md` file titled `world-building-expanded.md`.  
- Use bullet points for each cultural trait.  
- End with a short paragraph connecting these themes to potential conflicts or story arcs.

### Prompt 2: Defining Key Factions & Powers

**Context**  
- Attach or summarize `groups.md` if it already has some content.  
- Include references from `magic-rules.md` or `technology-rules.md` if relevant to the groups.

**Task**  
“Based on the existing factions in `groups.md`, flesh out at least three major powers. For each, provide:  
1. A short origin story.  
2. Current leadership.  
3. Their greatest challenge or conflict.  
4. Allies and enemies among other factions.”

**Output Requirements**  
- Return a single `.md` file titled `factions-expanded.md`.  
- Include subheadings for each faction (e.g., `## The Iron Brotherhood`).  
- Use bulleted lists under each heading for clarity.

### Prompt 3: Introducing a Central Conflict

**Context**  
- Summarize or attach `00-story-summary.md` if it exists, or a brief outline of your intended storyline from your `world-building.md` timeline.

**Task**  
“Propose a central conflict or inciting incident that ties together the world’s major themes and one or two key factions. Outline how at least one location from `locations.md` and one main character from `individuals/` get directly involved.”

**Output Requirements**  
- Provide a single `.md` file titled `central-conflict-proposal.md`.  
- Use an introductory paragraph describing the conflict.  
- Follow with 2–3 bullet points explaining how each faction is impacted or how they might respond.

---

## Usage Notes
- Always gather and **push** all relevant documents to your AI environment before using these prompts (per o1 **Context Pushing** best practice).  
- For new chapters or expansions, adapt these sample prompts to ensure you only request **one deliverable per prompt** and specify exactly how the output should be structured.  
- If you discover new must-have guidelines, add them to the **o1 Prompting Guidelines** section above so collaborators stay up to date.

