# The Depreciation Drag and Why the Capex-to-Cash Problem Is Temporary

**Sources:** SEC EDGAR filings (10-K, 10-Q), Amazon 2025 Letter to Shareholders.
**Date:** 2026-05-30.
**Verification:** 2026-05-30 — all raw numbers re-confirmed against actual filings. See correction log at bottom.

---

## The Lag: How Capex Becomes a Depreciation Hit

**Warning: The 2026-2028 depreciation projections below are estimates, not reported figures.** They are my own extrapolations based on the asset base and useful life schedules. Do not read them as filings.

This is the key mechanics that gets left out of the FCF panic:

**Capex** → Cash goes out the door today
**Depreciation** → Gets charged against earnings over the asset's useful life

So when a company spends $100B on data centers in 2024-2026, that doesn't hit the income statement as $100B in 2024. It gets spread out over the asset's life — 4 to 6 years for servers, 7 to 40 years for buildings. The real profit drag is front-loaded in the wrong direction: capex is high *now*, but the depreciation is climbing *now too*, and it will peak in 2-3 years before stabilizing as the capex growth rate slows.

The FCF compression is immediate. The earnings hit is amortized. That's why FCF looks worse than it is and net income looks better than it is — for now.

---

## Depreciation: What Each Company Is Running

**All figures below are from SEC EDGAR filings — see exact line items in the correction log.**

### Amazon

**Source:** amzn-20241231.htm (FY2024 10-K)

**Important distinction:** Amazon's cash flow statement shows a combined line: "Depreciation and amortization of property and equipment and capitalized content costs, operating lease assets, and other." The $52.8B figure includes capitalized content, operating lease assets, and intangibles — not just PP&E.

The segment-level breakdown gives you the PP&E-only depreciation:

| Period | PP&E Depreciation (segment D&A) | Total D&A (cash flow line) |
|---|---|---|
| FY2022 | $24.9B | $41.9B |
| FY2023 | $30.2B | $48.7B |
| FY2024 | $32.1B | $52.8B |
| TTM Q1 2025 | ~$34B (implied) | **$55.4B** |

AWS PP&E depreciation by segment (PP&E only, not total D&A):

| Period | AWS D&A |
|---|---|
| FY2022 | $9.9B |
| FY2023 | $12.5B |
| FY2024 | $13.3B |

AWS PP&E net on the balance sheet: $60.3B (FY2022) → $72.7B (FY2023) → **$110.7B (FY2024)**. Nearly doubled in two years.

**Server useful life — full history (not just the 2024 change):**
- Pre-January 2022: **4 years** (from FY2023 10-K: "We had previously increased the useful life of our servers from four years to five years in January 2022.")
- January 2022: Changed to **5 years**
- January 2024: Changed to **6 years** (effective Jan 1, 2024)
- January 2025: Changed back to **5 years for certain servers** (disclosed in FY2024 10-K)

**Dollar impact of the Jan 2024 change (5 → 6 years):**

From the FY2024 10-K, exact quote:
> "The effect of this change for the year ended December 31, 2024, based on servers that were included in 'Property and equipment, net' as of December 31, 2023 and those acquired during the year ended December 31, 2024, was a reduction in depreciation and amortization expense of **$3.2 billion** and a benefit to net income of **$2.5 billion**, or **$0.23 per basic share and $0.23 per diluted share**."

The company then reversed part of this in January 2025, extending useful life again for some servers — the accounting is fluid.

---

### Microsoft

**Source:** msft-20250630.htm (FY2025 10-K)

**The D&A line is combined:** "Depreciation, amortization, and other" — this bundles PP&E depreciation, intangible amortization, and other items. There is no standalone PP&E depreciation line in the cash flow statement.

| Period | D&A (combined line) |
|---|---|
| FY2022 | $14.5B |
| FY2023 | $13.9B |
| FY2024 | $22.3B |
| FY2025 | **$34.2B** |

D&A nearly doubled in two years. PP&E net on the balance sheet: $74.4B (FY2022) → $95.6B (FY2023) → $135.6B (FY2024) → **$205.0B (FY2025)**. A $69B jump in one year.

**Server useful life — current policy (from FY2025 10-K Note 1):**

> "computer equipment, **two to six years**"

**Historical change (from FY2023 10-K):**

> "In July 2022, we completed an assessment of the useful lives of our server and network equipment... we determined we should increase the estimated useful lives of both server and network equipment **from four years to six years**. This change in accounting estimate was effective **beginning fiscal year 2023**."

**Dollar impact of the July 2022 change:**

