# Good Enough Shipper — Grok Skill

A custom skill for Grok that enforces a "meet criteria and terminate" protocol. Stops endless AI refinement loops on projects, documents, code, creative work, reports, and business deliverables.

## Why it exists
Most AI conversations drift into perpetual optimization. This skill changes the objective: deliver when the explicit requirements are met at a working level. No more "one more tweak."

Inspired by real-world decision engines in high-stakes work (restoration claims, engineering, operations): gather info, decide, execute, stop.

## Installation (for Grok users)
1. Download or clone this repo.
2. Copy the `good-enough-shipper/` folder into your Grok skills directory (usually the persistent `/home/workdir/.grok/skills/` or equivalent).
3. The skill auto-activates on triggers like refinement loops, perfectionism, or "just one more pass."

## Usage
Mention the skill name or describe a stuck iterative task. It will:
- Assess against original requirements only.
- Flag true blockers.
- Cap iterations.
- Ship with: "Good enough to ship. Ready for delivery."

## Files
- `good-enough-shipper/SKILL.md` — Core instructions for the agent.
- `INSTALL.txt` — Quick human guide.

## License
MIT — feel free to use, modify, and share.

## Contributing
Pull requests welcome. Especially improvements for domain-specific use (e.g. restoration estimating, code review, content creation).

Built with the Grok skill-factory. Share it wide. Ship fast.
