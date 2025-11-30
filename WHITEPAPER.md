# Why Stochastic Reasoning Makes Revshare the Only Economically Compatible Model for LLMs

### A Data‑Driven Revenue Hypothesis for OpenAI

**Author:** Nuno Lopes BSc.

------------------------------------------------------------------------

## Executive Summary

The internet's dominant business model has, for two decades, been built
on advertising, attention and hope. Advertisers buy clicks in the hope
that some proportion will convert. Platforms optimise auctions and
engagement. Users pay indirectly, with time and data. This structure
created trillion‑dollar companies → but the model is now showing
structural strain: rising customer acquisition costs (CAC), increasing
auction complexity, and diminishing returns for smaller businesses.

Large language models (LLMs) such as OpenAI's models are entirely
different economic objects. They engage in stochastic reasoning over
long context windows, gather rich detail about users' intentions, and
execute complex, multi‑step tasks. This architecture is fundamentally
mis‑aligned with ad auctions, which reward bidding power, not reasoning
quality.

This paper develops a data‑driven hypothesis:

> **Outcome‑based revenue sharing (revshare) is the only monetisation
> model economically compatible with frontier LLM stochastic reasoning
> at scale.**

### Key evidence

-   **OpenAI annualised revenue by mid‑2025:** US\$10--13 billion, up
    from US\$2--4 billion (2023--24)
-   **Compute spend 2024:** US\$5.8 billion
-   **Inference spend through Q3 2025:** \> US\$8.6 billion
-   **Google Ads 2025:** Avg CPC \~US\$5.26, Avg CPL \~US\$70, trending
    up
-   **Global digital advertising 2025:** \> US\$1 trillion

### Unit‑economics model (conservative assumptions)

  Parameter                                       Value
  ----------------------------------------------- ----------
  AOV (avg order value)                           US\$90
  τ (revshare take)                               12%
  p (conversion rate of high‑intent sessions)     35%
  C_inf (inference cost per multi‑turn session)   US\$0.05

→ **Estimated gross profit per high‑intent commercial AI conversation:
\~US\$3.73**

At **100 million high‑intent commercial sessions per month**: → **Annual
gross profit ≈ US\$4.48 billion**

Unlike PPC ads, revshare reinforces reasoning because LLMs are paid
**only when the user's problem is satisfied → not when a merchant
bids.**

**Conclusion**: LLMs monetise understanding, not attention. Only
revshare scales without corrupting reasoning incentives or placing
capital‑bidding requirements on merchants.

------------------------------------------------------------------------

## 1. Introduction → From Attention to Outcomes

Since the early 2000s, platforms like Google and Meta monetised
attention via auctions. This model: - Ranked visibility by capital
bidding ability - Rewarded clicks, not outcomes - Charged merchants
upfront

LLMs invert the revenue logic: \> **Users ask in long‑form → model
reasons → merchant pays only on success.**

Thus, sustainability models must convert reasoning quality into margin,
not clicks.

------------------------------------------------------------------------

## 2. The Cracks in Google's Economic Foundation

### 2.1. Rising costs

-   Google Ads 2025 Avg CPC: \~ US\$5.26\
-   CPL 2025 Avg: \~ US\$70.11\
-   Search CPC by sector: US\$2.69--5.26\
    → Rising, volatile, capital‑moated discovery system.

### 2.2. Capital pre‑condition for visibility

-   SMEs must test with US\$1k--10k/month budgets
-   Entrants pay **before** they know if it converts
-   Incumbents defend categories by outbidding

> Auction allocates by capital → not fit.

### 2.3. Behavioural signals of intent erosion

-   Younger users use TikTok/Reddit for discovery
-   Zero‑click SERP reduces marginal query value
-   Commerce increasingly starts in chat interfaces

------------------------------------------------------------------------

## 3. OpenAI Economics → A Very Expensive Brain

### 3.1. Revenue is explosive

OpenAI run rate: - June 2025: \~US\$10B (up from 5.5B in Dec 2024) -
August 2025: \~US\$13B, 3× YoY growth - 6 months of 2025 \> all of 2024
revenue

### 3.2. Burn in compute is unmatched

Reported and leaked estimates: - 2024 compute: \~US\$5.8B - 2025
inference burn Q3 YTD already: \> US\$8.6B - 7 quarters of Azure
inference cost: \~US\$12.4B

