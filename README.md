# BF550 · Agentic coding tutorial

One notebook, `agentic-coding-tutorial.ipynb`, for the session of Wed Nov 18. It shows what makes
Claude Code an agent rather than a chatbot and the tools it uses to change files, and then you
use its loop to design, build and test a Claude Code skill: a BF550 tutor built around how you
learn best. You work
through it alongside the deck, with instructors and TAs in the room. Nothing here is submitted
and nothing here is graded. AI use in this tutorial is level 5: use Claude freely.

## Before you open it

Work on the SCC. Clone this repository there, open the folder in VS Code, and start
Claude Code from a terminal **in this folder**:

```bash
cd bf550-agentic-coding-tutorial   # or wherever you cloned it
claude
```

Claude Code works on the files of the folder it starts in.

## What you make here

- `tutor-spec.md`, in part 3: how your BF550 tutor should behave, worked out with Claude.
- `.claude/skills/bf550-tutor/SKILL.md`, in part 4: the tutor itself, a Claude Code skill
  built from your spec. It is built here first, so git shows every change to it; the last step
  installs a copy in `~/.claude/skills/`, so it works wherever you start Claude Code.

## Break it

This notebook is for changing, and today an agent changes it too. If a cell gets mangled,
`git checkout agentic-coding-tutorial.ipynb` puts it back the way it shipped. Commit and push
whenever you like; this repository is yours, and so is the `tutor-spec.md` you write in it.

Everything else about the course, including the schedule and the textbook, is at
[bu-cds-bf550.github.io](https://bu-cds-bf550.github.io).
