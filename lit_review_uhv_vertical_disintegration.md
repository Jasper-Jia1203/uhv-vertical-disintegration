# Literature Review: UHV Transmission and Firm Vertical Disintegration

**Date:** 2026-05-28
**Query:** 特高压输电（UHV）对企业垂直解体/垂直专业化（firm vertical disintegration / vertical specialization）的影响。机制：能源基础设施改善 → 降低外部交易成本 → 企业边界收缩（make-or-buy）

---

## Summary

This review maps four intersecting literatures: (1) UHV transmission microfounded empirics — just one paper (张福顺 & 王海成 2025) directly links UHV to firm-level specialization (GVC participation); (2) infrastructure → firm boundaries — a small but growing empirical literature showing that broadband/smart-city infrastructure promotes vertical specialization via reduced external transaction costs; (3) electricity-sector firm boundaries — studies of vertical (un)bundling in the power industry itself, providing the closest theoretical template for the self-generation mechanism; (4) vertical integration measurement — IO-table-based indices (Fan & Lang 2000; Alfaro et al. 2019) are the standard toolkit.

**Core gap:** No paper studies whether UHV transmission — by reducing electricity cost and improving reliability — causes Chinese manufacturing firms to narrow their boundaries (vertically disintegrate). The transaction-cost channel (infrastructure → lower external coordination costs → more outsourcing/specialization) is well-established for IT/broadband but entirely absent from the energy-infrastructure literature.

---

## Tier 1 — Must Read (★★★)

### T1.1 — Directly on UHV + Firm Specialization

#### 张福顺、王海成 (2025) — 新型基础设施与企业参与全球价值链分工——基于特高压输电工程的实证研究
- **Journal:** 中南财经政法大学学报, 2025(5), 148-160
- **Method:** Staggered DID. Customs + industrial firm database (2000–2013).
- **Key finding:** UHV significantly promotes firm GVC participation. Mechanisms: production efficiency + IT transformation. Stronger effects in electricity-importing regions, low-tech industries.
- **Relevance:** **Closest existing paper.** Uses UHV as treatment, studies firm-level specialization. But dependent variable is GVC participation (trade-based), NOT vertical integration/disintegration at the firm level. The mechanism channel (IT transformation) is downstream from our hypothesized channel (transaction cost → make-or-buy). Our paper would be complementary: same treatment, different (more fundamental) outcome.
- **Read for:** Identification strategy, UHV treatment definition, data merging approach (customs + industrial firm).

---

### T1.2 — Infrastructure → Vertical Specialization (Method Template)

#### 袁淳、丛慧云、耿春晓 (2023) — 信息基础设施建设与企业专业化分工——基于国家智慧城市建设的自然实验
- **Journal:** 财经研究, 2023, 49(6), 34-48
- **DOI:** 10.16538/j.cnki.jfe.20220814.202
- **Method:** Staggered DID. Smart-city pilot as treatment. 2009–2018 Chinese listed firms.
- **Key finding:** Smart-city information infrastructure significantly promotes firm vertical specialization (VSI). Mechanism: **reduces external transaction costs** (search, contracting, monitoring, default). Heterogeneity: weaker when internal control costs are high. Consequence: raises firm TFP.
- **DV construction:** Vertical Specialization Index (VSI) based on value-added-to-sales, adjusted using VAT rates.
- **Relevance:** **Closest method template.** Same logic: infrastructure → lower external transaction costs → firm specializes. Replace "smart city" with "UHV" and the core framework transfers. Read for: VSI construction, transaction-cost mechanism testing, staggered DID specification.
- **Search:** CNKI: "信息基础设施建设与企业专业化分工"

#### Bergeaud, Malgouyres, Mazet-Sonilhac & Signorelli (2021) — Technological Change and Domestic Outsourcing
- **Venue:** CEP Discussion Paper No. 1784 (LSE); IZA DP No. 14603
- **Method:** Staggered broadband roll-out in France (1999–2007). Employer-employee admin data.
- **Key finding:** Broadband → 4% increase in outsourcing expenditure, 1.6% increase in occupational concentration (Herfindahl). Firms refocus on core activities. Low-skill occupations outsourced to service contractors. High-skill workers gain (+4% wage); low-skill workers lose (−1%).
- **Relevance:** Clean causal evidence that **communication infrastructure → vertical disintegration**. The mechanism (reduced coordination costs → outsourcing of non-core tasks) is directly analogous to our electricity reliability → outsourcing channel.

