# Why Stochastic Reasoning Makes Revshare the Only Economically Compatible Model for LLMs

## A Data‑Driven Revenue Hypothesis for OpenAI

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
can execute complex, multi‑step tasks. This architecture is
fundamentally mis‑aligned with ad auctions, which reward bidding power
rather than reasoning quality.

This paper develops a data‑driven hypothesis:

> **Outcome‑based revenue sharing (revshare) is the only monetisation
> model economically compatible with frontier LLM stochastic reasoning
> at scale.**

Key arguments: - OpenAI reached an annualised revenue run‑rate of
\~US\$10--13B by mid‑2025, up from \~US\$2--4B in 2023--24. - Compute
costs are extraordinary → cumulative Azure inference likely \>US\$12B
since 2024, with 2025 inference YTD by Q3 \>US\$8.6B. - Google Ads 2025
benchmarks show Avg CPC \~US\$5.26 and Avg CPL \~US\$70, with upward
pressure especially for SMEs. - Global 2025 ad‑spend \>US\$1T, with
digital now the majority and accelerating toward 2030 dominance.

Quantitative modelled outcome: - A high‑intent, multi‑turn commerce
session can plausibly deliver **\~US\$3.73 gross profit → if the AOV is
US\$90, revshare τ = 12%, conversion p = 35%, and marginal inference
cost = US\$0.05**. - At 100M high‑intent sessions/month →
**\~US\$4.48B/year gross profit opportunity** --- enough to hedge
inference burn while scaling a reasoning‑aligned revenue layer without
capital gating.

Conclusion: LLMs monetise understanding → not attention. Only revshare
scales without corrupting reasoning incentives or embedding bidder
capital into the recommendation layer.

------------------------------------------------------------------------

## 1. Introduction → From Attention to Outcomes

Since the early 2000s, platforms like Google and Meta monetised
attention via auctions. This discovery system: - Captured user attention
(search, feeds, video) - Sold visibility to advertisers by bidding -
Optimised for clicks and impressions, not confirmed outcomes - Treated
capital, not merit, as the precondition for visibility

LLMs invert the model: - Rank semantic fit, implicitly vector‑space
compare many options - Clarify constraints through multi‑turn reasoning
chains - Execute via APIs and payments tool calls - Monetise only on
completed outcomes (revshare)

Thus auction‑driven ad‑models are structurally incompatible --- they
corrupt reasoning.

------------------------------------------------------------------------

## 2. The Cracks in Google's Economic Foundation

### 2.1. Rising Costs and Fragile Margins

Benchmarks indicate: - **2025 Avg CPC \~US\$5.26, Avg CPL
\~US\$70.11.** - Search CPC by vertical in US\$2.69--5.26 range. -
Display CPC \~US\$0.63, upward trend over multi‑year horizon.

Result: - Higher margins pressure - Paid bidding sophistication
required - Capital moated visibility

### 2.2. Capital as a Precondition for Visibility

To test discovery: - SMEs accept US\$1k--10k/month budgets - Uncertain
conversion - Entrants pay **before** knowing outcomes - Incumbents
defend categories by outbidding

Thus visibility is capital‑allocated, not merit‑allocated.

### 2.3. Behavioural Signals of Intent Erosion

Shifts: - Younger users use social platforms (TikTok, Reddit) for
discovery - "Zero‑click" answers reducing marginal downstream clicks and
SEO value - LLM chat interfaces used increasingly for commercial queries

------------------------------------------------------------------------

## 3. OpenAI Economics → A Very Expensive Brain

### 3.1. Revenue Growth

-   Internal and independent estimates suggest OpenAI revenue run‑rate
    reached \~US\$13B by August 2025, and was \~US\$10B by June 2025.
-   2025 H1 revenue \> full 2024 revenue.
-   One of the fastest‑scaling software infrastructures in history.

### 3.2. Compute Costs

Reported/leaked estimates: - **2024 Compute = US\$5.8B** (\~US\$3B
training, US\$1.8B inference, US\$1B research) - **2025 inference YTD by
Q3 already ≈ US\$8.67B** - **Cumulative Azure inference 7+ quarters ≈
US\$12.4B+**

Implication: - Frontier LLMs require a business model that scales via
reasoning performance, not bids or clicks.

------------------------------------------------------------------------

## 4. Why Stochastic Reasoning and Ad Auctions Are Incompatible

Actual LLM reasoning: 1. Accept long context 2. Embed constraints +
preferences 3. Compare many candidates implicitly in vector space 4.
Sample stochastically 5. Refine intent via multi‑turn questions

If you inject bids: - Candidate list becomes bidder‑biased - Trust
collapses - Feedback loops become noisy - Long‑term conversion
declines - Returns/cancellations explode

By contrast, revshare pays on real completed outcomes → reinforcing
reasoning quality.

------------------------------------------------------------------------

## 5. A Quantitative Model → Revshare Income from a Commercial Session

