# 🐍 CPython Contributions

My work on CPython focuses on the standard library stability and debugging tools.

| Pull Request | Description | Status |
| :--- | :--- | :--- |
| **[Fix `email` header folding (#142008)](https://github.com/python/cpython/pull/142008)** | Resolved a `HeaderWriteError` in `email.policy.default` caused by incorrect whitespace handling during header folding. Fixed logic in `_steal_trailing_WSP_if_exists` to prevent illegal double newlines in address headers. | 🟣 Merged |
| **[Fix `pdb` line prefix binding (#141779)](https://github.com/python/cpython/pull/141779)** | Resolved a scope binding issue in the Python Debugger (`pdb`), allowing correct dynamic customization of prompt prefixes. | 🟣 Merged |
| **[Fix `perf` trampoline assertions (#141613)](https://github.com/python/cpython/pull/141613)** | Hardened low-level profiling tests to correctly verify symbol integrity across process forks. | 🟣 Merged |

[← Back to Profile](../README.md)
