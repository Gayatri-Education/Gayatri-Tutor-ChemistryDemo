# Gayatri Chemistry Tutor — Quick Start & Hands-On Learning Walkthrough

![Gayatri AI](gai3.png)

**Edition:** Production SLM Edition (v3.0.1)  
**Target Syllabus:** Senior Secondary Chemistry (CBSE Class 11 & 12 / NCERT Aligned)  
**Execution Profile:** 100% Offline • Local Neural Inference (Qwen2.5-0.5B SLM) • Embedded SQLite  
**Data Privacy:** Zero Cloud Connectivity • Zero Telemetry • Strictly Air-Gapped Local Operation  

---

## 🎯 Welcome to Gayatri Chemistry Tutor

Unlike generic chatbots that simply dump textbook answers and rob students of the learning experience, **Gayatri is an evidence-based, Socratic pedagogical tutoring platform**. 

It does not do your homework for you. Instead, it acts as an **expert personal chemistry tutor** sitting beside you—guiding your deductive reasoning through everyday analogies, probing your understanding with calibrated questions, diagnosing physical misconceptions, and adapting to your pace in real time.

This guide takes you from zero to full offline operation in under 2 minutes, followed by **6 quick hands-on exercises** to experience the adaptive learning mechanics on your own machine.

---

## 🚀 1-Click Setup & Launch (Under 2 Minutes)

Gayatri runs completely self-contained. **No Python, no Git, no command line, and no GPU are required.**

