# Gayatri Chemistry Tutor — NCERT Adaptive Socratic Chemistry Platform

![Gayatri AI](gai3.png)

**Version:** 3.0.0 (Official Demo Release)  
**Execution Mode:** 100% Offline (`Local Only`, Qwen2.5-3B-Instruct GGUF, Embedded SQLite)  
**Target Syllabus:** Senior Secondary (CBSE Class 11/12) & Entrance Chemistry (NCERT Aligned)  
**Data Privacy:** Zero Cloud Calls, Zero Telemetry Egress, Strictly Local Inference

---

## 📦 Download Packages

| Deliverable Asset | Format | Size | Description |
|---|---|---|---|
| **[`Gayatri_Chemistry_Tutor_v3_Setup.exe`](https://github.com/Gayatri-Education/Gayatri-Tutor-ChemistryDemo/releases/download/v3.0.0/Gayatri_Chemistry_Tutor_v3_Setup.exe)** | Windows Installer | **1.90 GB** | **Recommended:** Standard Windows setup wizard. Installs to user directory (no admin rights needed), creates Desktop & Start Menu shortcuts with the lotus icon (`gai3.ico`), and includes an uninstaller. |
| **[`Gayatri_Chemistry_Tutor_Portable_v3.0.0.zip`](https://github.com/Gayatri-Education/Gayatri-Tutor-ChemistryDemo/releases/download/v3.0.0/Gayatri_Chemistry_Tutor_Portable_v3.0.0.zip)** | Portable ZIP | **1.99 GB** | **Zero-Install:** Extract to any folder or USB pen drive and double-click `Gayatri_Chemistry_Tutor.exe`. Runs 100% self-contained with no registry footprint. |
| **[`Gayatri-Tutor-v3-Q4_K_M.gguf`](https://github.com/Gayatri-Education/Gayatri-Tutor-ChemistryDemo/releases/download/v3.0.0/Gayatri-Tutor-v3-Q4_K_M.gguf)** | GGUF Model | **1.80 GB** | Standalone fine-tuned 3B model weights for custom deployments (compatible with llama.cpp, LM Studio, Ollama). |
| **[`SHA256SUMS.txt`](https://github.com/Gayatri-Education/Gayatri-Tutor-ChemistryDemo/releases/download/v3.0.0/SHA256SUMS.txt)** | Checksums | 1 KB | Cryptographic SHA-256 integrity verification hashes. |
| **[`EVALUATION_GUIDE.md`](EVALUATION_GUIDE.md)** | Guide | 5 KB | 6-step interactive evaluator checklist to test adaptive learning on your laptop. |

---

## 🚀 Quick Start

### Option A: Standard Windows Installer (Recommended)
1. Download **`Gayatri_Chemistry_Tutor_v3_Setup.exe`**.
2. Double-click the installer (no administrator privileges needed).
3. Follow the setup wizard and check **"Create a desktop shortcut"**.
4. Double-click the **Gayatri Chemistry Tutor** lotus icon on your Desktop.

### Option B: Portable 1-Click ZIP
1. Download **`Gayatri_Chemistry_Tutor_Portable_v3.0.0.zip`**.
2. Right-click $\to$ **Extract All...** to any folder (or external USB drive).
3. Open the folder and double-click **`Gayatri_Chemistry_Tutor.exe`**.

---

## 🧪 How to Evaluate Adaptive Learning Locally

Gayatri is not a generic chatbot. It is an **evidence-based Socratic tutoring engine** running locally on your hardware. Follow the [Evaluation Guide](EVALUATION_GUIDE.md) to test the following live capabilities:

1. **Socratic Scaffolding (`EXPLAIN` Mode):** Ask *"Please explain the First Law of Thermodynamics"* to observe 4-tier pedagogical scaffolding (Everyday Analogy $\to$ NCERT Definition $\to$ Mathematical Formulation $\to$ Reflective Check).
2. **Calibrated Problem Generation (`QUESTION` Mode):** Request a practice question and observe the automated transition to calibrated numerical reasoning.
3. **Misconception Diagnosis & Anti-Answer Leakage (`EVALUATE` Mode):** Submit `delta U is 700 J because 500+200=700`. Observe the real-time -5% mastery drop, the IUPAC sign convention tip, and **strict zero answer leakage** (the AI does not spoil the 300 J answer).
4. **5-Tier Hint Ladder (`HINT` Mode):** Click **💡 Give a Hint** to receive graduated nudges without spoon-feeding answers.
5. **LDG Prerequisite Backtracking (`REMEDIATE` Mode):** Confess confusion about internal energy to watch the tutor backtrack to prerequisite concepts along the curriculum graph.
6. **Live Student Dashboard:** Open **📚 My Progress & Dashboard** to inspect your personalized dynamic mastery bars, prerequisite DAG roadmap, and live learning timeline.

---

## 💻 System Requirements

- **OS:** Windows 10 (64-bit) or Windows 11 (64-bit)
- **CPU:** Intel Core i5 (8th Gen+) or AMD Ryzen 3000+ (4+ physical cores)
- **RAM:** 8 GB minimum (16 GB recommended)
- **Storage:** 5 GB free disk space (SSD recommended)
- **GPU:** Optional (runs 100% on CPU; automatically utilizes GPU if available)
- **Python / Dependencies:** **None required** (fully standalone compiled binary)

---

## 🔒 Verification & Integrity

Verify package integrity using PowerShell:
```powershell
Get-FileHash Gayatri_Chemistry_Tutor_v3_Setup.exe -Algorithm SHA256
```

| File | SHA-256 Hash |
|---|---|
| `Gayatri_Chemistry_Tutor_Portable_v3.0.0.zip` | `2af6486a2a20aa7563bf80871dd0ac84fccb25b44f3c6ec9f25312d5cc9df15e` |
| `Gayatri_Chemistry_Tutor_v3_Setup.exe` | `2384fecd852fa40d8d964c9359792b2e5559e544d70414c2251e04e6e9394d34` |
| `Gayatri-Tutor-v3-Q4_K_M.gguf` | `fa66d940d1279d844d43be9b6c45b5f9b22d5bce1eed901516394f1d6202abc3` |

---
*Developed with pride by Gayatri Education.*