#### Fort (2017) — Technology and Production Fragmentation: Domestic versus Foreign Sourcing
- **Journal:** Review of Economic Studies, 84(2), 650–687
- **DOI:** 10.1093/restud/rdw057
- **Method:** Firm-level technology adoption (electronic networks) × production fragmentation. US Census of Manufactures.
- **Key finding:** Communication technology adoption → 3.1pp increase in fragmentation probability. Effect 20% larger in codifiable industries. Disproportionately domestic (not foreign) sourcing.
- **Relevance:** Canonical paper linking technology/infrastructure to firm fragmentation. The theoretical framing (coordination costs ↓ → fragmentation ↑) is directly portable. Read for: theory section structure, identification of fragmentation margin.

---

### T1.3 — Vertical Integration Measurement

#### Alfaro, Antràs, Chor & Conconi (2019) — Internalizing Global Value Chains: A Firm-Level Analysis
- **Journal:** Journal of Political Economy, 127(2), 508–559
- **DOI:** 10.1086/700935
- **Method:** Property-rights model + firm-level upstreamness measures. Global firm-level data + IO tables.
- **Key finding:** Firm integration choices along the value chain depend on demand elasticity and relative contractibility of stages. More productive firms show different integration patterns.
- **Relevance:** State-of-the-art firm-level vertical integration measurement. The Ratio-Upstreamness concept may be adaptable. But full implementation requires multi-country firm ownership data — likely overkill. **Main practical value:** the IO-based VI measurement framework; adapt the simpler Fan & Lang (2000) approach for Chinese data.

#### Fan & Lang (2000) — The Measurement of Relatedness: An Application to Corporate Diversification
- **Journal:** Journal of Business, 73(4), 629–660
- **Method:** IO commodity-flow tables → inter-industry vertical relatedness (V_ij) + complementarity (C_ij) coefficients. Aggregate to firm level via segment sales weights.
- **Relevance:** **Most practical VI measurement for our context.** The vertical relatedness coefficients can be computed from Chinese IO tables (国家统计局投入产出表) and merged with industrial firm database via industry codes. Widely used in Chinese corporate finance research. Read for: exact formula, Chinese IO table adaptation.

---

### T1.4 — Theory: Technology and Firm Boundaries

#### Acemoglu, Aghion, Griffith & Zilibotti (2010) — Vertical Integration and Technology: Theory and Evidence
- **Journal:** Journal of the European Economic Association, 8(5), 989–1033
- **DOI:** 10.1111/j.1542-4774.2010.tb00546.x
- **Method:** Property-rights model (Grossman-Hart) + UK plant-level data.
- **Key finding:** Downstream (producer) R&D intensity → positively correlated with backward VI; upstream (supplier) R&D intensity → negatively correlated. Both effects stronger when supplier input share is large.
- **Relevance:** **Core theoretical framework.** The property-rights approach to firm boundaries — where technology/infrastructure shifts affect the relative importance of producer vs. supplier investments — maps directly onto our setting. UHV reduces the "electricity input" specificity → shifts optimal ownership toward outsourcing.

#### Fabrizio (2012) — Institutions, Capabilities, and Contracts: Make or Buy in the Electric Utility Industry
- **Journal:** Organization Science, 23(5), 1264–1281
- **DOI:** 10.1287/orsc.1110.0680
- **Method:** Panel of 240 US investor-owned utilities (1990–2007). Make (own generation) vs. buy (procurement) decisions.
- **Key finding:** Firms buy more when they have strong institutional safeguards + prior contracting experience. Institutional safeguards substitute for contracting experience and amplify the effect of production capabilities.
- **Relevance:** **Directly studies make-or-buy in electricity context.** The "self-generation vs. grid purchase" decision IS a make-or-buy choice. Our paper extends this logic: when the grid becomes more reliable (UHV), firms not only buy electricity instead of making it — they also outsource other production stages.

---

## Tier 2 — Quick Browse (★★)

### T2.1 — Chinese Electricity Unbundling

#### 汪勇、郑世林、邢剑炜 (2023) — 纵向一体化抑或专业化？——来自中国电力行业市场化改革的证据
- **Journal:** 经济科学, 2023(3)
- **Method:** 2003 "厂网分开" reform as natural experiment. Industrial firm database.
- **Key finding:** Vertical unbundling increased labor use in generation firms (lost coordination), increased material use in grid firms (transaction costs passed upstream). Net benefits depend on market structure.
- **Relevance:** Shows that the specialization-vs-coordination tradeoff is real and measurable in Chinese electricity data. The "lost coordination" finding is important: it means infrastructure-induced specialization is not automatic — institutions matter.

