# Research Specification: UHV Transmission and Firm Vertical Disintegration in China

**Date:** 2026-05-28
**Researcher:** Jasper
**Paper type:** theory + empirics

## Research Question

Does ultra-high voltage (UHV) transmission infrastructure cause Chinese manufacturing firms to vertically disintegrate (narrow their firm boundaries) or vertically integrate (expand their boundaries)? The theoretical prediction is ambiguous — the net direction is an empirical question. And through what mechanism does the dominant effect operate?

## Motivation

**Empirical puzzle.** China has invested trillions of RMB in UHV transmission since the mid-2000s, building the world's largest and most advanced long-distance power grid. Existing evaluations focus on aggregate outcomes: pollution reduction (Bai et al. 2026, JDE), health (Gao & Zhao 2025), economic growth from night-light data (Yu & Ma 2023). The microeconomic effects on firm organization — how firms adjust their boundaries in response to more reliable and cheaper electricity — remain entirely unexplored.

**Theoretical channel — the net effect is ambiguous a priori.** The transaction cost theory of the firm (Coase 1937; Williamson 1975) predicts that firms make-or-buy at the margin where internal coordination costs equal external market transaction costs. Electricity infrastructure enters BOTH sides of this calculus:

*Forces toward vertical DISINTEGRATION (specialization):*
1. **Self-generation exit:** Cheaper, more reliable grid power reduces the need for captive power plants — an immediate, mechanical form of vertical disintegration of the electricity input. This is the most direct and cleanly testable channel.
2. **Supply-chain de-risking:** Reliable external power reduces the risk of production disruptions, lowering the option value of internalizing upstream/downstream stages as a hedge.
3. **External transaction cost reduction:** Better infrastructure lowers search, contracting, and monitoring costs with external suppliers (analogous to the IT/broadband → outsourcing mechanism documented by 袁淳 et al. 2023 and Bergeaud et al. 2021).

*Forces toward vertical INTEGRATION (internalization):*
1. **Profitability → boundary expansion:** Lower electricity costs improve firm profitability → slack resources may be deployed to internalize adjacent production stages ("deep pockets" channel).
2. **Scale-biased advantage:** UHV disproportionately benefits large, electricity-intensive firms, which tend to be more vertically integrated. If UHV strengthens their competitive position, industry-level vertical integration may rise through composition effects.
3. **Agglomeration + consolidation:** Cheap, reliable power attracts upstream and downstream firms to co-locate in electricity-importing regions. Co-location may reduce the transaction costs of *both* outsourcing and acquisition — the net organizational effect depends on which margin adjusts faster.
4. **Internal investment de-risking:** Reduced electricity-price volatility lowers the risk premium on in-house capital investment, potentially making internal production of more stages feasible at the margin.

The property-rights approach (Grossman & Hart 1986; Acemoglu et al. 2010) provides a framework for nesting both forces: UHV shifts the relative importance of producer vs. supplier non-contractible investments, and the direction depends on which party's investment is more elastic to electricity reliability. **The theory section should derive conditions under which disintegration dominates — and let the empirics test which regime holds in Chinese manufacturing.**

**Policy relevance.** Infrastructure cost-benefit analysis routinely ignores firm-organizational responses. If UHV transmission promotes vertical specialization — and thereby improves allocative efficiency — the welfare gains are systematically understated. For developing countries planning grid investments (India, Indonesia, Sub-Saharan Africa), this channel has direct implications for investment appraisal.

## Hypothesis

**Primary hypothesis (H1 — two-sided):** UHV grid connection causes a change in firm-level vertical integration. The direction is an empirical question: if disintegration forces dominate → VI decreases; if integration forces dominate → VI increases. The theory model will identify the conditions governing which regime prevails.

**Mechanism hypothesis (H2 — disintegration channel):** The effect operates through reduced self-generation — firms that previously maintained captive power plants are more likely to shed the electricity-input stage after UHV connection. This channel is unambiguously disintegrating at the electricity-input margin; the question is whether it cascades to other production stages.

