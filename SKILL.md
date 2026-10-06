---
name: real-world-business-case-skill
description: Turn a real business, finance, AI, technology, or corporate-strategy event into a rigorous educational case study in visual Reading Mode or text-to-speech-friendly Listening Mode. Use when the user wants the economics, stakeholder incentives, strategic mechanism, FP&A implications, transferable framework, and a difficult decision question rather than a news summary.
---

# Real-World Business Case Skill

## Purpose

Use a concrete public event to teach reusable business, finance, strategy, economics, incentive-design, and decision-making knowledge. Move from specific evidence to mechanism to abstraction. Do not produce a news recap, a framework list, or automatic praise or criticism of management.

Use one shared analytical engine for both output modes. Change the presentation, not the intellectual depth.

For a standalone mode prompt or a detailed output contract, read only the relevant file:

- Reading Mode: [prompts/reading.md](prompts/reading.md)
- Listening Mode: [prompts/listening.md](prompts/listening.md)

## Select the case

If the user names an event, use it unless it lacks enough reliable public evidence; explain any material evidence gap. Otherwise choose a case that:

- has a specific decision, change, or conflict rather than a merely popular headline;
- contains a transferable financial, strategic, economic, or incentive mechanism;
- can be explained without private or employer-confidential information;
- adds variety when prior cases are known, instead of repeating the same underlying lesson;
- is recent when recency improves relevance, or historical when the mechanism is unusually instructive.

Good domains include corporate strategy, finance, artificial intelligence, semiconductors, technology platforms, gaming, consumer businesses, mergers and acquisitions, pricing, capital allocation, organizational incentives, business-model changes, and failures caused by bad metrics.

Do not assume the audience knows the company, industry, or jargon.

## Research and evidence discipline

When research tools are available, verify consequential and time-sensitive claims. Prefer primary sources: regulatory decisions, filings, audited reports, earnings materials, investor presentations, and official transaction documents. Use high-quality financial reporting for independent context or facts unavailable in primary sources.

- Never invent a financial figure, quotation, motive, or causal claim.
- Distinguish **Fact**, **Interpretation**, and **Assumption** when a reasonable reader could confuse them.
- Treat management statements as claims or intentions, not proof of outcomes.
- Attach dates or periods to figures whose meaning depends on time.
- If a useful calculation depends on unavailable inputs, show the relationship and identify the missing inputs instead of fabricating precision.
- Cite sources near material factual claims when the output format and tools permit it. In Listening Mode, keep spoken source references light and place a compact source list after the narrative if useful.

## Shared analytical workflow

### 1. Establish the event

Explain what happened, who was involved, what changed, and why the event is financially or strategically interesting. Provide enough industry and business-model context for a newcomer.

### 2. Follow the money

Trace only the economics that explain the case. Relevant lenses may include revenue, pricing, costs, margins, cash flow, capital allocation, unit economics, operating leverage, fixed versus variable costs, opportunity cost, switching costs, network effects, financing, balance-sheet consequences, and risk-reward asymmetry.

Make the money flow concrete. Identify who pays, who receives cash, what investment is required, what must improve, and over what time horizon. Avoid a mechanical checklist.

### 3. Map stakeholders

For each stakeholder material to the decision, explain:

- what the stakeholder is optimizing for;
- what information it possesses or lacks;
- what incentives and constraints it faces;
- where its interests align or conflict with others.

Consider management, employees, customers, suppliers, shareholders, creditors, regulators, competitors, platform partners, and society only when relevant.

### 4. Identify the incentive mechanism

Look for mechanisms such as principal-agent problems, Goodhart's Law, prisoner's dilemmas, moral hazard, adverse selection, key-performance-indicator gaming, short-term versus long-term incentives, coordination failure, platform lock-in, cannibalization, or organizational silos.

Explain a concept in plain language before applying its name. Show the behavior it predicts and the evidence that would support or weaken the diagnosis.

### 5. Explain the strategic mechanism

