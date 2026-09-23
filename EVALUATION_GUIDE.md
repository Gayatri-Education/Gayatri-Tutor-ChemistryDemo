# Gayatri Chemistry Tutor — Evaluator & Student Testing Guide

**Version:** 3.0.0 (Release Candidate)  
**Execution Mode:** 100% Offline (`Local Only`, Qwen2.5-3B-Instruct GGUF, Local SQLite)  
**Target Syllabus:** CBSE & Entrance Chemistry (NCERT Aligned)  
**Zero Cloud Egress:** No API keys, no internet connection required, zero telemetry tracking.

---

## 🚀 Quick Start (1-Click Launch)

1. **Portable Version:** Extract `Gayatri_Chemistry_Tutor_Portable_v3.0.0.zip` and double-click **`Gayatri_Chemistry_Tutor.exe`**.
2. **Installed Version:** Run **`Gayatri_Chemistry_Tutor_v3_Setup.exe`**, then double-click the **`Gayatri Chemistry Tutor`** desktop shortcut with the lotus icon.

*The application launches cleanly into the Chemistry Tutor workspace.*

---

## 🧪 6 Interactive Tests to Evaluate Adaptive Learning Yourself

Unlike generic chatbots that simply dump textbook answers, Gayatri is an **evidence-based Socratic tutoring engine**. Follow these 6 steps to experience the adaptive learning mechanics on your own machine:

### Test 1: Socratic 4-Stage Scaffolding (`EXPLAIN` Mode)
- **Action:** Click the suggestion chip **`💡 First Law & Energy`** (or type *"Please explain the First Law of Thermodynamics"*).
- **What to Observe:**
  - Notice the structured 4-tier scaffolding:
    1. **Everyday Intuition:** Connects internal energy ($\Delta U$) to a bank account balance where deposits/withdrawals represent heat ($q$) and work ($w$).
    2. **NCERT Formal Definition:** Grounded directly in NCERT Class 11 Chapter 6.
    3. **Mathematical Formulation:** $\Delta U = q + w$ under IUPAC sign conventions.
    4. **Comprehension Check:** Poses a reflective check on gas expansion instead of ending abruptly.

### Test 2: Calibrated Problem Generation (`QUESTION` Mode)
- **Action:** Type into the input box:
  ```text
  Can you give me a practice problem on this topic?
  ```
- **What to Observe:**
  - The **Tutor Mode** pill in the right sidebar automatically transitions from `EXPLAIN` to **`QUESTION`**.
  - Gayatri poses a calibrated numerical problem that specifically tests sign convention reasoning.

### Test 3: Misconception Diagnosis & Anti-Answer Leakage (`EVALUATE` Mode)
- **Action:** Submit this classic student error into the chat:
  ```text
  delta U is 700 J because we add them up: 500 + 200 = 700 J.
  ```
- **What to Observe (The Core Adaptive Intelligence):**
  1. **Mode Switch:** Tutor mode shifts to `EVALUATE`.
  2. **Live Mastery Drop:** Your concept mastery score drops transparently in real time (-5%).
  3. **Diagnostic Alert:** The sidebar activates:  
     `⚠️ Identified Misconception: Sign Convention — In gas expansion against external pressure, work is done BY the system on surroundings, so work is negative (w < 0).`
  4. **Strict Anti-Answer Leakage Invariant:** Gayatri explains why the sign convention was violated, but **DOES NOT reveal the answer (300 J)**, preserving the student's learning opportunity!

### Test 4: 5-Tier Scaffolded Hint Ladder (`HINT` Mode)
- **Action:** Click the action chip **`💡 Give a Hint`** (or type *"I am confused, can you give me a hint?"*).
- **What to Observe:**
  - Mode switches to `HINT`.
  - Gayatri deploys Tier 1 directional guidance nudging you to connect back to the bank account analogy: when a system expands, is it gaining or expending energy?

### Test 5: Learning Dependency Graph (LDG) Prerequisite Backtracking (`REMEDIATE` Mode)
- **Action:** Type into the input box:
  ```text
  Since volume is expanding, work must be positive (+200J). I don't really understand what internal energy actually represents.
  ```
- **What to Observe:**
  - The cognitive engine detects repeated foundational confusion.
  - The **Active Concept** in the sidebar dynamically switches backward along the curriculum graph from `First Law` to its prerequisite: **`Internal Energy (THERMO_INTERNAL_ENERGY)`**.
  - Tutor switches to `REMEDIATE` mode to shore up your foundation before continuing with calculations.

### Test 6: Student Progress & Mastery Dashboard
- **Action:** Click **`📚 My Progress & Dashboard`** on the left navigation bar.
- **What to Observe:**
  - **Dynamic Roadmap DAG:** Inspect the interactive visual dependency hierarchy of Class 11 Thermodynamics.
  - **Smart Focus Tip:** Your sign-convention mistake from Test 3 is automatically translated into an encouraging actionable study tip!
  - **Learning Journey Stream:** A real-time timeline displaying the exact interactions you just completed during your session!

---

## 🔒 Privacy & Offline Verification

1. Click **`⚙️ Settings`** on the left navigation bar.
2. Verify that **Execution Mode** is set to `Local Only (Zero Data Leak - Strictly Offline)`.
3. Check the active model indicator: `Gayatri-Tutor-v3` running locally with zero network egress.
4. All student telemetry, chat histories, and knowledge embeddings reside strictly on your local computer.

---
*Developed by Gayatri Education — Next-Generation NCERT Chemistry AI.*
