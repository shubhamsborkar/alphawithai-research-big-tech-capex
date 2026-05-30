# Capex Analysis: Big Tech AI Spending Deep Dive

**Sources:** SEC EDGAR filings (10-K, 10-Q), earnings call transcripts, investor relations pages.
**Date:** Q1 2025 filings (trailing through March 31, 2025).
**Last Verified:** 2026-05-30 — re-checked all raw numbers against actual filings.

---

## Source Line Items (Verified from EDGAR)

### Amazon — amzn-20251231.htm (FY2025) and amzn-20241231.htm (FY2024)

| Line (as it appears in filing) | FY2024 | FY2025 |
|---|---|---|
| Net cash provided by (used in) operating activities | $115,877M | $139,514M |
| Purchases of property and equipment | $(82,999M) | $(131,819M) |
| Proceeds from property and equipment sales and incentives | $5,341M | $3,499M |
| **Net Capex** (purchases minus proceeds) | **$77,658M** | **$128,320M** |
| Total net sales (revenue) | $637,959M | $716,924M |
| **Free Cash Flow** (10-K non-GAAP reconciliation) | **$38,219M** | **$11,194M** |

Amazon's 10-K defines FCF as: OCF minus "Purchases of property and equipment, net of proceeds from sales and incentives." FCF = $115,877M - $77,658M = $38,219M (FY2024); $139,514M - $128,320M = $11,194M (FY2025).

---

### Microsoft — msft-20250630.htm (FY2025 10-K)

| Line (as it appears in filing) | FY2023 | FY2024 | FY2025 |
|---|---|---|---|
| Net cash from operations | $87,582M | $118,548M | $136,162M |
| Additions to property and equipment | $(28,107M) | $(44,477M) | $(64,551M) |
| **Free Cash Flow** (derived) | **$59,475M** | **$74,071M** | **$71,611M** |
| Total revenue | $211,915M | $245,122M | $281,724M |

MSFT does not label a "FCF" line in the cash flow statement; FCF is derived as OCF minus additions to PP&E. FY2025 revenue was **$281.7B**, not the $262B estimate (corrected).

---

### Alphabet — goog-20241231.htm (FY2024 10-K)

| Line (as it appears in filing) | FY2024 |
|---|---|
| Net cash provided by operating activities | $125,299M |
| Purchases of property and equipment | $(52,535M) |
| **Free Cash Flow** (derived: $125,299 - $52,535) | **$72,764M** |
| Revenues | $350,018M |

No separate proceeds line for PP&E sales in Alphabet's cash flow statement.

---

### Meta — meta-20241231.htm (FY2024 10-K) and meta-20250331.htm (Q1 2025 10-Q)

| Line (as it appears in filing) | FY2024 | Q1 2025 |
|---|---|---|
| Net cash provided by operating activities | $91,328M | $24,026M |
| Purchases of property and equipment | $(37,256M) | $(12,941M) |
| Principal payments on finance leases | $(1,969M) | $(751M) |
| **Free Cash Flow** (10-K definition: OCF - capex - finance leases) | **$52,103M** | **$10,334M** |
| Revenue | $164,501M | $42,314M |

Meta's FCF definition explicitly includes principal payments on finance leases — **not** just OCF minus capex. The raw PP&E purchases line is $37,256M ($37.3B), not $39.2B. The $39.2B figure cited elsewhere is total capex including finance leases ($37,256M + $1,969M = $39,225M).

---

## Capex Comparison: All Four

| Company | FY2024 Capex | FY2025 Actual | YoY Growth | FY2026 Guidance |
|---|---|---|---|---|
| **Amazon** | $77.7B (net) | $128.3B (net) | **+65%** | $200B |
| **Microsoft** | $44.5B | $64.6B | **+45%** | No explicit number; "doubling down" |
| **Alphabet** | $52.5B | ~$75B (guided) | **+43%** | ~$75B (guiding flat) |
| **Meta** | $37.3B (PP&E only) / $39.2B (incl. leases) | $64-72B range (raised mid-year) | **+72-93%** | TBD from Q4 2025 call |

**Note:** Meta's capex definition matters — the "purchases of PP&E" line is $37.3B; adding finance lease principal payments gets to $39.2B. Cross-company comparisons should use the raw PP&E line for consistency.

### The YoY Jump in Absolute Dollars

- Amazon: +$50.7B net capex
- Microsoft: +$20.1B
- Alphabet: +$22.5B
- Meta: +$22.1B (PP&E only) or +$25.0B (including leases)

---

## Free Cash Flow: Verified Numbers

### Amazon

