---
title: 🟨 Fileverse
tags: build
description: Fileverse
image: https://pbs.twimg.com/profile_banners/3540691454/1535710532/1500x500
---

<h1 style="text-align: center;">🟨 Fileverse</h1>

<p style="text-align: center;
          font-style: italic"><a href="https://fileverse.io" target="_blank">fileverse.io</a></p>

# About
Self owned publishing, information sharing, data, documents, files, etc.

# Features
- Distributed backend powered by [gun.eco](https://gun.eco), IPFS, and/or Arweave
- Compatible with [Safe.global](https://safe.global) self-owned smart accounts
    - Use the Fileverse app directly in the Safe apps view instead of connecting to the fileverse.io web app separately
- Upload files publicly or privately
- Batch onchain actions with "Signless transactions"
    - "Settings" (Left navigation menu) > Select to enable "Signless transactions"
- Public comments
    - In the dPage view top menu bar > Select "Enable Public Discussions" (Square button with a plus sign)


# Community and support
- X: [@fileverse](https://twitter.com/fileverse)
- Email: [hello@fileverse.io](mailto:hello@fileverse.io)
- GitHub: [github.com/fileverse](https://github.com/fileverse)

# Opportunities

## Prioritization key
- P0: Important and time-sensitive blocker in moving forward
- P1: Important and and not as time-sensitive
- P2: Nice to have currently
- P3: Nice to have in the future

## Account

### Access acount without storing browser authentication cookies (P0)
- Account authorization keys are stored locally on the web browser (2024-01-16)
- Clearing the browser’s cache and cookies deletes the user key making it impossible to access the account

### Sign in with Ledger hardware account (P1)
- 2023-10-31
- This is important because it will allow users to have a Ledger approval account as a part of a Safe account
    - Safe accounts can use multi device/party/location/etc. authentication
- Device: Ledger Nano X
- Browser: Firefox and Brave
- Methods: WalletConnect, Ledger Live through WalletConnect, and MetaMask
- Attempted solutions: Disable VPN and ad blocker
- [Screenshot](https://drive.proton.me/urls/42EYAGF5Q8#N1w6fjP28hjV)

## Publish

### Navigation (P1)
- View navigation based on a view's headers: H1, H2, H3, and H4
    - Displays a view's outline/table of contents on the left and/or right side
- Collection navigation based on linked views
    - Displays an expandable/collapsible menu on the left and/or right side
- Dynamically resizes and collapses outline and menu navigation based on the screen size
- E.g. HackMD does both well, see [hackmd.io/@openinfo/hackmd](https://hackmd.io/@openinfo/hackmd)

### Human readable view links (P1)
- Fileverse native links, e.g. fileverse.io/{entity-name}/{your-view-name}
    - E.g.
        - fileverse.io/openinfo/fileverse
        - hackmd.io/@openinfo/hackmd
- Custom owned domain links, e.g. {mydomain.com}/fileverse

### Option to center the view title (P2)
- Center the view title instead of the title default of the view title in the top-left

## Editor

### Edit the Markdown code directly (P2)
- This is important for advanced users to customize the published view, e.g. [Create custom tables with HTML generator tools](https://hackmd.io/@openinfo/markdown#Tables)
- The editor can switch between the what-you-is-what-you-get (WYSIWYG) and raw code modes

### Import Markdown files into "dPages" (P2)
- Import a ".md" file to create a dPage
- Copy and paste raw Markdown code into a dPage
- Workaround: Copy and paste a published Markdown view into a dPage instead of the raw Markdown code

## Security

### Backup account (P1)
- Backup account (Not downloading on Firefox v121.0 2024-01-11)
    - "Settings" (Left navigation menu) > "End-to-End Encrypted Key" > Select "Download Keys"

### Backup view file (P1 In-progress)
- Download the dPage Markdown file

<p style="text-align: center; font-style: italic">This is not technical advice. Read the official documentation and do your own research.</p>