**Secondary hypothesis (H3 — heterogeneity):** 
- H3a: Disintegration forces are stronger in electricity-intensive industries (larger cost-share shock).
- H3b: Disintegration forces are stronger in regions with worse pre-UHV power reliability (larger reliability shock).
- H3c: Integration forces may dominate in industries with high asset specificity or where electricity is a small cost share.
- H3d: The self-generation mechanism is strongest where pre-UHV captive power was prevalent.

## Empirical Strategy

- **Method:** Staggered Difference-in-Differences with variation across prefecture-level cities in the timing of UHV line connection.
- **Treatment:** Whether the prefecture city where the firm is located has been connected to a UHV line in year t.
- **Control:** Firms in not-yet-connected cities (within the same province or region).
- **Key identifying assumption:** Parallel trends — firm vertical integration in treated and control cities would have followed the same trend absent UHV connection. The primary threat is non-random line placement (lines may be routed to areas with growing economic activity).
- **Robustness checks:**
  - Instrumental variables: terrain ruggedness, distance to major generation sources, historical grid planning documents (ex-ante route proposals vs actual routes)
  - Heterogeneity: main trunk lines vs branch lines (trunk routes are more exogenous)
  - Heterogeneity: power-importing vs power-exporting regions
  - Placebo: lead treatment indicators, spatial spillover buffers
  - Sun & Abraham (2021) / Callaway & Sant'Anna (2021) estimators for staggered adoption
- **Mechanism:** Self-generation (captive power plant status) as a mediating variable; test whether firms with pre-existing self-generation capacity drive the effect.

## Data

- **Primary dataset:** Chinese Annual Survey of Industrial Firms (工企数据库), covering all above-scale manufacturing firms.
- **Key variables:**
  - *Outcome (vertical integration):* Input-Output table-based vertical relatedness index (Fan & Lang 2000); value-added to sales ratio; in-house production of key inputs (when available).
  - *Treatment:* UHV line connection status by prefecture-year, constructed from SGCC (State Grid Corporation of China) project records.
  - *Mechanism:* Self-generation capacity or captive power plant indicator (from firm survey data).
  - *Controls:* Firm size, age, ownership, industry, export status; prefecture-level GDP, population, industrial structure.
- **Sample:** Manufacturing firms, 2000-2016 (covering pre- and post-UHV expansion periods).
- **Unit of observation:** Firm-year.

## Expected Results

The net direction is theoretically ambiguous — the paper's contribution is to resolve this ambiguity empirically. The self-generation channel (H2) is the most clearly signed prediction: firms with pre-existing captive power plants should unambiguously reduce self-generation after UHV connection. Whether this electricity-input disintegration cascades to broader vertical disintegration is the key empirical question. If disintegration dominates, we expect a 5-15% reduction in firm-level VI relative to the mean, with effects concentrated among (i) energy-intensive industries, (ii) firms with pre-existing self-generation capacity, and (iii) regions with historically poor power reliability. If integration dominates, the sign flips. Either outcome is informative — both are absent from the existing literature.

## Contribution

1. **Infrastructure effects:** First paper to examine how electricity transmission infrastructure affects firm boundaries, opening a new margin — organizational form — in the infrastructure evaluation literature.
2. **Transaction cost empirics:** Adds a novel, plausibly exogenous shock to the empirical literature on the determinants of vertical integration, complementing IT shocks (Fort 2017, ReStud) and regulatory shocks.
3. **UHV literature:** Expands the scope from aggregate environmental and economic outcomes to firm-level organizational responses.
4. **Policy:** Quantifies a previously unmeasured welfare channel of grid infrastructure investments.

## Open Questions

- **Data access:** Exact availability and coverage of the industrial firm database, especially self-generation indicators. Alternative: use energy expenditure share as a proxy.
- **UHV treatment mapping:** Whether UHV line connection data is publicly available at the prefecture-year level, or needs to be hand-collected from SGCC project reports.
- **IV strength:** Whether terrain ruggedness has sufficient first-stage power given the geographic scale of UHV routing.
- **Measurement of vertical integration:** The industrial firm database has limited information on input sourcing. Alternative approaches include using the firm's industry classification at a more disaggregated level combined with IO tables to construct a vertical integration proxy.
- **Estimation of staggered DiD:** Potential issues with treatment effect heterogeneity across cohorts; need to implement appropriate robust estimators.