Test why the decision may or may not make sense. Use only frameworks with explanatory value, such as competitive advantage, moats, switching costs, network effects, vertical integration, ecosystem strategy, platform economics, bundling, pricing power, market structure, economies of scale or scope, option value, real options, capital allocation, build-buy-partner choices, disruption, or path dependency.

State the causal chain. Do not substitute a framework label for an explanation.

### 6. Add the management and FP&A view

Use this section when it sharpens the decision. Translate strategy into:

- the few metrics financial planning and analysis would monitor;
- leading and lagging indicators;
- a management key performance indicator that could induce bad behavior;
- the forecast assumptions with the greatest value impact;
- a simple sensitivity or scenario analysis;
- the threshold at which the recommended decision changes.

Do not imply false precision. Connect operational drivers to cash flow, return on invested capital, or another decision-relevant outcome.

### 7. Abstract the case

Explicitly make the move: this case looks like it is about X, but structurally it is about Y. Derive one or more reusable frameworks and give recognition cues that would reveal the same structure in a different industry.

### 8. Frame the decision

Steelman the strongest credible arguments on multiple sides. Examine the do-nothing case, alternative uses of capital, second-order effects, reversibility, and the assumptions that must hold for management's choice to work.

### 9. End with one thinking question

Every case must end with exactly one meaningful discussion question. Never remove it during shortening or summarization.

The question must have no obvious correct answer, contain a real trade-off, require evidence from the case, and place the audience in a decision-making role such as chief executive officer, chief financial officer, financial planning and analysis leader, investor, regulator, or product leader. A strong question asks for a choice, the most sensitive assumption, and evidence that would reverse the choice.

Do not end with a quiz, a list of questions, a generic invitation to discuss, or any text after the single question.

## Reading Mode

Optimize for visual comprehension and deliberate study. Use descriptive Markdown headings, bullets, tables, compact calculations, comparison matrices, and limited quotations when they materially improve understanding. Keep the prose conversational and cohesive rather than turning the analysis into a listicle.

A useful sequence is: case title, what happened, why it matters, money, stakeholders and incentives, strategic mechanism, management and FP&A view, deeper framework, risks, transferable lesson, and the decision question. Adapt headings to the case while preserving the shared workflow.

## Listening Mode

Write a spoken narrative for a listener who never looks at the screen. Preserve the same evidence, financial reasoning, counterarguments, abstraction, and decision difficulty as Reading Mode.

- Do not use Markdown blockquotes or visually dependent tables.
- Avoid quotation marks and long direct quotations; paraphrase instead.
- Avoid markup or symbols that text-to-speech may vocalize awkwardly, including arrows, asterisks used for emphasis, slashes, inequality signs, and dense equations.
- Convert tables into narrated comparisons and equations into natural language.
- Expand uncommon abbreviations on first use. Say large numbers naturally.
- Minimize parentheses and dense bullet sequences.
- Use spoken signposts so the listener always knows the current stage and its connection to the prior one.
- Use headings only if they improve navigation without making the prose sound mechanical.

Natural transitions include: First, let us look at what actually happened. Now the interesting part is the money. Next, let us look at the incentives. Here is where the case becomes more general. Now imagine you are the chief financial officer. The deeper lesson is this. Finally, here is the decision I want you to make.

Audio-friendly means reformatted, not simplified.

## Output-quality checklist

Before returning a case, verify:

- The event is specific and adequately contextualized.
- Claims that could have changed are verified when research is available.
- Facts, interpretations, and assumptions are distinguishable where material.
- The money flow and value-creation logic are explicit.
- Stakeholder incentives and conflicts are explained, not merely named.
- Frameworks are relevant and connected through a causal mechanism.
- The management view links operating drivers to financial outcomes.
- The analysis presents strong arguments on more than one side.
- The abstraction can transfer to a different company or industry.
- Reading and Listening modes use the same analytical engine and depth.
- Listening Mode contains no blockquotes, avoids visual dependencies, and minimizes quotation marks.
- No private, employer-confidential, or personally identifying information appears.
- The final element is exactly one difficult decision question, with nothing after it.
