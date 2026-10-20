# Similar

**Found something useful? Find out where else the idea could work.**

I made Similar for those moments when something works and you think, “What else could I do with this?” Give it a discovery or a topic, and it helps your AI find more opportunities worth exploring.

**[Download the skill](https://github.com/xyloshin/similar/releases/download/v0.1.0-beta.4/similar-release.zip)** · Free · One AI assistant · Beta 0.1.0-beta.4

## What it does

Say you find a service selling surplus food cheaply. Similar looks for other ways to get that benefit, then asks where the same idea works outside food. That might lead to furniture a shop needs to clear, or cheaper vehicle rentals when a company needs a car moved to another branch.

You get two groups of ideas:

- **More ways to get the same benefit.**
- **Places outside that area where the same idea could help.**

Each idea explains what you could gain, the main catch, and one practical next step, with sources where needed. It weighs the benefit against the effort, cost, and what you can realistically do. There’s no set number or split: stronger ideas get the space, and weak ones don’t get added just to fill a list.

It explores obvious options, less obvious approaches, and opportunities that depend on particular access or circumstances. If it can’t establish anything useful for one group, it says so.

## Try it

Once installed, ask:

```text
Use $similar on this: my library lends tools I was about to buy.
What other useful opportunities come from that idea?
```

You can start with a broad topic too, such as public libraries in Singapore. Or say “Use Similar on what we just found” when the discovery is already in your chat. Add anything that matters, like your location, budget, or how much time you have.

## Use without installing

Give your AI [SKILL.md](SKILL.md) and ask it to follow those instructions for your topic. You don’t need the `$similar` shortcut for this.

Similar is a set of instructions, not a separate app. It uses your current assistant and its available tools. Live search or browsing lets it check current offers, costs, and conditions. Without that access, it should tell you which ideas still need checking.

## Optional: install in Codex

1. [Download the ZIP](https://github.com/xyloshin/similar/releases/download/v0.1.0-beta.4/similar-release.zip) and extract it.
2. Put the `similar` folder in `~/.codex/skills`, or `$CODEX_HOME/skills` if you’ve configured that location. The file should end up at `skills/similar/SKILL.md`.
3. Use `$similar` followed by your discovery or topic.

Already have a skill called `similar`? Keep your existing copy and try this one in a separate environment.

## A note on this beta

I’ve included [two recorded examples](EXAMPLES.md), with their prompts, answers, and source checks. They show what the earlier beta produced, not guaranteed savings or proof that it beats an ordinary prompt.

The current package and file links have been checked. The latest instruction changes haven’t had a fresh research run or clean-install test, and use in other AI apps hasn’t been tested. The [evaluation notes](EVALUATION.md) explain what was checked and what still needs testing.

Similar finds ideas for you to consider. It doesn’t make purchases, contact people, or change accounts.

## Feedback

If you try it, I’d like to hear what it found and whether it was useful. [Open an issue](https://github.com/xyloshin/similar/issues) with your starting idea and what worked or fell short. Leave out private details.

Free to use and adapt under the [MIT License](LICENSE).
