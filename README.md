# VITA Framework

A four-step framework for hard customer conversations.
Built by Abhishek Singh Baghel, September–October 2026.

VITA stands for **Validate, Identify, Trade-off, Assurance**.

I built it while preparing for a customer support engineering interview.
I needed one structure I could recall under pressure.
It has to work for an angry client, an unreasonable request, and a "no".

It is not a universal tool.
It fits most customer-facing conversations. It does not fit troubleshooting. More on that below.

---

## The four steps

### V: Validate

Acknowledge the emotion or the request before anything else.

> "I understand this matters to you."

If the client is threatening to leave, say what is at stake:

> "I don't want to lose you, and I'll personally see this through."

### I: Identify

Find the real intent behind the request.
What outcome do they actually want?

For a complaint, find out what actually broke.
Is it a real bug, or a missed step?
Watching the client use the product live is usually the fastest way to tell.

Root cause lives here. It does not get its own step.

### T: Trade-off (or Treat)

T flexes depending on the situation.

- **For a request:** Trade-off. Give them a real choice instead of a flat no.
  Often the outcome is already possible and they are not using the feature. Show them on the call.
- **For a complaint:** Treat. If it's a missed step, fix it right there.
  If it's a real bug, note it and tell them you are investigating.

### A: Assurance

Close by routing it honestly, and commit to coming back.

> "I'll check with the people who can confirm this, and then I'll get back to you today with what I found."

Assurance is not "don't worry".
It always contains two parts: **verify first, then return.**

---

## Rules that come with it

These came from running VITA against practice scenarios. Each one fixes a mistake I kept making.

- **Promise the process, not the outcome.**
  "I'll personally investigate this and keep you updated until it's resolved" is a promise you can always keep.
  "Fixed within an hour" is not.
- **Say "investigate", not "debug".**
  Don't use words that commit you to work you don't do.
- **Keep "I'll update you" separate from "it's fixed".**
  The update keeps the client calm. Silence after "I'll get back to you" is what makes them angry.
- **No engineering team behind you? Draw the line out loud.**
  Own setup, integrations, data, logs and workarounds.
  Hand core code changes to whoever owns the codebase, with a full diagnosis attached.

---

## Worked example

**Scenario:** A client is furious and threatening to leave.

- **V:** "You're right to be frustrated. I don't want to lose you, and I'll personally see this through."
- **I:** "Can you walk me through exactly what happened? Was it the output, the software, or time wasted on our side?"
- **T:** If it's a usage issue, show the right way on the call. If it's real, log it with full evidence.
- **A:** "I'm taking this to the team as top priority. You'll hear from me within 24 hours with what we found, sooner if I can."

---

## Where VITA does not fit

Forcing it where it doesn't fit shows. Use something else for these:

| Situation | Use instead |
|---|---|
| Something technical broke and needs diagnosis | Reproduce → Isolate → Check logs/data → Fix or escalate → Follow up |
| A major incident hitting many customers | Assess impact → Communicate first → Fix or escalate → Postmortem |
| "Tell me about a time…" questions | STAR+L (Situation, Task, Action, Result, Learning) |

---

## Prior work

VITA is not the first framework for difficult customers. I'm not claiming it is.

The closest well-known one is HEARD (Hear, Empathize, Apologize, Resolve, Diagnose), taught by the Disney Institute.
V and I cover similar ground to Hear and Empathize.

What VITA does differently:

- It centres on a **trade-off**, not an apology. Saying no without losing the client is built in.
- It makes **honest routing** part of the close. You don't promise anything before verifying it.
- T flexes between Trade-off and Treat, so one structure covers both requests and complaints.

---

## Version history

- **v1.0 (October 2026):** First public version.
  Started as five steps (VITRA, with R for Route). Cut to four, with routing folded into Assurance.
  Four letters hold up better under pressure.

---

## How to cite

> VITA Framework by Abhishek Singh Baghel (2026). https://github.com/AbhishekbuildsAutomations/vita-framework. Licensed under CC BY 4.0.

## Licence

The text, structure and examples are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
You can share and adapt them for any purpose, including commercially.
You must credit me, link to the licence, and say if you changed anything. Full text is in [LICENSE](LICENSE).

The licence covers this written version. The underlying idea of a four-step method can't be owned by anyone.