> "Based on the carrying amount of server and network equipment included in property and equipment, net as of June 30, 2022, the effect of this change in estimate for fiscal year 2023 was an increase in operating income of **$3.7 billion** and net income of **$3.0 billion**, or **$0.40 per both basic and diluted share**."

Note: This impact was in FY2023, not FY2025. The prior version said "after fixing the revenue number" — that was referring to the MSFT FY2025 10-K, which changed the revenue figure from $262B to $281.7B. The useful life change and its dollar impact are from the FY2023 10-K. These are two separate disclosures.

---

### Alphabet

**Source:** goog-20241231.htm (FY2024 10-K)

| Period | PP&E Depreciation |
|---|---|
| FY2022 | $13.5B |
| FY2023 | $11.9B |
| FY2024 | **$15.3B** |

Note: Depreciation actually *decreased* in FY2023 vs FY2022 ($13.5B → $11.9B). The FY2024 figure (+28% YoY) is the acceleration driven by new AI infrastructure.

PP&E net: $134.3B (FY2023) → **$171.0B (FY2024)** — a $36.7B jump in one year. Technical infrastructure (data centers, servers, networking) drove most of it: $112.5B → $139.6B gross.

**Useful life (from Note 1 — exact quote):**

> "We depreciate servers and network equipment generally over a period of **six years**."

No recent changes to useful life disclosed in the FY2024 filing.

---

### Meta

**Source:** meta-20241231.htm (FY2024 10-K) and meta-20250331.htm (Q1 2025 10-Q)

| Period | D&A |
|---|---|
| FY2022 | $8.7B |
| FY2023 | $11.2B |
| FY2024 | **$15.5B** |
| Q1 2025 (quarter) | **$3.9B** |

PP&E net: $96.6B (FY2023) → $121.3B (FY2024) → $133.6B (Q1 2025). Servers and network assets: $68.4B gross at end of FY2024, growing to $75.9B by Q1 2025.

**Useful life (FY2024 10-K, before the change):**

> "Servers and network assets: **Four to Five years**"

**Useful life change (Q1 2025 10-Q, exact quote):**

> "In January 2025, we completed an assessment of the useful lives of property and equipment, which resulted in an increase in the estimated useful lives of most servers and network assets to **5.5 years**, effective **January 1, 2025**."

**Dollar impact (Q1 2025 10-Q, exact quote):**

> "Based on the servers and network assets placed in service as of December 31, 2024, the financial impact of this change in estimate included a reduction in depreciation expense of **$826 million** and an increase in net income of **$695 million**, or **$0.27 per diluted share**, for the three months ended March 31, 2025."

Note: The Q1 impact is $826M. The FY2024 10-K (which predates the change) estimated the full-year FY2025 impact at ~$2.9B. Both are correct — the $2.9B is the annualized estimate; $826M is the Q1 actual for three months.

---

## The Capex-to-Depreciation Lag: Plain Numbers

**Warning: The projections below for 2026-2028 are estimates, not reported figures. They are based on the capex base, useful life schedules, and my assumptions about whether capex growth slows. Do not read them as filings.**

For Amazon, the depreciation schedule from the current asset base works roughly as follows:

| Year | Capex Spent | Approximate Annual D&A Run Rate | Notes |
|---|---|---|---|
| 2022 | ~$49B | ~$25B (PP&E only) | PP&E D&A was $24.9B |
| 2023 | ~$49B | ~$30B | 6-year servers depreciating |
| 2024 | ~$78B | ~$32B (PP&E only, reduced by server life extension) | 6-year life, $3.2B benefit from change |
| 2025 | ~$128B | ~$35B (PP&E only, estimated) | Server life extended back to 5 years for some assets |
| **2026** | **~$200B (guided)** | **~$45-50B (PP&E only, estimated)** | Capex doubling adds to base |
| **2027** | **?** | **~$60B+ (PP&E only, estimated)** | 2022-2023 capex completes depreciation; 2024-2025 capex still running |
| **2028** | **?** | **~$70B+ (PP&E only, estimated)** | Peak drag from current build cycle |

These estimates assume capex grows at the guided rate in 2026 and then plateaus. If it doesn't plateau, the estimates are low. If capex slows, depreciation peaks around 2030-2031 and then falls as a percentage of revenue.

For Microsoft and Meta, the same math applies — just with smaller bases and slightly shorter asset lives. Microsoft's PP&E net of $205B will generate accelerating depreciation for 4-6 years from the asset addition date.

---

## Jassy in His Own Words

