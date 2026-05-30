# Demand Signals: Backlog, Build Timing, and When the Cash Rolls In

**Sources:** SEC EDGAR filings (10-K, 10-Q), earnings call transcripts, investor relations.
**Date:** 2026-05-30.
**Verification:** 2026-05-30 — re-confirmed all figures against source filings. Microsoft $625B commercial backlog and OpenAI 45% concentration removed — neither is in the 10-K.

---

## The Backlog: What Each Company Reports

**Note on terminology:** "Backlog" is often reported as "Remaining Performance Obligations" (RPO) in 10-K filings under ASC 606 revenue recognition rules. These represent contracted future revenue not yet recognized — committed, not speculative. The numbers below are from confirmed filings unless noted otherwise.

---

### Microsoft — Commercial RPO

**Source:** msft-20250630.htm (FY2025 10-K)

| Period | Total RPO | Commercial RPO |
|---|---|---|
| June 30, 2025 | ~$375B | **~$368B** |
| June  30, 2024 | ~$275B | **~$269B** |
| **YoY Growth** | **~36%** | **~37%** |

- 40% of total RPO expected to be recognized in the next 12 months
- Microsoft does NOT break out RPO by segment (Intelligent Cloud vs. other) in the 10-K
- "Commercial remaining performance obligation" is the term used in the filing

