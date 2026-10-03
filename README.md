# Awesome Mac Workflows [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> A cookbook of real macOS workflows — Shortcuts, Alfred workflows, Raycast extensions, Keyboard Maestro macros, and Finder Quick Actions — organized by the outcome they get you, not the app that runs them.

Most Mac automation lists are organized by tool: here's every Alfred workflow, here's every Shortcut. That's useful for browsing, but useless when you actually have a problem — "I need to get these invoices out of my Downloads folder" doesn't care which app solves it. So this list is organized the other way: by outcome first, tool second. Each entry is tagged with what it needs to run.

- **Shortcut** — built with Apple's Shortcuts app (macOS and iOS)
- **Alfred** — a workflow for Alfred (needs the Powerpack)
- **Raycast** — an extension from the Raycast Store
- **Keyboard Maestro** — a macro for Keyboard Maestro
- **Quick Action** — a Finder right-click action, via Automator or Shortcuts
- **Hazel** — a rule for Hazel's folder-watching automation
- **App** — a small dedicated app that solves the outcome directly, no automation tool required

Don't have one of these tools yet? [Shortcuts](https://support.apple.com/guide/shortcuts-mac/welcome/mac) ships free on every Mac, [Alfred](https://www.alfredapp.com), [Raycast](https://www.raycast.com), [Keyboard Maestro](https://www.keyboardmaestro.com), and [Hazel](https://www.noodlesoft.com/) are all one download away.

## Contents

