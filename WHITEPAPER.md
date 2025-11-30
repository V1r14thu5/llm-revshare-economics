# Why Stochastic Reasoning Makes Revshare the Only Economically Compatible Model for LLMs

A Data‑Driven Revenue Hypothesis for OpenAI

By Nuno Lopes BSc.

Executive summary

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

Outcome‑based revenue sharing (revshare) is the only monetisation model
economically compatible with frontier LLM stochastic reasoning at scale.

Using benchmarks from advertising economics and inference compute cost,
the paper argues:

-   A high‑intent AI‑mediated session can generate \~US\$3.73 gross
    profit per session under conservative assumptions.
-   At 100 million high‑intent sessions/month, annual gross profit
    opportunity ≈ US\$4.48B --- enough to hedge current inference burn.
-   Unlike PPC, revshare reinforces stochastic reasoning because models
    are paid on successful outcomes, not bidder visibility.

------------------------------------------------------------------------

## 1. Introduction: From attention → outcomes

The web since the 2000s has monetised discovery by auctioning attention.
Google and Meta captured attention and auctioned visibility. Platforms
optimised for clicks or impressions --- indirect proxies for commercial
value.

LLMs shift the discovery interface to:

**Ask → reason → solve → execute → merchant pays on success.**

This implies a new objective function: the model should maximise solved
outcomes, not clicks or bids.

A bidder‑weighted auction model corrupts reasoning incentives by biasing
candidate pools toward high bidders, reducing long‑term conversion,
trust, satisfaction, and increasing returns and cancellations.

Thus, a monetised reasoning engine must be paid on *clean outcome
signals*.

------------------------------------------------------------------------

## 2. The cracks in Google's economic foundation

### 2.1. Rising costs and fragile margins

Benchmarks for 2025 indicate: - Avg Google Ads CPC ≈ US\$5.26, Avg CPL ≈
US\$70.11 - Search CPC range by sector US\$2.69--5.26 - Display CPC ≈
US\$0.63, trending upward

This embeds a rising CAC requirement into the discovery layer.

### 2.2. Capital as a precondition for visibility

SMEs typically require US\$1,000--10,000/month budgets to test PPC in
competitive verticals, facing volatility and outbidding by incumbents.

### 2.3. Intent erosion and behavioural shifts

Product and tutorial discovery is fragmenting to social platforms.
Zero‑click SERP experiences reduce marginal query value. LLM interfaces
are absorbing a growing share of first‑line, high‑value queries.

------------------------------------------------------------------------

## 3. OpenAI economics: A very expensive brain

### 3.1. Revenue growth is extraordinary

Public and internal targets indicate a 2025 run‑rate ≈ US\$10--13B by
mid‑2025--Q3, up from US\$2--4B in 2023--24.

### 3.2. Compute costs are unmatched

2024 compute ≈ US\$5.8B (training + inference + research). 2025
inference YTD by Q3 ≈ US\$8.6B+, cumulative Azure spend over 7+ quarters
≈ US\$12.4B+.

Meaning: even as per‑unit costs fall, aggregate inference cost will
remain enormous due to usage scale. Sustainability must therefore scale
faster with outcomes than compute per request.

------------------------------------------------------------------------

## 4. Why stochastic reasoning and auctions are incompatible

LLMs reason by: 1. Accepting long context windows 2. Encoding
constraints + preferences into embeddings 3. Evaluating many candidates
implicitly in vector space 4. Sampling stochastically 5. Refining via
multi‑turn questions

If bids influence recommendations, this creates: - Sponsor bias in the
candidate pool - Loss of trust - Noisy reinforcement signals - Lower
long‑term conversion - More returns and cancellations

------------------------------------------------------------------------

## 5. A quantitative model of revenue per conversation

### To evaluate the viability of revshare as a primary revenue model, consider a realistic multi‑turn commercial session.

### 5.1. Define the scenario

A user engages:

> "Find me a mid‑range pair of running shoes under £120 for
> overpronation, UK size 8, delivered this week."

The model: - Multi‑turn clarifies constraints - Calls Marketplace /
Store APIs - Shortlists by semantic fit, not bids - Explains
trade‑offs - Executes via Stripe/Shop APIs - Platform receives revshare
τ on completed order value

### 5.2. Conservative assumptions

  Parameter                                                 Value
  --------------------------------------------------------- ------------
  AOV = average order value                                 US\$90
  τ = platform revshare take‑rate                           12% (0.12)
  p = probability of transaction from high‑intent session   35% (0.35)
  C_inf = marginal inference + orchestration cost/session   US\$0.05

### 5.3. Expected revenue and margin

    Revenue ≈ 0.35 × 90 × 0.12 = US$3.78
    Gross profit ≈ 3.78 − 0.05 = US$3.73

### 5.4. Scaling to platform level

At 100M high‑intent sessions/month:

    100M × 3.73 × 12 ≈ 4.48 billion USD/year

