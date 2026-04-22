# cyber-daily-brief

Veille cybersécurité quotidienne générée automatiquement chaque matin à 7h (Europe/Paris) par un agent Claude Code distant planifié.

## Cible

Calixte Reymond — étudiant ESIEA 4A cybersécurité, alternance cyber governance avec angle technique.

## Structure

- `reports/YYYY-MM-DD.md` — rapport du jour (Top 3, autres news notables, trends, drafts LinkedIn pour les news ≥ 8/10)

## Sources couvertes

- The Hacker News
- BleepingComputer
- Krebs on Security
- Dark Reading
- Hacker News (top stories + Algolia front page)
- Recherches web complémentaires (CVE, ANSSI, CISA KEV, NIST NVD)

## Axes de scoring

Chaque news est notée /10 selon :
1. Impact GRC / régulation (NIS2, DORA, ANSSI, CRA, AI Act)
2. Criticité technique (CVSS, zero-day, nouvelle TTP)
3. Originalité du sujet
4. Angle LinkedIn pour un étudiant alternant cyber

## Déclenchement manuel

Via https://claude.ai/code/scheduled (bouton "Run now").
