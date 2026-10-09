# Contributing to AttendEase

## Workflow
1. Read README and `docs/TESTING.md`.
2. Reproduce an issue and check whether it is already reported.
3. Fork and clone the repository.
4. Create a focused branch, for example `git checkout -b fix/duplicate-roll-validation`.
5. Make one logical change and test it in a browser.
6. Review changes with `git diff --check` and `git diff`.
7. Commit with a descriptive message, e.g. `git commit -m "Fix duplicate roll number validation"`.
8. Push the branch and open a pull request. Explain the problem, root cause, fix, and tests; attach evidence where useful.
9. Respond to review comments and update the branch.

## Code expectations
- Keep the app dependency-free unless justified.
- Validate inputs and provide clear feedback.
- Escape user-entered text before inserting it into HTML.
- Avoid silently losing records.
- Update docs when behavior changes.

## Pull request checklist
- [ ] Addresses an issue or explains the improvement
- [ ] Tested affected behavior in a browser
- [ ] Existing features still work
- [ ] No unrelated changes
- [ ] Documentation and evidence included where useful
