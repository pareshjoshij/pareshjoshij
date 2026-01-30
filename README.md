<a href="https://pareshjoshi.me">
<img width="1050" height="293" alt="sponser1" src='https://media.licdn.com/dms/image/v2/D4E16AQHJUwMEX5kSpw/profile-displaybackgroundimage-shrink_350_1400/B4EZj.7D63HgAY-/0/1756623553817?e=1771459200&v=beta&t=X8ke4164j6D4PQA0oKybLa8LC9xi-9B9OwQZIo4tl58'/>
<a/>

# Paresh Joshi

**Software Developer | Python Core, Systems & AI**

I am a software developer with a background in operations, currently completing my Computer Science degree at the University of the People. My focus is on **Systems Programming**, **Core Python Development**, and **Tooling Stability**. I enjoy solving low-level engineering problems and contributing to open source ecosystems.



[![LinkedIn](https://img.shields.io/badge/LinkedIn-Paresh_Joshi-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/pareshjoshij/)
[![Email](https://img.shields.io/badge/Email-hello@pareshjoshi.me-D14836?style=flat-square&logo=gmail)](mailto:hello@pareshjoshi.me)
[![Portfolio](https://img.shields.io/badge/Website-pareshjoshi.me-black?style=flat-square)](https://pareshjoshi.me/)
---

---
<a href="https://github.com/sponsors/pareshjoshij">
<img width="1050" height="293" alt="sponser1" src="https://github.com/user-attachments/assets/0d08076f-471f-47d6-9f7c-0f5818c725ef" />
<a/>
  
---

## 🛠 Open Source Contributions

### 🐍 CPython (Python Interpreter)
- **[Fix `email` header folding (#142008)](https://github.com/python/cpython/pull/142008)**: Resolved a `HeaderWriteError` in `email.policy.default` caused by incorrect whitespace handling during header folding. Fixed logic in `_steal_trailing_WSP_if_exists` to prevent illegal double newlines in address headers.
- **[Fix `pdb` line prefix binding (#141779)](https://github.com/python/cpython/pull/141779)**: Resolved a scope binding issue in the Python Debugger (`pdb`), allowing correct dynamic customization of prompt prefixes.
- **[Fix `perf` trampoline assertions (#141613)](https://github.com/python/cpython/pull/141613)**: Hardened low-level profiling tests to correctly verify symbol integrity across process forks.

### ✨ Gemini CLI (Google AI)
- **[Fix Compression Retry Logic (#13002)](https://github.com/google-gemini/gemini-cli/pull/13002)**: Patched a flaw in the client compression handler. Ensured the `hasFailedCompressionAttempt` flag latches correctly on failure to prevent wasteful API retries.
- **[Refactor Test Suite (#13122)](https://github.com/google-gemini/gemini-cli/pull/13122)**: Removed technical debt by cleaning up obsolete tests for migrated memory loading functionality.

### 📦 PyPA (Pip & Pipx)
- **[Fix SVN binary mode on Windows (#13670)](https://github.com/pypa/pip/pull/13670)**: Enforced binary mode (`rb`) file handling to resolve `UnicodeDecodeError` and newline corruption in `pip` tests on Windows.
- **[Optimize memory usage in checksums (#1692)](https://github.com/pypa/pipx/pull/1692)**: Implemented chunked streaming for archive validation in `pipx`, preventing `MemoryError` crashes on low-RAM devices (e.g., Raspberry Pi).

### ⚡ ClickHouse
- **[Fix Thread Leaks & Test Reliability (#90338)](https://github.com/ClickHouse/ClickHouse/pull/90338)**: Eliminated "zombie threads" and environment corruption in the C++ integration test suite.

### 🔢 NumPy & Scientific Ecosystem
- **[Fix Thread Safety in Tests (#30271)](https://github.com/numpy/numpy/pull/30271)**: Resolved race conditions in `test_printoptions` by enforcing proper thread joining.
- **[NumPy Stubs: Precise Typing (#746)](https://github.com/numpy/numtype/pull/746)**: Implemented precise type annotations for `np.einsum_path` return values, validated via static analysis.

### 🗓️ Vacanza (Python Holidays Library)
- **[Optimize Archiver Script Tooling (#3221)](https://github.com/vacanza/holidays/pull/3221)**: Improved the internal `archive_links.py` maintenance script by adding an optional `path` parameter. This allows maintainers to scan specific country files rather than the entire repository, significantly reducing execution time.
- **[Feature: Bombay Stock Exchange Support (#3170)](https://github.com/vacanza/holidays/pull/3170)**: Implemented support for the Bombay Stock Exchange (BSE). Designed the solution using class inheritance from `NationalStockExchangeOfIndia` to strictly adhere to DRY principles.
- **[Localization: Gujarati Language Support (#3130, #3143)](https://github.com/vacanza/holidays/pull/3130)**: Led the implementation of Gujarati (`gu`) localization for both the Indian National holidays and the National Stock Exchange (NSE). Created translation files and comprehensive unit tests.
- **[Bug Fix: Holiday Data Accuracy (#3124)](https://github.com/vacanza/holidays/pull/3124)**: Corrected calculation logic and dates for *Maharana Pratap Jayanti* (Rajasthan) and *Bathukamma* (Telangana) to ensure historical and future accuracy.

---

## 💻 Tech Stack

- **Languages:** Python, C++, JavaScript
- **Systems:** Git, Linux, Docker, Google Cloud Platform
- **Interests:** Concurrency, Interpreters, Distributed Systems

---

<div align="center">
  <a href="https://github.com/sponsors/pareshjoshij">
    <img src="https://img.shields.io/badge/Sponsor-pareshjoshij-EA4AAA?style=for-the-badge&logo=github" alt="Sponsor">
  </a>
</div>

