---
title: "Enterprise LLM Selection: Frontier vs Open-Source Models"
parent: "Extra Section: AI for Pre-Sales"
nav_order: 5
duration: "4:42"
---

# Enterprise LLM Selection: Frontier vs Open-Source Models
{: .no_toc }

*Read duration: 4:42*

"Which model should we use?" sounds like an engineering question, but in a pre-sales conversation it's really a procurement question wearing a technical costume — it's about budget, data control, and risk tolerance as much as raw capability, and it's worth being able to frame it that way for a client who's currently fixated on capability benchmarks alone.

## Frontier Models

**Frontier models** are the proprietary, state-of-the-art models from major AI labs — OpenAI, Anthropic, and Google are the names that come up most in enterprise conversations. You access them through an API rather than downloading anything; the provider hosts the infrastructure, handles security and uptime, and charges per token. The trade-off is control: you're renting capability, not owning it, and you're dependent on the provider's pricing, availability, and data-handling terms — though major providers now offer enterprise agreements addressing exactly the data-retention and confidentiality concerns that come up most often in a security review.

Frontier models are usually the right default recommendation when a client's priority is getting to a working solution fast with minimal infrastructure investment, and when the use case benefits from the strongest available general reasoning — complex analysis, nuanced writing, multi-step problem solving.

## Open-Source and Open-Weight Models

**Open-weight models** — Llama, DeepSeek, Qwen, and Mistral are the names you'll hear most — publish their trained model files for anyone to download, self-host, and run. That unlocks a different set of trade-offs: a client can run the model entirely within their own infrastructure, which matters enormously for data residency and air-gapped or highly regulated environments where sending data to a third-party API isn't an option at all, regardless of that provider's terms. Open-weight models can also be fine-tuned on a client's own data far more deeply than most frontier API offerings allow, and at high volume, self-hosting can be meaningfully cheaper than per-token API pricing.

The cost of that control is operational: someone has to host, secure, monitor, and maintain the infrastructure running the model, which requires in-house ML/infrastructure talent a client may not have. Capability has also historically trailed the top frontier models on the hardest reasoning tasks, though the gap has narrowed significantly and is often irrelevant for narrower, well-defined tasks.

## A Decision Framework

| Dimension | Favors frontier | Favors open-weight |
|---|---|---|
| Data sensitivity | Standard enterprise agreement is sufficient | Regulatory or contractual requirement to keep data on-premises |
| Budget shape | Lower volume, want to avoid infrastructure investment | High, predictable volume where self-hosting cost wins |
| In-house talent | Limited ML/infra team | Existing MLOps capability |
| Task complexity | Complex, open-ended reasoning | Narrow, well-defined, repetitive task |
| Time to deploy | Need something running quickly | Timeline allows for setup and tuning |

Many enterprise engagements don't land on a single answer — an increasingly common and sophisticated pattern is **model routing**: using a frontier model for the smaller share of requests that need its full reasoning power, and a cheaper, self-hosted open-weight model — sometimes fine-tuned for the specific task — for the high-volume, routine share of requests. Proposing that kind of tiered architecture, rather than a single model for everything, is usually a stronger and more cost-conscious position than defaulting to "just use the best model" in front of a budget-conscious buyer.

{: .important }
> Never let a client's data residency or compliance requirement get overridden by a preference for "the best model." If the requirement is real, it eliminates frontier API options outright, regardless of capability — confirm this constraint early in discovery, not after you've already built a proposal around the wrong category.

<!-- prevnext:start -->

---

| [&larr; Previous: AI Terms Explained for Presales: LLMs, GenAI, Transformers & Agents](ai-terms-explained-for-presales-llms-genai-transformers-and-agents) | [Next: Where AI Creates Value: Automation, Augmentation & Differentiation &rarr;](where-ai-creates-value-automation-augmentation-and-differentiation) |
|:---|---:|

<!-- prevnext:end -->