### 5.1. Define the Commerce Session

-   High‑intent query engages AI agent
-   Multi‑turn clarification loop
-   Model calls marketplace or store APIs
-   Shortlist built by semantic fit
-   User selects
-   Platform receives take‑rate τ (revshare)

### 5.2. Conservative Order‑of‑Magnitude Assumptions

  -----------------------------------------------------------------------
  Parameter                           Value
  ----------------------------------- -----------------------------------
  **AOV** (Average Order Value)       US\$90

  **τ** (revshare take‑rate)          12% (0.12)

  **p** (conversion rate for          35% (0.35)
  high‑intent sessions)               

  **C_inf** (marginal inference cost  US\$0.05
  per multi‑turn orchestration        
  session)                            
  -----------------------------------------------------------------------

### 5.3. Expected Income and Margins

    E[Revenue per session] = p × AOV × τ
                          ≈ 0.35 × 90 × 0.12
                          ≈ US$3.78

    E[Gross Profit/session] = Revenue − C_inf
                          ≈ 3.78 − 0.05
                          ≈ US$3.73

### 5.4. Scaling to Platform Level

    100M high‑intent sessions/month → 100M × 3.73 × 12 ≈ US$4.48B/year
    200M high‑intent sessions/month → ≈ US$9B+/year

Model sustainability scales directly: - reasoning fit drives
conversion - bad reasoning collapses margins → ensuring incentive
cleanliness

------------------------------------------------------------------------

## 6. Fairness and Incentive Design

### 6.1. Allocation Principles

  Model      Allocation
  ---------- --------------------------------------
  PPC        capital bids for visibility
  Revshare   success only, semantic fit dominates

### 6.2. Small Business Advantage

Under PPC: - bid against global brands - capital requirement → upfront
budgets, volatility

Under revshare: - no capital requirement for discovery entry - long‑tail
sellers can rank if they best satisfy intent - merit allocation replaces
capital auctions

### 6.3. Reinforcing Reasoning Quality

The model is incentivised to: - clarify before proposing - avoid
low‑quality offers - reason to maximise solved outcomes - learn via
reinforcement directly linked to satisfied intent

Reasoning becomes the monetised asset → not clicks.

------------------------------------------------------------------------

## 7. Compute Burn ≈ Intelligence CapEx

-   Training runs may be treated as intelligence infrastructure CapEx
-   Inference costs/unit token/session decreases over time due to
    hardware + software + architecture
-   Revshare becomes a leveraged economic call‑option on future commerce
    GMV

------------------------------------------------------------------------

## 8. Forecast → Agentic Marketplaces

-   2025 global advertising spend exceeded US\$1T → digital taking
    majority share and trending toward full dominance by 2030.
-   If agents capture even 5--10% of global e‑commerce/services GMV →
    implied revenue pool rivals current PPC ad markets.
-   With revshare 10--15% on category fit → model unlocks expansion +
    substitution → supporting durable sustainability without reasoning
    corruption or capital gating.

------------------------------------------------------------------------

## 9. Conclusion

> **Search → monetises intent fragments.\
> LLMs → monetise reasoning chains.\
> Auctions corrupt reasoning. Revshare reinforces it.**

**Revshare is not optional --- it is the only incentive‑aligned
sustainability model for frontier LLM economics at scale.**

------------------------------------------------------------------------

## References

Cottier, M. et al. (2024). *The rising costs of training frontier AI
models*, arXiv preprint.\
Epoch (2025a). *OpenAI's revenue has been growing 3x a year since 2024*,
Epoch AI.\
Epoch (2025b). *Most of OpenAI's 2024 compute went to experiments*,
Epoch AI.\
Entrepreneur (2025). *OpenAI saw more revenue in 6 months than all of
last year*, Entrepreneur, 30 September.\
Financial Times (2025). *How high are OpenAI's compute costs? Possibly
higher than previously thought*, Financial Times, 12 November.\
GlobeNewswire (2023). *Digital Advertising and Marketing market to reach
\$1.5T by 2030*, GlobeNewswire, 23 March.\
LocaliQ (2025). *Search Advertising Benchmarks 2025*, LocaliQ, 2 June.\
Reuters (2025). *OpenAI annualised revenue hits \$10B*, Reuters, 9
June.\
StoreGrowers (2025). *27 Google Ads Benchmarks 2025*, StoreGrowers, 13
June.\
The Register (2025). *OpenAI has spent \$12B+ on inference*, The
Register, 12 November.\
WordStream (2025a). *Google Ads Benchmarks 2025*, WordStream, 29
September.\
WordStream (2025b). *How much does Google Ads cost in 2025?*,
WordStream, 24 October.\
WARC (2025). *Global advertising spend to pass \$1T*, WARC.\
eMarketer (2025). *Worldwide media ad spend crosses \$1T*, eMarketer, 31
Jan.
