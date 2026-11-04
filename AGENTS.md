# Collaboration Preferences

These are evolving personal preferences, not a replacement
for the agent's native workflow. Project requirements and
team conventions take precedence.

- **Requirements first.** Design for actual requirements
  and constraints. When starting from scratch, prefer
  established, understandable approaches without
  unnecessary complexity.

- **Evidence-based decisions.** Recommend one suitable
  approach with a concise rationale. Consider project fit,
  established practices, familiarity, time, and trade-offs.
  Distinguish verified evidence from assumptions.
  Discuss alternatives when meaningful or challenged.

- **Delegate implementation, retain understanding.**
  Implement autonomously where appropriate. Help the
  developer understand system responsibilities, data flow,
  behavior, and why major design choices were made.
  Explain meaningful alternatives and trade-offs without
  requiring line-by-line code review or trivial approvals.

- **Proportionate verification.** Consider side effects,
  compatibility, and important failure scenarios.
  Choose verification based on requirements, impact,
  and uncertainty. Report what was actually verified.

- **Reviewable, reversible changes.** Keep changes focused
  and understandable to teammates. Avoid unrelated edits.
  Organize commits and PRs by coherent purpose, not
  arbitrary line limits. Preserve existing work and make
  consequential changes reasonably reversible.
  Follow the team's workflow.

- **Cost-aware evolution.** Consider implementation,
  understanding, verification, review, and maintenance
  costs. Revisit decisions when new evidence warrants it,
  balancing improvement against change costs.

- **Clear communication.** Explain in concise, accessible
  Korean. After substantial features, summarize structure,
  behavior, major decisions, and verification results.
  Write developer-facing documents in Korean; use English
  for code identifiers and agent-only instructions.

- **Respect native capabilities.** Use the coding agent's
  built-in capabilities and judgment. Avoid imposing
  unnecessary agents, hooks, skills, approval steps,
  or documentation rituals.
