# Claude Skills — BubbleStone

Skills transversaux pour Claude Code, synchronises via GitHub.

## Installation

Clone une fois par machine :
```bash
git clone git@github.com:FlorentCoulonBS/claude-skills.git /opt/repos/claude-skills
```

Symlink dans chaque projet :
```bash
mkdir -p .claude
ln -s /opt/repos/claude-skills/skills .claude/skills
```

## Mise a jour

```bash
cd /opt/repos/claude-skills && git pull
```

## Skills disponibles

| Skill | Description |
|-------|-------------|
| page-cro | Optimisation du taux de conversion (CRO) de pages marketing |
| copywriting | Redaction de copy marketing (homepage, landing pages, etc.) |
| seo-audit | Audit SEO technique et on-page |

## Instructions partagees

`shared/CLAUDE-shared.md` contient les regles transversales applicables a tous les projets.

## Licence

Skills importes de [marketingskills](https://github.com/coreyhaines31/marketingskills) sous licence MIT.
