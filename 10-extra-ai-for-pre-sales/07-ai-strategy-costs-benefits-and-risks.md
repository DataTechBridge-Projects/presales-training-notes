---
title: "AI Strategy: Costs, Benefits & Risks"
parent: "Extra Section: AI for Pre-Sales"
nav_order: 7
duration: "9:14"
---

# AI Strategy: Costs, Benefits & Risks
{: .no_toc }

*Read duration: 9:14*

Every AI opportunity you bring to a client eventually needs to survive the same conversation a traditional engagement does: is it worth what it costs, and what could go wrong. AI initiatives fail that conversation more often than traditional ones — not because the technology is weaker, but because the value, cost, and risk are less obvious and easier to hand-wave. This lecture gives you a structured way to run that conversation deliberately instead of leaving it to enthusiasm.

## Business Value

Start by placing the opportunity in one of the three value categories from the previous lecture — automation, augmentation, or differentiation — because each implies a different way of quantifying value. Automation value is the most straightforward to size: hours currently spent on a task, multiplied by a fully-loaded cost per hour, compared against what the same work costs after AI assists it. Augmentation value is softer and usually shows up as a quality or risk metric instead of a time metric — fewer missed requirements, fewer estimation errors, faster time-to-decision on judgment calls. Differentiation value is the hardest to size in advance and is often better expressed as win-rate impact or a new revenue line than as a cost saving, since there's no "before" state to compare against.

Whichever category you're in, put a number on it before you put a proposal in front of the client. "This will help with proposal quality" doesn't survive a budget conversation; "this cuts proposal turnaround from four days to one and a half across roughly thirty proposals a year" does. That second version also does something the first can't: it gives the client a number to hold you accountable to later, which is exactly the kind of specificity that makes an internal budget sponsor comfortable championing the initiative up their own chain.

## Costs

AI project costs break into three buckets that are easy to underestimate individually, especially the second and third.

**Build cost** covers data preparation, model access or fine-tuning, and integration with the client's existing systems — the cost most proposals already account for, since it maps closely to a traditional project's development cost. **Run cost** is the ongoing cost of operating the solution once it's live — API or token costs at production volume, infrastructure if self-hosted, and monitoring — and it's the bucket most often underestimated, because a demo running at low volume gives no real signal about what the same workload costs at production scale. **Change cost** covers training the people who'll use the system, redesigning the workflows around it, and managing the adoption curve — frequently left out of the estimate entirely, even though a technically successful system that nobody actually adopts delivers zero value regardless of how well it was built.

| Cost bucket | What it covers | Common mistake |
|---|---|---|
| Build | Data prep, model access/fine-tuning, integration | Treated as the whole cost |
| Run | Ongoing API/infra cost at real volume | Estimated from low-volume demo usage |
| Change | Training, workflow redesign, adoption | Left out of the estimate entirely |

## Risks

Risk in an AI initiative also breaks into three categories, and each one calls for a different kind of mitigation language in the SOW. **Technical risk** covers the model itself — hallucination, data quality problems, and model behavior drifting over time as the underlying provider updates it; the mitigation is usually a human review step and a defined accuracy or acceptance threshold, the same acceptance-criteria discipline covered in the ideation lecture. **Operational risk** covers what happens when the AI component depends on systems and vendors outside your control — an API outage, a pricing change, or a fragile integration that breaks when an upstream system changes; the mitigation is a fallback path for when the AI component is unavailable, not just a plan for when it works. **Strategic risk** is the least technical and the easiest to skip in a proposal — over-reliance on a system nobody fully understands, regulatory exposure (especially for anything touching regulated data or automated decisions about people), and the possibility that a differentiation bet stops being differentiating once competitors catch up.

{: .important }
> Don't let the excitement of "everyone's doing agentic AI right now" substitute for this framework. A high-autonomy, high-novelty pitch with no accounting for operational and strategic risk isn't a bolder proposal — it's an under-scoped one, and it will surface as a change order or a credibility problem during delivery instead of during pre-sales, where it's far cheaper to catch.

Weigh the three risk categories against the value category from the start of this lecture, and a pattern emerges: automation opportunities tend to carry mostly technical and operational risk, which is manageable with good review steps and a fallback path. Differentiation and agentic opportunities carry meaningfully more strategic risk, precisely because they're doing something new enough that there's no established playbook for what happens when it goes wrong — which is exactly why they deserve the more cautious, phased approach covered next, rather than being scoped and priced the same way a routine automation project would be.

## Prioritizing With an ROI-Driven Approach

Once you've sized value, cost, and risk for a set of candidate AI opportunities, a simple two-axis view — value against combined cost and risk — is usually enough to guide a client toward a sensible sequence rather than tackling everything at once.

| | Low cost & risk | High cost & risk |
|---|---|---|
| **High value** | Quick win — prioritize first | Strategic bet — pilot with tight guardrails |
| **Low value** | Nice-to-have — backlog | Avoid — don't build a case for this |

Quick wins are usually automation opportunities with clean data and a narrow scope — the right place to build a client's confidence and internal appetite for AI before proposing anything bigger. Strategic bets are usually differentiation or agentic opportunities with real upside but real unknowns — the right response is a scoped pilot with explicit success criteria and a human checkpoint, not a full production commitment on the first engagement. Recommending the quick win first, even when the client is more excited about the strategic bet, is often the move that actually earns you the second, larger engagement — it demonstrates the discipline this whole framework is built around, rather than just the enthusiasm every vendor pitching AI already has.

<!-- prevnext:start -->

---

| [&larr; Previous: Where AI Creates Value: Automation, Augmentation & Differentiation](06-where-ai-creates-value-automation-augmentation-and-differentiation) | [Next: Extra Section: Google Partner Services &rarr;](../11-extra-google-partner-services/) |
|:---|---:|

<!-- prevnext:end -->