#### Wang, Zheng & Luo (2023) — Does specialization improve firm efficiency? Evidence from the vertical unbundling reform in the Chinese electricity industry
- **Journal:** Applied Economics, 2023
- **DOI:** 10.1080/00036846.2022.2136617
- **Relevance:** English version of the above. Read for international-audience framing.

#### Gao & Van Biesebroeck (2014) — Effects of Deregulation and Vertical Unbundling on the Performance of China's Electricity Generation Sector
- **Journal:** Journal of Industrial Economics, 2014
- **Key finding:** Unbundling reduced labor and material use in generation by 7% and 5%, effects appearing with a 2-year lag.
- **Relevance:** Early evidence on Chinese electricity unbundling effects.

---

### T2.2 — UHV Firm-Level Effects (Background)

#### Feng et al. (2025) — Identifying the new momentum from the instrumental substitution of energy industry in China: Empirical evidence from UHV
- **Journal:** Energy, 320, 2025
- **Method:** Double machine learning (DML) + random forest.
- **Key finding:** UHV → firm TFP increase. Mechanisms: cost reduction + capacity stimulation.
- **Relevance:** Confirms UHV affects firm-level outcomes through cost/capacity channels — consistent with our transaction-cost mechanism.

#### Sun et al. (2025) — Ultra-High Voltage Transmission and Corporate Operational Risk
- **Journal:** Korean Energy Economic Review, 2025
- **Method:** Callaway & Sant'Anna (2020) heterogeneity-robust DID.
- **Key finding:** UHV reduces operational risk via green innovation + financial flexibility.
- **Relevance:** The "operational risk" channel overlaps with our reliability → outsourcing logic.

#### 赵晶、刘玉洁、付珂语等 (2022) — 大型国企发挥产业链链长职能的路径与机制——基于特高压输电工程的案例研究
- **Journal:** 管理世界, 2022(5). 111 citations.
- **Method:** Case study of UHV project organization.
- **Key finding:** UHV construction involves "chain-leader" coordinating mechanisms (链长主导 + 科研-工程耦合 + 产学研用协同) that reshape industrial division of labor.
- **Relevance:** Qualitative evidence that UHV reorganizes industrial supply chains. Useful for motivating the research question.

---

### T2.3 — Electrification + Firm Dynamics (Adjacent Literature)

#### Kassem (2024) — Does Electrification Cause Industrial Development? Grid Expansion and Firm Turnover in Indonesia
- **Journal:** Journal of Development Economics, 2024
- **Method:** Grid expansion in Indonesia as treatment. Firm registration/exit data.
- **Key finding:** Grid expansion → increased firm entry, particularly in manufacturing. Accelerated exit of low-productivity incumbents.
- **Relevance:** Closest energy-infrastructure paper studying firm dynamics. But outcome is entry/exit, not firm boundaries.
- **Note:** PDF available in `master_supporting_docs/supporting_papers/`.

---

## Tier 3 — Background Reference (★)

### Classic Theory (cite, don't re-read)
- **Coase (1937)** — The Nature of the Firm. Economica.
- **Williamson (1975)** — Markets and Hierarchies. Free Press.
- **Williamson (1985)** — The Economic Institutions of Capitalism. Free Press.
- **Grossman & Hart (1986)** — The Costs and Benefits of Ownership: A Theory of Vertical and Lateral Integration. JPE, 94(4), 691–719.

### Benchmark Electrification Empirics
- **Dinkelman (2011)** — The Effects of Rural Electrification on Employment. Econometrica, 79(6), 1727–1776. (South Africa, IV strategy)
- **Lipscomb, Mobarak & Barham (2013)** — Development Effects of Electrification. AER, 103(3). (Brazil, terrain IV)
- **Allcott, Collard-Wexler & O'Connell (2016)** — How Do Electricity Shortages Affect Industry? AER, 106(3). (India, productivity losses)

### UHV Background (existing coverage)
| Paper | Journal | Year | Topic |
|---|---|---|---|
| Bai et al. (Ren, Zhao, Zhang & Bai) | JDE | 2026 | UHV → firm SO₂ |
| Gao & Zhao | Energy Economics | 2025 | UHV → health (CFPS) |
| Yu & Ma | 数量经济技术经济研究 | 2023 | UHV → night-light GDP |
| Han et al. | Energy Economics | 2025 | UHV → carbon-neutral tech innovation |
| 钱非非、魏守华 | 当代财经 | 2025 | UHV → PM2.5 |

---

## Thematic Organization

