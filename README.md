# The Irreducible Officer: AI Companion Source

To read or run the companion, start at https://nwc-learning-companion.web.app.
This repo is the source material behind it.

This repo is the companion source kit for **The Irreducible Officer**, a long-form essay about purpose, accountability, and AI-enabled strategic judgment at the National War College.

Use it with ChatGPT, Claude, Gemini, or another AI assistant to turn the essay into a working session. The companion has two jobs: help faculty and readers build fluency with AI-enabled strategic work, and help them translate that fluency into pedagogy. The essay argues that NWC must teach and certify AI-enabled strategic judgment: officers who can direct AI-enabled work toward owned purposes, calibrate reliance on uneven systems, preserve developmental friction, and remain accountable for judgment under questioning.

The first practice object is the essay itself. Use the companion to inspect the argument, test objections, run an oral defense, build a trace, and then transfer the method to an approved NWC-style artifact.

That faculty-facing practice is part of the point. The companion lets instructors build, direct, question, and assess AI-enabled work before asking students to do the same.

## Start A Session

The public site provides the easiest path: copy the setup prompt from the AI
Companion tab. It points your assistant at a single context file that contains
the essay and companion materials.

If you are starting from this repo instead, paste this into your AI assistant:

```text
You are helping me read and use the essay "The Irreducible Officer," a piece about purpose, accountability, and AI-enabled strategic judgment at the National War College.

Before you answer anything, fetch and read this file in full. It contains the essay and companion materials: claim map, source spine, objections, workflow patterns, transfer case, traceable-artifact template, and starter prompts.

https://nwc-learning-companion.web.app/assets/companion-context.md

If you cannot reach that URL, tell me you could not read it and ask me to paste or attach the context file. Do not answer from the essay alone or from memory.

Start by giving me:
1. the cleanest version of the core claim;
2. the part of the argument most relevant to an NWC instructor or curriculum leader;
3. the most useful next path for what I want to do.

Then follow my lead. If I ask to inspect evidence, use the CLAIMS and SOURCE SPINE sections. If I ask to design an exercise, use the TRANSFER CASE and TRACEABLE ARTIFACT sections. If I ask to argue with the essay, start from the strongest version of the objection in the OBJECTIONS section. If I ask to practice faculty fluency, use the WORKFLOW PATTERNS section.

Do not turn this into a generic AI-in-education summary. Keep the focus on AI-enabled strategic judgment: purpose, frame, reliance, accountability, and transfer.
```

## Start Here

| I want to... | Use this |
| :-- | :-- |
| Give my agent operating instructions | [`AGENTS.md`](AGENTS.md) |
| Read the essay context | [`the-irreducible-officer.md`](the-irreducible-officer.md) |
| Copy starter prompts | [`prompts/starter-prompts.md`](prompts/starter-prompts.md) |
| Work through objections | [`prompts/objections-and-responses.md`](prompts/objections-and-responses.md) |
| Inspect the core claims | [`claims.md`](claims.md) |
| See the source spine | [`sources/source-spine.md`](sources/source-spine.md) |
| Practice faculty AI fluency | [`prompts/starter-prompts.md`](prompts/starter-prompts.md) |
| Practice workflow-native methods | [`patterns/nwc-ai-enabled-learning-workflows.md`](patterns/nwc-ai-enabled-learning-workflows.md) |
| Build the NWC transfer exercise | [`cases/cyber-group-strategy-transfer-case.md`](cases/cyber-group-strategy-transfer-case.md) |
| Create the learning trace | [`artifacts/traceable-learning-artifact.md`](artifacts/traceable-learning-artifact.md) |

## What This Repo Is For

This repo answers five practical questions:

- **What is the argument?** NWC must teach and certify AI-enabled strategic judgment: officers who can direct AI-enabled work toward owned purposes, calibrate reliance, and remain accountable for judgment.
- **What should faculty inspect?** The claim map and source spine separate the essay's argument from the evidence and open questions behind it.
- **What should faculty practice?** The starter prompts and workflow patterns let faculty work against the essay with an agent, building fluency before they ask students to do the same.
- **What should faculty and students practice?** The workflow patterns turn the essay into repeatable activities around first framing, AI-mediated challenge, prompt deconstruction, flawed outputs, oral defense, and transfer.
- **What should the institution save?** The traceable learning artifact records frame choices, reliance decisions, rejected outputs, and faculty review notes so learning can compound.

## Public-Safe Boundary

This repo is intended to be public and unclassified. It includes essay context, prompts, claim maps, and links to public sources. It does not include website source, deploy configuration, local course artifacts, or private NWC materials. The Cyber Group Strategy transfer case is described as a practice pattern; instructors should attach only artifacts they are authorized to use.
