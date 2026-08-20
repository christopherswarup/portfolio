# Rebuilding a Revenue System When Nobody Trusts the Numbers

This is a composite of patterns I've worked through across several roles. I've rebuilt it from scratch and kept it company-neutral so the operating thinking is visible without exposing employer-specific material.

## The situation

The business did not really have one revenue problem.

It had several teams, motions and systems that each made sense on their own, but stopped making sense when you tried to connect them.

Marketing had one version of the lifecycle. Sales had another. Outbound, partner and customer teams had their own rules. The CRM contained years of logic. Reporting was trying to reconcile all of it after the fact.

Everyone could explain their part of the process.

Nobody could explain the whole revenue system with confidence.

The obvious answer was to "fix the CRM".

That would have been the wrong place to start.

## What was actually going wrong

The symptoms were familiar:

- Pipeline changed depending on which report you opened
- Lead quality arguments were being settled with anecdotes
- Routing exceptions had become normal operations
- Teams were using spreadsheets to work around the official process
- Different systems were making different decisions about the same record
- Marketing, Sales and Finance were not always working from the same definitions
- Tool changes were being discussed before ownership and process questions had been resolved

The technology was part of the problem, but it was not the root cause.

The real issue was that the business had never made some important decisions clearly enough.

Who owns this stage? What does this status actually mean? When has a handoff happened? What is a legitimate exception? Which system is authoritative? What evidence should leadership trust?

Until those questions were answered, more automation would simply make the confusion move faster.

## My role

My job was to pull the whole thing together.

That meant working across Marketing, Sales, SDR, Customer Success, Finance, Data and Technology to understand the current state, find the real breaks, agree the operating rules and then translate those rules into systems, data and reporting.

This is the kind of work I enjoy because it sits between strategy and implementation.

You have to be senior enough to resolve cross-functional trade-offs, but close enough to the detail to understand why the routing rule, field, workflow or report is behaving the way it is.

## What I changed first

I did not start with software.

I started with the commercial motion.

### 1. Get everyone onto the same picture

We mapped how demand actually entered and moved through the business — inbound, outbound, partner, product-led and customer motions where relevant.

Not the version in a slide deck. The version people were actually running.

That exposed where teams were using different definitions, where ownership disappeared between functions and where local workarounds had quietly become part of the process.

### 2. Make lifecycle and handoffs explicit

For the important stages and transitions, we defined:

- What the stage meant
- What had to be true before something entered it
- Who owned it
- What counted as acceptance or rejection
- What happened when it stalled
- When recycling was appropriate
- Which exceptions were legitimate

This sounds basic. In complex GTM environments, it rarely is.

A lot of pipeline problems are really definition and ownership problems wearing a reporting costume.

### 3. Decide which system gets to be right

Where multiple platforms were trying to control the same decision, we simplified the authority model.

One system should own a state or decision. Other systems can consume it, enrich it or act on it, but they should not quietly create competing truths.

That gave us a much cleaner basis for CRM, marketing automation, routing and reporting changes.

### 4. Focus data work on what changes a decision

I am not a fan of generic "clean the database" programmes with no commercial priority.

We focused first on the data that affected:

- Ownership
- Routing
- Customer treatment
- Pipeline
- Revenue reporting
- Forecasting
- Executive decisions

If a field can change money, ownership or customer experience, it deserves stronger governance than a field nobody uses.

### 5. Build governance into the model

The system needed a way to evolve without returning to hidden configuration and local rules.

So the design included:

- Named owners for important definitions
- A cross-functional place to resolve changes and exceptions
- SLA and adoption measures
- Data-quality checks tied to business decisions
- Change control for system logic
- A clear escalation path when teams could not agree

Governance was not the final slide in the project. It was part of the operating system.

## How I would sequence a build like this

I normally think about this type of transformation in this order:

1. Map what is really happening today
2. Find the decisions and ownership gaps underneath the symptoms
3. Agree the target lifecycle and operating model
4. Define the minimum data needed to run it properly
5. Translate that into system and integration requirements
6. Build in controlled stages
7. Test real scenarios and exceptions, not just happy paths
8. Train teams through the workflows they actually use
9. Reconcile reporting back to the new definitions
10. Put ownership and change governance around it

The sequence matters.

If you configure the technology before the business agrees how it wants to operate, you usually end up automating the argument.

## What got better

Because this is a company-neutral composite, I am deliberately not attaching employer-specific metrics to it.

The recurring improvements from this pattern of work were:

- One commercial language across teams
- Clearer handoffs and ownership
- Fewer manual interpretations and workarounds
- More defensible pipeline reporting
- Better conditions for automation and AI
- A clearer path for Marketing, Sales, Product and Finance to work from the same operating model
- A system that could change through visible governance rather than hidden configuration

For me, that is the commercial point of Revenue Operations and Marketing Operations.

Not more process.

**Better execution, better productivity, better decisions and more confidence in how activity becomes pipeline and revenue.**

## What I learned

A few lessons have held up across different companies:

- **CRM transformation cannot fix operating-model disagreement.** It usually makes the disagreement more expensive.
- **A definition is not shared because it exists in a document.** It is shared when teams use it to make the same decision.
- **Exception volume tells you a lot.** If everybody needs a workaround, the standard process is probably wrong.
- **Adoption is part of the design.** A technically perfect model nobody uses is still a failed model.
- **AI needs an operating foundation.** If ownership, evidence and data are unclear, AI gives you faster uncertainty rather than better judgement.
- **The best operating model creates leverage.** It should help the business do more useful work without headcount, tooling and complexity scaling at the same rate.

---

[← Back to overview](README.md) · [About me](PROFILE.md) · [Employer brief](EMPLOYER-BRIEF.md)

I keep additional case studies covering lifecycle governance, campaign operations, pipeline truth and attribution, team design and applied AI in a deeper private portfolio. Access is available on request.
