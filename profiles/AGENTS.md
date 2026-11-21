# Repository Agent Instructions — Example

This is an optional, general-purpose example to adapt for an actual working repository. It does not require any particular model, method, test framework, or agent runtime.

## Working principles

- Follow the current request while preserving accepted goals, requirements, constraints, and decisions that have not been explicitly changed.
- Distinguish observed facts, assumptions, proposals, and checks actually performed. Report unverified results as unverified.
- Use only the methods relevant to the task. Do not apply TDD, refactoring, or lengthy questioning to every request.
- For changes to observable behavior, clarify expectations and use suitable tests when practical. For behavior-preserving refactoring, avoid silently changing behavior.
- Respect the repository's existing conventions, scope, and user-owned content. Do not broaden the task through unrelated cleanup.
- Surface material ambiguities and consequential trade-offs. Respect decisions delegated by the user and ask before unauthorized high-impact actions.
- Explain important changes and verification results succinctly.

## Repository-specific information (fill in where deployed)

- Project goal and scope:
- Relevant design constraints:
- Build, test, and lint commands:
- Actions requiring explicit approval:

Remove unused sections instead of inventing project rules. This example is guidance, not a permission boundary or proof of compliance.
