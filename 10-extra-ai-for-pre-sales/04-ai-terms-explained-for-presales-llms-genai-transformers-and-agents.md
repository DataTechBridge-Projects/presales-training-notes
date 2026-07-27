---
title: "AI Terms Explained for Presales: LLMs, GenAI, Transformers & Agents"
parent: "Extra Section: AI for Pre-Sales"
nav_order: 4
duration: "10:59"
---

# AI Terms Explained for Presales: LLMs, GenAI, Transformers & Agents
{: .no_toc }

*Read duration: 10:59*

You don't need to be able to build a model to run a credible pre-sales conversation about one — but you do need to use the right words correctly, because a technical stakeholder on the client side will notice within the first two minutes if you're using "AI," "model," and "agent" interchangeably as filler words. This lecture is a working glossary of the four terms you'll hear most, explained at the depth you actually need: enough to define each one precisely, connect it to something concrete, and use it correctly in a live discovery call or technical Q&A.

## Large Language Models (LLMs)

A **large language model (LLM)** is a type of AI model trained on massive amounts of text to predict what word — more precisely, what "token," a chunk of a word — comes next in a sequence. That sounds mechanical, but at the scale these models are trained (essentially a large fraction of publicly available text, plus licensed and proprietary data), next-word prediction turns out to be enough to produce coherent answers, summaries, translations, and code. GPT, Claude, and Gemini are all LLMs; so are the open-source models covered later in this section, like Llama and Mistral.

The pre-sales scenario where this term matters most: a client asks "what model is this built on?" This is really a due-diligence question about capability, cost, and data handling, not a request for a technical lecture. You want to be able to say, in one sentence, which category of model you're proposing (a frontier LLM accessed via API, or a self-hosted open-source LLM) and why — a distinction the next lecture in this section covers in depth.

## Generative AI (GenAI)

**Generative AI** is the broader umbrella term for any AI system that creates new content — text, images, audio, video, or code — rather than only classifying or predicting from existing data. Every LLM is a generative AI system, but not every generative AI system is an LLM: an image generator or a music generator is generative AI built on different underlying model architectures.

This distinction matters in a client conversation because "AI" and "GenAI" get used loosely and interchangeably in the market, and a buyer's actual need is often narrower than the buzzword suggests. If a client says "we want to add AI to our reporting tool," the useful follow-up is finding out whether they mean something predictive (forecast next quarter's numbers), generative (auto-write a plain-English summary of the report), or something else entirely — because those are different projects with different data requirements, covered in more depth in the ideation lecture earlier in this section. Using "GenAI" precisely, instead of as a synonym for "AI" in general, is itself a small credibility signal.

## Transformers

The **transformer** is the neural network architecture that made the current generation of LLMs possible, introduced in a 2017 research paper and now underlying essentially every major model on the market. You don't need the math, but the one idea worth carrying into a client conversation is the **attention mechanism** — the transformer's core innovation, which lets a model weigh the relationship between every word in a passage and every other word simultaneously, regardless of how far apart they are in the text. Earlier architectures processed text strictly in order, one word at a time, which made it hard for a model to connect something mentioned at the start of a long document to something at the end. Attention solved that, and it's also what makes transformers efficient to train on modern hardware at massive scale — both together are why capability jumped so sharply once this architecture took over.

You'll rarely need to explain attention mechanisms in a sales conversation, but you will occasionally get a technical stakeholder who asks something like "is this transformer-based?" almost as a sanity check that you know what you're proposing. Being able to answer "yes — it's what every major LLM on the market today is built on" in one confident sentence, rather than visibly not recognizing the term, is the entire value of knowing this one.

## Agents / Agentic AI

An **agent**, in the AI sense, is a system that uses an LLM as a reasoning engine to plan and carry out a multi-step task — often using external tools like a database lookup, a search, or an API call — with some degree of autonomy, rather than just returning one answer to one prompt. The distinction that matters in a sales conversation is chatbot versus agent: a chatbot answers a question; an agent can look something up, take an action based on what it finds, and then decide what to do next based on the result of that action — a chain, not a single exchange.

This is the term most likely to get overused and under-defined in a client meeting, because "agentic" has become a popular buzzword attached to products that are really just a chatbot with a slightly longer memory. When a client asks for "an agent," the pre-sales job is to pin down exactly what it's allowed to do autonomously, what tools or systems it needs access to, and what happens when it's uncertain or wrong — the same autonomy questions covered in the ideation lecture's discussion of agentic AI risk. Precision here protects you later: an under-specified "agent" in a proposal is exactly the kind of vague deliverable language that turns into a change order once delivery starts.

## A Few More Terms Worth Knowing

A handful of related terms come up often enough alongside these four that they're worth defining briefly rather than leaving you to guess at them mid-conversation.

A **token** is the basic unit an LLM reads and generates — roughly three-quarters of a word on average in English, though it can be a whole word, part of a word, or a punctuation mark. This matters commercially because most frontier models are priced per token, both for what you send in and what the model sends back, which is why a client processing long documents at high volume needs a cost model built around token counts, not a flat per-user or per-seat estimate. **Parameters** are the internal numerical values a model adjusts during training to capture patterns in its training data — when you see a model described as having a certain number of billions of parameters, that's a rough (and imperfect) proxy for its scale and capability, and it's a number you'll occasionally hear a technical buyer reference when comparing models, even though it's rarely the deciding factor in choosing one.

A **prompt** is the instruction or question you give an AI model — the input side of the exchange. **Prompt engineering** is the practice of writing prompts deliberately and specifically (the same discipline behind the worked prompt example in the prototyping lecture) to get more reliable, useful output. The **context window** is the amount of text a model can consider at once — its short-term memory for a given conversation or document — and it matters commercially because a client with very long documents (a full contract library, for instance) may need a model with a larger context window, which can affect cost and vendor choice.

**Fine-tuning** is the process of taking a pre-trained model and further training it on a narrower, client-specific data set so it performs better on a specific task or in a specific voice — a heavier, more expensive customization than prompting alone, and a scoping decision worth flagging early rather than assuming it's included by default. **Retrieval-augmented generation (RAG)** is a technique for connecting a model to a specific set of documents or a database at the moment it answers a question, so it can ground its response in the client's actual content instead of only what it learned during training — this is usually the honest answer to a client's question "will it know our company's data," rather than fine-tuning, which is heavier and less often what's actually needed.

Finally, a **hallucination** is when a model produces a fluent, confident-sounding answer that's factually wrong or entirely fabricated — not a bug in the traditional sense, but a structural property of how these models generate text. Knowing this term, and being able to explain that it's why every AI-assisted workflow you propose includes a human review step, is one of the fastest ways to earn trust with a risk-conscious technical buyer instead of losing it.

<!-- prevnext:start -->

---

| [&larr; Previous: AI Project Ideation: Predictive, Generative, and Agentic AI](ai-project-ideation-predictive-generative-and-agentic-ai) | [Next: Enterprise LLM Selection: Frontier vs Open-Source Models &rarr;](enterprise-llm-selection-frontier-vs-open-source-models) |
|:---|---:|

<!-- prevnext:end -->
