---
title: "AI Project Ideation: Predictive, Generative, and Agentic AI"
parent: "Extra Section: AI for Pre-Sales"
nav_order: 3
duration: "11:36"
---

# AI Project Ideation: Predictive, Generative, and Agentic AI
{: .no_toc }

*Read duration: 11:36*

Every AI opportunity a client raises during discovery falls into one of three fundamentally different categories, and mixing them up is one of the fastest ways to lose credibility with a technical buyer. Knowing which category you're in changes what you scope, what data you need, what you demo, and how much risk language belongs in the SOW.

## Predictive AI

**Predictive AI** looks at historical data and forecasts or classifies something about the future or the unknown — a number, a category, or a probability. It's the oldest and most mature of the three categories, and it's what most "AI" projects were before generative AI became the default association with the term. A retailer using three years of sales history to forecast next quarter's demand by SKU, an insurer scoring a claim's likelihood of fraud, or a manufacturer predicting which machine is about to fail based on sensor readings are all predictive AI. The output is typically a number or a label, not a paragraph.

Predictive projects live or die on data quality. Before you position one, the discovery question that matters most is "how much clean, labeled historical data do you actually have on this?" — a client with five years of well-structured transaction history is a strong predictive candidate; a client who's excited about "predicting churn" but has no consistent record of who actually churned and when is not ready for this yet, no matter how much they want the outcome.

## Generative AI

**Generative AI** creates new content — text, images, code, audio — by producing output that follows the patterns it learned from training data, rather than looking up or calculating an answer. This is the category most buyers mean when they say "AI" today, and it covers everything from a chatbot answering support questions to a tool that drafts marketing copy, summarizes contracts, or writes code from a natural-language description.

The pre-sales-relevant nuance is that generative AI's biggest strength — fluent, human-sounding output — is also its biggest risk, because fluent output isn't the same as correct output. A generative tool that drafts a contract summary with total confidence and a subtly wrong clause is more dangerous than one that visibly fails, because a wrong summary that reads as authoritative can slip past review. Every generative AI proposal should include a review or validation step in the workflow, not just the generation step — and saying so explicitly in a client conversation is a strong credibility signal, because it shows you understand the technology's actual failure mode instead of just its capability.

## Agentic AI

**Agentic AI** goes a step further than either of the above: instead of returning a single answer to a single prompt, an agent uses an AI model as a reasoning engine to plan and carry out a multi-step task — often across multiple systems — with some degree of autonomy. A predictive model tells you a support ticket is likely a billing issue; a generative model can draft a reply to it; an agentic system can read the ticket, look up the customer's account in a billing system, decide whether a refund is warranted under policy, issue it, and reply to the customer — as a chain of actions, not a single response.

This is the newest and highest-risk category, and it's also where the most inflated client expectations tend to show up, because "agentic" gets used loosely in the market to describe things that are really just a slightly more elaborate chatbot. Positioning an agentic opportunity honestly means being explicit about autonomy: what the agent is allowed to do without a human in the loop, what it must escalate, and what happens when it's wrong. A refund-issuing agent with no spending cap and no human checkpoint is a very different — and much riskier — engagement than the same agent capped at $50 and required to flag anything above that for a person, even though both get called "an agentic support system" in a sales conversation.

## The Same Problem, Three Different Projects

It's worth seeing all three categories applied to a single business problem, because clients rarely arrive with the category already decided — they arrive with a pain point, and part of your value is showing them there's more than one way to attack it. Take a mid-size retailer's customer support operation as the example.

A **predictive** angle might classify each incoming ticket by likely category and urgency the moment it arrives, routing billing disputes to one queue and shipping issues to another before a human ever reads it — a modest, well-bounded project if the retailer already has a few years of tagged historical tickets to train against. A **generative** angle might draft a first-response reply to each ticket in the company's tone of voice, which a support agent reviews and sends rather than writing from scratch — faster to stand up than the predictive version, but entirely dependent on a reviewer staying in the loop, since a fluent, wrong reply sent unreviewed is a worse outcome than no automation at all. An **agentic** angle goes further still: the system reads the ticket, checks the order status in the retailer's fulfillment system, and — for a narrow, pre-approved category like "package marked delivered but customer says not received, order under $75" — issues a replacement automatically and only escalates anything outside that boundary to a person.

Notice the pattern: the three versions aren't equally mature asks. The predictive and generative versions are reasonable phase-one scopes for most clients; the agentic version is the kind of opportunity worth naming early and positioning as a later phase, once the retailer has confidence in the underlying classification and drafting components it depends on. Walking a client through this progression — rather than pitching the most ambitious version first — is usually what turns "that sounds interesting" into a signed SOW.

## A Framework for Spotting the Right Category in Discovery

You rarely need to ask a client "do you want predictive, generative, or agentic AI?" — most buyers don't think in those terms and won't know how to answer. Instead, listen for the shape of the problem they describe and translate it yourself.

| What the client describes | Likely category | What to ask next |
|---|---|---|
| "We want to know X before it happens" (demand, risk, failure, churn) | Predictive | How much clean historical data exists on X? |
| "We spend too much time writing/summarizing/drafting Y" | Generative | Who reviews the output today, and would they still need to? |
| "We want this whole process to just happen without someone managing it" | Agentic | What's the cost of the system getting a step wrong, and who's accountable? |

The data-readiness and risk questions in that table aren't a formality — they're what separates a scoped, fundable opportunity from a workshop idea that dies in the next budget cycle. A predictive pitch with no historical data isn't a smaller predictive project, it's not a predictive project yet; the real scope is a data-collection engagement first. An agentic pitch with no answer to "who's accountable when it's wrong" isn't ready for a SOW — it's ready for a narrower pilot with a human checkpoint built in from day one, positioned honestly as a first phase rather than the full vision.

## Turning Ideation into Positioning

Once you've placed an opportunity in one of the three categories, it should shape two things in your proposal: the acceptance criteria and the risk language. A predictive engagement's acceptance criteria center on model accuracy against a held-out data set — agree with the client up front on what accuracy is "good enough" to go live, because "make the forecast better" is not a criterion anyone can sign off on. A generative engagement's acceptance criteria center on the review workflow around the output, not just the output's quality in isolation. An agentic engagement needs the most explicit language of the three — named boundaries on what the system can do autonomously, an escalation path, and a rollback plan — because autonomy is precisely the feature that makes an agentic system valuable and the feature that makes it risky if it's under-specified.

{: .important }
> Don't let a client's enthusiasm for "agentic AI" as a buzzword push you into scoping full autonomy on day one. The safest and most fundable version of almost any agentic pitch is a phase-one pilot with a human checkpoint on the highest-risk actions, expanding autonomy only after the pilot proves out — that's a stronger, more sellable story than promising full autonomy up front and hoping the risk never materializes.

This same three-way lens carries forward into how you think about AI's business value more broadly, which is where the value framework later in this section picks up.

<!-- prevnext:start -->

---

| [&larr; Previous: From RFP to Clickable Prototype using AI](from-rfp-to-clickable-prototype-using-ai) | [Next: AI Terms Explained for Presales: LLMs, GenAI, Transformers & Agents &rarr;](ai-terms-explained-for-presales-llms-genai-transformers-and-agents) |
|:---|---:|

<!-- prevnext:end -->
