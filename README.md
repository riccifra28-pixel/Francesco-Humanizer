# Francesco-Humanizer

> **AI can make you faster. It shouldn't make you sound like AI.**

Francesco-Humanizer is an experimental Agent Skill designed to rewrite AI-generated text while preserving the author's own voice, personality and intent.

It is designed to be used by AI agents that support skill-based instructions and can be adapted to different writing contexts and individual authors.
The project was created to explore a simple question:

**Can AI help us communicate faster without making everyone sound the same?**

## What it does

Francesco-Humanizer follows a four-step process:

**1. Detect**

Identifies common patterns associated with AI-generated writing, such as repetitive structures, generic corporate language, excessive transitions and predictable phrasing.

**2. Understand the writer**

When real examples of the author's writing are available, the skill analyzes vocabulary, sentence rhythm, punctuation, tone and recurring expressions to build an internal voice profile.

**3. Rewrite**

The text is rewritten to sound natural and personal while preserving its original meaning, facts and intent.

**4. Self-check**

The result is reviewed again for remaining AI-like patterns, unnecessary wording and loss of the author's voice.

## What makes it different

This is not a simple "make this text sound human" prompt.

The goal is to make AI adapt to the **writer**, rather than making the writer adapt to AI.

The skill therefore prioritizes:

- Personal voice over generic "human" writing
- Meaning over stylistic changes
- Natural rhythm over artificial imperfections
- Specific language over corporate clichés
- Authenticity over optimization

## Use cases

The skill can be particularly useful for:

- LinkedIn posts
- Job applications
- Cover letters
- Professional emails
- Personal branding
- Sports marketing communication
- Presentations and project proposals

## Testing

The skill has been manually evaluated across seven test cases covering:

- AI-pattern reduction
- Voice matching
- Factual accuracy
- Minimal intervention
- Corporate language and personal voice
- Sports marketing communication
- Integrated rewriting

The current manual evaluation averages **9.3/10**.

See [TEST.md](TEST.md) for the full test cases, outputs and evaluations.
## Why I built it

AI is becoming an increasingly powerful tool for research, analysis and content creation.

But there is a potential downside: if everyone uses the same tools in the same way, everyone can start to sound the same.

I wanted to experiment with the opposite approach:

**Use AI to accelerate the work, while keeping the human voice behind it.**

## Workflow

```text
AI-generated text
       ↓
AI pattern detection
       ↓
Author voice analysis
       ↓
Context-aware rewrite
       ↓
Final AI-pattern check
       ↓
Human-sounding output

## Project status

**Current version: v1.0**

Francesco-Humanizer is currently an experimental personal project focused on voice-preserving AI rewriting.

The current version prioritizes:
- reliable AI-pattern detection
- author-specific voice matching
- preservation of meaning and facts
- context-aware rewriting
- minimal intervention when appropriate
