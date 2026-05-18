---
name: article-summary-writer
description: Use this skill when the user needs to write, revise, evaluate, or structure an academic article summary. Trigger for scholarly article summaries, argumentative article summaries, empirical article summaries, reverse outlines, critical reading notes, and summary quality checks. Do not use for general topic essays, literature reviews, opinion papers, annotated bibliographies, or full article critiques unless the user explicitly asks to adapt the summary into those formats.
---

# Academic Article Summary Writer

## Purpose

Help the user produce a short, focused, academically appropriate summary of one scholarly article.

The summary must explain the article itself, not write a general essay about the article's topic. It should identify, explain, and analyze the author's main purpose, thesis or findings, evidence, methods, and significance, depending on the article type.

## When to Use This Skill

Use this skill when the user asks for any of the following:

- Summarize a scholarly article.
- Write an article summary for a class or academic assignment.
- Create a reverse outline before writing a summary.
- Identify the thesis, research question, evidence, methods, findings, or implications of an article.
- Revise an existing article summary for clarity, focus, organization, or academic tone.
- Check whether a summary is too evaluative, too broad, too opinion-based, or too topic-focused.
- Distinguish between summarizing an argumentative article and summarizing an empirical article.

Do not use this skill when the user primarily wants:

- A general essay about the article topic.
- A full literature review.
- A detailed critique or personal evaluation.
- A rhetorical analysis unless explicitly requested.
- A popular-audience summary unless explicitly requested.
- A full translation without summary work.

## Required Inputs

Ask for missing information only when it is necessary. Useful inputs include:

1. The article text, PDF, citation, abstract, or excerpt.
2. The assignment instructions, if any.
3. The required length or word count.
4. The required citation style, if any.
5. Whether the article is argumentative, empirical, theoretical, review-based, or unknown.
6. Whether the user needs a reverse outline, a full summary, revision, or quality check.

If the article type is unclear, infer it from the article structure:

- Argumentative articles usually advance a thesis or position and support it through arguments and evidence.
- Empirical articles usually include research questions, hypotheses or predictions, methods, results, findings, limitations, and implications.

## Core Principles

Follow these principles in every output:

1. Write about the article, not merely about the article's subject.
   - Correct focus: “The author argues that...”
   - Incorrect focus: writing a general informational essay about the topic.

2. Prioritize the article's central claim, purpose, method, evidence, and significance.
   - Do not attempt to include every detail.

3. Use the user's own wording only when requested.
   - Otherwise, paraphrase in clear academic prose.
   - Avoid long direct quotations.
   - If quoting is necessary, use brief quotations only.

4. Avoid unsupported personal opinion.
   - Do not add praise, criticism, agreement, disagreement, or personal reflection unless the user explicitly requests evaluation.

5. Maintain a clear, organized structure.
   - A standard summary is usually written in paragraph form.
   - Avoid headings unless the user, assignment, or output format asks for them.

6. Adapt to assignment instructions.
   - If the assignment specifies required topics or structure, follow those requirements over the default structure below.

## Workflow

### Step 1: Identify the Article Type

Determine whether the article is mainly:

- Argumentative
- Empirical
- Theoretical/conceptual
- Review article
- Mixed or unclear

If unclear, proceed with a hybrid structure and state any assumptions briefly.

### Step 2: Extract the Core Information

For all article types, identify:

- Full article title and author, if available.
- Topic.
- Research question, problem, or purpose.
- Main thesis, argument, or finding.
- How the article is positioned in relation to existing research or debate.
- Significance, implication, or contribution.

For argumentative articles, also identify:

- Main thesis or position.
- Major supporting arguments.
- Key evidence used to support each argument.
- How the evidence develops the thesis.
- Why the thesis matters.

For empirical articles, also identify:

- Research question.
- Hypotheses, predictions, or rationale.
- Methods: participants, sample, materials, data, procedure, variables, and controls where relevant.
- Main results.
- Whether findings align with prior research.
- Limitations, if discussed.
- Implications or applications.

### Step 3: Create a Reverse Outline When Helpful

Use a reverse outline when the article is complex, long, or poorly understood.

Reverse outline procedure:

1. Read or inspect the abstract, introduction, and conclusion.
2. Summarize the main question, thesis, or findings.
3. Skim headings, subheadings, and topic sentences.
4. Record the purpose of each section.
5. Identify how each section supports the article's central purpose.
6. Use this outline to decide what belongs in the final summary.

A reverse outline should be concise and should not become a full summary unless requested.

### Step 4: Choose the Summary Structure

Use one of the following structures.

#### Default Structure for an Argumentative Article

Paragraph 1:

- Identify the article, author, topic, research question or purpose, and thesis.

Body paragraph(s):

- Explain the main supporting arguments.
- Explain the key evidence or examples.
- Show how the arguments support the thesis.

Final paragraph:

- Explain the significance of the thesis or what the article helps readers understand.

#### Default Structure for an Empirical Article

Paragraph 1:

- Identify the article, author, topic, research question, and purpose.

Body paragraph(s):

