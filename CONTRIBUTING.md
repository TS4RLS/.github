<p align="center">
  <img src="https://raw.githubusercontent.com/TS4RLS/Engine/main/assets/logo.png" width="500" alt="TS4RLS — The Sims 4 Random Loading Screen">
</p>

# Contributing to TS4RLS

TS4RLS is split across two repos, each with its own `CONTRIBUTING.md`:

- **[Engine](https://github.com/TS4RLS/Engine)** - the loading-screen generator, GUI, and CLI
- **[Website](https://github.com/TS4RLS/Website)** - source for ts4rls.stuxie.dev

Open your issue or PR on whichever of those the change actually belongs to.
This `.github` repo itself holds only the org profile
(`profile/README.md`) and org-wide defaults - contributions here are
typically fixes to those, or to files that fall back to this repo when a
target repo doesn't have its own (see GitHub's
[community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file-for-your-organization)).

## Versioning

Bump [`VERSION.md`](VERSION.md) and add a matching entry to
[`CHANGELOG.md`](CHANGELOG.md) in the same PR, following
[Semantic Versioning](https://semver.org/) (`MAJOR.MINOR.PATCH`),
independent of the other repos' own versions.
