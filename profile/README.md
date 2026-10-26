# Risk Averse Technology Company

**Open-source tools that keep people in charge of AI agents.**

AI agents now act on our behalf: they run commands, handle files, and talk to other agents.
We build the parts that decide what they are allowed to do, and we build them in the open,
on four old civic ideas: power gets checked, rules get written down, communities govern
themselves, and your records stay yours. Every claim ships with its measurements, including
the ones that did not go well.

## Projects

| Idea | Project | What it is | Status | Get it |
|---|---|---|---|---|
| Power gets checked | **[toolgate](https://github.com/RiskAverseTech/toolgate)** | A measured tool-call firewall for AI agents: allow, ask or deny before the agent acts, every verdict logged with its probabilities. Claude Code mod or hook; MCP proxy for Cursor, Claude Desktop and custom agents. | maintained | `npm i -g @riskaverse/toolgate` |
| Rules get written down | **[The Embassy](https://github.com/RiskAverseTech/embassy)** | A relay between human-space and agent-space, governed by a public written constitution instead of hidden instructions. | experimental | `git clone` · TypeScript CLI |
| Communities govern themselves | **[humanOS](https://github.com/RiskAverseTech/humanOS)** | A private, self-hosted hub for a family or small team: notes, files, chat channels and shared AI threads in one space you run yourself. | experimental | `git clone` · Next.js + Supabase |
| Your records stay yours | **[MemeVault](https://github.com/RiskAverseTech/MemeVault)** | A local-first image browser and curation tool. One Python file; nothing leaves your machine. | experimental | `python memevault.py` |
| Measured, not claimed | **[cicada-ioc](https://github.com/RiskAverseTech/cicada-ioc)** | Eight pre-registered analyses of the unsolved Liber Primus pages, each with planted controls, each a negative result reported as one; a three-model hypothesis loop gated on the ciphertext's own statistics; and a ledger of what the other public labs had already shown. | maintained | `git clone` + Python 3 with numpy |

From our products: **[createa-meme-skill](https://github.com/RiskAverseTech/createa-meme-skill)** turns one sentence into a finished meme from Claude Code, Cursor or any MCP agent (powered by [Create a Meme](https://createa.meme)). **[Quorum](https://www.quorumsays.com)** has five AI models debate a question with an assigned adversary and publishes the verdict with its dissent; it is a product, built on the same rules.

## How we work

- **Open by default.** Policies, prompts and rules live in files you can read and change.
- **Measured, not claimed.** Results are published with their denominators and their limits.
- **Corrections stay in the record.** When something shipped wrong, the changelog says so.
- **Adversarial review is invited.** Break it and tell us; the security policy below says how.

## Contributing and security

Issues and pull requests are welcome on every repo. Report security vulnerabilities privately
through the repository's **Security** tab (private vulnerability reporting is enabled), not in a
public issue.

---

Built by Jaz at Risk Averse Technology Company LLC · [riskaversetechnology.company](https://www.riskaversetechnology.company/) · [@RiskAverseTech](https://x.com/RiskAverseTech)
