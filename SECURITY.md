# Security policy

This policy covers the eight public repositories of the RiskAverseTech
organization:

- [toolgate](https://github.com/RiskAverseTech/toolgate) (has its own `SECURITY.md`, which takes precedence)
- [embassy](https://github.com/RiskAverseTech/embassy)
- [humanOS](https://github.com/RiskAverseTech/humanOS) (has its own `SECURITY.md`, which takes precedence)
- [MemeVault](https://github.com/RiskAverseTech/MemeVault)
- [cicada-ioc](https://github.com/RiskAverseTech/cicada-ioc)
- [liber-primus-site](https://github.com/RiskAverseTech/liber-primus-site)
- [createa-meme-skill](https://github.com/RiskAverseTech/createa-meme-skill)
- [.github](https://github.com/RiskAverseTech/.github) (this repository)

## Reporting a vulnerability

Please report suspected vulnerabilities privately, not in a public issue or pull
request.

Open a private report on the affected repository through its **Security** tab,
then **Report a vulnerability**. Only the maintainers see it. There is no
separate email channel.

Include what you found, which repository and commit, how to reproduce it, and
what an attacker could do with it. A suggested fix is welcome but not required.

## What to expect

These projects are maintained by one person. We aim to acknowledge a report
within a few business days; timelines after that are best-effort, not
contractual. We will confirm the issue with you, agree on a disclosure date, fix
it, and credit you in the release notes and the advisory unless you prefer not
to be named. Corrections stay in the record: a fixed issue is described in the
repository's changelog or release notes, not quietly patched.

## Scope

In scope: code and configuration in this organization's public repositories.

Out of scope: weaknesses in third-party services the projects talk to (for
example Supabase, Vercel, the X API, model providers, or TypeSafe's Jev); report
those to the vendor. Findings that require an attacker to already control the
machine the software runs on are usually out of scope for the local-first tools,
but tell us anyway if you are unsure.

## Supported versions

Only the latest version on each repository's default branch, or the latest
published package or release where one exists, receives fixes.