**Source:** [Amazon 2025 Letter to Shareholders](https://www.aboutamazon.com/news/company-news/amazon-ceo-andy-jassy-2025-letter-to-shareholders), published April 9, 2026. All quotes verified word-for-word against the actual letter.

---

**On the 2014 AWS operating plan review:**

> "At our 2014 AWS operating plan review, the discussion started with a senior leader at the company musing, 'Tell me again why we're doing this business?'"

---

**On why the path isn't linear:**

> "There's a band I like from New Zealand called 'The Beths,' who've written several excellent records, with thought-provoking lyrics. I eagerly await their new releases, and when their latest album dropped last summer titled 'Straight Line Was a Lie,' it made me think about how prescient that expression is. Most long-term endeavors do not follow a linear straight line, up and to the right. Progress jumps around; it'll zig up, then sometimes stall, or zag down, or force you back to the starting line. Sometimes, it feels like you're running in circles. But, the path is rarely straight."

---

**On the current AI capex and FCF trade-off:**

> "We are willing to make large capex investments and endure short-term FCF headwinds for the substantial medium to long-term FCF surplus. AI is a once-in-a-lifetime opportunity where the current growth is unprecedented and the future growth even bigger. AWS has a significant leadership position with the broadest functionality, strongest security and operational performance, largest share of customers and revenue, strong desire from customers to run their AI in AWS, and an opportunity to build what could be a new pillar for Amazon in chips. We're not going to be conservative in how we play this — we're investing to be the meaningful leader, and our future business, operating income, and FCF will be much larger because of it."

---

**The AWS scale comparison — exact figures from the letter:**

> "Three years after AWS launched commercially, it had a $58 million revenue run rate. Three years into this AI wave, AWS's AI revenue run rate is over $15 billion in Q1 2026 (nearly 260 times larger than AWS at that same point)"

> "AWS revenue increased 20% YoY, from $108 billion to $129 billion."

> "In Q4 2025, AWS reported 24% YoY growth with a $142 billion dollar revenue run rate."

Note: The $4.6B AWS figure was from an earlier letter (2024). In the 2025 letter, Jassy anchors on the $58M run rate three years after AWS launch and the $15B+ AI run rate in Q1 2026. The 260x comparison is between those two figures, not involving $4.6B.

---

## What This Changes About the Picture

The FCF fear is real on a cash flow basis but structurally incomplete. Here's why:

1. **Capex is an investment, not a cost.** When Amazon spends $128B on data centers, it doesn't disappear — it becomes a $128B+ asset on the balance sheet that generates returns for 5-10+ years.

2. **Depreciation is the lag, not the problem.** The earnings hit from $128B capex will show up gradually over 4-6 years, not all at once. The income statement will show higher D&A, lower margins, and lower net income — but the underlying cash generation of the assets hasn't changed.

3. **The peak profit drag is ahead, not behind.** For Amazon especially, the biggest D&A increases are still coming as 2024-2026 capex works through the depreciation schedule. Net income will look worse before it looks better.

4. **Jassy's case is historical, not theoretical.** AWS in 2014 faced the same FCF headwinds and market skepticism. The result: AWS grew from a $58M run rate to $129B in annual revenue. The capex that looked wasteful in 2014 generated enormous returns.

5. **The question is whether the AI revenue ramp is real.** Jassy points out AI revenue run rate at AWS is 260x where AWS was at the same stage of its cycle. If that holds, the capex-to-depreciation lag is a rounding error on a 10-year horizon. If it doesn't, it's a problem.

---

## Correction Log: What Was Right, Wrong, and Changed

### Errors Corrected

| Item | Prior (wrong) | Verified (correct) | Source |
|---|---|---|---|
| Amazon total D&A description | Called it "PP&E depreciation only" | It's a combined line including capitalized content, operating leases, and intangibles | amzn-20241231.htm cash flow statement |
| Amazon server useful life history | Only mentioned the Jan 2024 change (5→6 years) | Full history: 4 years pre-2022, 5 years Jan 2022, 6 years Jan 2024, back to 5 years for some assets Jan 2025 | amzn-20241231.htm and amzn-20231231.htm |
| Meta useful life dollar impact | Used $2.9B for Q1 impact | Q1 2025 actual impact was **$826M**. The $2.9B is the FY2024 10-K's forward estimate for full-year FY2025 | meta-20250331.htm (Q1 2025 10-Q) |
| Jassy's AWS baseline figure | Said $4.6B in revenue | The letter uses **$58 million** run rate (three years after AWS launch), not $4.6B | aboutamazon.com 2025 letter |
| 2026-2028 depreciation projections | Not labeled | **Now clearly labeled as estimates** — not from any filing | N/A |

### Verified as Correct

| Item | Value | Source |
|---|---|---|
| Amazon D&A: FY2024 $52.8B (total), $32.1B (PP&E only) | Verified | amzn-20241231.htm |
| Amazon PP&E net: FY2024 $252.7B | Verified | amzn-20241231.htm balance sheet |
| AWS PP&E D&A: FY2024 $13.3B | Verified | amzn-20241231.htm segment table |
| Amazon Jan 2024 server life change impact: -$3.2B D&A, +$2.5B net income | Verified (exact quote) | amzn-20241231.htm |
| MSFT D&A: FY2025 $34.2B, FY2024 $22.3B | Verified | msft-20250630.htm |
| MSFT PP&E net: FY2025 $205.0B | Verified | msft-20250630.htm balance sheet |
| MSFT server life change: 4→6 years, July 2022, effective FY2023 | Verified (exact quote) | msft-20250630.htm (references FY2023 10-K) |
| MSFT server life change FY2023 impact: +$3.7B operating income, +$3.0B net income | Verified (exact quote) | msft-20250630.htm |
| Alphabet PP&E depreciation: FY2024 $15.3B, FY2023 $11.9B | Verified | goog-20241231.htm |
| Alphabet PP&E net: FY2024 $171.0B | Verified | goog-20241231.htm balance sheet |
| Alphabet server useful life: 6 years | Verified (exact quote) | goog-20241231.htm |
| Meta D&A: FY2024 $15.5B, Q1 2025 $3.9B | Verified | meta-20241231.htm, meta-20250331.htm |
| Meta PP&E net: FY2024 $121.3B, Q1 2025 $133.6B | Verified | meta-20241231.htm, meta-20250331.htm |
| Meta server useful life change: 4-5 years → 5.5 years, Jan 2025 | Verified (exact quote) | meta-20250331.htm |
| "Straight Line Was a Lie" quote | Exact words confirmed | aboutamazon.com |
| "Tell me again why we're doing this business?" quote | Exact words confirmed | aboutamazon.com |
| "Willing to make large capex investments" quote | Exact words confirmed | aboutamazon.com |
| AWS AI run rate: $15B+ in Q1 2026, 260x comparison | Exact figures confirmed | aboutamazon.com |
| AWS 2025 revenue: $129B, up 20% YoY | Exact figure confirmed | aboutamazon.com |

### Cross-Check: Amazon D&A vs Earnings Release

Amazon's Q1 2025 earnings release confirms TTM D&A of **$55,373M** for the twelve months ended March 31, 2025. The FY2024 10-K shows $52,795M for the year ended December 31, 2024. These are consistent (different time periods — FY vs TTM). ✓

---

## Sources

- [Amazon 10-K FY2024](https://www.sec.gov/Archives/edgar/data/1018724/000101872425000004/amzn-20241231.htm) — D&A, PP&E net, segment D&A, server useful life history, Jan 2024 change impact
- [Amazon 10-K FY2023](https://www.sec.gov/Archives/edgar/data/1018724/000101872424000008/amzn-20231231.htm) — prior server useful life
- [Amazon Q1 2025 Earnings Release](https://ir.aboutamazon.com/news-release/news-release-details/2025/Amazon-com-Announces-First-Quarter-Results/default.aspx) — TTM D&A $55,373M
- [Microsoft 10-K FY2025](https://www.sec.gov/Archives/edgar/data/789019/000095017025100235/msft-20250630.htm) — D&A $34.2B, PP&E $205B, useful life policy
- [Microsoft 10-K FY2023](https://www.sec.gov/Archives/edgar/data/789019/000095017024079846/msft-20230930.htm) — server life change from 4 to 6 years, dollar impact
- [Alphabet 10-K FY2024](https://www.sec.gov/Archives/edgar/data/1652044/000165204425000014/goog-20241231.htm) — PP&E depreciation $15.3B, PP&E $171B, useful life
- [Meta 10-K FY2024](https://www.sec.gov/Archives/edgar/data/1326801/000132680125000017/meta-20241231.htm) — D&A $15.5B, PP&E $121.3B, useful life
- [Meta 10-Q Q1 2025](https://www.sec.gov/Archives/edgar/data/1326801/000132680125000054/meta-20250331.htm) — D&A Q1 $3.9B, useful life change to 5.5 years, $826M Q1 impact
- [Amazon 2025 Letter to Shareholders](https://www.aboutamazon.com/news/company-news/amazon-ceo-andy-jassy-2025-letter-to-shareholders) — Jassy quotes, AWS figures, AI run rate