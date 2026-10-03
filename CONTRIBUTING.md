# Contributing

Thanks for taking the time to contribute. This list only stays useful if the entries stay current, accurate, and genuinely good — please read through before opening a pull request.

## What belongs here

This is organized by **outcome**, not by tool. An entry is a specific, concrete workflow — a downloadable Shortcut, Alfred workflow, Raycast extension, Keyboard Maestro macro, Hazel rule, or Finder Quick Action — that gets you from a starting point to a finished outcome (e.g. "a raw screenshot" → "a framed, uploaded, link-copied screenshot"). It is not a general app recommendation; apps belong on a list like [awesome-mac](https://github.com/jaywcjlove/awesome-mac) unless the app itself *is* the one-click solution to the outcome (see the `App` tag below).

## Before you submit

- **Search first.** Check the README and open pull requests to make sure the workflow isn't already listed.
- **It has to actually work.** Test the Shortcut, workflow, or macro yourself before submitting it. A broken download is worse than no entry.
- **macOS, outcome-first.** Scope it to a concrete outcome a Mac user actually has, not a generic tool feature.
- **One resource per pull request** makes review faster, unless you're adding several items to the same new outcome.

## Format

Add your entry under the outcome section it belongs to, in this exact format:

```markdown
- **Tag:** [Name](https://example.com) - A short, factual description that ends with a period.
```

`Tag` is one of: `Shortcut`, `Alfred`, `Raycast`, `Keyboard Maestro`, `Quick Action`, `Hazel`, or `App` (for a dedicated app that solves the outcome directly without a separate automation tool). If your resource needs a tag that doesn't fit, propose one in the PR description.

- Keep descriptions to one sentence, stating what the workflow actually does, not why it's great.
- Capitalize the first letter of the description; end with a period.
- Link to the actual workflow/macro page (RoutineHub, the Alfred Forum, the Keyboard Maestro forum, the Raycast Store, a GitHub repo, or similar) — not a review article or a download mirror.
- If no existing outcome fits, propose a new `## Outcome Name` section, phrased as a concrete outcome (e.g. "Back Up Photos Before Reformatting a Drive"), and add it to the [Contents](README.md#contents) table of contents.
- Every link in the README must be unique — if the resource you want to add is already linked elsewhere in the file, cross-reference that section by name instead of re-linking the same URL.

## Checklist

Before opening a pull request, confirm:

- [ ] You tested the workflow yourself and it works as described.
- [ ] The link goes to the actual workflow/macro page, not a review or mirror.
- [ ] The entry uses the `- **Tag:** [Name](url) - Description.` format with a valid tag.
- [ ] The entry is under the right outcome (or you've proposed a new one and added it to the table of contents).
- [ ] This exact URL isn't already linked anywhere else in the README.

## Removing an entry

If a workflow is broken, the gallery page has been taken down, or the resource no longer meets the bar above, open a pull request removing it and explain why in the description.

Thanks again for contributing!
