---
title: 📄 HackMD opportunities
tags: hackmd
description: HackMD opportunies
image: https://pbs.twimg.com/profile_banners/3540691454/1535710532/1500x500
---

Opportunities
===

## Security

- [ Native sign-in with multi-factor authentication (MFA) #319 ](https://github.com/hackmdio/hackmd-io-issues/issues/319) (P0)
    - Currently MFA is through third-parties, e.g. Twitter, GitHub, and etc.
- Backup notes based on folder architecture (P1)
    - Organize notes into folders in the app. 
    - *Settings* > *Download all notes* downloads the notes into local directories that match the app folder architecture.
    - This will make backing up a large amount of notes  user-friendly.

## Editor

### Web app

- More shortcut/hotkey commands to handle Markdown generation (P1)
- What you see is what you get (WYSIWYG) editor for Markdown (P1)
    - Great for beginner users to get started writing
- Spelling and grammar check
    - [LanguageTool](https://languagetool.org/) compatibility (Open-source) (P1)
    - Add new words to the spell checker dictionary (P1)
- Word and character counters (P2)
    - Show the counts for highlighted text.
- Table builder UI in the toolbar (P2)
    - Disable interchanging row background colors
        - A.k.a. zebra striping
        - *See [Disable zebra striping in Github table markdown](https://stackoverflow.com/questions/50302165/disable-zebra-striping-in-github-table-markdown) on stackoverflow.com*
    - Add lists within a cell
        - Based on HTML elements
        - *See [tablesgenerator.com](https://www.tablesgenerator.com/html_tables)*
- Offline web editor and/or desktop app (P2)
- Import multiple .md files from local storage (P2)

### Visual Studio Code (VS Code)

- Edit HackMD team notes in VS Code (Currently view-only) [#100](https://github.com/hackmdio/vscode-hackmd/issues/100) (P1)

## Version control systems (VCS)

- GitLab integration for individual use (P1)
- [Radicle.xyz](https://radicle.xyz) integration – [Guide](https://docs.google.com/document/d/1_1h1C7IlcHJeRDy72E2ycb7br3lumpU631rN9CMpm8E/edit#heading=h.rprz9yqw2qqg) (P2)
- Allow shared users of a note that have *Admin* and *Write* access to Push/Pull a note with GitHub. (P2)
    - The Push and Pull options do not show in a shared user's Note.
    - Note overflow menu (3 dots in the top-right) > *Versions and GitHub Sync* > *Pull from GitHub* or *Push to GitHub*
    - Workaround: Create a public team: [Create and manage Team](https://hackmd.io/@docs/create-and-manage-team)
    - Workaround: Shared users can maintain a separate note to push/pull with GitHub.

## Other

- Mobile app for reading and editing (P2)
    - Mobile web app works well for viewing and editing.

# Research

## UX
- [ ] Color, style, and theme with HTML and CSS
- [ ] Set HackMD book page's tab to a custom title.
    - Currently the book page tab title shows the link text from the book index page.
- [ ] How to build light/dark mode toggle
    - E.g. [Batch Download All Your Notes :package:](https://blog.hackmd.io/blog/2019/02/27/batch-download-all-your-notes)

## Publish

- [ ] Decentralize image hosting, e.g. Arweave and/or IPFS
- [ ] Automate saving directly to Arweave and/or IPFS: [Tweet](https://twitter.com/adamshurwitz/status/1613635255591702536) *by @adamshurwitz 2023-01-12*

<p style="text-align: center; font-style: italic">This is not technical advice. Always read the official documentation and do your own research.</p>