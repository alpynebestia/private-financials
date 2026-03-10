# MEMORY.md — Private Financials

## Max (Investor-Profil)
- CH-Resident, keine Kapitalgewinnsteuer
- Hohe Risikobereitschaft, Zeithorizont 5-10 Jahre
- Ziel: 20-40% p.a.
- ADHS → FOMO-anfällig (rein wenn zu spät, drin bleiben wenn Peak erreicht)
- Braucht regelbasiertes System, keine Bauchentscheidungen
- Broker: Interactive Brokers (IBKR)
- Options-Level 3 (Aktienoptionen, komplexe/gehebelte ETPs)

## Portfolio-Eckdaten
- Investierbar: $380k ($280k Equity + $100k CHF-Margin @ 1.45%)
- Cash auf IBKR: $100k (Margin-Puffer, nicht investiert)
- Margin: Ausschließlich CHF, max $100k, nie erhöhen
- Ziel-Portfolio: target-v1.md (5 Tiers + Regeln)

## Ursprüngliches Portfolio (vor Umschichtung)
- QQQ: 282.5 Stk, Avg $529, 53% Gewicht (+15%)
- FWRA: 11,200 Stk, Avg $7.20, 29% Gewicht (+18.4%)
- CRSP: 730 Stk, Avg $64.40, 12% Gewicht (-17.7%)
- BLLG: 18,321 Stk, Avg $0.58, 6% Gewicht (+77.6%) — Blue Lagoon Resources (Kanada, Mining), NICHT Blockchain

## Strategie-Entscheidungen
- QQQ von 53% → 7% trimmen (zu passiv, Bewertungsprämie, Doppel-Exposure)
- CRSP von 12% → 3% (zu viel für binäres Biotech)
- FWRA von 29% → 5% (Kapital für Einzeltitel freimachen)
- BLLG (Blue Lagoon Resources) behalten bei ~4%
- Neu: 12 Einzeltitel + 5 Options-Trades
- CHF-Margin statt USD (1.45% vs ~6%)

## Tools & Infrastruktur
- Perplexity für Deep Research → Ergebnisse in research/
- Rho baut Strategie → portfolio/
- IBKR API-Anbindung geplant (ab Montag, wenn MacBook da)
- IB Gateway + Python (ib_insync) für automatisierte Orders

## Offene Punkte
- [ ] MacBook-Setup am Montag (IB Gateway installieren)
- [ ] IBKR API-Zugang aktivieren
- [ ] Erste Umschichtung durchführen (Prio 1: QQQ/FWRA trimmen)
- [ ] Options-Chains live prüfen (MSFT, NVDA, META, LLY, QQQ)
- [ ] Indexoptionen-Permission bei IBKR beantragen (für QQQ Put-Spreads)

## Session-Log

### 2026-03-10 (Erste Session)
- Portfolio-Bestandsaufnahme: 4 Positionen, $325k Aktien + $100k Cash
- Perplexity-Research: Sektor-Analyse, 15 Einzeltitel, ETF-Vergleich, CRSP-Bewertung
- Ziel-Portfolio v1 gebaut: 5 Tiers (Core/AI/Satelliten/Beta/Options)
- Options-Strategie: 5 Trades (MSFT/NVDA/META/LLY LEAPS + QQQ Hedge)
- Anpassung: $100k Cash nicht investierbar, stattdessen $100k CHF-Margin (1.45%)
- BLLG-Korrektur: Blue Lagoon Resources (Mining), NICHT Blockchain ETF
- Portfolio-Validierung via Perplexity: Korrelationsrisiko, Timing, Margin
- Recherche nicht-korrelierte Sektoren (Defence, Uranium, India)
- Entscheidung: v1 bleibt, keine Diversifikation in andere Sektoren
- Begründung: Weniger Komplexität > marginaler Drawdown-Schutz bei ADHS-Profil
- Repo-Struktur aufgebaut (portfolio/, research/, prompts/, memory/)
- Nächster Schritt: MacBook-Setup Montag, dann IBKR-Anbindung + Umschichtung starten
