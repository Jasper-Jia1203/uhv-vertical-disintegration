# Research Specification: UHV Transmission and Firm Vertical Disintegration in China

**Date:** 2026-05-28
**Researcher:** Jasper
**Paper type:** theory + empirics

## Research Question

Does ultra-high voltage (UHV) transmission infrastructure cause Chinese manufacturing firms to vertically disintegrate (narrow their firm boundaries), and what is the mechanism?

## Motivation

**Empirical puzzle.** China has invested trillions of RMB in UHV transmission since the mid-2000s, building the world's largest and most advanced long-distance power grid. Existing evaluations focus on aggregate outcomes: pollution reduction (Bai et al. 2026, JDE), health (Gao & Zhao 2025), economic growth from night-light data (Yu & Ma 2023). The microeconomic effects on firm organization — how firms adjust their boundaries in response to more reliable and cheaper electricity — remain entirely unexplored.

**Theoretical channel.** The transaction cost theory of the firm (Coase 1937; Williamson 1975) predicts that firms make or buy decisions at the margin where internal coordination costs equal external market transaction costs. Electricity infrastructure enters both sides: (1) cheaper grid power reduces the need for self-generation — an immediate form of vertical disintegration of the power input; (2) more reliable external power reduces the risk of supply-chain disruptions, making outsourcing of non-core production stages (logistics, parts manufacturing) more attractive. The property-rights approach (Grossman & Hart 1986) further predicts that reduced asset specificity in power supply shifts the optimal ownership structure toward external procurement.

**Policy relevance.** Infrastructure cost-benefit analysis routinely ignores firm-organizational responses. If UHV transmission promotes vertical specialization — and thereby improves allocative efficiency — the welfare gains are systematically understated. For developing countries planning grid investments (India, Indonesia, Sub-Saharan Africa), this channel has direct implications for investment appraisal.

## Hypothesis

**Primary hypothesis (H1):** UHV grid connection causes a decrease in firm-level vertical integration (increase in vertical specialization).

**Mechanism hypothesis (H2):** The effect operates through reduced self-generation — firms that previously maintained captive power plants are more likely to disintegrate after UHV connection.

**Secondary hypothesis (H3):** The effect is stronger for firms in industries with higher electricity intensity and for firms located in regions with more unreliable pre-UHV power supply.

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

UHV connection is expected to reduce firm-level vertical integration by 5-15% relative to the mean, with effects concentrated among (i) energy-intensive industries, (ii) firms with pre-existing self-generation capacity, and (iii) regions with historically poor power reliability. The mechanism through self-generation should account for a substantial share of the total effect. Effects should be larger for branch lines (local distribution) than trunk lines (inter-regional transit).

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