| Period | Operating Cash Flow | Net Capex | Free Cash Flow | FCF/OCF |
|---|---|---|---|---|
| FY2024 | $115.9B | $77.7B | **$38.2B** | **33.0%** |
| FY2025 | $139.5B | $128.3B | **$11.2B** | **8.0%** |
| TTM Q1 2025 | $113.9B | $88.0B | $25.9B | 22.8% |

Amazon's FCF collapsed by **-$27.0B (-71%)** as capex grew +65% while OCF grew +20%.

### Microsoft

| Period | Operating Cash Flow | Capex | Free Cash Flow | FCF/OCF |
|---|---|---|---|---|
| FY2024 | $118.5B | $44.5B | **$74.1B** | **62.7%** |
| FY2025 | $136.2B | $64.6B | **$71.6B** | **52.6%** |
| Q2 FY2025 (quarter) | $22.3B | $15.8B | $6.5B | 29.1% |

MSFT FCF dropped -$2.5B (-3.3%) despite +$17.6B OCF growth, because capex added $20.1B.

### Alphabet

| Period | Operating Cash Flow | Capex | Free Cash Flow | FCF/OCF |
|---|---|---|---|---|
| FY2024 | $125.3B | $52.5B | **$72.8B** | **58.1%** |

Alphabet is the only company where OCF growth (~$15B YoY) is keeping pace with capex growth (~$10B YoY), so FCF is roughly flat.

### Meta

| Period | Operating Cash Flow | Capex (PP&E) | Finance Leases | Free Cash Flow | FCF/OCF |
|---|---|---|---|---|---|
| FY2024 | $91.3B | $37.3B | $2.0B | **$52.1B** | **57.0%** |
| Q1 2025 (quarter) | $24.0B | $12.9B | $0.8B | **$10.3B** | **43.0%** |

Meta's Q1 FCF margin dropped to 43% in a single quarter. Full-year FY2025 FCF will depend on whether capex stays at $64-72B run rate.

---

## Capex Intensity (% of Revenue) — Corrected

| Company | FY2024 | FY2025 | Change |
|---|---|---|---|
| Amazon | 12.2% | 17.9% | +5.7 pp |
| Microsoft | 18.1% | 22.9% | +4.8 pp |
| Alphabet | 15.0% | ~21.4% (using ~$75B capex) | +6.4 pp |
| Meta | 22.7% (PP&E only) | ~24-26% (using $64-72B capex on $164.5B base) | +1-3 pp |

**Correction from prior version:** MSFT FY2025 revenue is $281.7B (not $262B), so capex intensity was 22.9%, not 25%. The step-up is real but the baseline was off.

---

## Analyst Estimates: Where Does FCF Land in FY2025?

- **Amazon:** Street consensus was ~$12-15B FCF for FY2025. Actual came in at $11.2B — below consensus.
- **Microsoft:** $71.6B FCF in FY2025. Amy Hood gave no capex guidance on the Q2 call; the question is whether $71.6B is a trough or a floor as capex continues to climb.
- **Alphabet:** $75B capex guidance with OCF running ~$132B TTM implies ~$57B FCF for FY2025.
- **Meta:** At $64-72B capex range, FY2025 FCF likely lands in the $20-30B range — roughly half of FY2024's $52.1B.

---

## Is the Market Right to Be Scared?

### The Case FOR the fear being legitimate:

1. **Amazon's FCF fell 71% in one year.** From $38B to $11B. Even for a company with $140B OCF, going from 33% FCF/OCF to 8% is a structural shock.
2. **Capex guidance keeps rising.** Amazon went from $77B → $128B → $200B in three years. Meta raised mid-year from $60-65B to $64-72B. No one is signaling a plateau.
3. **FCF margins are compressing everywhere.** MSFT dropped from 63% to 53%. Meta's quarterly FCF fell to 43%. Alphabet is the only one holding steady.
4. **Azure and AWS growth is real but the capex-to-revenue lag is long.** These data centers take 2-3 years to build; the revenue payback is further out.
5. **$200B capex at Amazon in 2026 is a massive bet.** If AI demand softens, the write-down risk is real.

### The Case AGAINST the fear being overblown:

1. **Operating cash flow is growing everywhere.** Amazon grew OCF by +20% ($115.9B → $139.5B). MSFT grew by +15%. The underlying businesses are healthy.
2. **The assets are long-lived.** Nadella specifically noted "more than half" of MSFT's AI capex goes into 15+ year assets. This isn't server depreciation — it's infrastructure with a multi-decade horizon.
3. **AWS is capacity-constrained.** Not all Amazon capex is speculative — cloud demand is outpacing supply.
4. **No solvency risk.** These companies are financing the build with OCF, not distressed debt. Debt markets are not pricing any of these companies as risky.
5. **Alphabet's FCF stability** shows it's possible to invest aggressively and still generate cash. The gap between Amazon's FCF collapse and Alphabet's is partly structural (AWS reinvestment cycle vs Google's more balanced build).

### My Take

**The market is right to be cautious, but wrong to be catastrophizing.**

The FCF compression is real and historically significant. But it's a cash flow problem, not an insolvency problem. The real question — whether AI infrastructure generates the revenue to justify $300B+ in combined annual capex — won't be answered for 2-3 years.

Amazon is the most exposed to the bull/bear debate. Microsoft and Alphabet have more visible revenue lines (Azure, Google Cloud) to point to. Meta is making the most aggressive bet with the least clear AI monetization path outside of ads.

---

## What Was Right vs Wrong (Correction Log)

### Corrected from prior version:

| Item | Prior (wrong) | Verified (correct) | Source |
|---|---|---|---|
| MSFT FY2025 revenue | ~$262B | $281,724M ($281.7B) | msft-20250630.htm, Consolidated Statements of Income |
| Meta FY2024 capex (PP&E line) | $39.2B | $37,256M ($37.3B) | meta-20241231.htm, "Purchases of property and equipment" |
| Meta Q1 2025 capex (PP&E line) | $13.7B | $12,941M ($12.9B) | meta-20250331.htm, "Purchases of property and equipment" |
| MSFT capex as % of revenue | ~25% | 22.9% ($64,551M / $281,724M) | Derived: recalculated after fixing revenue |

### Verified as correct:

| Item | Value | Source |
|---|---|---|
| Amazon FY2024 OCF | $115,877M | amzn-20241231.htm |
| Amazon FY2024 net capex | $77,658M | amzn-20241231.htm (purchases minus proceeds) |
| Amazon FY2025 OCF | $139,514M | amzn-20251231.htm |
| Amazon FY2025 net capex | $128,320M | amzn-20251231.htm |
| Amazon FY2025 FCF | $11,194M | amzn-20251231.htm non-GAAP reconciliation |
| MSFT FY2024 capex | $44,477M | msft-20250630.htm |
| MSFT FY2025 capex | $64,551M | msft-20250630.htm |
| MSFT FY2023 capex | $28,107M | msft-20250630.htm |
| MSFT FY2025 OCF | $136,162M | msft-20250630.htm |
| MSFT FY2025 FCF | $71,611M | Derived: $136,162M - $64,551M |
| Alphabet FY2024 OCF | $125,299M | goog-20241231.htm |
| Alphabet FY2024 capex | $52,535M | goog-20241231.htm |
| Alphabet FY2024 revenue | $350,018M | goog-20241231.htm |
| Meta FY2024 OCF | $91,328M | meta-20241231.htm |
| Meta FY2024 FCF | $52,103M | meta-20241231.htm (OCF - PP&E - finance leases) |
| Meta Q1 2025 OCF | $24,026M | meta-20250331.htm |
| Meta Q1 2025 FCF | $10,334M | meta-20250331.htm |

### Key definitional notes:

- **Amazon FCF** = OCF minus "purchases of PP&E, net of proceeds from sales and incentives." Net capex excludes proceeds from asset sales and incentives.
- **Microsoft FCF** = OCF minus "additions to property and equipment." No proceeds adjustment.
- **Alphabet FCF** = OCF minus "purchases of property and equipment." No proceeds adjustment.
- **Meta FCF** = OCF minus "purchases of property and equipment" **and principal payments on finance leases.** Meta's definition is broader than the others.

---

## Sources

- [Amazon 10-K FY2024](https://www.sec.gov/Archives/edgar/data/1018724/000101872425000004/amzn-20241231.htm)
- [Amazon 10-K FY2025](https://www.sec.gov/Archives/edgar/data/1018724/000101872426000004/amzn-20251231.htm)
- [Microsoft 10-K FY2025 (AR25)](https://www.sec.gov/Archives/edgar/data/789019/000095017025100235/msft-20250630.htm)
- [Microsoft 10-Q Q2 FY2025](https://www.sec.gov/Archives/edgar/data/789019/000095017025010491/msft-20241231.htm)
- [Alphabet 10-K FY2024](https://www.sec.gov/Archives/edgar/data/1652044/000165204425000014/goog-20241231.htm)
- [Meta 10-K FY2024](https://www.sec.gov/Archives/edgar/data/1326801/000132680125000017/meta-20241231.htm)
- [Meta 10-Q Q1 2025](https://www.sec.gov/Archives/edgar/data/1326801/000132680125000054/meta-20250331.htm)