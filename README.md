# Hello, I'm Paresh Joshi 👋

![Banner](https://media.licdn.com/dms/image/v2/D4E16AQHJUwMEX5kSpw/profile-displaybackgroundimage-shrink_350_1400/B4EZj.7D63HgAY-/0/1756623553817?e=1766016000&v=beta&t=gdFpGw1xOQnhu72Byu2bJdiXXA1cm_N3PxHrZWTfUUU)

## Software Developer | Python Core, Systems & AI
Building robust systems by blending 7+ years of professional experience with a focus on **Core Python Development**, **Concurrency**, and **System Stability**.

---

## 👨‍💻 About Me
I am a Software Developer making a dedicated career transition from an extensive background in operations—driven by a passion for solving low-level engineering problems.

- 🌱 Currently studying **Computer Science at University of the People**
- 👯 Open to collaboration on **Open Source & Freelance Projects**
- 📫 Contact: **hello@pareshjoshi.me**, **pareshjoshij@gmail.com**

---

## ⭐ Featured Open Source Contributions

### 🐍 CPython (Python Interpreter)
- **[Fix `pdb` line prefix binding (#141779)](https://github.com/python/cpython/pull/141779)**: Resolved a scope binding issue in the Python Debugger (`pdb`), allowing dynamic customization of prompt prefixes.
- **[Fix `perf` trampoline assertions (#141613)](https://github.com/python/cpython/pull/141613)**: Hardened low-level profiling tests to correctly verify symbol integrity across process forks (Systems Programming).

### ✨ Gemini CLI (Google AI)
- **[Fix Compression Retry Logic (#13002)](https://github.com/google-gemini/gemini-cli/pull/13002)**: Patched a logic flaw in the client compression handler. The fix ensures the `hasFailedCompressionAttempt` flag correctly latches on failure, preventing wasteful API retries and unnecessary token consumption.
- **[Remove Technical Debt in Tests (#13122)](https://github.com/google-gemini/gemini-cli/pull/13122)**: Cleaned up the test suite by removing obsolete, skipped tests for hierarchical memory loading (functionality migrated to core), improving maintainability and reducing debt.

### 📦 PyPA (Pip & Pipx)
- **[Fix SVN binary mode on Windows (#13670)](https://github.com/pypa/pip/pull/13670)**: Resolved `UnicodeDecodeError` and newline corruption in `pip` tests by enforcing binary mode (`rb`) file handling, restoring CI stability on Windows.
- **[Optimize memory usage in checksums (#1692)](https://github.com/pypa/pipx/pull/1692)**: Implemented chunked streaming for archive validation in `pipx`, preventing `MemoryError` crashes on low-RAM devices (Raspberry Pi/CI) by eliminating full-file loading.

### ⚡ ClickHouse (High-Performance C++ DB)
- **[Fix Thread Leaks & Test Reliability (#90338)](https://github.com/ClickHouse/ClickHouse/pull/90338)**: Eliminated "zombie threads" and environment corruption in the integration test suite.

### 🔢 NumPy & Scientific Ecosystem
- **[Fix Thread Safety in Tests (#30271)](https://github.com/numpy/numpy/pull/30271)**: Resolved race conditions and thread leakage in `test_printoptions` by enforcing proper thread joining logic.
- **[Precise Typing for `einsum_path` (#746)](https://github.com/numpy/numtype/pull/746)**: Implemented precise type annotations for `np.einsum_path` return values (NumPy Stubs), validating changes with static analysis (Mypy) to ensure correctness.
- **[Fix CLI Argument Parsing (#748)](https://github.com/numpy/numtype/pull/748)**: Corrected CLI argument handling in build tools to match documentation, removing redundant flags (`-f`) and streamlining the execution workflow.

---

## 🛠️ Tech Stack
<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" alt="Python"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="40" alt="C++"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git-scm/git-scm-icon.svg" width="40" alt="Git"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" alt="JS"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="40" alt="HTML5"/>
  <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" width="40" alt="GCP"/>
</p>

---

## 🏆 GitHub Trophies
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=pareshjoshij&theme=tokyonight&no-frame=true&column=6" />
</p>

---

## 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pareshjoshij&show_icons=true&theme=tokyonight&hide_border=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pareshjoshij&layout=compact&theme=tokyonight&hide_border=true" height="150" />
</p>

---

## 📝 Latest Blog Posts
- [From Theory to Reality: My First Steps Building with Gemini and Imagen](https://pareshjoshi.me/blog/from-theory-to-reality-my-first-steps-building-with-gemini-and-imagen/)
- [The Art of Conversation: My Journey into Prompt Design with Vertex AI](https://pareshjoshi.me/blog/the-art-of-conversation-my-journey-into-prompt-design-with-vertex-ai/)

➡️ [Read More on My Blog](https://pareshjoshi.me/blog/)

---

## 🌐 Connect With Me
<p align="center">
  <a href="https://pareshjoshi.me/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/pareshjoshij/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:hello@pareshjoshi.me"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>
