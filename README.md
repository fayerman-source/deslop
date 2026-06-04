# Deslop: Plain Legal Writing Skill for AI Agents

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Style Guide: Plain English](https://img.shields.io/badge/Style_Guide-Plain_English-blue.svg)](https://www.plainlanguage.gov)

![Deslop Hero Banner](assets/deslop_hero_banner.png)

A plug-and-play skill for AI coding assistants and agentic frameworks (including **Google Antigravity**, **Gemini CLI**, **Claude Code**, and others). This skill instructs the agent to perform clear **legal writing** and general prose editing by auditing, drafting, and translating text to follow plain English principles.

It incorporates the key tenets of plain-language legal drafting (inspired by Bryan Garner's *Legal Writing in Plain English*) to transform dense, archaic legalese and repetitive, verbose **AI slop** into clear, precise, and readable prose.

> [!NOTE]
> **Universal Applicability & Slop Mitigation**: While this skill is equipped with safety guards to preserve essential legal terms of art, its core rules on sentence architecture, active voice, and omitting needless words apply to **all forms of professional, technical, and general English writing** (such as business memos, technical documentation, and correspondence). By enforcing high-density, direct language and banning boilerplate fillers, this style guide serves as an effective tool to mitigate verbose and repetitive AI-generated text ("AI slop").

---

## 🌟 Features

* **Legalese Buster**: Automatically identifies and replaces archaic terms (*aforesaid*, *hereinafter*, *said*, *such*) and redundant doublets/triplets (*null and void*, *give, devise, and bequeath*).
* **Sentence & S-V-O Optimization**: Reconstructs long, winding sentences to place subjects and verbs close together near the beginning, keeping sentence lengths to a readable 20-word average.
* **Nominalization De-bloater**: Converts buried verbs (like *make a decision* or *conduct an analysis of*) back into strong, active verbs (*decide*, *analyze*).
* **Deep Issue Framing**: Restructures complex legal issues into the clean "premise-premise-question" format (under 75 words) rather than convoluted "Whether" statements.
* **Rule Tabulation**: Formats dense multi-part legal rules, conditions, and lists into structured, parallel, and indented sub-items.
* **Double-Entry Number Clean-up**: Eliminates parenthetical repetition (e.g., *three (3) days* -> *3 days* or *three days*).
* **Gender-Neutral Drafting**: Replaces binary/clunky pronouns (*he or she*, *his or her*) with clean, inclusive, and modern gender-neutral phrasing.
* **Oxford Comma Enforcement**: Guarantees the serial comma is used to resolve and prevent list ambiguity.
* **Omitting Needless Words**: Strips redundant modifiers (e.g., *completely finish* -> *finish*), empty "throat-clearing" introductory phrases, and roundabout sentences to achieve maximum density.
* **ABA Publication Style Compliance**: Standardizes restrictive/nonrestrictive clauses (*that* vs. *which*), quotation punctuation, date/name formatting, U.S. abbreviations, and "attorney fees" terminology.
* **Structural Formatting**: Redesigns long, dense walls of legal text using informative headings and lists.

---

## 🚀 Installation

You can install this skill either for a specific project workspace or globally for all your projects.

### Option 1: Workspace Installation (Project-Specific)
Clone this repository directly into the `.agents/skills` folder of your project workspace:

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/deslop.git .agents/skills/deslop
```

### Option 2: Global Installation
Clone this repository into the global skills directory of your agent configuration (e.g., for Gemini CLI/Antigravity):

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/deslop.git ~/.gemini/config/skills/deslop
```

---

## 💡 How to Use

Once installed, your AI agent will automatically detect and apply the skill when you ask it to edit legal documents, or you can invoke it explicitly:

* **Explicit Prompting**:
  > *"Review this contract clause using the `plain-legal-writing` skill."*
  > *"Draft a brief response to this motion following the `plain-legal-writing` guidelines."*
* **Slash Commands**:
  If your agent supports slash commands in its TUI, you can trigger it directly:
  ```text
  /deslop Audit this NDA agreement: [paste agreement text]
  ```

---

## 📄 Example Transformation

### Before (Legalese)
> *In the event that the Party of the Second Part fails to make payment of any sum due hereunder subsequent to the receipt of written notice of default, the Party of the First Part may, at its option, declare this Agreement null and void and of no further force and effect, and may proceed to exercise any and all remedies available to it under the law.*

### After (Plain English)
> *If Jones fails to pay any amount due after receiving a written default notice, Smith may terminate this agreement and pursue any legal remedies.*

---

## 🤝 Contributing

Contributions to improve style guidance, expand rules, or support additional agent frameworks are welcome! Feel free to open an issue or submit a pull request.

## ⚖️ License

Distributed under the MIT License. See `LICENSE` for more information.
