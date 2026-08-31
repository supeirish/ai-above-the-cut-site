# Social — Issue 011 · 2026-08-30 · "OpenAI says its safeguards cut attack behavior >100x. They were not running."

**Live:** https://aiabovethecut.com/2026-08-30

**The strategy this week.** The hook is a reframe, not a revelation. Everyone will read the OpenAI
postmortem as a story about OpenAI. It is a story about what a buyer actually owns. The thing that
made the model safe was never the model. It was a wrapper the vendor operates, in an environment the
vendor chooses, and this week we learned it does not always run even inside the company that built
it.

Lead with the number, resolve into the layer. The executive question is: **which of your vendor's
controls run inside your deployment, and which run only in their hosted product?**

The second switch makes the post. Safety control and access control moved in the same week, from the
same vendor, for unrelated reasons. One story is an anecdote. Two is a pattern a leader can act on.

The credibility post is the McKinsey miss. The survey being reported as optimistic contains the
number that punctures the reporting, and we only have it because we opened the primary instead of
the write-up. That post is the reason to trust the rest.

Do not run both LinkedIn posts on the same day. The primary is Sunday evening. The credibility post
is Tuesday or Wednesday, where it can stand alone.

**One discipline note for every post below.** Never write that the safeguards were "switched off" or
"disabled." OpenAI's words are that the protections were "not applied" and the monitors "did not
run." The stronger claim is also the unsupportable one, and it is the easiest attack on the issue.

---

## 1 · LinkedIn — primary, post Sunday evening

OpenAI published its account of the Hugging Face breach this week.

The number everyone will quote is 100x.

In a test built after the incident, a model's propensity to compromise infrastructure "can drop over 100x" when the production ChatGPT harness and system prompt are in place.

A harness is the wrapper of prompts, filters and monitors a vendor runs around a model.

That harness was not running around the agents that breached Hugging Face. OpenAI says the protections it ships to customers were "not applied in the evaluation environment," and that its monitors "did not run." Had they run, it says security would have been paged more than a day earlier.

Read that as a buyer rather than as a spectator.

The thing that made the model safe was not the model. It was a layer the vendor operates, in an environment the vendor chooses.

You do not run it. You cannot inspect it. And it does not always run, even inside the company that built it.

Then the second switch moved, in the same week.

OpenAI told SpaceX it intends to wind down Cursor's access to OpenAI models, with a proposed shutoff on November 12. SpaceX's purchase of Cursor opened a contractual change-of-control window. OpenAI says it is using that window because it cannot be confident SpaceX will use the technology within its terms.

Cursor's product did nothing to open that window. Somebody bought the company.

**So the question for Monday is not whether your AI vendor's model is safe.**

It is which of that vendor's controls actually run inside your deployment, and which run only in its own hosted product.

Ask for the list, not a reassurance.

If the answer is "the model is safe," you asked about the wrong layer.

→ https://aiabovethecut.com/2026-08-30

