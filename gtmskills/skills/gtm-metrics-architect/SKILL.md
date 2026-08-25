---
name: gtm-metrics-architect
description: Design or audit a GTM/marketing measurement system using a metric-class ladder (Activity, Output, Outcome, Impact) applied at the right organisational level (Org, Programme, Function, Tactic-type, Tactic), so every metric on a dashboard is tied to an actual decision. Use whenever a user is building a reporting dashboard, defining KPIs, auditing an existing report before it goes to leadership, or asks why metrics "look fine but nothing changes." Trigger this whenever a metric or dashboard is proposed without a stated decision it drives, or when Activity-level numbers (clicks, opens, follows) are being presented as if they proved business Impact.
---

# GTM Metrics Architect

The most common measurement failure in GTM isn't having too few metrics — it's reporting a metric at the wrong level of the ladder and letting it stand in for a level it doesn't actually reach.

## The metric-class ladder

| Class | Answers | Example | Risk if mistaken for the level above |
|---|---|---|---|
| **Activity** | What actions did we take? | Follows, likes, opens, clicks | Looks like engagement, proves nothing about pipeline |
| **Output** | What did those actions produce? | Leads, inquiries, cost-per-lead | Looks like demand, doesn't confirm quality or conversion |
| **Outcome** | What changed as a result? | Pipeline generated, conversion rate | Looks like revenue impact, doesn't confirm it closed or was profitable |
| **Impact** | What effect landed on the actual business goal? | Revenue, cost of sales, pipeline-per-rep | This is the only class that answers "did it matter" |

Two cross-cutting classes apply at any level:
- **Efficiency** — magnitude divided by resource spent (e.g. pipeline $ per rep, cost per lead)
- **Readiness** — capability to perform, independent of current output (e.g. team certification levels, database completeness, capacity utilisation)

**The failure to catch:** reporting an Activity or Output number in a context that implies Impact. "Engagement is up" is an Activity claim; it is not evidence of pipeline health, and presenting it as if it were is the single most common way exec reporting loses credibility.

## Apply the ladder at the right altitude

A metric only belongs on a dashboard if a real decision *at that level* depends on it:

**Organisation → Programme → Function → Tactic-type → Tactic**

A Tactic-level metric (e.g. subject-line open rate) has no business on an Organisation-level board — it doesn't inform any decision made at that altitude. Conversely, an Org-level Impact metric is too coarse to diagnose which specific tactic to fix.

## Build sequence

1. **Strategy** — define scope, name the stakeholders, and state the decisions the measurement system needs to support *before* picking metrics.
2. **Execution** — build the reporting, test it against real decisions, launch, train the people who'll read it.
3. **Evolution** — monitor whether it's actually being used to decide anything; refine or retire metrics that aren't.

## How to apply it

1. **Audit the existing dashboard/report.** For each metric: what class is it (Activity/Output/Outcome/Impact/Efficiency/Readiness)? What level is it aimed at?
2. **State the decision.** For each metric, name the specific decision it's meant to drive. If none exists, it's decorative — cut it, or attach it to a real decision.
3. **Check for class-inflation.** Flag any Activity/Output metric being narrated as if it proved Impact.
4. **Rebuild at the right altitude.** Match each surviving metric to the organisational level where its decision actually gets made.

## Output format

- **Metric-by-metric classification** (class + level)
- **Decision each metric drives** — or "none found, recommend cutting"
- **Class-inflation flags** — where Activity/Output is being read as Impact
- **Rebuilt metric set**, organised by decision-owner and level

---
*Skill 5 of 6 in the [GTM Skills collection](../../README.md) by [Christopher Swarup](https://github.com/christopherswarup) — GTM Ops leader, 15+ years in RevOps/MOPS across Finastra, Equinix, Nutanix, Pleo, Contentsquare and DevRev.*
