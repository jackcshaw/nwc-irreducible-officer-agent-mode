# The Irreducible Officer: Agent Mode

This repo is the companion source kit for **The Irreducible Officer**, a long-form essay about purpose, accountability, and AI-enabled strategic judgment at the National War College.

Use it with Codex, Claude Code, or another coding agent to turn the essay into a working session. The essay argues that strategic decisions are increasingly built from AI-shaped inputs, and that NWC must teach and certify AI-enabled strategic judgment: officers who can direct AI-enabled work toward owned purposes, calibrate reliance on uneven systems, preserve developmental friction, and remain accountable for judgment under questioning.

The companion has two jobs. It helps readers test the essay's claims, and it helps faculty practice the fluency the essay calls for: building, directing, questioning, and assessing AI-enabled work while keeping strategic judgment with the human.

## Connect Your Agent

Paste this into your coding agent:

```text
You are helping me read and use the essay "The Irreducible Officer."

Use this companion GitHub repo as your source of truth:
https://github.com/jackcshaw/nwc-irreducible-officer-agent-mode

If you can access GitHub or run shell commands, clone or open that repo first. Start with only these files:
- README.md
- AGENTS.md
- the-irreducible-officer.md
- claims.md
- prompts/starter-prompts.md
- prompts/objections-and-responses.md
- sources/source-spine.md
- patterns/nwc-ai-enabled-learning-workflows.md
- cases/cyber-group-strategy-transfer-case.md
- artifacts/traceable-learning-artifact.md

Do not answer from the essay alone. Use the repo to help me do one useful thing with the argument: understand it, inspect a claim, test an objection, practice a workflow, design an exercise, create a flawed AI assessment, run oral defense, or build a trace.

Start by giving me:
1. the cleanest version of the core claim;
2. the part of the argument most relevant to an NWC instructor or curriculum leader;
3. the most useful starter prompt from the repo for my next step.

If I ask to inspect evidence, read `claims.md` and `sources/source-spine.md`. If I ask to design an exercise, read `cases/cyber-group-strategy-transfer-case.md` and `artifacts/traceable-learning-artifact.md`. If I ask to argue with the essay, read `prompts/objections-and-responses.md`.

If you cannot access GitHub directly, tell me the smallest set of repo files you need me to paste before you continue.
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
| Practice workflow-native methods | [`patterns/nwc-ai-enabled-learning-workflows.md`](patterns/nwc-ai-enabled-learning-workflows.md) |
| Practice faculty AI fluency | [`prompts/starter-prompts.md`](prompts/starter-prompts.md) |
| Build the NWC transfer exercise | [`cases/cyber-group-strategy-transfer-case.md`](cases/cyber-group-strategy-transfer-case.md) |
| Create the learning trace | [`artifacts/traceable-learning-artifact.md`](artifacts/traceable-learning-artifact.md) |

## What This Repo Is For

This repo answers five practical questions:

- **What is the argument?** NWC must teach and certify AI-enabled strategic judgment in work built from direct AI use and inherited AI-shaped inputs: officers who can direct AI-enabled work toward owned purposes, calibrate reliance, and remain accountable for judgment.
- **What should faculty inspect?** The claim map and source spine separate the essay's argument from the evidence and open questions behind it.
- **What should faculty practice?** The workflow patterns and starter prompts let faculty work against the essay with an agent, building fluency before they ask students to do the same.
- **What should students practice?** The prompts turn the essay into activities around framing, assumptions, reliance, flawed outputs, oral defense, and reusable artifacts.
- **What should the institution save?** The traceable learning artifact records frame choices, reliance decisions, rejected outputs, and faculty review notes so learning can compound.

## Public-Safe Boundary

This repo is intended to be public and unclassified. It includes essay context, prompts, claim maps, and links to public sources. It does not include website source, deploy configuration, local course artifacts, or private NWC materials. The Cyber Group Strategy transfer case is described as a practice pattern; instructors should attach only artifacts they are authorized to use.
