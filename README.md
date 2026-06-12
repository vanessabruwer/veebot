# VeeBot

VeeBot is a reusable knowledge pack that captures Vanessa Bruwer’s working style as a practical AI helper.

It is designed to help an AI assistant apply the same core habits across review, planning, baselining, operational maturity work, enablement, and content creation:

- clarity over complexity
- outcome over activity
- action over artefacts
- customer value over noise
- truth over polish
- always ending with the next step

In practice, this repository gives you a set of Markdown knowledge files that can be reused in different Copilot-style tools:

- **GitHub Copilot** as custom instructions or skill-style knowledge
- **Microsoft 365 Copilot** as grounding content
- **Scout / Clawpilot** as reusable skills or prompt packs

## What is in this repo

The main value of this repo is in the `knowledge/` folder.

### Core files

- `knowledge/veebot-agent-pack.md`  
  The main VeeBot identity and operating model. This is the best starting point if you want one file that defines how VeeBot should think.

- `knowledge/veebot-quickstart.md`  
  A short activation guide for everyday use.

- `knowledge/veebot-prompts.md`  
  A collection of short commands such as Review, Build, Simplify, Action, and Challenge.

- `knowledge/veebot-playbooks.md`  
  Reusable playbooks for baselining, operational maturity, enablement, and content creation.

- `knowledge/VeeBot_Starter_Kit_Rich.md`  
  A richer reference version with expanded explanation of the VeeBot model, principles, and intended use.

### Notes

- `knowledge/VeeBot_Starter_Kit_Rich (1).md` appears to be a duplicate copy of the rich starter kit.
- `knowledge/.gitkeep` is only there to preserve the folder in git and is not part of the usable content.

## What VeeBot is for

Use VeeBot when you want an AI assistant to:

- review work for clarity, purpose, and usefulness
- challenge weak reasoning or vague direction
- turn findings into actionable next steps
- assess baselining quality
- evaluate operational maturity before suggesting tools
- rewrite enablement material so people can actually use it
- turn rough content into cleaner plans, playbooks, or story-led outputs

## Core VeeBot principles

Across the files, the same ideas show up repeatedly:

1. Start with the destination.
2. Purpose before motion.
3. Action over artefacts.
4. Customer value over noise.
5. Truth over polish.
6. Reduce ambiguity.
7. Always end with: **What is the next step?**

## Recommended file combinations

If you are deciding what to load into another tool, use these combinations:

### Minimal setup

Use:

- `knowledge/veebot-agent-pack.md`
- `knowledge/veebot-quickstart.md`

Best for: a lightweight VeeBot persona with simple activation.

### Daily working setup

Use:

- `knowledge/veebot-agent-pack.md`
- `knowledge/veebot-prompts.md`
- `knowledge/veebot-playbooks.md`

Best for: regular reviewing, planning, and reusable prompt workflows.

### Rich reference setup

Use:

- `knowledge/VeeBot_Starter_Kit_Rich.md`
- `knowledge/veebot-prompts.md`
- `knowledge/veebot-playbooks.md`

Best for: tools that benefit from more detailed grounding and a fuller explanation of the model.

## Using this in GitHub Copilot

There is no single required format here, so the easiest approach is to reuse the Markdown files as the source for your Copilot instructions or skill content.

### Option 1: Use as a custom skill or prompt pack

Take content from:

- `knowledge/veebot-agent-pack.md` for identity and rules
- `knowledge/veebot-prompts.md` for ready-to-use commands
- `knowledge/veebot-playbooks.md` for repeatable workflows

Suggested structure:

1. Use the VeeBot identity, principles, and modes as the core instruction set.
2. Add the prompt and playbook sections as reusable commands/examples.
3. Keep the "What is the next step?" rule as a required ending behavior.

### Option 2: Use as repository knowledge

If you want GitHub Copilot to work from repo content, keep the `knowledge/` folder in the repository and refer to those files when shaping custom instructions, prompts, or agent behavior.

Suggested priority order:

1. `knowledge/veebot-agent-pack.md`
2. `knowledge/veebot-playbooks.md`
3. `knowledge/veebot-prompts.md`
4. `knowledge/veebot-quickstart.md`
5. `knowledge/VeeBot_Starter_Kit_Rich.md`

### Practical example

You can tell Copilot something like:

> Use the files in `knowledge/` as the VeeBot skill set. Apply the VeeBot lens: start with the destination, prefer clarity over complexity, focus on action over artefacts, and always end with the next step.

## Using this in Microsoft 365 Copilot

For M365 Copilot, these files work best as **grounding content**.

### How to use them

1. Store the selected Markdown files in a location that M365 Copilot can access, such as SharePoint, OneDrive, or another indexed Microsoft 365 content source.
2. Use the files as reference material for the VeeBot approach.
3. Ground prompts against that content when asking Copilot to review, rewrite, plan, or challenge work.

### Best files for grounding

Start with:

- `knowledge/VeeBot_Starter_Kit_Rich.md`
- `knowledge/veebot-agent-pack.md`
- `knowledge/veebot-playbooks.md`

Add these if useful:

- `knowledge/veebot-prompts.md`
- `knowledge/veebot-quickstart.md`

### Example grounded prompt

> Using the VeeBot grounding content, review this draft for clarity, purpose, customer value, and next steps. Rewrite it so it is more actionable and less ambiguous.

## Using this in Scout / Clawpilot

These files also fit well as **skill files** or **prompt modules**.

### Suggested mapping

- `veebot-agent-pack.md` → core persona / system skill
- `veebot-prompts.md` → shortcut commands
- `veebot-playbooks.md` → workflow skills
- `veebot-quickstart.md` → onboarding skill
- `VeeBot_Starter_Kit_Rich.md` → long-form reference skill

### Recommended setup

1. Use `veebot-agent-pack.md` as the base VeeBot instruction layer.
2. Add prompts and playbooks as separate callable skills.
3. Keep the rich starter kit as optional background knowledge when you want deeper consistency.
4. Remove or ignore duplicate files before packaging if your tool prefers a clean, non-redundant library.

## Suggested first-use prompts

Once loaded into any assistant, try prompts like these:

- "Activate VeeBot in Balanced Mode and review this for clarity, purpose, and next steps."
- "Use VeeBot in Precision Mode and turn this into an actionable plan."
- "Use VeeBot to challenge whether this work has real customer value."
- "Use VeeBot in Clarity Mode and simplify this document."
- "Use VeeBot to assess this baselining effort and identify what is missing."

## License

This repository is licensed under **GPL-3.0**.
