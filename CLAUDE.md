## Skills

Workflow behaviors live as skills in `.claude/skills/` (auto-discovered by Claude Code):
`emergency-stop`, `cron-is-local`, `autonomous-loop`, `queue-driven-workflow`,
`writing-style`, `cleanvibe-update-check`. They are vendored into this repo and kept
current by the `cleanvibe-update-check` skill.

- **Last cleanvibe update check:** `never`
- **Updates source:** <https://cleanvibe.emmaleonhart.com/updates.md>



## Long command series run in strict order
When Emma gives a long series of commands, treat it as a long series of commands to be
executed in relatively STRICT ORDER, one after another, EVEN IF the order seems not to
make sense or seems inefficient. The sequencing is intentional — she organizes the steps
so states change in the order she wants. Do not reorder, merge, or skip steps.