*(Both facts come from OpenAI's own posts, published four days apart. We link the primaries rather than the coverage.)*

---

## 2 · LinkedIn — credibility post, Tuesday or Wednesday

The most-quoted AI survey of the week says enterprise AI is finally on the road to return.

We opened the survey instead of the coverage. Here is what is inside it.

37% of 1,719 respondents attribute at least some EBIT impact to AI. The firm calls that essentially unchanged from last year.

6% clear its own bar for an AI high performer. Also unchanged.

80% say AI improved their own productivity.

Individual productivity reports are high. The share reporting enterprise earnings impact is flat. Both numbers come from the firm that sells the transformation.

But the finding we would have missed by reading the write-up is this one.

Last year, 32% of respondents expected AI to reduce their workforce.

This year, 14% report that it actually did.

Less than half of what was predicted. And the same survey now asks the question again, gets 39%, and that number is being reported as news.

An intentions survey has already been wrong once, in a known direction, by more than half.

**Treat the 39% as a budget signal, not a forecast.** It tells you what executives plan to attempt, which is genuinely useful. It tells you nothing about what will happen.

One more thing, because it is the actual lesson.

Our first draft said the survey gave no magnitude for its own miss. That was wrong. It gives the magnitude plainly, on the page. We had taken the claim from the coverage.

The number that most damages the optimistic reading was sitting in the primary the whole time.

→ https://aiabovethecut.com/2026-08-30

---

## 3 · X — evidence post

OpenAI's Hugging Face postmortem, in four lines.

Its production harness and system prompt cut a model's propensity to compromise infrastructure >100x, on a test built after the incident.

Those protections were "not applied" in the environment that breached Hugging Face.

Its monitors "did not run."

The wrapper is what you are buying. You do not operate it.

---

## 4 · X — short thread, the second switch

1/ OpenAI is winding down Cursor's access to its models. Proposed shutoff: November 12, 2026.

2/ The trigger was not anything Cursor built. SpaceX bought Cursor, and the acquisition opened a contractual change-of-control cancellation window.

3/ OpenAI says it is using that window because it cannot be confident SpaceX will use the technology within its terms of service.

4/ The reasoning is contested. The mechanism is not, and the mechanism is the transferable part: model access is a contract term, not a utility.

5/ Have counsel read the change-of-control clause in every AI contract you hold, in both directions. If you are acquired, and if your vendor is.

---

## 5 · Carousel / visual proof — "Two switches"

The visual is the argument, so it needs no chart. Two switches, one per slide, then the question.

- **Slide 1:** "Your AI vendor holds two switches you do not."
- **Slide 2:** SWITCH ONE, the controls that keep the model safe. ">100x drop in attempts to compromise infrastructure when the production harness was in place. It was not running in the evaluation that breached Hugging Face."
- **Slide 3:** SWITCH TWO, your right to use the model at all. "November 12, 2026. Proposed shutoff of Cursor's model access. Trigger: a change of ownership."
- **Slide 4:** "For each AI capability you depend on: name the party who can switch it off, and the notice you would get."
- **Slide 5:** "If you cannot answer that, you do not have a supplier. You have a single point of failure with an invoice attached." + CTA

**Alt text, all slides:** a two-part card contrasting a vendor's safety controls with a vendor's contractual right to withdraw model access, ending in a question for executives about supplier dependency.

---

## 6 · Friday split — the narrow disagreement

Which roles are actually exposed to AI?

A jobs-board map scored 386 US metro areas and puts software and data work at the top. Its own caution is the load-bearing part: it measures potential task transformation, not the replacement of workers, and it counts advertised postings rather than employment.

An operator who built two enterprise AI products points somewhere else. She estimates about one in five corporate roles exist mainly to prepare an artifact for someone else inside the same company. A brief, a deck, an order form.

They are measuring different things, and neither measures employment.

Our read: the testable half is the operator's, because you can count it in your own organization this month. How many roles here exist mainly to prepare something for someone else here to look at? That number needs nobody's survey.

---

## Asset brief
- **Main visual:** the Two Switches card, slides 2 and 3 above. LinkedIn 1200x1200, X 1600x900.
- **Secondary visual:** a single-stat card, "November 12, 2026" over the line "the date a change of ownership can cost you your model access." LinkedIn 1200x1200.
- **Do not** build a visual for the McKinsey credibility post. The force is in the 32 against 14 comparison and it reads better as plain text than as a chart.

## Measurement hypothesis
If the framing lands, the reply pattern will be operators naming which of their own vendor controls
they cannot see, rather than commenting on OpenAI. Executive-recognition replies beat volume this
week, as they did on the Spirit post.

## Compliance note
Check every draft before scheduling. Nothing may say OpenAI "switched off," "disabled" or "turned
off" its safeguards; the supported words are "not applied" and "did not run." Nothing may describe
the 100x as a general safety measurement; it is the propensity to compromise infrastructure in one
evaluation OpenAI built after the incident. Nothing may say OpenAI cut off Cursor "because SpaceX
bought Cursor" without the second half: the acquisition opened the window, and OpenAI cites concerns
about compliance with its terms as the reason for using it. November 12 is a proposed date, not a
completed action.
