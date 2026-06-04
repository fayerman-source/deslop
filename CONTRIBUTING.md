# Contributing to Plain Legal Writing Skill

First off, thank you for taking the time to contribute! Contributions from legal professionals, linguists, and developers help make this skill highly effective, precise, and safe to use.

---

## How to Contribute

### 1. Suggesting Rule Additions or Changes
* If you find a legal term of art that was incorrectly simplified, or a legalese phrase that should be banned, please open a **Rule Suggestion** issue.
* Provide sources or style guides (e.g., Garner's manuals, SEC handbook, bar association guidelines) backing up the suggestion.

### 2. Modifying the Skill Directives
If you are submitting a Pull Request to update the rules:
* Add the rule under the appropriate section in [SKILL.md](SKILL.md) with a clear rule title, formatting requirements, and rationales.
* Include corresponding "Before" and "After" examples in [samples/comparison.md](samples/comparison.md) demonstrating the exact transition.
* Ensure the new rule is neutral, objective, and does not copy copyright-protected text verbatim from proprietary manuals.

### 3. Submitting a Pull Request
1. Fork the repository and create your branch from `main`.
2. Commit your changes using descriptive commit messages (e.g., `feat: add rule for disclaiming warranties under UCC`).
3. Open a Pull Request using the provided PR template.
4. Ensure all examples in `samples/comparison.md` are accurate and legally sound.

---

## Code & Writing Style Guide

When editing the skill directives or adding examples:
* **Concision**: Keep rule explanations short and action-oriented. Use bold text to emphasize actions.
* **Gender-Neutral Language**: Use gender-neutral plural or singular *they/them* structures for all examples.
* **Fidelity**: Ensure that simplified text retains the exact legal mechanics and liabilities of the original legalese.
* **Citations**: If a rule derives from a specific source (e.g., UCC section, state bar code, specific case law), include a brief inline markdown footnote citation if possible.
