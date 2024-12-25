# Contributing

Just follow the usual github work-flows.

- **Issues** are code-related, usually leading to an action
- **Discussions** are used for ideas, questions etc. (things are more casual)

## Maintainers

- keep instructions minimal (assume the target-audience knows what they're doing)
- do not close issues or PRs lightly. Ideally, the authors will close themselves.
- prefer cli reproducers

### PRs

* Maybe file an issue first, especially for larger/intrusive stuff
* Include only changes relevant to the issue/PR at hand
  * No whitespace changes, no additional changes, no beautification etc.
  * You can add "TODO:" markers or add new issues for relevant changes
* Ideally, the diff to review is minimal  
* Ideally, your commit(s) can be later included in other branches/forks via `git cherry pick`

### Disciplines

* Academics and Practicals complement each other
* Brute-Force fast workers and highly disciplined structural/strategic works complement and need(!) each other
  * the former can crash a project (increasing tech-debt, breaking stuff for other users)
  * the latter can stale a project (not making any progress)

### Release

The release-process is currently semi-automated. You can try it out on your fork.

Follow those instructions:

- Edit version https://github.com/deepnest-io/Deepnest/blob/master/package.json#L3
- https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository
- create a distribution locally via `npm run dist-all` (add version to folder, then zip & upload it)