- [Start My Work Session](#start-my-work-session)
- [Shut Down & End the Day](#shut-down--end-the-day)
- [Prepare Screenshots for Publishing](#prepare-screenshots-for-publishing)
- [Organize Downloaded Invoices & Receipts](#organize-downloaded-invoices--receipts)
- [Tame the Downloads Folder](#tame-the-downloads-folder)
- [Resize & Compress Images for the Web](#resize--compress-images-for-the-web)
- [Clean Up Clipboard Text Before Pasting](#clean-up-clipboard-text-before-pasting)
- [Capture a Quick Note or Idea](#capture-a-quick-note-or-idea)
- [Jump Into a Dev Project](#jump-into-a-dev-project)
- [Join a Meeting Fast](#join-a-meeting-fast)
- [Plan & Review the Day](#plan--review-the-day)
- [More Workflow Galleries](#more-workflow-galleries)
- [Guides from MacNative](#guides-from-macnative)
- [Communities](#communities)
- [Related Awesome Lists](#related-awesome-lists)

## Start My Work Session

Open the right apps, silence the wrong notifications, and get to the first task without ten minutes of clicking around.

- **Keyboard Maestro:** [Launch apps and windows at login or wake](https://forum.keyboardmaestro.com/t/how-to-customise-how-my-apps-and-windows-launch-on-start-up/31579) - Community macro recipes for opening a fixed set of apps, arranged into saved window positions, the moment you sit down each day.
- **Shortcut:** [Set up a Focus on Mac](https://support.apple.com/guide/mac-help/set-up-a-focus-to-stay-on-task-mchl613dc43f/mac) - Apple's guide to building a Work Focus that Shortcuts' built-in "Set Focus" action can switch on as the first step of a start-of-day shortcut.

## Shut Down & End the Day

Close out cleanly so tomorrow starts from zero open windows, not forty.

- **Alfred:** [Quit Application Workflow](https://www.alfredforum.com/topic/7954-quit-application-workflow/) - Community workflow that quits every open app, or all but a chosen few, in one keystroke.

Pair it with the automatic Trash and Downloads cleanup in the "Tame the Downloads Folder" section below for a Mac that resets itself overnight.

## Prepare Screenshots for Publishing

Go from a raw screenshot to something you'd actually put in a blog post, changelog, or App Store listing.

- **Shortcut:** [Frame Screenshots](https://routinehub.co/shortcut/7923/) - Drops a real device frame around an iPhone or iPad screenshot from a library of nearly 300 frames, no image editor required.
- **Shortcut:** [Upload to Imgur](https://routinehub.co/shortcut/1052/) - Uploads an image straight from the share sheet or Shortcuts and copies the hosted link, ready to paste into a post or issue.

## Organize Downloaded Invoices & Receipts

Stop invoices from piling up in Downloads — get them renamed and filed the moment they land.

- **Shortcut:** [Send Expense Receipt as PDF via Email](https://routinehub.co/shortcut/15587/) - Renames a receipt to `Expense-{occasion}-{date}-{location}.pdf`, files it in a dated folder, and emails it on, all from one run.
- **Hazel:** [Rename a file based on its content](https://www.noodlesoft.com/forums/viewtopic.php?f=4&t=6844) - Forum recipe for having Hazel read the vendor name and invoice date out of a PDF and rename the file to match, without opening it.
- **Hazel:** [Automatic invoice renaming with OCR](https://www.noodlesoft.com/forums/viewtopic.php?f=3&t=16084) - A more advanced version of the same idea that adds OCR text extraction, for scanned invoices that don't have selectable text.
- **Shortcut:** [Get started with folder automation in macOS Tahoe](https://sixcolors.com/post/2025/08/get-started-with-folder-automation-in-macos-tahoe/) - How to trigger a Shortcut the moment a file is added to a folder, which is the Shortcuts-only alternative to Hazel for this exact outcome.

## Tame the Downloads Folder

The folder everything lands in first, and nothing ever leaves on its own.

- **Hazel:** [Use Automatic Deletion](https://www.noodlesoft.com/manual/hazel/hazel-basics/manage-your-trash/use-automatic-deletion/) - Official recipe for having Hazel sweep Downloads older than a set number of days straight to the Trash, and empty the Trash on its own schedule.

## Resize & Compress Images for the Web

Images that load fast and don't eat your CMS's storage quota, without opening Photoshop.

- **Quick Action:** [ImageOptim](https://imageoptim.com) - Installs a Finder service so you can right-click any image (or a whole folder of them) and compress it in place, no app window needed.
- **Quick Action:** [Compressing images and PDFs from the Finder context menu](https://danielsaidi.com/blog/2026/09/15/using-automator-workflows-to-compress-images-and-pdfs) - Walkthrough for building your own Automator Quick Action that batch-compresses a Finder selection on right-click.
- **Shortcut:** [About transform actions in Shortcuts on Mac](https://support.apple.com/guide/shortcuts-mac/apd1d9413cfb/mac) - Apple's reference for the built-in Resize Image and Convert Image actions, enough to build a drag-and-drop "shrink for web" shortcut in a few minutes.

## Clean Up Clipboard Text Before Pasting

Paste a quote from a PDF or a webpage and get plain text out, not three inherited fonts.

- **Keyboard Maestro:** [Paste as Plain Text](https://forum.keyboardmaestro.com/t/paste-as-plain-text-in-microsoft-word-and-excel/34162) - A macro mapped to its own hotkey that strips formatting from whatever is on the clipboard before pasting, including into apps that resist it like Word and Excel.

Alfred, Raycast, and most clipboard managers also ship a built-in "paste as plain text" hotkey — check your tool's preferences before building a custom one.

## Capture a Quick Note or Idea

Get a thought out of your head and into a system before it's gone, from wherever you are.

- **Alfred:** [Obsidian Quickly](https://www.alfredforum.com/topic/23015-obsidian-quickly/) - Adds a new note to a chosen folder, appends to an "incoming tasks" note, or logs straight to today's daily note in Obsidian.
- **Alfred:** [QuickNote](https://rknight.me/blog/quicknote-alfred-workflow/) - Type a keyword and your text, hit enter, and it's appended to a running scratch note — nothing to open, nothing to file later.

## Jump Into a Dev Project

Get from "I need to fix that bug" to an open editor, a running terminal, and the right branch in one keystroke.

- **Alfred:** [alfred-pj](https://github.com/igrybkov/alfred-pj) - Detects a project's type and opens it in the matching editor, with modifier keys to send it to the terminal, Finder, or the repo's page instead.
- **Raycast:** [Visual Studio Code — Recent Projects](https://www.raycast.com/thomas/visual-studio-code) - Jump straight to any recently opened VS Code workspace, or run editor commands, without switching to VS Code first.
- **Alfred:** [alfred-iterm-workflow](https://github.com/caiogondim/alfred-iterm-workflow) - Opens a new iTerm2 tab, window, or pane in a chosen directory straight from Alfred's search bar.

## Join a Meeting Fast

No hunting through a calendar app for a link thirty seconds before a call starts.

- **Raycast:** [Zoom](https://www.raycast.com/raycast/zoom) - Start an instant meeting, join one by ID, or jump into the next meeting on your calendar, all without opening Zoom.
- **App:** [MeetingBar](https://github.com/leits/MeetingBar) - Free, open-source menu bar app that shows your current or next meeting at all times and joins it with one click or a global hotkey.

## Plan & Review the Day

A fixed five minutes at the start or end of the day instead of task management by vibes.

- **Raycast:** [Things](https://www.raycast.com/loris/things) - Search, review, and quick-add Things 3 to-dos from Raycast, so a daily review doesn't require switching apps.

## More Workflow Galleries

Didn't find what you need above? These are the libraries where the entries on this page come from — browse them directly.

- [RoutineHub](https://routinehub.co) - The largest community library for discovering and sharing Apple Shortcuts.
- [MacStories Shortcuts Archive](https://www.macstories.net/shortcuts/) - 300+ curated, tested Shortcuts maintained by the MacStories team.
- [Automators Talk](https://talk.automators.fm) - Forum and podcast community dedicated to Shortcuts and macOS/iOS automation.

## Guides from MacNative

Deep dives and comparisons from MacNative, a hand-picked directory of native macOS apps, that pair directly with the workflows above.

- [Raycast vs Tinycast vs Vicinae vs SuperCMD](https://macnative.io/blog/raycast-vs-tinycast-vs-vicinae-vs-supercmd) - A head-to-head comparison of native Raycast alternatives, useful before committing to a launcher for the workflows above.
- [Best Mac Clipboard Managers Without a Subscription](https://macnative.io/blog/mac-clipboard-managers-no-subscription) - One-time-purchase and free clipboard managers compared.
- [Best Menu Bar Apps for Mac](https://macnative.io/blog/best-menu-bar-apps-for-mac) - A roundup of menu bar utilities worth keeping installed alongside MeetingBar.
- [Best Note-Taking Apps for Mac in 2026](https://macnative.io/blog/best-note-taking-apps-for-mac) - A current comparison of native note-taking apps for quick-capture workflows.
- [Scrolling Screenshot on Mac: Free Full-Page Capture](https://macnative.io/blog/how-to-take-a-scrolling-screenshot-on-mac) - How to capture full-page, scrolling screenshots before framing and uploading them.
- [How We Pick Apps for MacNative](https://macnative.io/blog/how-we-pick-apps) - The editorial bar MacNative uses to decide which Mac apps make the cut.

Browse the full [MacNative directory](https://macnative.io) for more hand-picked, native-first macOS apps, organized by [category](https://macnative.io/categories).

## Communities

- [r/macapps](https://www.reddit.com/r/macapps/) - Subreddit for discovering and discussing macOS apps.
- [r/macOS](https://www.reddit.com/r/MacOS/) - General subreddit for macOS news, tips, and troubleshooting.
- [r/shortcuts](https://www.reddit.com/r/shortcuts/) - Subreddit dedicated to Apple Shortcuts automations.
- [MacRumors Forums](https://forums.macrumors.com) - Long-running community forum for Mac hardware, software, and workflow discussions.

## Related Awesome Lists

- [awesome-raycast](https://github.com/j3lte/awesome-raycast) - Auto-generated, always-current list of every extension in the Raycast Store.
- [awesome-alfred-workflows](https://github.com/derimagia/awesome-alfred-workflows) - A broader curated list of Alfred workflows across every category, not just outcome-based ones.
- [awesome-mac](https://github.com/jaywcjlove/awesome-mac) - A much broader, general-purpose list of macOS apps and tools.
- [awesome-macos-command-line](https://github.com/herrbischoff/awesome-macos-command-line) - Curated list of command-line tools and tricks specific to macOS.
- [awesome-mac-launch-platforms](https://github.com/macnative/awesome-mac-launch-platforms) - Where to launch and promote a macOS app: directories, subreddits, and newsletters.

## Contributing

Contributions are very welcome — this list is only as good as the people maintaining it. Before opening a pull request, please read the contribution guidelines in `CONTRIBUTING.md` (see the badge at the top of this file).

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors to this list have waived all copyright and related or neighboring rights to this work.
