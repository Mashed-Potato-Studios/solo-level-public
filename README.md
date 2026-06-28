# Solo Level (Public)

This is the **public-facing repo** for [Solo Level](https://github.com/Mashed-Potato-Studios/solo-level).
It is the source of truth for what is shipping, what is next, and what users are reporting.

## What lives here

- [**Roadmap**](./ROADMAP.md) — what we're working on, by quarter, with status.
- [**Changelog**](./CHANGELOG.md) — what shipped in each release.
- [**Issues**](../../issues) — bug reports and feature requests from the community.
- [**Discussions**](../../discussions) — Announcements, Ideas, Q&A, Show and tell.
- [**Projects**](../../projects) — public board mirroring the roadmap.

## What does NOT live here

The source code is private. Architecture decisions, internal docs, tests, and
CI configuration stay in the private
[`Mashed-Potato-Studios/solo-level`](https://github.com/Mashed-Potato-Studios/solo-level)
repo. Please do not post snippets of internal code, paths, or filenames here.

## How updates get here

The team maintains a sanitized `public` branch in the private repo. Whenever
the public-facing docs change (roadmap, changelog), the team force-pushes
that branch to this repo:

```bash
# from a clone of the private repo, on a branch containing only public-safe files
git remote add public git@github.com:Mashed-Potato-Studios/solo-level-public.git
git push public public:main --force
```

Only the files the team has explicitly curated land here. Nothing else from
the private repo is ever pushed.

## How to report a problem

1. Search [existing issues](../../issues) first — yours may already be tracked.
2. If not, open a new issue. Include: Solo Level version, OS, repro steps,
   expected vs. actual behavior.
3. For questions or ideas, prefer [Discussions](../../discussions) so others
   can benefit from the answer.

## Status

![issues](https://img.shields.io/github/issues/Mashed-Potato-Studios/solo-level-public)
![discussions](https://img.shields.io/github/discussions/Mashed-Potato-Studios/solo-level-public)