# Private Financials — Max Veit

Privates Investment-Repo. Kein Teil von ALPYNE.

## Struktur

```
portfolio/           ← Aktuelle & Ziel-Positionen, Strategien
  current-holdings.md    IST-Portfolio (IBKR Positionen)
  target-v1.md           SOLL-Portfolio v1 mit Regeln
  options-strategy.md    Options-Trades & Regeln

research/            ← Marktanalysen & Perplexity-Ergebnisse
  2026-03/               März 2026
    sektor-analyse-full.md       Volle Sektor- & Aktienanalyse
    sektor-analyse-summary.md    Zusammenfassung
    options-analyse.md           Options-Strategie-Analyse

prompts/             ← Wiederverwendbare Prompts für Perplexity
  options-strategy.md    Options-Research Prompt
```

## Eckdaten

- **Broker:** Interactive Brokers (IBKR)
- **Wohnsitz:** Schweiz (keine Kapitalgewinnsteuer)
- **Gesamtkapital:** ~$425k
- **Risikoprofil:** Hoch, 5-10 Jahre Horizont
- **Ziel:** 20-40% p.a.

## Workflow

1. Perplexity für Deep Research → Ergebnisse in `research/YYYY-MM/`
2. Rho baut daraus Strategie → `portfolio/`
3. Prompts für wiederkehrende Analysen in `prompts/`
4. Monatlich Gewichtungs-Check, quartalsweise Full Review
