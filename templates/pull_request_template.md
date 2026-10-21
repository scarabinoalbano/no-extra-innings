<!--
No Extra Innings pull request template.
Copy this file into the .github/ folder of your repository.
The Starter fills in "Kickoff brief" and "Starter's note" before the handoff,
the Closer or quick reviewer fills in "Closer's summary", and both go through
the "Walkthrough" checklist before the merge.
-->

# Handoff: [story ID and title]

**Risk level:** Low / Medium / High

## Kickoff brief

[link to docs/briefs/STORY-ID.md]

## Starter's note

**Decisions made:**

- [decision and why]

**Open questions:**

- [question, or "None"]

**AI review findings not fixed, and why:**

- None

### Ready for refinement

- [ ] Tests written from the acceptance criteria before the code
- [ ] Acceptance tests pass
- [ ] CI green
- [ ] AI review run against the kickoff brief; every finding fixed or explained
- [ ] Note with decisions and open questions

## Closer's summary

On low-risk stories, the quick reviewer fills this in.

**What changed and why:**

- [change and reason]

**Behavior changes (agreed with the Starter and covered by a test):**

- None

**Checks:**

- [ ] Test plan and tests reviewed
- [ ] Within the time box (30 minutes for a quick review, 2 hours for medium risk, half a day for high), or the overrun noted for the retrospective
- [ ] AI review in CI passed
- [ ] Cross-team review approved, if the kickoff brief requires it; any requested changes applied by the Closer

## Walkthrough

Low-risk story or small change? The Starter can review the diff and the tests instead of meeting.

- [ ] The Closer walked through the main changes and why
- [ ] The Starter reviewed every change the Closer or quick reviewer made
- [ ] Acceptance tests pass; none changed without agreement
- [ ] Any behavior change is agreed and covered by a test
- [ ] Open questions from the Starter's note are resolved or ticketed
- [ ] Exploratory testing done, if the kickoff brief marks the story as risky
- [ ] The Starter can explain the final code
- [ ] Anything the Closer fixed more than once is added to the agent's instructions

Ready to merge. The Starter merges.