At 200M sessions/month → ≈ US\$9B+/year.

This revenue is incentive‑clean: if the model reasons badly, conversion
collapses and revshare revenue disappears --- ensuring reasoning remains
the core monetised asset.

------------------------------------------------------------------------

## 6. Fairness and incentive design

### 6.1 Revshare vs PPC

PPC → allocates by auction bids. Revshare → pays on completed outcomes.

### 6.2 Small business advantage

Revshare allows long‑tail merchants to outrank brands by semantic fit
without upfront capital gating.

### 6.3 Incentive for reasoning quality

Under revshare, the model is incentivised to: - Clarify constraints
first - Avoid low‑quality suggestions - Reduce cancellations and
returns - Learn via reinforcement linked to satisfaction → reasoning
becomes the monetised flywheel, not a cost sink.

------------------------------------------------------------------------

## 7. OpenAI's burn as economic investment

### 7.1 Training as intelligence CapEx asset

Billions spent on training runs ≈ intelligence infrastructure CapEx,
amortisable over years.

### 7.2 Inference as variable cost with declining unit price

Unit inference cost decreases via hardware + software + architecture
improvement: - GPUs/TPUs/chips improve - Batching, quantisation,
sparsity - MoE, distillation, model efficiency

Thus revshare becomes a margin‑expanding call‑option on future
AI‑mediated GMV.

------------------------------------------------------------------------

## 8. Forecast: From ads → agents

### 8.1 Macro context

-   2025 global ad‑spend passed US\$1T+, now digital‑majority and
    accelerating toward 2030 dominance
-   2030 forecast digital ads/marketing → 1.5T USD
-   2029 media/entertainment potential pool → 3.5T USD+

### 8.2 Substitution + expansion

-   AI agents compress funnels and create new demand
-   Unlock long‑tail supply previously priced out of PPC

If agents capture even 5--10% of global e‑commerce/services by 2030 →
GMV rivals legacy PPC markets. 10--15% revshare on massive category‑fit
commerce → sustainable high‑margin flywheel.

------------------------------------------------------------------------

## 9. Conclusion

Search monetises *intent fragments.*\
LLMs monetise the *reasoning chain.*

Only **revshare** scales with stochastic reasoning without corrupting
incentives, embedding bidder bias, or gating merchants by capital.

Certainly:

> **Revshare is not optional --- it is the only incentive‑aligned
> monetisation model compatible with frontier LLM stochastic reasoning
> at economic scale.**

------------------------------------------------------------------------

## References

Cottier, M. et al. (2024) *The rising costs of training frontier AI
models*, arXiv preprint.

Epoch (2025a) 'OpenAI's revenue has been growing 3x a year since 2024',
Epoch AI. Available at: https://epoch.ai/data‑insights/openai‑revenue

Epoch (2025b) 'Most of OpenAI's 2024 compute went to experiments', Epoch
AI. Available at: https://epoch.ai/data‑insights/openai‑compute‑spend

Entrepreneur (2025) 'OpenAI saw more revenue in six months than all of
last year', Entrepreneur, 30 September. Available at:
https://www.entrepreneur.com/business‑news/openai‑saw‑more‑revenue‑6‑months‑vs‑2024/497774

Financial Times (2025) 'How high are OpenAI's compute costs? Possibly a
lot higher than previously thought', Financial Times, 12 November.
Available at:
https://www.ft.com/content/fce77ba4‑6231‑4920‑9e99‑693a6c38e7d5

LocaliQ (2025) 'Search Advertising Benchmarks 2025', LocaliQ, 2 June.
Available at: https://localiq.com/blog/search‑advertising‑benchmarks/

Reuters (2025) 'OpenAI's annualized revenue hits \$10 billion, up from
\$5.5 billion in December 2024', 10 June. Available at:
https://www.reuters.com/business/media‑telecom/openai‑annualised‑revenue‑10‑b‑vs‑point‑of‑2024‑2025‑06‑09/

StoreGrowers (2025) *27 Google Ads Benchmarks 2025*, StoreGrowers, 13
June. Available at: https://www.storegrowers.com/google‑ads‑benchmarks/

The Register (2025) 'OpenAI has spent \$12B on inference with
Microsoft', The Register, 12 November. Available at:
https://www.theregister.com/2025/11/12/openai‑inference‑report/

WARC (2025) 'Global advertising spend passed \$1T', WARC. Available at:
https://www.warc.com/content/feed/global‑advertising‑spend‑passed‑1‑trillion‑2025

WordStream (2025a) 'Google Ads Benchmarks 2025', WordStream. Available
at: https://www.wordstream.com/blog/2025‑google‑ads‑benchmarks

WordStream (2025b) 'Google Ads Costs 2025', WordStream. Available at:
https://www.wordstream.com/blog/google‑ads‑cost‑2025
