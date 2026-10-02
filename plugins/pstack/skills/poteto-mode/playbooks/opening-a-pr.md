### Finish work

Invoked at the end of every other playbook.

1. **Checkout.** Work in the shared repository checkout. Before you commit, list the live agents and stop every one that still writes in this tree, including grandchildren you never launched. A delegate's children do not inherit its brief. Confirm each stop, then run `git status` and read the tree you are about to commit.
2. **Commits.** Commit liberally on a local branch. Rebase into small, ordered commits when the story needs it. Amend when the fix belongs in a just-made commit.
3. **Hygiene.** Run `/deslop` over the diff before commit. Run `/no-comments` before you call the change ready for human review. Write commit messages with `/technical-writing`, then apply `/unslop`.
4. **Handoff.** Name the branch, tip SHA, what changed, and how you verified it. Do not push unless the operator explicitly asks in this session.

**Reply:** branch and SHA, verification evidence, and open decisions.
