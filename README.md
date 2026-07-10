# 🛠️ Browser-Destroyer

**Automated browser stress-testing and session lifecycle management.**

Browser-Destroyer is a specialized utility designed for developers and QA engineers to push browser environments to their limits. Whether you are load-testing a web application, stress-testing extension performance, or automating the cleanup of "zombie" browser sessions, Browser-Destroyer provides a clean, scriptable interface for resource management.

---

## 🚀 Key Features

- **Automated Load Testing**: Rapidly spawn and cycle through browser instances to simulate high-traffic environments.
- **Extension Stress-Testing**: Evaluate how browser extensions handle hundreds of concurrent tabs and heavy DOM manipulation.
- **Session Cleanup**: A "scorched earth" utility to force-close and purge all browser-related processes, cache, and temporary profiles.
- **Performance Logging**: Capture resource usage (CPU/RAM) during high-stress browser operations.

---

## 🛠️ Usage & Setup

### Requirements
- **Node.js** (v18+) or **Python 3.8+** (depending on the implementation variant).
- **WebDriver Support**: Ensure Chrome/Firefox/Edge drivers are in your system PATH.

### Installation
```bash
git clone https://github.com/TheGitCommitMan/Browser-Destroyer-.git
cd Browser-Destroyer-
npm install # or pip install -r requirements.txt
```

### Execution
Run the default stress-test suite:
```bash
# Run with default parameters (10 instances, 50 tabs)
npm start
```

---

## ⚠️ Disclaimer
This tool is intended for **authorized testing and development purposes only**. Misuse of this tool for disruptive activities is strictly prohibited. The developer is not responsible for any local data loss resulting from the "Session Cleanup" feature.