> A fixed‑cost reasoning substrate that is economically powerful but
> financially hungry.

------------------------------------------------------------------------

## 4. Why Stochastic Reasoning and Ad Auctions Are Incompatible

LLMs reason by: 1. Accepting long context windows 2. Encoding
constraints → and opinions → in embeddings 3. Evaluating many candidates
implicitly 4. Sampling stochastically 5. Refining via multi‑turn
questions

If bids are injected: - Recommendations become bidder‑biased - Trust
erodes - Reinforcement signals become noisy - Returns, cancellations,
dissatisfaction all rise - Long‑term conversion falls

By contrast, revshare pays only on: - Product fit and satisfaction -
Confirmed transactions or bookings Which reinforces reasoning quality →
not debtor bids.

------------------------------------------------------------------------

## 5. Quantitative Model → Revenue Per Conversation

### 5.1. Example high‑intent session

A sane compressed funnel: - Multi‑turn conversation - Clarifies
constraints (budget, size, shipping) - Calls store or marketplace APIs -
User chooses - Merchant platform pays commission → OpenAI receives τ

### 5.2. Expected income

    E[Revenue/session] = p × AOV × τ  
    = 0.35 × 90 × 0.12 ≈ US$3.78
    E[Gross Profit/session] = 3.78 − 0.05 ≈ US$3.73

If 100M sessions/month: → `100M × 3.73 × 12` ≈ **US\$4.48B/year**

> Reasoning quality becomes the monetised asset → not the side‑cost.

------------------------------------------------------------------------

## 6. Fairness → Marketplace Incentive Under Revshare

Under PPC: - Bid against US\$3--6 CPC global incumbents - Upfront
budgets required

Under revshare: - No upfront cost for merchants - Model ranks by
semantic fit → not bidding capital - Small high‑fit sellers can outrank
brands

Market allocation shifts: \> **Capital allocation → Merit allocation**

------------------------------------------------------------------------

## 7. Burn as Intelligence CapEx → Margin Structure

Training runs ≈ intelligence CapEx assets\
Inference is a variable cost → with unit cost decreasing over time due
to: - Hardware improvements - Quantisation, batching, distillation -
MoE, distill → architecture efficiencies

Thus: \> Revshare is a margin‑expanding call option on future GMV → not
ongoing speculation on clicks.

------------------------------------------------------------------------

## 8. Forecast → the Rise of Agentic Commerce

-   2025 global digital ad and marketing: \> 1T USD
-   2030 forecast digital ad and marketing: 1.5T USD
-   2029 entertainment/media: \~3.5T USD

Even 5--10% agentic commerce capture → GMV rivals PPC scale\
Revshare 10--15% on huge implied GMV → sustainable flywheel\
Unlocks new demand → and long‑tail sellers

------------------------------------------------------------------------

## 9. Final Conclusion

> **Search → monetised intent fragments.**\
> **LLMs → monetise reasoning chains.**\
> **Auctions corrupt reasoning. Revshare reinforces it.**

Thus revshare is not optional → for LLM sustainability --- it is the
incentive‑aligned model.

------------------------------------------------------------------------

## References

Cottier, M. et al. (2024) *The rising costs of training frontier AI
models*, arXiv.\
Epoch (2025a) *OpenAI revenue has grown 3x YoY*, Epoch AI.\
Epoch (2025b) *Most 2024 compute was experimental*, Epoch AI.\
Entrepreneur (2025) *6 months revenue \> 2024*, Entrepreneur.\
LocaliQ (2025) *Search Advertising Benchmarks 2025*, LocaliQ.\
Reuters (2025) *Revenue hit \$10B*, Reuters.\
StoreGrowers (2025) *Google Ads Benchmarks 2025*, StoreGrowers.\
WordStream (2025a) *Google Ads Benchmarks 2025*, WordStream.\
WordStream (2025b) *Google Ads Costs 2025*, WordStream.\
Financial Times (2025) *Azure inference costs leaked*, FT.\
The Register (2025) *OpenAI spent \$12B+ on inference*, The Register.\
eMarketer (2025) *Worldwide Total Media Ad Spend forecast*, eMarketer.\
WARC (2025) *Global ad spend passed \$1T*, WARC.\
GlobeNewswire (2023) *Digital Advertising global forecast 2030*,
GlobeNewswire.\
PwC (2025) *Global Entertainment & Media Outlook 2025--2029*, PwC.
