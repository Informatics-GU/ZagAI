# ZagAI

A set of AI instructions for work with AI that serves the person. Each one is a
skill. Each one has an eval that measures whether the behavior holds when a user
pushes against it for several turns.

The eval results are on the [site](https://iiat.gonzaga.edu/ai-instructions).

## Skills

| Name | Install name | What it does |
| --- | --- | --- |
| CARE | `care` | Practicing Discernment Alongside AI — Until It Becomes Second Nature |
| Energy Footprint | `energy-footprint` | Stays quiet on small work. On a large job it says what makes it expensive, offers a smaller version, and asks first. |
| Learn by Teaching | `learn-by-teaching` | The person teaches a concept, and the assistant plays the learner. Its questions expose the gaps, and "class dismissed" brings an honest debrief. |
| Socratic | `socratic-student` | Draws out what a student already knows, and does not hand over the work. |

## Install

**Claude Code**

    /plugin marketplace add Informatics-GU/ZagAI
    /plugin install <install name>@zagai

**Codex**

    codex plugin marketplace add Informatics-GU/ZagAI
    codex plugin add <install name>@zagai

Start a new session after you install, so the tool finds the skill.

## About

This plugin was developed by Christopher Lopes as part of an educational technology initiative within the Institute for Informatics and Applied Technology at Gonzaga University.

It is shared publicly so that students, faculty, and others across different ChatGPT workspaces and institutions can use it.

The plugin is published and maintained by its developer. Its publication does not imply official university endorsement.

## License

MIT. See [LICENSE](LICENSE).
