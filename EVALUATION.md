# Does Similar help?

No superiority claim is established by this package. The recorded examples demonstrate
the design; they do not prove that the skill beats a simpler prompt.

## v0.1.0-beta.4 update, 20 October 2026

This revision incorporates the maintained personal skill's requirements for research
outside the original domain, two output groups, all three research approaches at each
level, preservation of distinct findings when simplifying, and clearer explanation
and completion checks. The public version accepts broad-topic input and uses the
current assistant and its available tools throughout.

The instructions and package were checked for consistency. The recorded runs below
predate this revision and were not rerun for beta.4. They are not behavioral validation
of the new requirements. Clean installation and cross-assistant behavior remain untested.

Useful next behavioral checks:

- Start from an investing discovery and check that the second group contains supported
  opportunities outside investing, or explicitly reports that none were established.
- Ask to simplify a response and check that every distinct finding remains unless a
  shortlist was requested or a withdrawal is explicitly explained.
- Start from a broad topic and check that both research levels and all three approaches
  inform the work without requiring an anecdote.

## Checks recorded for v0.1 beta

The public package includes two selected test cases recorded on 6 October 2026.
A fresh Codex agent applied the skill, and the maintainer reviewed the actual
outputs against the supplied requests:

- A broad topic after unrelated conversation: answered black-hat marketing generally,
  without redirecting to the earlier GitHub project or requiring a starting anecdote.
- No topic or discovery: asked one short question instead of inventing a task.

See [inputs, complete responses, and limitations for these two cases](evaluation/input-checks.md).
These checks had no live research. They establish observed behavior in those runs,
not consistent performance across models. Some responses remain longer than others.
The [recorded research demonstrations](EXAMPLES.md) separately exercise live sources:

- A broad library topic produced several specific services and a shared-access
  connection beyond libraries, with membership and access conditions distinguished.
- A surplus-food discovery extended into furniture, theatre seats and vehicle
  relocation, with geographic availability and material costs attached to each idea.

Each demonstration used a fresh Codex research agent. The reviewer spot-checked
selected decisive claims against official sources, including equipment access,
reservation and return rules, ticket fees, and vehicle-relocation conditions. The
complete responses are preserved in the linked records. These were selected cases,
not a blinded benchmark or evidence of real customer outcomes.

Fresh native installation across agent apps and baseline comparisons remain untested.

## A fair comparison

Choose several real discoveries from different domains. Include a case with scarce
evidence, a mistaken premise, and one where the user lacks an important qualification.
Keep private details out of shared results.

For each case, use fresh chats with the same model, tools, source material, context,
and approximate research budget. Use one assistant in both conditions. Compare:

**Simple prompt**

```text
Here is my discovery and context: [insert the complete case].
Find similar opportunities I can actually use. Give important conditions,
supporting evidence where needed, and concrete next steps.
```

**Skill prompt**

```text
Use Similar with this discovery and context: [insert the same complete case].
```

Make SKILL.md available only in the skill condition. Preserve both complete outputs
and the research sources. Repeat some cases to account for variation.

## Judge usefulness, not length

Hide which condition produced each answer when practical. Ask a reviewer to check:

- Did it find a useful, distinct opportunity beyond the obvious variations?
- Is the connection to the starting discovery defensible?
- Are important factual claims supported, with uncertainty and eligibility clear?
- Does the next step fit the user's actual constraints?
- Can someone new to the topic explain the idea and first step after one reading?
- How much user effort, research time, or tool cost did it require?

Record fabricated or inapplicable claims explicitly. Count duplicate suggestions as
one. Do not reward a long list that creates more work for the user.

Publish wins, ties, and losses with the model/version, date, prompts, tools, and case
selection method. Report what happened in the tested cases; do not generalize a few
good examples into a claim that the skill always performs better.
