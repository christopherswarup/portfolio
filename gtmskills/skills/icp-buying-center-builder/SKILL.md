---
name: icp-buying-center-builder
description: Build an Ideal Customer Profile sized against the realistically obtainable market (not total market) and defined at the buying-centre level (the specific department/function with the need), keeping stable "fit" attributes separate from fast-changing "intent" signals. Use whenever a user is defining an ICP, sizing a market opportunity, building a target-account data model, or setting up intent/signal scoring. Trigger this whenever an ICP or market-sizing exercise is proposed at the whole-account or whole-market level — that's the most common sizing error and it silently inflates every projection built on top of it.
---

# ICP & Buying-Centre Builder

Two mistakes account for most broken ICPs: sizing against the wrong market number, and defining "ideal customer" at the wrong altitude.

## Fix 1 — size against what's actually obtainable

Use the standard sizing funnel, but plan against the right layer of it:

- **Total market** — every possible buyer, anywhere, ever. Useful for long-range strategy only.
- **Serviceable market** — the slice reachable given your current product, geography, and channel.
- **Obtainable market** — the slice you can realistically win given competition, current share, and resourcing.

**The rule:** plan and forecast against the *obtainable* number. Using the total-market number as the working target is the single most common cause of GTM plans that look enormous on a slide and never materialise in pipeline.

## Fix 2 — define ICP at the buying-centre level

An "ideal customer" isn't a whole company or even a whole segment — it's the specific department or function that actually owns the budget and the pain. Two companies that look identical at the account level (same industry, same size, same revenue) can have completely different buying centres, timelines, and champions for the exact same product.

**Define the ICP at buying-centre granularity**: which function, what's their specific pain, who owns budget, what triggers them to act. Account-level or segment-level "ICP" definitions are too coarse to actually qualify against.

## Keep two attribute types separate

| Type | Nature | Use |
|---|---|---|
| **Fit attributes** | Firmographic/technographic — slow-changing (industry, size, tech stack) | Builds the *stable* target list — who to even consider |
| **Intent signals** | Fast-changing (hiring surges, tech changes, content consumption, trigger events) | Decides *when* to engage a fit-qualified account — timing, not eligibility |

Mixing these into one blended score usually means fast-moving intent noise drowns out the stable fit signal, or vice versa — keep them as two layers, not one number.

## Build methods (pick based on speed vs. depth needed)

- **Internal** — interview top-performing reps, mine CRM/billing/win-loss data. Fast, cheap, directionally useful — but risks "find more of the same" bias if your current customer base is itself skewed.
- **External/predictive** — statistical modeling against a broader dataset to surface non-obvious correlates. Needs clean input data and cross-functional trust in the output to actually get used.

## How to apply it

1. Confirm which market layer (total/serviceable/obtainable) the current target is actually sized against — correct if it's total.
2. Push the ICP definition down to buying-centre granularity — name the function, not just the account type.
3. Separate the fit-attribute list from the intent-signal list explicitly.
4. Choose internal vs. external build method based on how much rep/CRM history exists and how fast the answer is needed.

## Output format

- **Sizing check** — which market layer the current number represents, and the corrected obtainable-market figure if it was wrong
- **ICP defined at buying-centre level** — function, pain, budget owner, trigger
- **Fit-attribute list** (stable) and **intent-signal list** (timing) — kept separate
- **Recommended build method** with the trade-off stated

---
*Skill 4 of 6 in the [GTM Skills collection](../../README.md) by [Christopher Swarup](https://github.com/christopherswarup) — GTM Ops leader, 15+ years in RevOps/MOPS across Finastra, Equinix, Nutanix, Pleo, Contentsquare and DevRev.*
