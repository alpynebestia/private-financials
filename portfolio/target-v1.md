# Ziel-Portfolio v1 — Max Veit

Stand: 2026-03-10 | Investierbar: $380,000

## Kapitalstruktur

| Quelle | Betrag | Rolle |
|--------|--------|-------|
| Aktienbestand (umschichtbar) | $280,000 | Kernkapital |
| CHF-Margin (IBKR) | $100,000 | Hebel, 1.45% p.a. Zinsen (~$1,450/Jahr) |
| **Total investierbar** | **$380,000** | |
| Cash auf IBKR (nicht investiert) | $100,000 | Margin-Puffer / Maintenance Margin |

### Margin-Logik
- **Währung:** CHF-Margin (1.45% p.a.) statt USD (~6%) → $1,450/Jahr statt $6,500
- **Impliziter CHF-Short:** Sinnvoll für CH-Resident mit CHF-Einkommen (natürlicher Hedge)
- **Break-Even:** Portfolio muss >1.45% auf den Margin-Anteil machen → trivial
- **$100k Cash bleibt als Puffer:** Schützt gegen Margin Calls bei Drawdowns
- **Max Margin-Auslastung:** $100k fest, NICHT erhöhen auch wenn IBKR mehr anbietet

## Strategie

- **Profil:** Hohe Risikobereitschaft, 5-10 Jahre Horizont, CH-Resident (keine Kapitalgewinnsteuer)
- **Ziel:** 20-40% p.a. durch konzentrierten Wachstumsfokus
- **Ansatz:** Core Compounders + High-Conviction AI + thematische Satelliten + Options-Hebel
- **Disziplin-Schicht:** Feste Regeln für Entry, Exit, Rebalancing — keine Bauchentscheidungen

---

## Zielallokation

| Tier | Beschreibung | Gewicht | ~Betrag |
|------|-------------|---------|---------|
| 1 | Core Compounders | 43% | ~$163k |
| 2 | High-Octane AI | 24% | ~$91k |
| 3 | Satelliten & Moonshots | 10% | ~$38k |
| 4 | Breites Beta | 12% | ~$46k |
| 5 | Options (Hebel + Hedge) | 7% | ~$27k |
| — | Cash Reserve (Trading) | 4% | ~$15k |
| **Total** | | **100%** | **~$380k** |

### Tier 1 — Core Compounders (43%, ~$163k)

Strukturell starke Unternehmen mit zweistelligem Wachstum, starken Bilanzen, berechenbarer Trajectory.

| Ticker | Name | Gewicht | ~Betrag | These | Fwd P/E |
|--------|------|---------|---------|-------|---------|
| MSFT | Microsoft | 8% | $30k | Azure/AI-Plattform, +18.8% Umsatz 2026 | ~23 |
| GOOGL | Alphabet | 8% | $30k | Cloud +48%, Search/AI, günstigste Mega-Cap | ~22-26 |
| AMZN | Amazon | 7% | $27k | AWS re-acceleriert, Ads +24%, PEG ~0.6 | ~26-29 |
| META | Meta | 7% | $27k | Umsatz +26.8% 2026, Fwd P/E ~21, AI-Infra | ~21 |
| TSM | TSMC | 6% | $23k | Foundry-Monopol, AI-CAGR 55-59%, Fwd P/E ~24 | ~24-26 |
| LLY | Eli Lilly | 4% | $15k | GLP-1 Leader, +40% YoY, PEG ~0.7 | ~25-29 |
| ETN | Eaton | 3% | $11k | Power-Infra für AI/Data-Center, ROE >20% | ~24-27 |

### Tier 2 — High-Octane AI (24%, ~$91k)

Höheres Wachstum, höhere Bewertung, höhere Volatilität. Hier kommt das Alpha.

