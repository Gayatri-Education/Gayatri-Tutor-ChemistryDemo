# Gayatri Chemistry Tutor v3.0.1 — Hotfix & SLM Release

**Release Version:** 3.0.1  
**Architecture:** 100% Offline Senior Secondary NCERT Chemistry Adaptive Socratic AI Tutor  
**Model:** `Gayatri-Tutor-SLM-Q4_K_M.gguf` (Qwen2.5-0.5B fine-tuned Socratic tutor, Q4_K_M GGUF, 379 MB)  
**Execution Environment:** Windows 10/11 x64 (Native frozen binary, zero Python installation required)  

---

## 🌟 What's New & Fixed in v3.0.1

1. **Installer & Startup Crash Fix (`llama.cpp` Runtime Hook):**
   - Fixed Windows frozen binary DLL path resolution in `llama-cpp-python` v0.3+ via pre-import runtime hook (`hooks/rthook-llama_cpp.py`).
   - Ensures `ggml-base.dll`, `ggml-cpu.dll`, `ggml.dll`, and `llama.dll` resolve reliably regardless of install directory.

2. **Ultra-Lean Socratic SLM Integration:**
   - Switched default model from heavy 3B model (1.84 GB) to high-speed fine-tuned 0.5B Small Language Model (`Gayatri-Tutor-SLM`, 379 MB).
   - Instant response latency on CPU with low RAM footprint (~800 MB active memory).
   - Atomic RAG evidence cards (<75 tokens) for bounded context efficiency.

3. **Streamlined Package Size:**
   - Stripped 85+ MB of unused debug WebEngine assets (`qtwebengine_devtools_resources.debug.pak`) and software renderers.
   - Clean application distribution without bloated heavy ML frameworks (`scipy`, `torch`, `sentence-transformers` excluded).

4. **Reliable Model Search & Setup Automation:**
   - Reordered model detection paths to look directly inside `<install_dir>\models\gayatri\`.
   - Added `setup_model.bat` first-run helper that automatically detects and stages `Gayatri-Tutor-SLM-Q4_K_M.gguf` from the user's `Downloads` folder.

5. **Modern Animated Splash Screen:**
   - Dark gradient frameless card with lotus logo, smooth animated loading bar, dynamic initialization status, and minimum 2.4-second guarantee to ensure PySide6 WebEngine and neural weights are completely ready before revealing the workspace.

6. **Pedagogical Memory & Student Name Preservation:**
   - Injected live student pedagogical state (`Mastery Estimate`, `Target Difficulty Level`, `Known Misconceptions`) directly into the SLM prompt contract.
   - Fixed student profile display name resolution across dashboard analytics.

---

## 📦 Download Packages

| Asset | Format | Size | Description |
|---|---|---|---|
| **`Gayatri_Chemistry_Tutor_Portable_v3.0.1.zip`** | Portable ZIP | ~600 MB | **Recommended:** Extract anywhere and launch `Gayatri_Chemistry_Tutor.exe`. 100% offline. |
| **`Gayatri_Chemistry_Tutor_v3.0.1_Setup.exe`** | Windows Setup | ~600 MB | Standard Windows installer with Start Menu & Desktop shortcuts. |
| **`Gayatri-Tutor-SLM-Q4_K_M.gguf`** | Model Weights | 379.4 MB | Socratic fine-tuned 0.5B model weights. |
| **`SHA256SUMS.txt`** | Checksums | 1 KB | SHA-256 integrity verification hashes. |
| **`EVALUATION_GUIDE.md`** | Testing Guide | 5 KB | 6-step interactive evaluator checklist to test adaptive learning on your laptop. |

---

## 🚀 Quick Setup Instructions

1. Download **`Gayatri_Chemistry_Tutor_Portable_v3.0.1.zip`** (or the Setup Installer).
2. Download **`Gayatri-Tutor-SLM-Q4_K_M.gguf`** (379 MB) to your `Downloads` folder.
3. Extract the ZIP to your chosen folder.
4. Double-click **`setup_model.bat`** (it will auto-detect the model from your `Downloads` folder and install it).
5. Launch **`Gayatri_Chemistry_Tutor.exe`** (or click the desktop shortcut).

---

## 💻 System Requirements

- **Operating System:** Windows 10 (64-bit) or Windows 11 (64-bit)
- **RAM:** 4 GB minimum (8 GB recommended)
- **Disk Space:** ~1.2 GB free storage (Application + Model)
- **CPU:** Any dual-core or quad-core x64 processor (Intel Core i3/i5/i7 or AMD Ryzen)
- **Python / Dependencies:** **None required** (Fully self-contained)

---
*Developed by Gayatri Education — Next-Generation NCERT Chemistry AI.*
