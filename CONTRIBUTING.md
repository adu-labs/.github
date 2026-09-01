# Contributing to Adu Labs

Thank you for helping improve Adu Labs projects. These repositories favor small,
evidence-backed changes over large feature drops.

## Before opening a pull request

1. Search existing issues and discussions.
2. For a new feature or behavior change, open an issue describing the problem
   before implementing a solution.
3. Keep one pull request focused on one independently verifiable outcome.
4. Add or update tests, examples, benchmarks, or fault experiments as required
   by the change.
5. Remove all secrets, personal data, proprietary code, internal identifiers,
   and non-public operational details.

## Required change record

Meaningful changes should make the following information reviewable:

- **Problem:** What user or system problem does this solve?
- **Constraints:** What correctness, compatibility, performance, or security
  boundaries matter?
- **Decision:** What approach was chosen and why?
- **Alternatives:** What credible alternatives were considered?
- **Verification:** How was the behavior tested or measured?
- **Revision:** What assumption or earlier design changes because of this work?

Use an ADR for decisions that affect architecture, public contracts, persistent
state, security boundaries, or cross-component behavior.

## AI-assisted contributions

AI-assisted contributions are welcome. The contributor remains the author and
reviewer of the submitted change.

- Disclose material AI assistance in the pull request.
- Do not submit generated code that you cannot explain and verify.
- Do not include secrets, private prompts, employer data, or confidential source
  material in external model contexts.
- Treat model output as untrusted input: review it, test it, and check its
  dependencies and licenses.
- Share decision rationale and evidence. Do not publish private chain-of-thought.

## Commit messages

Use a scoped, outcome-oriented subject:

```text
feat(router): add atomic route snapshot replacement
fix(proxy): stop retries after client cancellation
test(limiter): cover concurrent burst exhaustion
perf(proxy): reduce response buffer allocations
docs(adr): explain retry safety boundary
```

Preferred types: `feat`, `fix`, `test`, `perf`, `refactor`, `docs`, `build`,
`ci`, `chore`, and `experiment`.

## Pull request quality bar

- The project builds and relevant tests pass.
- New behavior has a deterministic verification path where possible.
- Performance claims include reproducible methodology and limitations.
- Security-sensitive changes name the trust boundary and at least one abuse
  case.
- Public interfaces and compatibility implications are documented.
- The diff contains no unrelated formatting or mechanical churn.

## License

By contributing, you agree that your contribution will be licensed under the
license of the repository receiving it.