| Ticker | Name | Gewicht | ~Betrag | These | Fwd P/E |
|--------|------|---------|---------|-------|---------|
| NVDA | Nvidia | 10% | $38k | AI-GPU-Dominanz, +62-73% YoY, Fwd P/E ~22-25 | ~22-25 |
| AVGO | Broadcom | 5% | $19k | AI Custom Chips, 2026E Umsatz +53% | ~32 |
| ASML | ASML | 5% | $19k | EUV-Monopol, Rekord-Bookings 13.2 Mrd EUR | ~39 |
| NOW | ServiceNow | 4% | $15k | AI-Workflow, -31% in 12M → Fwd P/E ~23, 60%+ Upside laut Analysten | ~23 |

### Tier 3 — Thematische Satelliten & Moonshots (10%, ~$38k)

Höchstes Risk/Reward. Begrenzte Größe, asymmetrische Payoffs.

| Ticker | Name | Gewicht | ~Betrag | These |
|--------|------|---------|---------|-------|
| BLLG | Blue Lagoon Resources | 4% | $15k | Behalten (bereits +77%), kanadischer Gold/Silber-Mining-Explorer |
| CRSP | CRISPR Therapeutics | 3% | $11k | Reduziert von 12% → Moonshot-Bucket, 2 Mrd Cash |
| NVO | Novo Nordisk | 3% | $11k | GLP-1 #2, Trailing P/E ~14, kurzfristig gedrückt |

### Tier 4 — Breites Beta (12%, ~$46k)

Basis-Diversifikation, Rebalancing-Reserve.

| Ticker | Name | Gewicht | ~Betrag | These |
|--------|------|---------|---------|-------|
| QQQ | Nasdaq 100 | 7% | $27k | Getrimmt von 53% → Core-Tech-Basis |
| FWRA | FTSE All-World | 5% | $19k | Globale Diversifikation, reduziert von 29% |

### Tier 5 — Options (7%, ~$27k)

Asymmetrischer Hebel + Crash-Absicherung. Kann auf Null gehen.

| # | Typ | Underlying | Strike | Expiry | Budget | Risk |
|---|-----|-----------|--------|--------|--------|------|
| 1 | Long Call LEAP | MSFT | ATM bis 5% OTM | Jan/Jun 2027 | ~$6k | 3/5 |
| 2 | Bull Call Spread | NVDA | 10% OTM / 30% OTM | Jan 2027 | ~$5k | 4/5 |
| 3 | Long Call LEAP | META | ATM bis 5% OTM | Jan 2027 | ~$5k | 3/5 |
| 4 | Long Call LEAP (ITM) | LLY | 5-10% ITM | Jan 2028 | ~$4k | 2-3/5 |
| 5 | Put-Spread (Hedge) | QQQ | 10% OTM / 30% OTM | Sep 2026 | ~$3k | 2/5 |

Details & Regeln: siehe `options-strategy.md`

### Cash Reserve: 2-3% (~$10k)

Für opportunistische Nachkäufe bei Drawdowns.

---

## Umschichtungsplan (von IST → SOLL)

### Ausgangslage
- Aktuelles Portfolio: ~$325k (4 Positionen)
- Davon umschichtbar: $280k aus Aktienbestand
- Zusätzlich: $100k CHF-Margin (1.45% p.a.)
- Cash ($100k): bleibt als Margin-Puffer, wird NICHT investiert

### Verkaufen / Trimmen

| Position | IST | SOLL | Aktion | Frei werdendes Kapital |
|----------|-----|------|--------|----------------------|
| QQQ | $171,816 (53%) | $27,000 (7%) | Verkauf ~84% | ~$145k |
| FWRA | $95,514 (29%) | $19,000 (5%) | Verkauf ~80% | ~$76k |
| CRSP | $38,690 (12%) | $11,000 (3%) | Verkauf ~72% | ~$28k |

**Frei aus Verkäufen:** ~$249k
**Plus CHF-Margin:** $100k
**Total zum Investieren:** ~$349k

### Behalten

| Position | IST | SOLL | Aktion |
|----------|-----|------|--------|
| BLLG | $18,871 (5%) | $15,000 (4%) | Leicht trimmen (-$4k) |

