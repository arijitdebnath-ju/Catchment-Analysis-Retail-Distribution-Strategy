# Retail Banking Catchment Intelligence & Distribution Strategy --- West Bengal

A multi-dimensional retail banking strategy project that combines
district- and town-level market intelligence, MSME opportunity sizing,
banking-network benchmarking, and credit-distribution analysis to
identify priority catchments and recommend where and how a bank can
strengthen its presence across West Bengal.

> **Project focus:** Catchment intelligence • Retail banking
> distribution • Branch network strategy • MSME market sizing • Deposit
> and CASA analysis • Credit deployment • Peer benchmarking

------------------------------------------------------------------------

## Table of Contents

-   [Project Overview](#project-overview)
-   [Business Problem](#business-problem)
-   [Project Objectives](#project-objectives)
-   [Analytical Framework: Four
    Lenses](#analytical-framework-four-lenses)
    -   [Lens 1 --- Deposit and Geographic Catchment
        Intelligence](#lens-1--deposit-and-geographic-catchment-intelligence)
    -   [Lens 2 --- MSME Catchment and Market
        Sizing](#lens-2--msme-catchment-and-market-sizing)
    -   [Lens 3 --- Credit Distribution and Annual Credit
        Plan](#lens-3--credit-distribution-and-annual-credit-plan)
    -   [Lens 4 --- Branch Network and Peer
        Benchmarking](#lens-4--branch-network-and-peer-benchmarking)
-   [Selected Findings and Figures](#selected-findings-and-figures)
-   [Strategic Recommendations](#strategic-recommendations)
-   [Data Sources and Workbook
    Structure](#data-sources-and-workbook-structure)
-   [Methodology and Key Metrics](#methodology-and-key-metrics)
-   [Tools and Technologies](#tools-and-technologies)
-   [Limitations and Data Quality
    Notes](#limitations-and-data-quality-notes)
-   [Repository Structure](#repository-structure)
-   [How to Use the Project](#how-to-use-the-project)
-   [Disclaimer](#disclaimer)

------------------------------------------------------------------------

## Project Overview

This project develops a data-led framework for evaluating retail banking
catchments and distribution opportunities across West Bengal. It
examines where deposits and businesses are concentrated, how banking
infrastructure is distributed, where MSME demand may be underserved, and
how credit is being deployed relative to Annual Credit Plan (ACP)
targets.

The analysis is organised into four complementary lenses:

1.  **Deposit and geographic catchment intelligence** --- district- and
    town-level deposit concentration, branch presence, CASA composition,
    and high-density centres.
2.  **MSME market intelligence** --- the distribution of micro and small
    enterprises, district-level MSME load per bank branch, and potential
    expansion catchments.
3.  **Credit distribution analysis** --- ACP target-versus-disbursement
    performance, priority-sector lending (PSL), sectoral allocation, and
    bank-level comparisons.
4.  **Banking network benchmarking** --- rural, semi-urban, and
    urban/metro branch distribution, year-on-year network changes, and
    peer positioning.

The intended output is a practical decision-support framework:
prioritise locations, distinguish between branch-led and digitally
enabled distribution, and align products with the economic
characteristics of each catchment.

## Executive Summary

The project evaluates West Bengal's retail banking opportunity through four connected dimensions: **deposit potential, MSME concentration, credit deployment, and branch-network coverage**. It combines district- and town-level analysis with bank and peer comparisons to identify where banking demand is concentrated, where enterprise activity is high relative to branch presence, and how distribution can be aligned with local market needs.

The analysis highlights a West Bengal MSME base of **2.17 million units**, with **98.9% classified as micro enterprises**, and identifies districts such as **Purba Medinipur (approximately 419 MSMEs per branch), Maldah (385), and Uttar Dinajpur (331)** as high-load markets in the district comparison. Deposit analysis places **Kolkata** at the top of the displayed district ranking, while network benchmarking examines the balance between rural/semi-urban reach and urban/metro concentration.

The resulting framework supports three strategic decisions: **where to prioritise**, **which customer segments to target**, and **which distribution model to deploy**—from full-service branches and SME relationship coverage to Business Correspondent and digital-led channels.

## Business Problem

A bank's distribution strategy cannot be based on branch counts alone. A
location with a large deposit base may already be well served, while a
district with a smaller overall market may have a high concentration of
businesses relative to its existing banking infrastructure.

Similarly, expanding physical branches without understanding the
customer and enterprise mix can increase operating costs without
producing proportionate growth.

The project addresses five connected business questions:

-   **Where is the market?** Which districts and towns account for a
    large share of deposits, savings, and business activity?
-   **Where is capacity constrained?** Which districts have high MSME
    counts relative to the existing banking network?
-   **What should the bank distribute?** Which products and channels fit
    the local economic profile?
-   **How is the competitive network positioned?** How does the branch
    footprint vary across rural, semi-urban, and urban/metro markets?
-   **Where should management focus?** Which catchments merit network
    infill, specialised SME coverage, digital/BC-led distribution, or
    consolidation?

## Project Objectives

-   Build a district- and town-level view of West Bengal's retail
    banking catchments.
-   Examine deposit composition, including current-account and
    savings-account balances and CASA ratios where available.
-   Identify high-density towns and districts that may support
    additional banking capacity.
-   Quantify the state's micro and small enterprise base and compare it
    with the banking branch network.
-   Rank districts using market size, MSME-per-branch load, and
    opportunity tiers.
-   Compare rural, semi-urban, and urban/metro branch footprints across
    reporting periods.
-   Benchmark ICICI Bank against selected public- and private-sector
    peers using the supplied datasets.
-   Review ACP achievement, priority-sector disbursements, and sectoral
    credit allocation.
-   Translate the analysis into catchment-specific distribution,
    product, and channel recommendations.

------------------------------------------------------------------------

## Analytical Framework: Four Lenses

### Lens 1 --- Deposit and Geographic Catchment Intelligence

**Workbook:** `ICICI_Catchment_Project_Lens1.xlsx`

This lens studies the spatial distribution of deposits and banking
infrastructure across West Bengal, moving from district-level analysis
to individual towns and centres.

**What it examines**

-   District-level branch counts and deposit balances.
-   Current-account and savings-account balances and CASA ratios.
-   Deposit concentration across major district catchments.
-   Town/centre-level deposit density and branch presence.
-   High-density centres that may merit closer evaluation for network
    expansion.
-   District and town prioritisation through strategic tiers.

**Selected workbook outputs**

  Metric                                    Workbook dashboard value
  --------------------------------------- --------------------------
  Total catchment deposits (FY26 label)                    1,322,140
  Total network branches                                       9,123
  Overall CASA ratio (FY26 label)                             38.25%
  Average CASA per branch (FY26 label)                         55.44
  Kolkata district deposits                                  500,887
  North 24 Parganas district deposits                        210,680
  Hooghly district deposits                                   65,932
  Howrah district deposits                                    63,011

The dashboard identifies Kolkata as the largest district catchment by
deposits in the displayed ranking. North 24 Parganas is another major
market, while the town-level analysis highlights centres such as
Bidhannagar, Ichhapur Defence Estate, Chittaranjan, New Barrackpore, and
Dum Dum.

**Illustrative town-level observations**

-   **Bidhannagar:** 144 branches and 66,069 in deposits; the workbook
    reports deposit density of approximately 458.81 per branch.
-   **Ichhapur Defence Estate:** 3 branches and 1,121 in deposits;
    reported density of approximately 373.67.
-   **Chittaranjan:** 4 branches and 1,231 in deposits; reported density
    of approximately 307.75.
-   **New Barrackpore:** 18 branches and 5,406 in deposits; reported
    density of approximately 300.33.

*The workbook's dashboard labels the headline series FY24--FY26 / FY26.
The figures above are reproduced as displayed; the source unit should be
confirmed against the original source statement before interpreting them
as a specific currency unit.*

**Business use**

This lens supports a distinction between: - established, high-volume
markets that may call for productivity, relationship deepening, and
digital servicing; and - high-density or emerging centres that warrant a
closer look at incremental branch or service-point capacity.

### Lens 2 --- MSME Catchment and Market Sizing

**Workbook:** `ICICI_Catchment_Project_Lens2.xlsx`

This lens estimates the addressable micro and small enterprise market
across West Bengal and compares district-level enterprise concentration
with the number of operating bank branches.

**What it examines**

-   District-wise micro and small enterprise counts.
-   Total addressable MSME units and each district's share of the state
    market.
-   Existing bank branch counts by district.
-   MSME units per branch as a proxy for potential banking-service load.
-   Opportunity tiers and district-level expansion priorities.
-   Product and channel recommendations aligned with local economic
    activity.

**State-level market sizing in the workbook**

  Metric                                  Workbook value
  ------------------------------------- ----------------
  Total MSME units                             2,173,503
  Micro units                                  2,149,257
  Small units                                     24,246
  Micro share of total                             98.9%
  Bank branches used in the benchmark              9,123
  Average MSME units per branch                   238.24

The market is overwhelmingly micro-enterprise-led: approximately 98.9%
of the units in the workbook are classified as micro enterprises.

**Selected district findings**

  District              MSME units   Branches   MSMEs per branch
  ------------------- ------------ ---------- ------------------
  North 24 Parganas        260,433      1,106             235.47
  Kolkata                  194,657      1,683             115.66
  South 24 Parganas        181,065        582             311.11
  Purba Medinipur          146,212        349             418.95
  Murshidabad              144,601        467             309.64
  Howrah                   129,242        515             250.96
  Nadia                    114,327        448             255.19
  Paschim Medinipur        113,814        368             309.28
  Maldah                    89,411        232             385.39
  Uttar Dinajpur            62,915        190             331.13

**Key observations**

-   **Purba Medinipur** has the highest MSME-to-branch ratio in the
    displayed district analysis: approximately 419 units per branch,
    around 76% above the statewide benchmark of 238.24.
-   **Maldah** follows with approximately 385 MSME units per branch.
-   **Uttar Dinajpur, South 24 Parganas, Murshidabad, and Paschim
    Medinipur** also have ratios materially above the state benchmark.
-   **North 24 Parganas** is the largest market by MSME volume in the
    workbook, with 260,433 units.
-   **Kolkata** has a large enterprise base but a much lower
    MSME-per-branch ratio, reflecting its denser existing branch
    network.

The MSME-per-branch ratio is used as a screening indicator, not as a
direct measurement of unmet credit demand. It does not account for
branch capacity, digital adoption, business size, credit eligibility, or
the presence of non-branch channels.

**Business use**

The analysis supports differentiated distribution choices: - physical or
specialised service-point evaluation in high-load catchments; - Business
Correspondent (BC), merchant, and digital channels for geographically
dispersed micro enterprises; - dedicated SME relationship coverage in
industrial and commercial clusters.

### Lens 3 --- Credit Distribution and Annual Credit Plan

**Workbook:** `ICICI_Catchment_Project_Lens3.xlsx`

This workbook contains Annual Credit Plan (ACP) and Lead Bank Scheme
Management Information System (LBS-MIS) material, including bank-level
disbursement statements and sector-level priority lending information.

**What it is intended to examine**

-   Annual ACP targets against actual disbursements.
-   Priority-sector and non-priority-sector credit deployment.
-   Bank-level performance comparisons.
-   Sectoral allocation within priority-sector lending.
-   Year-on-year movement in selected credit indicators.
-   Potential opportunities in MSME, agriculture, housing, education,
    and other lending categories.

**Figures displayed in the workbook's FY24 dashboard**

  Metric                                 Workbook dashboard value
  ------------------------------------ --------------------------
  West Bengal ACP target                        ₹397,423.85 crore
  West Bengal disbursement                      ₹594,826.32 crore
  Statewide achievement                                    149.7%
  ICICI Bank ACP target                          ₹16,235.04 crore
  ICICI Bank disbursement                        ₹62,537.66 crore
  ICICI Bank achievement                                   385.2%
  ICICI priority-sector disbursement             ₹22,110.31 crore
  ICICI non-priority disbursement                ₹40,427.35 crore

The workbook dashboard also reports MSME and agriculture as the largest
components of ICICI's priority-sector disbursement mix.

**Important validation status**

This lens should be treated as a partially validated analytical
component, not as a final West Bengal district-level credit-catchment
result. The workbook includes a district-level source sheet containing
**Chhattisgarh** districts (for example, Balod, Bastar, Bilaspur, and
Dhamtari), and parts of its management commentary and proposed catchment
strategy refer to Raipur and other Chhattisgarh locations.

The FY24 SLBC sheets contain West Bengal-labelled ACP material, but the
geographical mismatch in the district-level source means that the
Chhattisgarh district records and related location-specific
recommendations must not be represented as West Bengal findings.

Before using this lens for external or management decisions: 1. Replace
or remove the non-West-Bengal district source data. 2. Reconcile
dashboard totals with the underlying bank-level statement. 3. Verify
reporting periods, units, and the mapping between FY23/FY24 source tabs.
4. Recalculate sector shares and achievement ratios from validated
source rows.

### Lens 4 --- Branch Network and Peer Benchmarking

**Workbook:** `ICICI_Catchment_Project_Lens4.xlsx`

This lens compares the distribution of bank branches across rural,
semi-urban, and urban/metro population groups and examines how the
reported footprint changes between FY23 and FY24.

**What it examines**

-   Branch distribution by population group.
-   Deep-geography footprint, defined in the workbook as rural plus
    semi-urban branches.
-   Urban/metro concentration.
-   Year-on-year branch-count changes.
-   ICICI's footprint relative to selected private-sector peers and
    public-sector benchmarks.
-   Strategic implications for rural inclusion, semi-urban expansion,
    and metro productivity.

**Figures displayed in the workbook dashboard**

  Metric                                             FY23    FY24
  ---------------------------------------------- -------- -------
  Total bank network                               11,728   8,470
  Rural branches                                    2,333   3,250
  Semi-urban branches                               2,266   1,658
  Urban/metro branches                              7,129   3,562
  Deep-geography branches (rural + semi-urban)      4,599   4,908

According to the dashboard: - Deep geography accounts for approximately
**57.9%** of the FY24 network. - Urban/metro branches account for
approximately **42.1%**. - The dashboard reports a **6.7% increase** in
deep-geography branches, from 4,599 to 4,908. - The reported overall
network contracts by 3,258 branches between the two displayed periods.

**ICICI Bank figures displayed in the dashboard**

  Metric                    FY23    FY24
  ---------------------- ------- -------
  Total branches             680     288
  Rural branches             ---      34
  Semi-urban branches        ---      55
  Urban/metro branches       ---     199
  Deep-geography share     25.9%   30.9%
  Urban/metro share        74.1%   69.1%

The dashboard reports that ICICI's deep-geography share increased by
approximately **5.0 percentage points**, while its urban/metro share
declined by the same amount. It also positions ICICI at **#4 among the
private-bank peer group** on the displayed deep-geography measure.

**Peer comparison shown in the workbook**

  Bank                    FY24 branches   Deep-geography share
  --------------------- --------------- ----------------------
  ICICI Bank                        288                  30.9%
  HDFC Bank                         342                  33.9%
  Axis Bank                         356                  39.6%
  Bandhan Bank                    1,727                  78.1%
  Kotak Mahindra Bank                49                   4.1%

**Business use**

The workbook frames the strategic choice as a balance between: -
protecting the economics of established urban/metro catchments; -
improving access in semi-urban markets; - extending rural reach through
lower-cost distribution and service channels.

**Data reconciliation note:** the FY23/FY24 dashboard totals should be
reconciled with the underlying source tabs before being used as
definitive network totals. In particular, the FY23 dashboard total of
11,728 does not match the FY23 branch-network source tab's displayed
grand total of 9,773. The FY24 dashboard total should also be checked
against its source statement. The dashboard values above are therefore
reported as workbook outputs, not independently certified totals.

------------------------------------------------------------------------

## Selected Findings and Figures

The following are the most useful headline outputs from the workbooks,
with the caveats above applying to the relevant lenses.

  -----------------------------------------------------------------------
  Area                                Finding
  ----------------------------------- -----------------------------------
  Deposit concentration               Kolkata is the largest district
                                      catchment in Lens 1, with 500,887
                                      in the dashboard's displayed
                                      deposit measure.

  Geographic opportunity              Lens 1 identifies high-deposit
                                      towns and centres such as
                                      Bidhannagar, Ichhapur Defence
                                      Estate, and Chittaranjan.

  MSME market size                    Lens 2 reports 2.17 million MSME
                                      units across West Bengal.

  Enterprise composition              Micro enterprises account for
                                      approximately 98.9% of the Lens 2
                                      market estimate.

  Banking-service load                The Lens 2 statewide benchmark is
                                      approximately 238 MSME units per
                                      bank branch.

  High-load district                  Purba Medinipur records
                                      approximately 419 MSMEs per branch
                                      in Lens 2.

  Other high-load districts           Maldah (385), Uttar Dinajpur (331),
                                      South 24 Parganas (311),
                                      Murshidabad (310), and Paschim
                                      Medinipur (309) are above the
                                      statewide benchmark.

  Network mix                         Lens 4's dashboard reports a 57.9%
                                      rural-plus-semi-urban share for the
                                      FY24 bank network.

  ICICI footprint mix                 Lens 4's dashboard reports a 30.9%
                                      deep-geography share and 69.1%
                                      urban/metro share for ICICI in
                                      FY24.

  Credit deployment                   Lens 3's FY24 dashboard reports
                                      ICICI disbursement of ₹62,537.66
                                      crore against an ACP target of
                                      ₹16,235.04 crore; this requires
                                      source reconciliation and should be
                                      treated cautiously.
  -----------------------------------------------------------------------

## Strategic Recommendations

The workbooks point towards a **catchment-led, two-speed distribution
strategy** rather than uniform branch expansion.

### 1. Prioritise high-load MSME districts

Use the MSME-per-branch measure to shortlist districts for deeper field
validation and potential distribution expansion. Purba Medinipur and
Maldah emerge as priority candidates in the workbook's district ranking,
followed by other above-benchmark districts.

### 2. Separate market size from market saturation

North 24 Parganas has the largest MSME base in the Lens 2 analysis,
while Kolkata has a large market but a much lower MSME-per-branch ratio.
Expansion decisions should therefore consider both total addressable
demand and existing service capacity.

### 3. Use a differentiated distribution model

-   **Micro-enterprise catchments:** merchant QR, digital onboarding,
    Business Correspondents, small-ticket working-capital products, and
    transaction-led assessment.
-   **Small-business and industrial catchments:** specialised SME
    relationship managers, working-capital facilities, machinery
    finance, trade services, and supply-chain finance.
-   **Urban/metro catchments:** relationship deepening, CASA growth,
    wealth and transaction banking, and improved branch productivity.
-   **Rural and dispersed catchments:** BC-led access, assisted digital
    services, and targeted local partnerships.

These are strategic recommendations derived from the analytical
segmentation; they are not claims that the proposed products or branch
openings have been implemented.

### 4. Evaluate town-level opportunities before committing capital

High deposit density or high MSME load should trigger further
assessment, not an automatic branch-opening decision. A final site
decision should also consider catchment overlap, travel time, competitor
presence, local operating costs, customer acquisition potential, and the
economics of alternative channels.

### 5. Link credit strategy to local economic activity

The project proposes aligning products with local business
clusters---for example, trade and working capital for commercial
centres, agri-linked finance for agricultural catchments, and
merchant-focused products for micro-enterprise markets. Credit
recommendations from Lens 3 should only be operationalised after the
geographical and source-data issues are resolved.

------------------------------------------------------------------------

## Data Sources and Workbook Structure

The repository currently contains four Excel workbooks. Their sheets
include cleaned analytical tables, source statements, district/town
breakouts, dashboards, and management summaries.

  --------------------------------------------------------------------------
  Workbook                               Main contents
  -------------------------------------- -----------------------------------
  `ICICI_Catchment_Project_Lens1.xlsx`   Deposit and CASA analysis, district
                                         and town catchments, centre-level
                                         density, dashboards, and
                                         district/town strategy.

  `ICICI_Catchment_Project_Lens2.xlsx`   West Bengal MSME data, cleaned
                                         district-level analysis,
                                         MSME/branch ratios, opportunity
                                         tiers, and management insights.

  `ICICI_Catchment_Project_Lens3.xlsx`   FY23/FY24 ACP statements, LBS-MIS
                                         material, sectoral credit analysis,
                                         peer benchmarking, and management
                                         recommendations. Contains a
                                         district-source geography mismatch
                                         requiring correction.

  `ICICI_Catchment_Project_Lens4.xlsx`   FY23/FY24 branch-network tables,
                                         cleaned population-group summaries,
                                         peer benchmarking, dashboards, and
                                         network strategy.
  --------------------------------------------------------------------------

The workbooks contain both source-data tabs and derived
dashboard/management-summary tabs. Where a dashboard figure conflicts
with its source table, the source should be reconciled before the number
is used in a final presentation or business decision.

## Methodology and Key Metrics

The project uses descriptive and comparative analysis to turn banking
and enterprise datasets into catchment-level decision support.

### Deposit and CASA analysis

-   Aggregate deposits by district and town.
-   Compare current and savings balances.
-   Calculate CASA ratio where the underlying fields are available.
-   Compare deposit balances with branch counts.
-   Use deposit per branch as a descriptive density measure.

### MSME market sizing

For a district:

\[ `\text{Total MSMEs}`{=tex} = `\text{Micro Units}`{=tex} +
`\text{Small Units}`{=tex} \]

\[ `\text{MSMEs per Branch}`{=tex} =
`\frac{\text{Total District MSMEs}}{\text{District Bank Branches}}`{=tex}
\]

\[ `\text{District Market Share}`{=tex} =
`\frac{\text{District MSMEs}}{\text{Statewide MSMEs}}`{=tex}
`\times 100`{=tex} \]

The MSME-per-branch ratio is a relative screening metric. It should not
be interpreted as the number of enterprises currently unserved by banks.

### Banking-network segmentation

\[ `\text{Deep Geography Branches}`{=tex} =
`\text{Rural Branches}`{=tex} + `\text{Semi-Urban Branches}`{=tex} \]

\[ `\text{Deep Geography Share}`{=tex} =
`\frac{\text{Rural} + \text{Semi-Urban Branches}}`{=tex}
{`\text{Total Branches}`{=tex}} `\times 100`{=tex} \]

\[ `\text{Urban/Metro Share}`{=tex} =
`\frac{\text{Urban/Metro Branches}}`{=tex}
{`\text{Total Branches}`{=tex}} `\times 100`{=tex} \]

Year-on-year branch movement is assessed by comparing the same
population-group categories across the reporting periods.

### Credit distribution

-   Compare ACP targets with actual disbursements.
-   Calculate target achievement as disbursement divided by target.
-   Separate priority-sector and non-priority-sector lending.
-   Examine sectoral composition and bank-level performance.
-   Validate units and reporting periods before comparing figures across
    source statements.

------------------------------------------------------------------------

## Tools and Technologies

The current repository is primarily an **Excel-based business analytics
and strategy project**. The supplied artefacts use spreadsheet-based
data organisation, calculations, dashboards, and management summaries.

-   Microsoft Excel / spreadsheet analysis
-   Data cleaning and tabular analysis
-   Descriptive and comparative analytics
-   Catchment and market sizing
-   Banking peer benchmarking
-   KPI design and management reporting

No Python, SQL, Power BI, GIS, or machine-learning implementation is
included in the four currently uploaded workbooks. Those technologies
should only be added to the project stack if corresponding
implementation files are subsequently included in the repository.

## Repository Structure

``` text
Catchment-Analysis-Retail-Distribution-Strategy/
│
├── ICICI_Catchment_Project_Lens1.xlsx
│   └── Deposit, CASA, district/town catchment and centre-density analysis
│
├── ICICI_Catchment_Project_Lens2.xlsx
│   └── MSME market sizing, district prioritisation and MSME/branch analysis
│
├── ICICI_Catchment_Project_Lens3.xlsx
│   └── ACP, priority-sector credit and sectoral disbursement analysis
│
├── ICICI_Catchment_Project_Lens4.xlsx
│   └── Branch network distribution and peer benchmarking
│
└── README.md
```

## How to Use the Project

1.  Clone or download the repository.
2.  Open the relevant Excel workbook in Microsoft Excel or a compatible
    spreadsheet application.
3.  Start with the `Dashboard` and `Management Insights` sheets for the
    executive summary.
4.  Review the cleaned analytical sheets and source-data tabs to
    understand the underlying calculations.
5.  Use the district/town or bank-level tables to investigate individual
    findings.
6.  Reconcile the flagged source-data issues before reusing the affected
    figures in presentations or business decisions.

``` bash
git clone https://github.com/arijitdebnath-ju/Catchment-Analysis-Retail-Distribution-Strategy.git
```

## Disclaimer

This is an analytical and strategic case-study project based on the data
contained in the repository's Excel workbooks. It is intended for
educational, analytical, and portfolio demonstration purposes. The
findings and recommendations should not be interpreted as official ICICI
Bank strategy, internal bank reporting, or a commitment to open branches
or extend credit. All reported figures are workbook-derived and remain
subject to source verification and reconciliation.
