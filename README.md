![banner](https://github.com/user-attachments/assets/7052c566-185e-4d23-b0c0-17ea0222cb24)

---

# Paresh Joshi 🦅

**Software Developer | Python Core, Systems & AI**

Software Developer specializing in **Systems Programming**, **Core Python Development**, and **Tooling Stability**. With a background in operations and active contributions to CPython, PyPA, and NumPy, I focus on solving low-level engineering bottlenecks and building high-performance open-source tools. I am currently completing my Computer Science degree at the University of the People.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Paresh_Joshi-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/pareshjoshij/)
[![Email](https://img.shields.io/badge/Email-hello@pareshjoshi.me-D14836?style=flat-square&logo=gmail)](mailto:hello@pareshjoshi.me)
[![Portfolio](https://img.shields.io/badge/Website-pareshjoshi.me-black?style=flat-square)](https://pareshjoshi.me/)

---

<a href="https://github.com/sponsors/pareshjoshij">
<img width="1050" height="293" alt="sponsor1" src="https://github.com/user-attachments/assets/0d08076f-471f-47d6-9f7c-0f5818c725ef" />
</a>

---

## ❄️ Winter of Code (WoC 2026) Featured Project

### 🗓️ Vacanza (Python Holidays Library)
**Interactive `.ics` Calendar [Download Portal](https://holidays.readthedocs.io/en/latest/downloads/)** For my Winter of Code task, I architected and implemented a fully functional web portal allowing non-technical users to filter, preview, and download customized `.ics` holiday calendars. 

([Issue](https://github.com/vacanza/holidays/issues/3168) / [PR](https://github.com/vacanza/holidays/pull/3282))

<img width="1091" height="599" alt="downloadportal" src="https://github.com/user-attachments/assets/beb5a539-4394-4bdc-aea7-6b2854ebf188" />

**The Challenge:** Generating localized calendars for all supported countries, financial markets, subdivisions, and categories across a 20-year span (2015–2035) resulted in **~55,000+ files and 9,000+ directories**. Committing this to the repository would cause massive bloat and exhaust Read the Docs (RTD) build resources.

**My Solution & Technical Implementations:**
* **CI/CD Artifact Injection:** Designed a GitHub Actions pipeline (`deploy-gh-pages.yml`) that dynamically generates the 55k+ files on-the-fly *only* during deployment, hosting the portal entirely on **GitHub Pages** to keep the main source tree clean.
* **High-Performance Python Generator:** Engineered `generate_site_assets.py` utilizing `ProcessPoolExecutor` to parallelize the heavy lifting of building `.ics` files and lightweight `.json` previews.
* **Client-Side Assembly (Alpine.js):** Built a responsive frontend that fetches the lightweight JSON for instant UI previews. When a user requests a download, the JS merges the selected categories and dynamically stitches the final `.ics` blob directly in the browser.

---

## 🛠 Open Source Contributions

### 🐍 CPython (Python Interpreter)
* **[Fix `email` header folding (#142008)](https://github.com/python/cpython/pull/142008)**: Resolved a `HeaderWriteError` in `email.policy.default` caused by incorrect whitespace handling during header folding. Fixed logic in `_steal_trailing_WSP_if_exists` to prevent illegal double newlines in address headers.
* **[Fix `pdb` line prefix binding (#141779)](https://github.com/python/cpython/pull/141779)**: Resolved a scope binding issue in the Python Debugger (`pdb`), allowing correct dynamic customization of prompt prefixes.
* **[Fix `perf` trampoline assertions (#141613)](https://github.com/python/cpython/pull/141613)**: Hardened low-level profiling tests to correctly verify symbol integrity across process forks.

### ✨ Gemini CLI (Google AI)
* **[Fix Compression Retry Logic (#13002)](https://github.com/google-gemini/gemini-cli/pull/13002)**: Patched a flaw in the client compression handler. Ensured the `hasFailedCompressionAttempt` flag latches correctly on failure to prevent wasteful API retries.
* **[Refactor Test Suite (#13122)](https://github.com/google-gemini/gemini-cli/pull/13122)**: Removed technical debt by cleaning up obsolete tests for migrated memory loading functionality.

### 📦 PyPA (Pip & Pipx)
* **[Fix Flaky Animation Tests (#1697)](https://github.com/pypa/pipx/pull/1697)**: Replaced rigid `time.sleep()` synchronization with a deterministic polling loop using `default_timer()`. This eliminated race conditions on slow CI runners and significantly sped up local test execution.
* **[Fix SVN binary mode on Windows (#13670)](https://github.com/pypa/pip/pull/13670)**: Enforced binary mode (`rb`) file handling to resolve `UnicodeDecodeError` and newline corruption in `pip` tests on Windows.
* **[Optimize memory usage in checksums (#1692)](https://github.com/pypa/pipx/pull/1692)**: Implemented chunked streaming for archive validation in `pipx`, preventing `MemoryError` crashes on low-RAM devices (e.g., Raspberry Pi).

### ⚡ ClickHouse
* **[Fix Thread Leaks & Test Reliability (#90338)](https://github.com/ClickHouse/ClickHouse/pull/90338)**: Eliminated "zombie threads" and environment corruption in the C++ integration test suite.

### 🔢 NumPy & Scientific Ecosystem
* **[Fix Thread Safety in Tests (#30271)](https://github.com/numpy/numpy/pull/30271)**: Resolved race conditions in `test_printoptions` by enforcing proper thread joining.
* **[NumPy Stubs: Precise Typing (#746)](https://github.com/numpy/numtype/pull/746)**: Implemented precise type annotations for `np.einsum_path` return values, validated via static analysis.

### 🗓️ Vacanza (Python Holidays Library)
* **[Optimize Archiver Script Tooling (#3221)](https://github.com/vacanza/holidays/pull/3221)**: Improved the internal `archive_links.py` maintenance script by adding an optional `path` parameter. This allows maintainers to scan specific country files rather than the entire repository, significantly reducing execution time.
* **[Feature: Bombay Stock Exchange Support (#3170)](https://github.com/vacanza/holidays/pull/3170)**: Implemented support for the Bombay Stock Exchange (BSE). Designed the solution using class inheritance from `NationalStockExchangeOfIndia` to strictly adhere to DRY principles.
* **[Localization: Gujarati Language Support (#3130, #3143)](https://github.com/vacanza/holidays/pull/3130)**: Led the implementation of Gujarati (`gu`) localization for both the Indian National holidays and the National Stock Exchange (NSE). Created translation files and comprehensive unit tests.
* **[Bug Fix: Holiday Data Accuracy (#3124)](https://github.com/vacanza/holidays/pull/3124)**: Corrected calculation logic and dates for *Maharana Pratap Jayanti* (Rajasthan) and *Bathukamma* (Telangana) to ensure historical and future accuracy.

---

## 💻 Tech Stack

* **Languages & Core:** Python (CPython internals, ProcessPoolExecutor), C++, JavaScript (Alpine.js)
* **Systems & DevOps:** Git, Linux, Docker, Google Cloud Platform, GitHub Actions, CI/CD Pipelines
* **Interests:** Concurrency / Multi-threading, Interpreters, Distributed Systems, Low-level Profiling

---

<div align="center">
  <a href="https://github.com/sponsors/pareshjoshij">
    <img src="https://img.shields.io/badge/Sponsor-pareshjoshij-EA4AAA?style=for-the-badge&logo=github" alt="Sponsor">
  </a>
</div>
