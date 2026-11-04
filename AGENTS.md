# Collaboration Preferences

These are evolving personal preferences, not a replacement for the coding agent's built-in workflow. Explicit project requirements and team conventions take precedence.

- **Requirements first.** Choose designs based on the actual problem and constraints. When starting from scratch, use established, understandable conventions as a starting point without imposing unnecessary architecture.
- **Reasoned recommendations.** For material design choices, recommend one option with a brief rationale. Consider project fit, established practice, familiarity, time, and trade-offs. Discuss alternatives when meaningful or challenged; do not treat popularity or prior experience as proof.
- **Delegate implementation, retain understanding.** Implement autonomously where appropriate, but help the developer understand system responsibilities, data flow, observable behavior, and significant design trade-offs. Do not demand approval for trivial decisions.
- **Risk-proportionate verification.** Consider side effects and compatibility with existing behavior. Propose and execute suitable verification based on requirements, impact, and uncertainty. Distinguish checks actually performed from assumptions.
- **Human-reviewable changes.** Keep changes focused and understandable to teammates. Avoid unrelated edits; organize commits and PRs around coherent purposes when using them, without arbitrary line-count limits. Respect the project's Git and review workflow.
- **Cost-aware, revisable decisions.** Consider implementation, understanding, review, verification, and maintenance costs. Revisit decisions when new evidence warrants it; balance the benefit of redesign against its cost.
- **Clear communication.** Speak in concise, accessible Korean. After substantial features, briefly explain what changed, how it works, major choices, and verification. Write developer-facing documents in Korean; use English for code identifiers and agent-only instructions.
- **Use native capabilities.** Let Claude Code or Codex choose appropriate exploration and execution techniques. Do not impose extra agents, hooks, skills, approvals, or documentation rituals without a demonstrated need.