**OpenAI concentration:** The 10-K confirms the partnership (Microsoft is a major investor, with reciprocal revenue-sharing arrangements and rights to OpenAI's IP). The 10-K does NOT disclose any customer-level RPO breakdown. No percentage of Azure backlog attributed to any single customer appears in the filing. The concentration risk is real and worth tracking, but the specific "45% of Azure backlog" figure is not supported by the 10-K.

---

### Amazon — Long-Duration Performance Obligations

**Source:** amzn-20251231.htm (FY2025 10-K, reported on Q4 2025 earnings call)

| Period | Long-Duration RPO | YoY Growth | Weighted Avg Life |
|---|---|---|---|
| FY2025 (Dec 31, 2025) | **$244B** | **~+40%** | **4.1 years** |

- Primarily attributed to AWS
- Jassy confirmed this on the Q4 2025 earnings call
- This replaces the prior estimate of $177-189B (which was the FY2024 10-K figure before FY2025 was filed)

**What this means:** $244B in committed future revenue with a 4.1-year weighted average life gives Amazon significant revenue visibility well beyond current quarter. The backlog is growing faster than revenue (+40% vs ~20% AWS growth rate), meaning the conversion tail is extending.

---

### Alphabet — Revenue Backlog

**Source:** goog-20241231.htm (FY2024 10-K) and goog-20250331.htm (Q1 2025 10-Q)

| Period | RPO / Revenue Backlog | Attribution |
|---|---|---|
| Dec 31, 2024 | **$93.2B** | Primarily Google Cloud |
| Dec 31, 2023 | $74.1B | Primarily Google Cloud |
| **YoY Growth** | **+25.8%** | |
| Mar 31, 2025 | $92.4B | Primarily Google Cloud |

- Approximately half expected to be recognized within 24 months
- Clean attribution to Google Cloud (not a company-wide figure)

---

### Summary: Backlog Comparison

| Company | Confirmed Backlog | YoY Growth | Weighted Avg Life | Attribution |
|---|---|---|---|---|
| Microsoft | ~$368B (commercial RPO) | ~+36% | ~40% in next 12 months | Total company |
| Amazon | **$244B** | **~+40%** | **4.1 years** | Mostly AWS |
| Alphabet | $93.2B | +26% | ~50% in 24 months | Google Cloud |

---

## Build Timing: What the Companies Actually Say

**Important:** The companies do not give specific data center build times or inflection years in their filings or earnings calls. What they describe is a capacity-constrained demand environment where supply is the binding constraint, not demand.

---

**From Microsoft Q2 FY2025 call (January 29, 2025):**

Satya Nadella:
> "We have more than doubled our overall data center capacity in the last three years. And we have added more capacity last year than any other year in our history."

Amy Hood:
> "More than half of our cloud and AI related spend was on long-lived assets that will support monetization over the next 15 years and beyond."

**On the two-part constraint (Keith Weiss, Morgan Stanley):**
> "When I talk about being at a capacity constraint, it takes two things. You have to have a space — that's the infrastructure and the land. And then you have to have kits. We're continuing, and you've seen that's why our spend has pivoted this way to be in the long-lived investment. We have been short power and space."

> "As you see, those investments land that we've made over the past three years, we get closer to that balance by the end of this year."

**On CapEx-to-revenue correlation (Karl Keirstead, UBS):**
> "The frontend has been this infrastructure build — data centers. And then you'll see the pivot to more CPU and GPU, and that pivot will more directly correlate to revenue."

---

**From Amazon Q1 2025 call (May 1, 2025):**

Andy Jassy:
> "As fast as we put capacity in, it's being consumed. I think we could be doing more if we had more capacity."

> "Supply chain and capacity issues will continue to get better as the year proceeds."

**CFO Brian Olsavsky:**
> "We do have a lot of investment in infrastructure going on and planned for the second half of the year."

---

**What this means for timing:**

There is no official "X months to build a data center" disclosure from any of these companies. The picture that emerges from the calls is:

1. **Capacity is the constraint, not demand.** Both Jassy and Nadella describe demand as outpacing supply. This is the opposite of a demand problem.

2. **Build cycles are multi-year.** MSFT describes a ~3-year cadence for major capacity additions and says the balance is "approaching" by end of FY2025. Amazon is still behind — supply chain issues persisting into H2 2025.

3. **Asset lives are 15+ years.** Amy Hood's "15 years and beyond" framing means the companies are modeling returns on a generational horizon, not a quarterly one.

4. **The capex-to-revenue pivot is beginning, not ending.** MSFT says FY26 will pivot from long-lived infrastructure toward servers "more correlated to revenue." That shift is the inflection point management is pointing to — **but they don't give a specific year.**

---

## When Does This Actually Start Turning Into Revenue?

**Estimate — not from filings:**

Based on what management described on earnings calls:

- **Microsoft:** H2 FY2025 (the period ending June 2025) was described as when the capacity constraint begins to ease. The pivot from infrastructure-heavy CapEx to server CapEx (directly correlated to revenue) was expected to start in FY26. Azure growth acceleration was guided for H2.

- **Amazon:** Already converting — AWS at $129B revenue (+20% YoY). Capacity is the binding constraint. As supply chain eases through 2025, revenue follows the backlog. Jassy describes AI revenue as already real and growing triple digits.

- **Alphabet:** More measured. Google Cloud backlog has ~24 months of visibility on half the $93B. The growth path is there but the base is smaller.

**The honest answer:** The companies are pointing to H2 2025 through FY2026 as when the revenue inflection becomes visible. But they are not giving specific years for "peak depreciation" or "normalized FCF" — those are estimates made from the data, not from management guidance.

---

## Is the Demand Booked or Hope?

**Booked:**
- Microsoft: $368B commercial RPO, growing ~36% YoY
- Amazon: $244B long-duration RPO, growing ~40% YoY, 4.1-year weighted average life
- Alphabet: $93B revenue backlog, +26% YoY, attributed to Google Cloud

**The demand signal is real.** RPO is contracted revenue — it represents customers who have committed to pay for services not yet delivered. The 36-40% growth rates are not indicative of hope; they are indicative of committed demand outpacing the companies' ability to deliver.

**The risks:**
1. **Microsoft concentration:** The 10-K confirms OpenAI as a major partnership with revenue-sharing, but does not disclose what percentage of Azure or commercial RPO depends on OpenAI. This is worth tracking through the 10-Q disclosures or independent verification.
2. **RPO recognition timing:** If contracts are terminated or delayed, RPO can be reduced. The "40% in next 12 months" for MSFT and "~50% in 24 months" for GOOGL means there is execution risk built into these numbers.
3. **Supply push-out:** Both companies mentioned third-party supply delays (GPU kits, motherboards, components) pushing deliveries into later quarters. If supply constraints persist, the backlog converts slower than the contract life implies.

---

## Key Takeaways

1. **The backlog is real and growing at 26-40% YoY across all three companies.** This is not speculative demand — it is contracted, recognized under accounting rules, and growing faster than current revenue.

2. **Capacity, not demand, is the constraint.** Both Microsoft and Amazon explicitly say demand exceeds supply. Alphabet is more measured but still growing.

3. **Timing is not disclosed.** No company gives a specific build time or inflection year. The estimates in this file are derived from the data, not from management guidance. The "H2 2025 through FY2026" timing comes from earnings call language, not specific date commitments.

4. **Microsoft's OpenAI concentration risk is real but unquantified in the 10-K.** The partnership is disclosed; the backlog percentage is not. Don't use the 45% figure unless you can source it independently.

5. **The conversion path is clear but the pace is uncertain.** The backlog exists. The capacity is coming. The question is whether AI revenue grows fast enough that the 2026-2028 depreciation peak is absorbed by the revenue ramp — and that answer is still 2-3 years away.

---

## Sources

- [Microsoft 10-K FY2025](https://www.sec.gov/Archives/edgar/data/789019/000095017025100235/msft-20250630.htm) — Commercial RPO ~$368B, partnership with OpenAI disclosed, no customer concentration percentage
- [Alphabet 10-K FY2024](https://www.sec.gov/Archives/edgar/data/1652044/000165204425000014/goog-20241231.htm) — Revenue backlog $93.2B
- [Alphabet 10-Q Q1 2025](https://www.sec.gov/Archives/edgar/data/1652044/000165204525000027/goog-20250331.htm) — RPO $92.4B as of Mar 31, 2025
- [Amazon 10-K FY2025](https://www.sec.gov/Archives/edgar/data/1018724/000101872426000004/amzn-20251231.htm) — Long-duration RPO $244B, 4.1-year weighted average life
- [Microsoft Q2 FY2025 Earnings Call Transcript](https://www.microsoft.com/en-us/investor/events/fy-2025/earnings-fy-2025-q2) — Build timing, capacity constraints, CapEx pivot
- [Amazon Q1 2025 Earnings Call Transcript](https://ir.aboutamazon.com/news-release/news-release-details/2025/Amazon-com-Announces-First-Quarter-Results/default.aspx) — Demand signals, capacity constraint