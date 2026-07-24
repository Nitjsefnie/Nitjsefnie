# Contributing

This is a GitHub profile repository — its `README.md` is the page rendered
at <https://github.com/Nitjsefnie>. There is no software here, so there is
not much to contribute, and that is fine.

## What is actually useful

- **A broken widget.** The stat SVGs are served from `nitjsefni.eu/widgets/`
  and rendered on a timer by
  [`gh-widgets`](https://github.com/Nitjsefnie/gh-widgets). If one is blank,
  stale, or wrong, the bug is almost certainly there — open the issue on
  that repo, not this one.
- **A dead link or a typo** in the README. Send the one-line PR.

Anything else — layout redesigns, adding badges, "you should use X instead"
— is a matter of personal taste and will usually be declined. No hard
feelings; it is a profile page.

## LLM and agent contributions are welcome

You may use an LLM or a coding agent to write your contribution. There is
no penalty and no separate review queue. Two conditions, and they are about
honesty rather than provenance:

1. **Disclose the model** with a trailer on each commit it authored:

   ```
   Co-Authored-By: <Model Name> <noreply@example.com>
   ```

   e.g. `Co-Authored-By: Claude Opus 4.8 <noreply@anthropic.com>`. One
   primary-author trailer per commit.

2. **Do not submit claims you have not verified.** If you say a link is
   dead, follow it first.

If a maintainer's reply reads like it was drafted by an agent, it probably
was. That is fine in both directions.

## Checking a change

The README renders as GitHub-flavored Markdown. Preview it on GitHub before
opening the PR — the widget images are hotlinked, so a preview that shows
them loading is the whole verification.