### Theoretical Foundations

The paper sits at the intersection of **transaction cost economics** (Coase 1937; Williamson 1975, 1985) and the **property-rights theory of the firm** (Grossman & Hart 1986; Hart & Moore 1990). The core logic: infrastructure quality enters the firm's make-or-buy calculus by shifting the relative cost of internal coordination vs. external market transactions.

Acemoglu et al. (2010) provide the closest theoretical template: technology intensity of upstream vs. downstream industries has opposite effects on vertical integration, and these effects are amplified by input cost shares — a prediction directly testable with UHV as the technology shifter.

### Empirical Evidence: Infrastructure → Firm Boundaries

Three papers form the evidentiary backbone:
1. **袁淳 et al. (2023):** Smart-city IT infrastructure → +vertical specialization via reduced external transaction costs. Staggered DID. Chinese listed firms.
2. **Bergeaud et al. (2021):** Broadband → +4% outsourcing, +1.6% occupational concentration. France.
3. **Fort (2017):** Firm IT adoption → +3.1pp fragmentation probability. US manufacturing.

All three share the same mechanism: infrastructure/technology reduces coordination costs → firms outsource non-core activities. **None studies energy infrastructure.**

### Electricity-Sector Firm Boundaries

Fabrizio (2012) directly studies make-or-buy decisions in electricity generation — firms with better contracting capabilities and institutional safeguards buy more and make less. The Chinese electricity unbundling literature (汪勇 et al. 2023; Wang et al. 2023; Gao & Van Biesebroeck 2014) shows that forced vertical separation has measurable costs (lost coordination) and benefits (specialization), with net effects depending on market institutions.

### Measurement Toolkit

Fan & Lang (2000) IO-based vertical relatedness is the workhorse for Chinese data. Alfaro et al. (2019) provide the state-of-the-art but require multi-country ownership data. 袁淳 et al. (2023) VSI based on value-added-to-sales (adjusted for VAT rates) is a simpler alternative for within-China analysis. For the self-generation mechanism channel, the industrial firm database's energy balance sheet items (self-generation indicators) provide a direct measure.

---

## Gaps and Opportunities

1. **No energy-infrastructure → firm-boundaries paper.** The IT/broadband → specialization channel is established. Energy infrastructure — despite being a larger cost share for manufacturing — has never been studied through this lens.

2. **张福顺 & 王海成 (2025) is the only UHV + firm specialization paper**, and it uses GVC participation (trade-based) as the outcome. Our paper would be the first to study UHV → domestic vertical integration/disintegration (firm organization-based).

3. **The self-generation channel is completely unexplored.** Fabrizio (2012) studies make-or-buy in US electricity generation, but no paper studies how grid reliability → reduced self-generation → broader vertical disintegration cascade in manufacturing.

4. **Chinese IO tables allow clean VI measurement.** Fan & Lang (2000) methodology can be adapted to Chinese IO tables (available for 2002, 2007, 2012, 2017) merged with industrial firm database. This is feasible and precedented in Chinese corporate finance.

5. **No theory model of infrastructure → firm boundaries.** A simple extension of Acemoglu et al. (2010) where grid reliability enters the supplier's cost function would generate novel comparative statics.

---

## Suggested Reading Order

```
Week 1: Theory + Measurement Foundation
  → Acemoglu et al. (2010) — theory template
  → Fan & Lang (2000) — VI measurement
  → 袁淳 et al. (2023) — closest method template

Week 2: Core Empirics
  → 张福顺 & 王海成 (2025) — only UHV + specialization paper
  → Fort (2017) — technology → fragmentation
  → Bergeaud et al. (2021) — broadband → outsourcing

Week 3: Electricity Context + Mechanism
  → Fabrizio (2012) — make-or-buy in electricity
  → 汪勇 et al. (2023) / Wang et al. (2023) — Chinese electricity unbundling
  → Kassem (2024) — grid + firm dynamics

Week 4: Background + Gap Confirmation
  → Dinkelman (2011), Lipscomb et al. (2013) — electrification canon
  → Remaining UHV papers (Feng 2025, Sun 2025, 赵晶 2022) — confirm gap
```

---

## Key Data Sources for This Research

| Data | Coverage | Key Variables |
|---|---|---|
| Chinese Industrial Firm Database (工企数据库) | 1998–2013 | Value added, sales, intermediate inputs, self-generation, industry codes |
| Chinese IO Tables (投入产出表) | 2002, 2007, 2012, 2017 | Inter-industry input-output coefficients → vertical relatedness |
| UHV line connection data | ~2006 onward | Prefecture-year UHV connection status (treatment) |
| Customs Database (海关数据库) | 2000–2013 | GVC participation (for comparison with 张福顺 2025) |

