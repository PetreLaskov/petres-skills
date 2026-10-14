# Petre's Skills

LLM agent skills developed by Petre Laskov in collaboration with AI.

These are reusable instructions for shaping how an agent approaches a task.
Each skill states its purpose, when it applies, and the qualities its work
should have. They are intended to be tried, questioned, and refined through use.

## Skills

### [Reasoned Account](skills/reasoned-account/SKILL.md)

Ask for a substantial, integrated account of a view that helps you think the
question through for yourself. The skill develops the framing, intellectual
moves, methods, evidence, intuitions, and judgments behind an answer, explains
how the considerations fit together, and makes useful ways of thinking
transferable.

Use it when you want to understand the intellectual foundations of a take,
including where it is uncertain and what would change it. It is designed to
support independent judgment and substantive disagreement. Ordinary brief
explanations and procedural walkthroughs do not need its full treatment.

### [Independent Reader](skills/independent-reader/SKILL.md)

Read what a passage communicates before comparing it with the author's intent.
The skill prepares an exact text packet for a fresh reader and supports four
modes: implications, reader perspective, emotional tone, and revision inference.
It anchors observations in the text and keeps plausible readings distinct from
claims about the author's motives or actual audience response.

A blind reading requires a clean context. If author-related memory, profile,
project guidance, or earlier evaluations are already visible, the reader stops
and reports the limitation. The companion [reader prompt](skills/independent-reader/references/reader-prompt.md)
is included; use the complete folder.

## Using a skill

The complete instructions live in `skills/<skill-name>/SKILL.md`. Read the
file, then use the skill folder with an agent that supports this format, or
provide its instructions directly for the task at hand.

For example:

> Use Reasoned Account to develop your view on this question. Explain the
> framing, important intellectual moves, evidence, and judgments, and help me
> think it through independently.

The initial Reasoned Account edition was developed with OpenAI Codex and
published on 14 October 2026. Its usefulness remains to be assessed through
actual use; publication does not establish a measured improvement in model
performance.

[AI Resources on Petre's website](https://petrelaskov.github.io/knowledge/ai-resources/)
