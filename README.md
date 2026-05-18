# Article Summary Skill

A Codex-compatible skill for writing, revising, outlining, and quality-checking academic article summaries.

This skill is designed for scholarly article summaries, including argumentative articles, empirical articles, reverse outlines, summary plans, and revision checks. It helps keep the response focused on the article itself rather than drifting into a general essay about the article's topic.

## Repository Contents

```text
.
├── SKILL.md
├── README.md
└── LICENSE
```

## Skill Name

```text
article-summary-writer
```

## Use Cases

Use this skill when you need to:

- summarize one scholarly article;
- distinguish between argumentative and empirical article summaries;
- identify the article's thesis, research question, methods, evidence, findings, or implications;
- create a reverse outline before writing a summary;
- revise an existing article summary for focus, clarity, concision, and academic tone;
- check whether a summary is too evaluative, too broad, or too focused on the general topic rather than the article.

## Not Intended For

This skill is not primarily intended for:

- full literature reviews;
- general topic essays;
- personal reflections;
- annotated bibliographies;
- full article critiques;
- popular-audience summaries, unless explicitly requested.

## Installation

Place this repository, or the `SKILL.md` file, in a Codex skills directory supported by your environment.

Example local layout:

```bash
~/.codex/skills/article-summary-skill/SKILL.md
```

Alternatively, clone the repository:

```bash
git clone https://github.com/Yubin3915/article-summary-skill.git
```

## Example Prompts

```text
Use the article-summary-writer skill to summarize this empirical article.
```

```text
Use article-summary-writer to create a reverse outline before drafting the article summary.
```

```text
Check whether my article summary focuses on the article itself rather than the general topic.
```

## Maintenance Notes

When updating this skill, keep the following principles stable:

1. The summary should focus on the article, not merely the article's subject.
2. Argumentative articles should be summarized through thesis, supporting arguments, evidence, and significance.
3. Empirical articles should be summarized through research question, hypotheses or rationale, methods, findings, limitations, and implications.
4. The skill should avoid fabricating article content when only partial text is provided.
5. The skill should adapt to assignment instructions when the user provides them.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
