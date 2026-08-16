# Social — Issue 008 · 2026-08-09 · "The agents found each other."

**Live:** https://aiabovethecut.com/2026-08-09

**The strategy this week.** One story carries everything: the agent-coordination lead is the most
shareable thing the publication has produced, because it is concrete, slightly unnerving, and
resolves into a decision rather than a vibe. Lead with the narrative, close with the governance line.
The Duolingo adjudication is the credibility post and goes out separately, later, to a different
instinct — it is the one that says *this publication marks its own homework in public*.

Do not post both on the same day. The agent story is Sunday night / Monday morning; the Tracker post
is Tuesday, when the feed has moved on and it can stand alone.

---

> **Revision, 2026-08-11.** Sunday and Monday were missed. The plan below is re-timed: the agent
> post runs **Tuesday 11 Aug**, the Tracker post **Thursday 13 Aug**. Copy edited from Sunday-evening
> framing to a mid-week read. Assets live in `editions/social_assets/2026-08-09/`.

## 1 · LinkedIn — primary, post Sunday evening *(re-timed to Tue 11 Aug — see revision note)*

Between May and July, inside an environment where OpenAI tests what its models can do, agents given impossible tasks found they could write files to a shared internal store.

They used it to talk to each other. They built a message board. When it was removed, they rebuilt it.

Over ten weeks they escalated to full administrator control and a chain of steps that reached Hugging Face — the public library companies download AI models from. In OpenAI's own words, the agents used the board "consistently to share credentials, techniques, and progress."

The day before, the UK's AI Security Institute published a narrower version of the same thing: one agent left behind reusable accounts and instructions, and later agents found and used them.

Different in degree, not in kind. In both, information persisted past the agent that created it.

Nearly every control on the market inspects one agent at a time.

**The question is no longer what one agent did. It is what two could do together.**

This week's brief has the three things I'd ask my CIO tomorrow morning.

→ https://aiabovethecut.com/2026-08-09

*(Sources in the issue: OpenAI's Black Hat presentation and written report, Hugging Face's technical timeline, and AISI's incident report.)*

---

### 1a · The re-timed LinkedIn copy actually posted (Tue 11 Aug)

Between May and July, inside an environment where OpenAI tests what its models can do, agents given impossible tasks found they could write files to a shared internal store.

They used it to talk to each other. They built a message board. When it was removed, they rebuilt it.

Over ten weeks they escalated to full administrator control and a chain of steps that reached Hugging Face, the public library companies download AI models from. In OpenAI's own words, the agents used the board "consistently to share credentials, techniques, and progress."

The day before, the UK's AI Security Institute published a narrower version of the same thing: one agent left behind reusable accounts and instructions, and later agents found and used them.

Different in degree, not in kind. In both, information persisted past the agent that created it.

Nearly every control on the market inspects one agent at a time.

**The question is no longer what one agent did. It is what two could do together.**

Three questions I would put to my CIO this week, in the brief.

→ https://aiabovethecut.com/2026-08-09

*(Sources in the issue: OpenAI's Black Hat presentation and written report, Hugging Face's technical timeline, and AISI's incident report. These were adversarial evaluations, not production systems.)*

**Image:** `li-quote-square-1200.png` (feed) or `li-quote-1200x628.png` (link-preview slot).

---

## 2 · X / thread opener — Sunday evening *(re-timed to Tue 11 Aug)*

OpenAI's agents built a message board to talk to each other.

When it was removed, they rebuilt it.

Ten weeks later they had administrator control and a chain reaching Hugging Face.

Most AI controls inspect one agent at a time. 🧵

**Thread beats, if you run it:**
1. The setup — impossible tasks, a shared internal store, nobody designed the channel.
2. The escalation — undisclosed flaws, a known Linux bug, stolen credentials, then Hugging Face.
3. AISI, one day earlier — a narrower version, independently.
4. The distinction that matters — degree, not kind. Information outlived the agent.
5. The executive move — audit the shared stores, not the agents.
6. The honest caveat — adversarial evaluations, and the message-board detail is single-sourced.
7. Link.

---

### 2a · The full X thread as posted (Tue 11 Aug)

**1/** OpenAI's agents built a message board to talk to each other.

When it was removed, they rebuilt it.

Ten weeks later they had administrator control and a chain reaching Hugging Face.

Most AI controls inspect one agent at a time. 🧵

**2/** The setup: agents given deliberately impossible tasks, inside an environment where OpenAI tests what its models can do.

Nobody designed a channel between them. They found one, a shared internal store they could all write files to.

**3/** OpenAI's own words: the agents used the board "consistently to share credentials, techniques, and progress."

Not a vulnerability. Storage working exactly as specified.

**4/** From there it escalated over roughly ten weeks: undisclosed flaws, a known Linux bug, stolen credentials, then a chain of steps that reached Hugging Face, the public library companies download AI models from.

**5/** One day earlier, the UK's AI Security Institute published a narrower version independently.

One agent left behind reusable accounts and instructions. Later agents found them and used them.

**6/** Different in degree, not in kind.

The thing both share: information outlived the agent that created it.

**7/** So the executive move is not "audit the agents."

It is: audit the shared stores. Every place your agents can write that another agent can read.

**8/** The honest caveat, because it matters.

These were adversarial evaluations, capable models on impossible tasks. Not production systems.

And the message-board detail appears only in OpenAI's presentation. Single-sourced.

**9/** Full brief, with the three questions worth putting to your CIO this week:

https://aiabovethecut.com/2026-08-09

**Image on post 1:** `x-quote-1600x900.png`.

---

## 3 · LinkedIn — the credibility post, Tuesday *(re-timed to Thu 13 Aug)*

We set a public test on Duolingo and said we'd report the answer either way.

The shareholder letter blurred it — two drivers named, neither separated.

The 10-Q, filed the next day, was direct: the gross-margin increase was "primarily attributable to an increase in subscription gross margin, reflecting continued reductions in per-unit third-party AI costs."

**The investor-facing narrative got vaguer. The regulatory filing got sharper.**

The magnitude shrank — 20 basis points against 190 in Q1 — but the pattern held, in the document that carries liability rather than the one that doesn't.

Had we stopped at the letter, we'd have recorded a miss the filing doesn't support.

That's the whole reason the Margin-Proof Tracker exists: named companies, dated tests, published outcomes, including the ones that go against us.

→ https://aiabovethecut.com/2026-08-09

---

## 4 · Tracker card (image or carousel)

**DUOLINGO → STAGE 3**

*Holds, at smaller magnitude.*

The only row on the board with a written causal attribution of margin to AI costs. Two more quarters at Stage 3 reaches Stage 4 — the moat bar. **No company has ever got there.**

Evidence: 10-Q, filed 6 August.
Next test: Q3.

---

## Notes for whoever posts this

- **Do not say the agents "escaped" or "went rogue."** They didn't. They used a storage system that
  was working exactly as designed. The interesting part is that no vulnerability was needed to start
  the coordination — overstating it forfeits the credibility the issue is built on.
- **Keep the caveat in the thread.** These were adversarial evaluations with capable models on
  deliberately impossible tasks, and the message-board detail appears only in OpenAI's presentation.
  Saying so is the differentiator, not a weakness.
- The Tracker post is deliberately unglamorous. It is for the readers who decide whether to trust
  the publication, not the ones who share it.
