# Real-World Business Case Skill

Turn a concrete event in business, finance, artificial intelligence, technology, or corporate strategy into a rigorous educational case study.

This project is not a news-summary prompt. It uses an event as the doorway into the economics, incentives, strategic mechanism, and decision trade-offs underneath it. The result should help someone recognize the same structure when it appears in another company or industry.

```text
Real Event
    ↓
Money
    ↓
Stakeholders
    ↓
Incentives
    ↓
Strategy
    ↓
FP&A
    ↓
Transferable Framework
    ↓
Decision Question
```

## Why learn through cases

Definitions are easy to memorize and easy to forget. A case makes a concept earn its place. Instead of beginning with a theory such as platform economics, the analysis begins with a decision made by real people using real capital. It then follows the money, identifies who benefits and who bears risk, and only afterward names the reusable mechanism.

That sequence helps readers move from recognition to transfer:

1. Understand what actually happened.
2. See the financial and behavioral forces that shaped the decision.
3. Separate fact from interpretation and assumption.
4. Abstract the event into a framework that travels.
5. Make a difficult decision under uncertainty.

## Two modes, one analytical engine

### Reading Mode

Use Reading Mode when the output will be studied on screen. It supports headings, tables, bullets, equations, compact calculations, and comparison matrices. It is optimized for scanning, revisiting assumptions, and comparing stakeholders or scenarios.

### Listening Mode

Use Listening Mode when the output will be heard through text-to-speech, especially while driving or walking. It uses spoken transitions, natural descriptions of numbers, and verbal comparisons instead of tables or visually dependent notation. It preserves the same financial and strategic depth as Reading Mode; it is not a shortened or easier version.

Both modes end with exactly one genuinely difficult decision question. That question is part of the learning method, not an optional conclusion.

## The analytical engine

Every case moves through the same underlying logic:

- **Event:** Establish the company, industry, actors, decision, and change without assuming prior knowledge.
- **Money:** Trace the relevant revenue, costs, cash flow, margins, capital allocation, unit economics, financing, and risk asymmetry.
- **Stakeholders:** Identify what each important party is optimizing for, what it knows, and where incentives align or conflict.
- **Incentive mechanism:** Explain the relevant behavioral structure, such as a principal-agent problem, key-performance-indicator gaming, moral hazard, or cannibalization.
- **Strategic mechanism:** Test the decision through only the frameworks that explain it, such as switching costs, network effects, vertical integration, option value, or build-versus-buy.
- **Management and FP&A:** Translate strategy into metrics, forecast assumptions, sensitivities, and decision thresholds. FP&A means financial planning and analysis.
- **Abstraction:** State what the case appears to be about and what it is structurally about, then derive a transferable framework.
- **Decision:** Steelman multiple sides, test the do-nothing alternative and opportunity cost, and finish with one hard role-based question.

The engine is selective rather than mechanical. A case should not mention every business concept; it should use the few concepts that do the most explanatory work.

## Repository structure

```text
real-world-business-case-skill/
├── README.md
├── SKILL.md
├── LICENSE
├── prompts/
│   ├── reading.md
│   └── listening.md
└── examples/
    ├── reading-example.md
    └── listening-example.md
```

`SKILL.md` is the canonical, portable skill definition. The files in `prompts/` are convenient standalone prompts. The examples analyze the same public acquisition in both modes so the presentation difference is easy to inspect.

## Use with an LLM

### ChatGPT, Claude, Gemini, or another chat model

Paste the contents of `prompts/reading.md` or `prompts/listening.md` into the system or instruction field, then provide a company, event, or area of interest. If the product supports project instructions, save the chosen prompt there.

### Codex or another skill-aware agent

Copy this folder into the product's skills directory or point the agent to `SKILL.md`. Invoke the skill by name and specify a mode. The skill is intentionally portable: it requires no private data, proprietary tool, or user-specific configuration.

### Example invocation

> Analyze a real-world case about a company's strategic decision. Use Listening Mode. I want to understand the financial logic, stakeholder incentives, strategic mechanism, transferable lesson, and finish with one difficult decision question.

You may also provide a specific event:

> Use Reading Mode to analyze Microsoft's acquisition of Activision Blizzard. Distinguish verified facts from interpretation and assumptions. Focus on capital allocation, platform economics, regulatory remedies, and the assumptions that would make the acquisition create value.

If current web research is available, ask the model to verify time-sensitive facts using filings, earnings materials, official announcements, regulator decisions, and high-quality financial reporting. A model should never invent a figure to make a case feel complete.

## What good output looks like

A strong case is concrete before it is abstract, financially literate without becoming a spreadsheet dump, neutral about management, and explicit about uncertainty. It gives the reader enough context to disagree intelligently. Most importantly, it teaches a mechanism that remains useful after the headline is forgotten.

## License

Released under the [MIT License](LICENSE).
