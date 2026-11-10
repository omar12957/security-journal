# Day 01: Setup & Environment Initialization

### 3 Things I Learned
1. **Version Control vs. Remote Hosting:** Git handles tracking local code changes, while GitHub serves as the remote audit trail and collaboration platform.
2. **Terminal Nuances:** Standard keyboard shortcuts differ in Bash (e.g., using `Shift + Insert` to paste and escaping multi-line commands with `\`).
3. **Cross-Platform Formatting:** Setting `core.autocrlf` ensures line endings remain consistent across Windows and Unix environments without causing Git diff issues.

### 1 Confusing Point
- Terminal execution behavior: recognizing when an empty return value indicates success versus an error, and understanding terminal PATH lookup when CLI commands like `code .` fail.

### Git Commands Used Today
- `git --version`
- `git config --global user.name "..."`
- `git config --global user.email "..."`
- `git config --list`
- `git clone <repo-url>`