### Step 1: Download Release Assets
From the [Official Release Page](https://github.com/Gayatri-Education/Gayatri-Tutor-ChemistryDemo/releases/latest), download two files to your `Downloads` folder:
1. **The Application Package:**
   - **Option A (Setup Wizard):** `Gayatri_Chemistry_Tutor_v3.0.1_Setup.exe` (143 MB)
   - **Option B (Portable ZIP):** `Gayatri_Chemistry_Tutor_Portable_v3.0.1.zip` (210 MB)
2. **The Socratic Model Weights:**
   - `Gayatri-Tutor-SLM-Q4_K_M.gguf` (379 MB)

### Step 2: Install or Extract
- **If you chose Setup Wizard (.exe):**  
  Double-click `Gayatri_Chemistry_Tutor_v3.0.1_Setup.exe`. Follow the setup wizard to install the application. It will automatically create a Desktop shortcut with the lotus icon.
- **If you chose Portable ZIP (.zip):**  
  Right-click `Gayatri_Chemistry_Tutor_Portable_v3.0.1.zip` $\to$ **Extract All...** to any folder (e.g., your Desktop or a USB drive).

### Step 3: Model Setup (Automated 1-Click)
- In the installed application folder (or extracted portable folder), double-click **`setup_model.bat`**.
- It will automatically detect `Gayatri-Tutor-SLM-Q4_K_M.gguf` in your `Downloads` folder and install it into place in 3 seconds.

### Step 4: Launch Gayatri
- Double-click the **`Gayatri Chemistry Tutor`** desktop shortcut (or `Gayatri_Chemistry_Tutor.exe` in the portable folder).
- The elegant frameless splash screen will initialize the neural weights and launch you straight into the Socratic tutoring workspace.

---

## 🧪 6 Hands-On Learning Tests to Experience Adaptive Socratic Tutoring

Follow these 6 interactive steps inside the chat to witness the cognitive architecture in action:

---

### Test 1: Socratic 4-Stage Scaffolding (`EXPLAIN` Mode)
*Observe how Gayatri builds foundational intuition before presenting formal mathematical equations.*

- **Action:** Click the suggestion chip **`💡 First Law & Energy`** (or type: *"Please explain the First Law of Thermodynamics"*).
- **What to Observe:**
  1. **Everyday Analogy:** Connects internal energy ($\Delta U$) to a bank account balance where heat ($q$) and work ($w$) represent energy deposits and withdrawals.
  2. **Formal NCERT Definition:** Grounded directly in NCERT Class 11 Chapter 6.
  3. **Mathematical Law:** $\Delta U = q + w$ under strict IUPAC sign conventions.
  4. **Comprehension Check:** Poses a reflective check on gas expansion instead of ending abruptly.

---

### Test 2: Calibrated Problem Generation (`QUESTION` Mode)
*Observe how Gayatri generates targeted problems matched to your active concept.*

- **Action:** Type into the input box:
  ```text
  Can you give me a practice problem on this topic?
  ```
- **What to Observe:**
  - Notice the **Tutor Mode** indicator in the right sidebar automatically switches from `EXPLAIN` to **`QUESTION`**.
  - Gayatri poses a calibrated numerical problem that specifically tests whether you understand how expansion work affects internal energy.

---

### Test 3: Misconception Diagnosis with Zero Answer Leakage (`EVALUATE` Mode)
*Observe the core pedagogical invariant: diagnosing conceptual errors without spoiling the solution.*

- **Action:** Submit this classic student mistake into the chat:
  ```text
  delta U is 700 J because we add them up: 500 + 200 = 700 J.
  ```
- **What to Observe (The Anti-Answer-Leakage Invariant):**
  1. **Mode Switch:** Tutor mode shifts to **`EVALUATE`**.
  2. **Live Mastery Adjustment:** Your concept mastery score drops transparently in real time (-5%).
  3. **Diagnostic Alert:** The sidebar activates:  
     `⚠️ Identified Misconception: Sign Convention — In gas expansion against external pressure, work is done BY the system on surroundings, so work is negative (w < 0).`
  4. **Strict Anti-Answer Leakage Invariant:** Gayatri explains why your sign convention was violated, but **DOES NOT reveal the numerical answer (300 J)**, preserving the student's opportunity to deduce the correct answer independently.

---

### Test 4: 5-Tier Scaffolded Hint Ladder (`HINT` Mode)
*Observe how Gayatri provides progressive directional nudges rather than giving up the formula.*

- **Action:** Click the action chip **`💡 Give a Hint`** (or type: *"I am confused, can you give me a hint?"*).
- **What to Observe:**
  - Mode switches to **`HINT`**.
  - Gayatri deploys a Tier 1 directional hint connecting back to the bank account analogy: when a system expands against surroundings, is it expending or receiving energy?

---

### Test 5: Curriculum Graph Prerequisite Backtracking (`REMEDIATE` Mode)
*Observe how the cognitive engine automatically steps backward when foundational concepts are shaky.*

- **Action:** Type into the input box:
  ```text
  Since volume is expanding, work must be positive (+200J). I don't really understand what internal energy actually represents.
  ```
- **What to Observe:**
  - The cognitive engine detects repeated foundational confusion.
  - The **Active Concept** in the sidebar dynamically switches backward along the curriculum dependency graph from `First Law` to its prerequisite: **`Internal Energy (THERMO_INTERNAL_ENERGY)`**.
  - Tutor switches to **`REMEDIATE`** mode to rebuild foundational understanding before advancing.

---

### Test 6: Interactive Student Mastery & Progress Dashboard
*Inspect your personalized mastery roadmap and real-time learning timeline.*

- **Action:** Click **`📚 My Progress & Dashboard`** on the left navigation bar.
- **What to Observe:**
  - **Dynamic Roadmap DAG:** Inspect the interactive visual dependency hierarchy of Class 11 Thermodynamics.
  - **Smart Focus Tip:** Your sign-convention mistake from Test 3 is automatically translated into an encouraging, actionable study recommendation.
  - **Learning Journey Stream:** A real-time timeline displaying the exact pedagogical milestones you achieved during your session.

---

## ⚡ Hardware Performance & Resource Verification

Gayatri's Production SLM Edition is engineered for extreme efficiency. You can verify its performance live in **Windows Task Manager** (`Ctrl + Shift + Esc`):

| Metric | Measured on 8 GB RAM (Student Laptop) | Measured on 16 GB RAM (Desktop) |
|---|---|---|
| **CPU Utilization** | Modest 4-core CPU utilization during generation | Smooth multi-threaded generation |
| **Total Memory Footprint** | **~650 – 850 MB** (GUI + Chromium + Neural Engine) | **~750 – 900 MB** total active memory |
| **Generation Latency (TTFT)** | **< 200 ms** to first streaming token | **< 120 ms** to first streaming token |
| **Streaming Speed** | **18 – 28 tokens / second** (faster than human reading speed) | **28 – 42 tokens / second** |
| **Cold Startup Time** | **< 2.4 seconds** | **< 1.8 seconds** |

---

## 🔒 100% Offline Air-Gapped Privacy Verification

Gayatri ensures complete student data sovereignty:

1. Click **`⚙️ Settings`** on the left navigation bar.
2. Verify that **Execution Mode** is locked to `Local Only (Zero Data Leak - Strictly Offline)`.
3. Check the active model indicator: `Gayatri-Tutor-SLM-Q4_K_M.gguf` running locally on your CPU.
4. **Disconnect your Wi-Fi / Ethernet completely**: Gayatri continues to respond instantly, stream tokens, update your student progress, and evaluate answers with zero interruption.

---

## 💡 Need Help or Have Feedback?

- **Issues & Support:** File an issue on our [GitHub Repository](https://github.com/Gayatri-Education/Gayatri-Tutor-ChemistryDemo/issues).
- **Documentation & Architecture:** Visit [Gayatri Education](https://github.com/Gayatri-Education).

*Developed with pride by Gayatri Education — Shaping the Future of NCERT Socratic AI Tutoring.*
