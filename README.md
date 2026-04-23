# product-report

A [Claude Code](https://claude.ai/code) skill that reads a codebase and translates it into sharp business language — value propositions, selling points, competitive framing, and a pitch.

Built for engineers who need to sell, founders preparing for demos, and PMs who want a grounded product brief.

## Install

```bash
npx skills add mriziq/product-report
```

## Usage

Navigate to any codebase and invoke the skill:

```
/product-report
```

No arguments needed. Claude will explore the codebase on its own before producing the brief.

## What You Get

The skill produces a structured **business brief** with seven sections:

| Section | What it covers |
|---|---|
| **What This Product Actually Does** | Plain-English summary grounded in the actual code |
| **Core Value Proposition** | Value Prop Canvas: customer jobs, pains relieved, gains created — plus a tight VP statement |
| **Selling Points (Ranked)** | 5–8 points, each tied to specific code evidence, ranked by differentiation |
| **Competitive Framing** | Category positioning + Blue Ocean analysis |
| **Jobs-to-Be-Done Narrative** | A customer story in JTBD format |
| **The Pitch (30 seconds)** | A crisp, memorable verbal pitch |
| **Strategic Observations** | Moats, risks, TAM implications, design assumptions |

## Design Philosophy

Every claim in the output traces back to something actually in the code. No hallucinated features, no generic buzzwords. The skill is built on a simple constraint: **if it's not in the codebase, it doesn't go in the brief.**

The persona is a former senior engineer who crossed over to the product and business side — someone who reads systems and markets simultaneously, and writes with conviction rather than hedging.

## Frameworks Used

- [Value Proposition Canvas](https://www.strategyzer.com/library/the-value-proposition-canvas) — jobs, pains, gains
- [Blue Ocean Strategy](https://www.blueoceanstrategy.com/) — eliminate, reduce, raise, create
- [Jobs-to-Be-Done](https://www.christenseninstitute.org/jobs-to-be-done/) — customer motivation framing

## License

MIT