### Neu kaufen

| Ticker | Betrag | Priorität |
|--------|--------|-----------|
| NVDA | ~$38k | 1 — Sofort |
| MSFT | ~$30k | 1 — Sofort |
| GOOGL | ~$30k | 1 — Sofort |
| AMZN | ~$27k | 1 — Sofort |
| META | ~$27k | 1 — Sofort |
| TSM | ~$23k | 1 — Sofort |
| AVGO | ~$19k | 2 — Woche 1-2 |
| ASML | ~$19k | 2 — Woche 1-2 |
| NOW | ~$15k | 2 — Woche 1-2 |
| LLY | ~$15k | 2 — Woche 1-2 |
| ETN | ~$11k | 3 — Woche 2-3 |
| NVO | ~$11k | 3 — Woche 2-3 |
| Options | ~$27k | 3 — Nach Aktien-Aufbau |

---

## Regeln (Anti-FOMO-System)

### Entry-Regeln
1. **Kein FOMO-Kauf:** Nur kaufen wenn der Titel auf der Liste steht UND innerhalb 10% seines 50-Tage-Durchschnitts liegt
2. **Gestaffelter Einstieg:** Neue Positionen in 2-3 Tranchen über 2-3 Wochen aufbauen
3. **Keine neuen Positionen ohne vorherige Analyse** — erst recherchieren, dann Portfolio-File updaten, dann kaufen

### Exit-Regeln
4. **Take-Profit:** Wenn eine Position >15% des Portfolios wird → automatisch auf Zielgewicht zurück trimmen
5. **Stop-Loss:** Wenn eine Tier-3-Position >40% fällt → verkaufen, kein Nachkauf
6. **Thesis-Break:** Wenn ein Unternehmen fundamentale Guidance massiv verfehlt (>20% unter Konsens) → Position halbieren, neu bewerten

### Rebalancing
7. **Monatlich:** Portfolio-Gewichte checken. Wenn eine Position >3 Prozentpunkte vom Ziel abweicht → rebalancen
8. **Quartals-Review:** Gesamte Strategie und Einzeltitel-Thesen überprüfen. Perplexity-Research für Updates
9. **Kein Handeln zwischen Reviews** außer bei Regel 4, 5, 6

### ADHS-Schutz
10. **72-Stunden-Regel:** Jede Kauf/Verkauf-Entscheidung die nicht unter Regel 4-6 fällt → 72 Stunden warten
11. **Rho checkt:** Ich monitore und erinnere an Regeln wenn nötig
12. **Max Margin $100k CHF** — NICHT erhöhen auch wenn IBKR mehr anbietet

### Margin-Regeln
13. **Margin-Währung:** Ausschließlich CHF (1.45% p.a.), kein USD-Margin
14. **Margin-Call-Schutz:** $100k Cash bleibt als Puffer auf IBKR. Wird NICHT investiert, NICHT abgehoben
15. **Notfall-Deleverage:** Falls Portfolio >30% fällt → Margin auf $50k reduzieren (Positionen trimmen), um Zwangsliquidierung zu vermeiden
16. **Keine Margin-Erhöhung** — egal wie gut es läuft. $100k ist das Maximum

---

## Monitoring & Reviews

- **Wöchentlich:** Rho checkt Kurse, berichtet nur bei regelrelevanten Events
- **Monatlich:** Gewichtungs-Check, Rebalancing wenn nötig
- **Quartalsweise:** Full Review mit frischer Perplexity-Recherche, Thesen-Update
- **Ad-hoc:** Bei Earnings-Surprises (>10% Kursreaktion) oder Makro-Events

---

## Disclaimer

Dies ist keine Anlageberatung. Keine Garantie für Renditen. Vergangene Performance ist kein Indikator für zukünftige Ergebnisse. Maximilian Veit trifft alle Kauf-/Verkaufsentscheidungen eigenverantwortlich.