---

## BibTeX Entries (Core Papers)

```bibtex
@article{zhang2025uhv,
  author  = {张福顺 and 王海成},
  title   = {新型基础设施与企业参与全球价值链分工——基于特高压输电工程的实证研究},
  journal = {中南财经政法大学学报},
  year    = {2025},
  number  = {5},
  pages   = {148--160}
}

@article{yuan2023smartcity,
  author  = {袁淳 and 丛慧云 and 耿春晓},
  title   = {信息基础设施建设与企业专业化分工——基于国家智慧城市建设的自然实验},
  journal = {财经研究},
  year    = {2023},
  volume  = {49},
  number  = {6},
  pages   = {34--48},
  doi     = {10.16538/j.cnki.jfe.20220814.202}
}

@article{fort2017technology,
  author  = {Fort, Teresa C.},
  title   = {Technology and Production Fragmentation: Domestic versus Foreign Sourcing},
  journal = {Review of Economic Studies},
  year    = {2017},
  volume  = {84},
  number  = {2},
  pages   = {650--687},
  doi     = {10.1093/restud/rdw057}
}

@techreport{bergeaud2021technological,
  author  = {Bergeaud, Antonin and Malgouyres, Clément and Mazet-Sonilhac, Clément and Signorelli, Sara},
  title   = {Technological Change and Domestic Outsourcing},
  institution = {CEP Discussion Paper No. 1784},
  year    = {2021}
}

@article{alfaro2019internalizing,
  author  = {Alfaro, Laura and Antràs, Pol and Chor, Davin and Conconi, Paola},
  title   = {Internalizing Global Value Chains: A Firm-Level Analysis},
  journal = {Journal of Political Economy},
  year    = {2019},
  volume  = {127},
  number  = {2},
  pages   = {508--559},
  doi     = {10.1086/700935}
}

@article{fan2000measurement,
  author  = {Fan, Joseph P. H. and Lang, Larry H. P.},
  title   = {The Measurement of Relatedness: An Application to Corporate Diversification},
  journal = {Journal of Business},
  year    = {2000},
  volume  = {73},
  number  = {4},
  pages   = {629--660}
}

@article{acemoglu2010vertical,
  author  = {Acemoglu, Daron and Aghion, Philippe and Griffith, Rachel and Zilibotti, Fabrizio},
  title   = {Vertical Integration and Technology: Theory and Evidence},
  journal = {Journal of the European Economic Association},
  year    = {2010},
  volume  = {8},
  number  = {5},
  pages   = {989--1033},
  doi     = {10.1111/j.1542-4774.2010.tb00546.x}
}

@article{fabrizio2012institutions,
  author  = {Fabrizio, Kira R.},
  title   = {Institutions, Capabilities, and Contracts: Make or Buy in the Electric Utility Industry},
  journal = {Organization Science},
  year    = {2012},
  volume  = {23},
  number  = {5},
  pages   = {1264--1281},
  doi     = {10.1287/orsc.1110.0680}
}
```

---

## Post-Flight Verification

| Claim | Status | Evidence |
|---|---|---|
| 张福顺 & 王海成 (2025) — UHV → GVC participation, staggered DID | PASS | Confirmed via journal page (中南财经政法大学学报 2025/5) + author faculty page |
| 袁淳 et al. (2023) — Smart city → vertical specialization, 财经研究 | PASS | Confirmed via journal HTML + English abstract page |
| Fort (2017) — Technology → production fragmentation, REStud | PASS | Confirmed via OUP abstract page + DOI |
| Bergeaud et al. (2021) — Broadband → outsourcing, CEP DP 1784 | PASS | Confirmed via LSE CEP + IZA pages |
| Alfaro et al. (2019) — Internalizing GVCs, JPE | PASS | Confirmed via HBS faculty page + Harvard DASH |
| Fan & Lang (2000) — Measurement of relatedness, J Bus | PASS | Confirmed (note: J Bus, not JAE as initially assumed) |
| Acemoglu et al. (2010) — Vertical integration & technology, JEEA | PASS | Confirmed via OUP + MIT DSpace |
| Fabrizio (2012) — Make or buy in electric utilities, Org Sci | PASS | Confirmed via ACM DL + DOI |
| No prior paper studies UHV → domestic vertical disintegration | PASS | Confirmed by absence in all searches across 4 dimensions |
