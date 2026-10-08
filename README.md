# Similar

**Turn one useful discovery into more opportunities you can actually use.**

Version 0.1 beta.

Found something that worked? Similar explores other ways to get the same benefit,
then looks for places where the underlying principle could work too. It checks the
conditions and gives you concrete next steps.

For example: surplus-food deals reward flexible collection. Similar followed that
idea to discounted vehicle rentals where the driver helps a rental company move a
vehicle between branches. See the [recorded demonstration](examples/surplus-opportunities.md)
for the connection, availability and costs to check.

## Try it

```text
Use $similar on this discovery: our library provides a tool I was about to buy.
Find other ways to meet that need and useful applications of the same principle.
```

Give your assistant a discovery or a broad topic, plus any important constraints.
For example, "Use $similar on public libraries in Singapore" starts an exploration
without requiring a story about something you have already tried. You can also say
"Use Similar on what we just found" when the context is already in the chat.

The result is a few useful ideas explained in plain language, each covering:

- What you could gain.
- When it applies, including important costs or conditions.
- One next step and supporting sources where needed.

Expect compact cards: a clear title, a short explanation, an example where useful,
and a first step. Important catches sit with the relevant idea. You don't need to
understand the skill's research framework or specialist vocabulary.

See [two recorded research demonstrations](EXAMPLES.md), with actual prompts, outputs,
and source checks. They demonstrate the method, not customer outcomes or a measured
advantage over an ordinary prompt.

## Install in Codex

Download this repository's files into a folder named `similar`. Place that folder
in your personal skills directory: `$CODEX_HOME/skills` when configured, otherwise
`~/.codex/skills`. The resulting file should be `skills/similar/SKILL.md`.

If a skill named `similar` already exists, keep your existing copy and try this
package in a separate environment. Do not overwrite it just to try the release.

Invoke it with `$similar` followed by your discovery or topic. The instructions are also
readable as a standalone file: give [SKILL.md](SKILL.md) to another assistant and
ask it to follow the method. Native installation and invocation depend on that
assistant's skill support; cross-platform compatibility has not been tested here.

## What it needs

One assistant. No required API key, second AI subscription, scripts, or plugins.
Live research tools help verify current policies, offers, and other changing facts.
Without them, the assistant should identify leads and clearly say what is unverified.

Optional **thorough mode** asks for an independent second researcher if your
environment provides one and its use is authorized. It compares findings and checks
decisive claims. If no second researcher is available, Similar still works with one
assistant and discloses the limitation.

## Why use a skill for this?

"Find similar opportunities" can be a useful prompt on its own. Similar makes the
intended search explicit: same benefit, different mechanism; then same mechanism,
different context. It also asks for evidence, qualifying conditions, and useful next
steps instead of a list of loosely related ideas.

That is a design intention, not a proven performance advantage. Use the
[comparison guide](EVALUATION.md) to test whether it improves your actual results.

## Scope

Use it for discoveries in work, learning, everyday services, creative projects, or
other domains. It is not a product lookalike search or a guarantee of savings,
eligibility, or profit. It proposes opportunities; acting on them remains a separate
request.

## Feedback and license

Useful feedback includes the starting discovery, relevant constraints, what the
skill found, and what turned out to be useful or wrong. Remove private details before
sharing examples.

Released under the [MIT License](LICENSE).
