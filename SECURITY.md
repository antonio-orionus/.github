# Security Policy

This policy covers every public repository under
[antonio-orionus](https://github.com/antonio-orionus) that has no `SECURITY.md`
of its own. A repository with its own file follows that file instead.

## Reporting a vulnerability

Please report security issues privately through a GitHub security advisory:
open the affected repository's **Security** tab and choose
**Report a vulnerability**, or go to

```
https://github.com/antonio-orionus/<repository>/security/advisories/new
```

Please do not open a public issue, pull request or discussion for a
vulnerability.

Include:

- the affected repository, and the version, release or commit
- steps or a minimal example that reproduces the issue
- what an attacker could gain: data access, code execution, tampered
  downloads, denial of service

## Supported versions

Fixes go into the latest release (or the default branch, for repositories
without releases). Older versions do not get security fixes.

## Scope

In scope: the code, release assets, installers and package manifests
(Homebrew, Scoop) published from these repositories, and their build and
release pipelines.

Out of scope: forks of other projects. Report those to the upstream project.

## Response

I aim to acknowledge reports within 7 days. Valid issues get a fix and a
release before public disclosure whenever practical, and reporters are
credited in the advisory unless they prefer otherwise.