- Explain the hypotheses or rationale, methods, and main results.
- Connect findings to the research question or predictions.

Final paragraph:

- Explain implications, applications, limitations, or significance of the findings.

#### Short Summary Structure

Use when the user requests a very brief summary:

1. Article identification.
2. Research question or purpose.
3. Main thesis or finding.
4. Key support, method, or evidence.
5. Significance.

#### Structured Notes Format

Use when the user requests preparation notes rather than prose:

- Citation:
- Article type:
- Topic:
- Research question/purpose:
- Thesis/main finding:
- Methods/evidence:
- Main results/arguments:
- Limitations:
- Implications/significance:
- Summary-ready sentence:

## Writing Rules

When drafting the final article summary:

- Use academic but clear language.
- Use reporting verbs accurately, such as “argues,” “claims,” “examines,” “demonstrates,” “finds,” “suggests,” “compares,” or “analyzes.”
- Keep the article's author as the subject when appropriate.
- Avoid overusing direct quotations.
- Avoid first-person statements unless the assignment requires reflection.
- Avoid introducing external facts not found in the article unless the user asks for contextualization.
- Keep chronology and causality faithful to the article.
- Preserve uncertainty: use “suggests” or “indicates” when the article does not prove something conclusively.
- Do not exaggerate findings, especially in empirical summaries.

## Handling Missing or Partial Article Text

If the user provides only an abstract:

- Produce an abstract-based summary.
- State that the summary is limited to the abstract.
- Do not invent methods, results, arguments, or implications not visible in the provided text.

If the user provides only a citation or title:

- Ask for the article text, abstract, or assignment requirements unless the user asks for a general template only.

If the article is inaccessible:

- Explain what cannot be determined.
- Offer a fill-in template or summary framework.

## Output Formats

Choose the most appropriate output format based on the user's request.

### Full Summary

Use polished paragraph form. Avoid subheadings unless requested.

### Reverse Outline

Use concise bullets or a table:

| Section | Main point | Function in article |
|---|---|---|

### Summary Plan

Use bullets:

- Opening sentence:
- Main claim/finding:
- Key support:
- Methods or evidence:
- Significance:
- Notes to avoid:

### Revision Feedback

Use this format:

1. Main issue:
2. Why it matters:
3. Suggested revision:
4. Revised version, if requested:

### Quality Check

Evaluate the summary against this checklist:

- Does it summarize the article rather than the general topic?
- Does it identify the research question, purpose, thesis, or main finding?
- Does it explain the main support, evidence, method, or results?
- Does it avoid unsupported opinion?
- Is it concise enough for the assignment?
- Is it written mostly in the user's own words?
- Does it explain significance or implications?
- Does it follow assignment instructions?

## Common Problems to Prevent

Watch for these problems and correct them:

1. Topic drift:
   - The summary becomes a general essay about the subject instead of the article.

2. Excessive detail:
   - The summary tries to include every point from the article.

3. Missing thesis or finding:
   - The summary lists facts but does not identify the author's central claim or result.

4. Unsupported evaluation:
   - The summary includes personal opinion or critique when not requested.

5. Overquoting:
   - The summary relies too heavily on direct quotations instead of paraphrase.

6. Method omission in empirical summaries:
   - The summary reports results without explaining how the study was conducted.

7. Significance omission:
   - The summary ends without explaining why the article's argument or findings matter.

8. Misrepresentation:
   - The summary states claims more strongly than the article supports.

## Templates

### Argumentative Article Summary Template

In “[Article Title],” [Author] examines [topic/problem] and asks [research question or issue]. The article argues that [main thesis]. To support this claim, [Author] first [supporting argument 1], showing that [evidence or reasoning]. The article then [supporting argument 2], using [evidence/example] to demonstrate [connection to thesis]. Overall, the article contributes to [field/debate/topic] by showing that [significance].

### Empirical Article Summary Template

In “[Article Title],” [Author] investigates [topic/problem] by asking whether/how [research question]. The study predicts or examines [hypothesis/purpose], based on [rationale]. Using [method/data/sample/procedure], the author(s) analyze [variables/materials/evidence]. The main findings show that [result 1] and [result 2]. These findings suggest that [implication], although [limitation if relevant]. The article is significant because [contribution/application].

### Very Short Summary Template

[Author]'s “[Article Title]” examines [topic] in order to [purpose/research question]. The article argues/finds that [main thesis/finding]. It supports this point through [main evidence/method/arguments]. The article's significance lies in [implication or contribution].

## Final Response Requirements

When returning a final answer to the user:

- Provide the requested article summary, outline, revision, or evaluation directly.
- Mention any important limitation, such as missing full text or abstract-only analysis.
- Do not include internal reasoning.
- Do not fabricate article content.
- Keep the response aligned with the requested length, tone, and format.

## Final Quality Gate

Before completing, verify:

- The output is about the article, not merely the topic.
- The article type was handled correctly.
- The summary includes purpose, thesis/finding, support/method, and significance.
- The wording is concise, clear, and mostly paraphrased.
- No unsupported personal evaluation was added.
- No claims were invented beyond the provided article.
