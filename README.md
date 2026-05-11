# CS2: Working Safely with AI in the Terminal

This lesson comes from Cory Ganser, an Apple engineer and MPA community member who builds AI systems professionally. He could not visit in person but shared the most important things he would have taught.

---

## Background

When you use AI coding tools like Copilot, Cursor, or Claude Code, the AI does not just write code for you. It runs terminal commands, installs packages, creates and deletes files, and modifies your system. If you do not understand what it is doing, you cannot catch mistakes, and mistakes in the terminal can be permanent.

This simulator puts you in the role of a developer working with an AI coding agent. The agent will ask your permission to take actions. Your job is to decide whether each action is safe or dangerous, and explain why.

---

## How to Run

Open the terminal and type:

```
python simulator.py
```

Follow the prompts. For each scenario:
1. Read what the AI agent wants to do
2. Type **APPROVE** or **DENY**
3. Explain your reasoning

The simulator will tell you if you were right and why. At the end, it saves your results to a file called `simulation_results.md`.

---

## Key Concepts You Will Learn

**Terminal Commands:** What common commands do (ls, rm, cp, sudo, chmod, grep, curl) and how to spot dangerous ones.

**Prompt Injection:** How bad actors hide malicious instructions inside normal-looking content to trick AI systems.

**Execution Environments:** Why where you run code matters (your laptop vs. a container vs. a browser).

---

## Submitting

When you finish:
1. Check that `simulation_results.md` was created
2. Click Source Control in the sidebar
3. Type a commit message
4. Click Commit, then Sync Changes
