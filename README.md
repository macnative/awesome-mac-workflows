# Awesome Mac Workflows [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> A curated list of native-first apps, automation tools, scripts, and resources for building a faster macOS workflow.

Most "best Mac apps" lists are just long, unsorted catalogs. This one is scoped to **workflows** — the launchers, automation tools, and small utilities that chain together into a daily system, with a bias toward apps that are genuinely native (AppKit/SwiftUI) over Electron wrappers, and toward tools that are either free, open source, or a one-time purchase where a good option exists.

If you ship or discover something that belongs here, this list only stays useful if people keep it current — see the Contributing section below.

## Contents

- [Window Management & Tiling](#window-management--tiling)
- [Launchers & Quick Actions](#launchers--quick-actions)
- [Automation & Scripting](#automation--scripting)
- [Clipboard Managers](#clipboard-managers)
- [Text Expansion & Snippets](#text-expansion--snippets)
- [Menu Bar Management](#menu-bar-management)
- [Screenshots & Screen Recording](#screenshots--screen-recording)
- [Terminal, Shell & Dev Environment](#terminal-shell--dev-environment)
- [File Management & Archiving](#file-management--archiving)
- [Notes & Knowledge Management](#notes--knowledge-management)
- [Calendar & Tasks](#calendar--tasks)
- [Focus & Time Tracking](#focus--time-tracking)
- [Shortcuts, Scripts & Learning Resources](#shortcuts-scripts--learning-resources)
- [Guides from MacNative](#guides-from-macnative)
- [Communities](#communities)
- [Related Awesome Lists](#related-awesome-lists)

## Window Management & Tiling

- [Rectangle](https://rectangleapp.com) - Free, open-source window snapping with keyboard shortcuts, inspired by Spectacle.
- [Moom](https://manytricks.com/moom/) - Window arranging and resizing with custom layouts, a grid overlay, and multi-monitor support.
- [yabai](https://github.com/koekeishiya/yabai) - Tiling window manager built on binary space partitioning, designed for scripting and keybinding.
- [Amethyst](https://github.com/ianyh/Amethyst) - Automatic tiling window manager for macOS modeled after xmonad.
- [AltTab](https://github.com/lwouis/alt-tab-macos) - Windows-style Alt-Tab window switcher with live thumbnails for every open window.
- [Contexts](https://contexts.co) - Window switcher that lists every open window grouped by app, searchable by title.

## Launchers & Quick Actions

- [Alfred](https://www.alfredapp.com) - The original macOS launcher; its Powerpack adds workflows, clipboard history, and custom actions.
- [Raycast](https://www.raycast.com) - Command launcher with a large extension store, AI commands, snippets, and window management.
- [Tinycast](https://tinycast.dev) - Free, open-source native launcher that runs Raycast extensions rendered as SwiftUI.
- [Vicinae](https://www.vicinae.com) - Native, extensible launcher with a TypeScript SDK, clipboard history, and window management.
- [SuperCmd](https://supercmd.sh/en) - Native Swift launcher combining AI agents, clipboard history, snippets, and window management.
- [LaunchBar](https://www.obdev.at/products/launchbar/) - Long-running keyboard-driven launcher built around an "instant send" action pipeline.

## Automation & Scripting

- [Shortcuts](https://support.apple.com/guide/shortcuts-mac/welcome/mac) - Apple's native automation app for building multi-step workflows across macOS and iOS.
- [Keyboard Maestro](https://www.keyboardmaestro.com) - Macro and automation tool for triggering actions from hotkeys, schedules, or app events.
- [Hammerspoon](https://www.hammerspoon.org) - Lua-scriptable bridge to macOS APIs for building custom automations and window layouts.
- [BetterTouchTool](https://folivora.ai) - Gesture, trackpad, keyboard, and window-snapping customization with a built-in scripting layer.
- [Hazel](https://www.noodlesoft.com/) - Rule-based file automation that watches folders and automatically sorts, renames, or tags files.
- [Automator](https://support.apple.com/guide/automator/welcome/mac) - Apple's drag-and-drop workflow builder for chaining actions and Quick Actions.

## Clipboard Managers

- [Maccy](https://maccy.app) - Lightweight, open-source, search-as-you-type clipboard manager that stays out of the way.
- [Paste](https://pasteapp.io) - Clipboard manager with iCloud sync, pinned items, and a visual history board.
- [Clipy](https://github.com/Clipy/Clipy) - Open-source clipboard history manager and snippet tool inspired by ClipMenu.

## Text Expansion & Snippets

- [Espanso](https://espanso.org) - Privacy-first, cross-platform text expander written in Rust, fully scriptable.
- [TextExpander](https://textexpander.com) - Mature snippet and expansion tool with shared team snippets and fill-in fields.

## Menu Bar Management

- [Bartender](https://www.macbartender.com) - The original menu bar organizer; hide, reorder, and trigger menu bar items on rules.
- [Ice](https://github.com/jordanbaird/Ice) - Free, open-source, GPL-licensed Bartender alternative with an Ice Bar for notched displays.
- [Stats](https://github.com/exelban/stats) - Open-source system monitor for the menu bar covering CPU, RAM, disk, network, and sensors.
- [iStat Menus](https://bjango.com/mac/istatmenus/) - Detailed system monitoring in the menu bar with historical graphs and sensor data.

## Screenshots & Screen Recording

- [CleanShot X](https://cleanshot.com) - Screenshot and screen recording tool with scrolling capture, annotation, and cloud sharing.
- [Shottr](https://shottr.cc) - Fast, free screenshot tool with scrolling capture, annotation, and OCR.
- [Kap](https://getkap.co) - Open-source screen recorder that exports directly to GIF, MP4, or WebM.
- [Gifski](https://gifski.app) - Open-source GIF encoder that converts video into small, high-quality GIFs.

## Terminal, Shell & Dev Environment

- [iTerm2](https://iterm2.com) - The long-standing power-user terminal replacement for macOS, with split panes and deep customization.
- [Warp](https://www.warp.dev) - GPU-accelerated terminal with AI command search and a block-based output model.
- [Ghostty](https://ghostty.org) - Fast, native, GPU-accelerated terminal emulator with minimal configuration.
- [Homebrew](https://brew.sh) - The missing package manager for macOS, used to install most of the tools on this list.
- [Oh My Zsh](https://ohmyz.sh) - Community-driven framework for managing zsh configuration, themes, and plugins.
- [Starship](https://starship.rs) - Fast, customizable, cross-shell prompt written in Rust.
- [OrbStack](https://orbstack.dev) - Fast, lightweight Docker and Linux VM replacement for Docker Desktop on macOS.

## File Management & Archiving

- [ForkLift](https://binarynights.com) - Dual-pane file manager with cloud storage and remote server connections.
- [Path Finder](https://cocoatech.com) - Finder replacement with dual panes, a module system, and deep file inspection tools.
- [Keka](https://www.keka.io/en/) - Free macOS file archiver supporting ZIP, 7z, and RAR extraction, including password-protected archives.
- [DaisyDisk](https://daisydiskapp.com) - Visual disk-space analyzer that maps what's filling up your drive.

## Notes & Knowledge Management

- [Obsidian](https://obsidian.md) - Local-first Markdown knowledge base with backlinks, graph view, and a large plugin ecosystem.
- [Bear](https://bear.app) - Native Markdown note-taking app with tags, cross-note linking, and fast search.
- [Craft](https://www.craft.do) - Structured, block-based notes app with real-time collaboration and a native Mac feel.
- [Logseq](https://logseq.com) - Open-source, local-first outliner for networked notes and daily journaling.

## Calendar & Tasks

- [Fantastical](https://flexibits.com/fantastical) - Natural-language calendar app with a compact menu-bar view and task integration.
- [BusyCal](https://www.busymac.com) - Calendar app with natural-language input, smart filters, and unified account support.
- [Things 3](https://culturedcode.com/things/) - Native task manager built around Areas, Projects, and a daily Today view.
- [OmniFocus](https://www.omnifocus.com) - Deep GTD-style task manager with custom perspectives and forecasting.

## Focus & Time Tracking

- [Focus](https://heyfocus.com) - Blocks distracting apps and websites during scheduled or on-demand focus sessions.
- [Session](https://www.stayinsession.com) - Pomodoro-style focus timer with distraction blocking and session analytics.
- [one sec](https://one-sec.app) - Adds a mindful pause before opening distracting apps, across Mac, iOS, and the browser.

## Shortcuts, Scripts & Learning Resources

- [RoutineHub](https://routinehub.co) - The largest community library for discovering and sharing Apple Shortcuts.
- [MacStories Shortcuts Archive](https://www.macstories.net/shortcuts/) - 300+ curated, tested Shortcuts maintained by the MacStories team.
- [Automators Talk](https://talk.automators.fm) - Forum and podcast community dedicated to Shortcuts and macOS/iOS automation.

## Guides from MacNative

Deep dives and comparisons from MacNative, a hand-picked directory of native macOS apps, that pair directly with the tools above.

- [Raycast vs Tinycast vs Vicinae vs SuperCMD](https://macnative.io/blog/raycast-vs-tinycast-vs-vicinae-vs-supercmd) - A head-to-head comparison of the native Raycast alternatives listed above.
- [Best Mac Clipboard Managers Without a Subscription](https://macnative.io/blog/mac-clipboard-managers-no-subscription) - One-time-purchase and free clipboard managers compared, including Maccy and Paste.
- [Best Menu Bar Apps for Mac](https://macnative.io/blog/best-menu-bar-apps-for-mac) - A roundup of menu bar utilities worth keeping installed.
- [Best Note-Taking Apps for Mac in 2026](https://macnative.io/blog/best-note-taking-apps-for-mac) - A current comparison of native note-taking apps for Mac.
- [Scrolling Screenshot on Mac: Free Full-Page Capture](https://macnative.io/blog/how-to-take-a-scrolling-screenshot-on-mac) - How to capture full-page, scrolling screenshots without paid tools.
- [How We Pick Apps for MacNative](https://macnative.io/blog/how-we-pick-apps) - The editorial bar MacNative uses to decide which Mac apps make the cut.

Browse the full [MacNative directory](https://macnative.io) for more hand-picked, native-first macOS apps, organized by [category](https://macnative.io/categories).

## Communities

- [r/macapps](https://www.reddit.com/r/macapps/) - Subreddit for discovering and discussing macOS apps.
- [r/macOS](https://www.reddit.com/r/MacOS/) - General subreddit for macOS news, tips, and troubleshooting.
- [r/shortcuts](https://www.reddit.com/r/shortcuts/) - Subreddit dedicated to Apple Shortcuts automations.
- [MacRumors Forums](https://forums.macrumors.com) - Long-running community forum for Mac hardware, software, and workflow discussions.

## Related Awesome Lists

- [awesome-mac](https://github.com/jaywcjlove/awesome-mac) - A much broader, general-purpose list of macOS apps and tools.
- [awesome-macos-command-line](https://github.com/herrbischoff/awesome-macos-command-line) - Curated list of command-line tools and tricks specific to macOS.
- [awesome-mac-launch-platforms](https://github.com/macnative/awesome-mac-launch-platforms) - Where to launch and promote a macOS app: directories, subreddits, and newsletters.

## Contributing

Contributions are very welcome — this list is only as good as the people maintaining it. Before opening a pull request, please read the contribution guidelines in `CONTRIBUTING.md` (see the badge at the top of this file).

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors to this list have waived all copyright and related or neighboring rights to this work.
