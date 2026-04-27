# COPY.md

Brand voice in a single markdown file. Tells your AI assistant how to write like you, not like an AI. The single highest-leverage thing in here is the banned phrases list.

This is one of a family of five templates that customise AI for the way you actually work.

| Template | What it covers | When to do it |
|----------|----------------|---------------|
| **[CLAUDE.md](https://github.com/catrinmdonnelly/CLAUDE.md)** | Who you are, how you work, what's on your desk | First. Even if you do nothing else, this gets you 70% of the value |
| **[COPY.md](https://github.com/catrinmdonnelly/COPY.md)** (this repo) | How things should sound. Voice + banned phrases | Second. Voice is the most-violated AI default |
| **[DESIGN.md](https://github.com/catrinmdonnelly/DESIGN.md)** | How things should look. Design tokens + banned aesthetics | Third. Only if you make visual things (websites, slides, social posts) |
| **[CONTEXT.md](https://github.com/catrinmdonnelly/CONTEXT.md)** | What each project is and where it's going | Per project, when you start working in a specific folder |
| **[NORTH-STAR.md](https://github.com/catrinmdonnelly/NORTH-STAR.md)** | Career-level direction. The why behind the projects | Last, and only if you have multiple businesses or want to think strategically |

You don't have to do all five. The minimum useful set is **CLAUDE.md + COPY.md**. Add the others as you need them.

They reference each other. Your CLAUDE.md tells AI to read the others when the relevant work comes up, so you do not have to think about which file is needed when.

## Why this exists

The hardest part of using AI for copy isn't capability. It's voice. AI defaults to a smooth, hedged, slightly American, slightly corporate register that sounds the same across every business. A COPY.md is the only thing that breaks that default.

The thing that makes it work isn't a beautifully written tone document. It's the **banned phrases list**. Research from Atom Writer and Dotdigital benchmarks shows AI follows explicit vocabulary rules at ~90% compliance, versus ~55% for vague principles like "be friendly" or "be approachable."

Write the list. Update it weekly. Watch the copy improve.

## Built on the work of others

The voice document is one of the most-written types of brand document. If anything in here is good, the credit goes to:

- **[Mailchimp Content Style Guide](https://styleguide.mailchimp.com/voice-and-tone/)** for the canonical voice-vs-tone framing. Voice is fixed, tone shifts by context. That distinction structures this whole template.
- **[GOV.UK Style Guide](https://www.gov.uk/guidance/style-guide/a-to-z-of-gov-uk-style)** for the plain-English standard and the "useful before clever" approach.
- **[Shopify Polaris Voice and Tone](https://polaris-react.shopify.com/content/voice-and-tone)** for rationale-first writing. Explains why a rule exists, not just the rule.
- **[Nielsen Norman Group](https://www.nngroup.com/articles/tone-of-voice-dimensions/)** for the four-dimension tone-of-voice framework (funny vs serious, formal vs casual, etc.).
- **[Wikipedia: Signs of AI Writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing)** for the most thorough public list of AI tells. The Banned phrases section borrows heavily from this.
- **[Dotdigital](https://dotdigital.com/blog/how-to-create-a-brand-voice-guide-that-ai-can-actually-use/)** and **Atom Writer** for the compliance benchmarks: ~90% with explicit vocabulary rules vs ~55% for vague principles. That insight is the whole reason this template leads with banned phrases.

What's mine is the non-tech-friendly format, the conversational walk-through, the per-brand voice variation pattern, and the integration with CLAUDE.md and DESIGN.md as a coherent family.

## Who it's for

- **Solo founders** who want their AI assistant to write in their actual voice, not a generic one
- **Marketers and writers** sick of fighting AI defaults on every draft
- **Small teams** sharing a single voice source of truth via git
- **Anyone using Claude, ChatGPT, Gemini** to draft copy for a real audience

## What's in this repo

| File | What |
|------|------|
| `COPY.md` | The template. Walk through it with Claude (paste it into a chat) or fill it in by hand. |
| `README.md` | This file. |
| `LICENSE` | MIT. |

## How to use

There are two ways to use this template:

### Conversational (the easy way, for non-technical users)
1. Open `COPY.md` in this repo, copy the whole file
2. Paste it into a Claude chat. Claude reads the meta-instruction at the top and walks you through it section by section
3. Claude pays special attention to the Banned phrases list (the highest-leverage section) and asks you to provide real verbatim phrases for the voice fingerprint
4. At the end, you get a clean version (comments stripped) to save as `COPY.md` in your project folder

### Manual (for writers and marketers)
1. Copy `COPY.md` to your project folder
2. Fill in each section. Spend most time on Banned phrases and the voice fingerprint. They are the high-leverage parts.
3. Delete the HTML comments. Save.

### The non-negotiable wiring step

Whichever way you use it, you must add this line to your `CLAUDE.md` so AI actually reads `COPY.md` before writing:

```
Read COPY.md before writing any user-facing copy. Apply the banned phrases list strictly. When in doubt, use the self-check before sending.
```

Without that line, AI treats COPY.md as a suggestion. With it, AI treats it as a rule.

### Keep it alive
Add to the banned phrases list every time AI reaches for a word or phrase that isn't yours. The file gets stronger over time.

## The five things I learned from research

1. **Banned phrases beat principles.** ~90% AI compliance for vocabulary rules vs ~55% for vague principles. Lead with the ban list.
2. **Before-and-after pairs lift compliance 25-35%.** Three to five worked rewrites teach the AI more than three pages of philosophy.
3. **A "voice fingerprint" of real sentences is the most powerful single input.** Five to ten verbatim things you've actually written. Don't polish them.
4. **Negative examples are mandatory.** Tell the AI what slop looks like, not just what the target is.
5. **Tag rules as hard or soft.** "NEVER use em dashes" outperforms "prefer commas." Use IMPORTANT and YOU MUST for the rules that actually matter.

## The categories of banned phrases

Twelve buckets to think in. Each one is its own section in the template:

1. **Corporate jargon**: leverage, synergy, stakeholders, deliverables, bandwidth
2. **Empty intensifiers**: robust, seamless, innovative, world-class
3. **AI tells (vocabulary)**: delve, tapestry, landscape, foster, multifaceted, comprehensive, vibrant
4. **AI tells (structural)**: "It's worth noting that...", "In today's fast-paced world...", three-noun lists, em dashes
5. **Hype and superlatives**: game-changing, revolutionary, transformative, unlock
6. **Fake urgency**: limited spots, don't miss out, last chance
7. **Hedged / weasel language**: "industry experts agree", "studies show"
8. **Salesy openers**: "I hope this email finds you well", "I'd love to pick your brain"
9. **Empty flattery**: "I love what you're doing" without specifics
10. **Disclaimers dressed as authenticity**: "no sales pitch", "genuinely just curious"
11. **Generic CTAs**: "learn more", "get started today", "click here"
12. **AI self-narration**: "Certainly!", "Great question!", "Here's a breakdown..."

## References

The best thinking I found while writing this:

### Primary style guides
- [Mailchimp Content Style Guide](https://styleguide.mailchimp.com/voice-and-tone/): the canonical voice-vs-tone framing
- [GOV.UK Style Guide (A to Z)](https://www.gov.uk/guidance/style-guide/a-to-z-of-gov-uk-style): best-in-class plain-language reference
- [Shopify Polaris Voice and Tone](https://polaris-react.shopify.com/content/voice-and-tone): rationale-first writing
- [Buffer's style guide write-up](https://buffer.com/resources/style-guide/): small-team practical example
- [Voice and Tone Guides directory](https://voiceandtoneguides.webflow.io/): curated examples

### Frameworks
- [Nielsen Norman Group: Tone of Voice Dimensions](https://www.nngroup.com/articles/tone-of-voice-dimensions/): the four-dimension framework
- [Wikipedia: Signs of AI Writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing): the most thorough public list of AI tells

### AI-specific guidance
- ["Why Does ChatGPT Delve So Much?" (COLING 2025)](https://aclanthology.org/2025.coling-main.426.pdf): academic paper on AI vocabulary tells
- [Walter Writes: Most Common ChatGPT Words to Avoid](https://walterwrites.ai/most-common-chatgpt-words-to-avoid/)
- [Dotdigital: How to create a brand voice guide AI can actually use](https://dotdigital.com/blog/how-to-create-a-brand-voice-guide-that-ai-can-actually-use/): the compliance benchmarks

### Books worth reading
- *Nicely Said*: Nicole Fenton & Kate Kiefer Lee (the foundational text)
- *Strategic Writing for UX*: Torrey Podmajersky
- *Everybody Writes*: Ann Handley
- *On Writing Well*: William Zinsser

## Pair this with

- [CLAUDE.md](https://github.com/catrinmdonnelly/CLAUDE.md): context file Claude reads on every session
- [CONTEXT.md](https://github.com/catrinmdonnelly/CONTEXT.md): per-project context file
- [NORTH-STAR.md](https://github.com/catrinmdonnelly/NORTH-STAR.md): career-level direction
- [DESIGN.md](https://github.com/catrinmdonnelly/DESIGN.md): design system in a single markdown file

## License

MIT.

Made by Catrin Donnelly.
