# Pull requests

Use the pull request template and complete its "Issue, change, and prevention"
section for every PR, including features, refactors, documentation, and maintenance.
Keep the explanation in plain language and scale its detail to the change.

Use five short points: issue or need; change; verification; cause or risk;
and how to catch or prevent it. Include the expected result and conditions,
checks and limits, broader issue class and assumption, and a concrete check
with one or two prevention questions or actions. Do not invent a past bug
for new work. Use "N/A: reason" when appropriate.

When opening a PR through a CLI, API, or coding agent with an explicit body,
include these answers yourself: supplying a body can bypass template insertion.
Follow the destination repository's own contribution and validation instructions.
Only report checks that actually ran.

Keep the five points terse, then add "Lesson for future work": explain the broader
pattern, the incomplete assumption, the missed check, and reusable questions or
actions. Before implementing, write "The user can [task/capability] under
[conditions]" and verify the whole task. Report what remains untested.

This is the account-wide fallback. A repository with its own template or
contribution guide uses its local file, which should retain the same exercise.
