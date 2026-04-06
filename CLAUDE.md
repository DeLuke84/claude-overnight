# Claude Overnight — Remote Agent Instruktionen

Dieses Repo ist das Output-Ziel fuer naechtliche Remote-Trigger-Sessions.

## Kontext

- `portfolio-context.md` — Aktienportfolio, Watchlist, Bewertungskriterien
- `deep-research/` — Research-Skill mit 8-Phasen-Pipeline, Quellen-Scoring, Triangulation

## Research-Auftraege

Wenn du einen Research-Auftrag erhaeltst:
1. Lies zuerst `portfolio-context.md` fuer Kontext (Watchlist, Tiers, Regelwerk)
2. Lies `deep-research/SKILL.md` fuer die Research-Methodik
3. Lade die relevanten Reference-Dateien aus `deep-research/reference/`
4. Fuehre die Research-Pipeline durch
5. Schreibe den Output als Markdown nach `output/YYYY-MM-DD_[thema].md`
6. Committe und pushe das Ergebnis

## Output-Konvention

Alle Ergebnisse landen in `output/` mit Datums-Prefix. Der User reviewed und pflegt manuell ins Second Brain Vault ein.

## Sprache

Deutsch fuer Inhalte, Englisch fuer technische Begriffe.
