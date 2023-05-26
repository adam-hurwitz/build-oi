---
title: 📄 HackMD GitHub
tags: hackmd
description: HackMD GitHub integration
image: https://pbs.twimg.com/profile_banners/3540691454/1535710532/1500x500
---

GitHub
===

## About
- *See [Sync a Note with GitHub](https://hackmd.io/s/link-with-github)*
    - Must have 1 push/pull in order for the option to show.
- Encourage collaboration: [Add GitHub badge](https://hackmd.io/s/link-with-github#Add-GitHub-badge) to the HackMD note.

## Enable

#### 1. Set up GitHub permissions.

- Make sure your HackMD email has GitHub access.
- GitHub account level email: Profile (Top-right button) > *Settings* > *Emails* > *Add email address*
- Or GitHub repository's permission settings: *Team admin*, *Team member*, or *Invitee admin*

#### 2. Link GitHub to HackMD.
    
a. HackMD menu (Bottom-left button with username) > *Settings* > *Integration* > Select *Link with GitHub*.
    
b. *HackMD Hub by HackMD would like permission to: ...* > Select *Authorize HackMD Hub*    

- Error for a user without access: `request to https://github.com/login/oauth/access_token failed, reason: read ECONNRESET`
    
c. Manage GitHub [Hackmd Hub app](https://github.com/apps/hackmd-hub) access.

#### 3. Enable GitHub in a Note.
    
a. Note overflow menu (3 dots in the top-right) > *Versions and GitHub Sync* > *Pull from GitHub* or *Push to GitHub* > Select *Authorize more repos*
    
b. *Install & Authorize HackMD Hub* > For enhanced security only authorize HackMD access for *Only select repositories* vs. *All repositories*. > Select *Install & Authorize*
    
#### 4. Change the GitHub .md file associated with a note.
    
a. Unlink: Note overflow menu (3 dots in the top-right) > *Versions and GitHub Sync* > *GitHub Link Settings* > Select *Unlink*.
    
b. Re-link to a new GitHub .md file.

## Branches

- Create new branch from HackMD
    - New repositories without a `main` branch
    - New feature branch in an existing repositiory
- Sync with existing GitHub feature branches.
- Submit pull requests (PR) in GitHub to merge feature branches with the main and/or production branch(es).
- It can be useful to have a feature branch for each HackMD note.

## Push

- [Push to GitHub](https://hackmd.io/s/link-with-github#Push-to-GitHub)
- Each [HackMD named version](#HackMD-named-versions) will push as a Git commit.
    - HackMD auto-saved versions will not produce commits.
- Commit message
    - Auto-generated based on the HackMD version name and description
    - Use a common commit message [style guide](https://docs.google.com/document/d/1W0pYNbK1a0teJDt96Jcli7RVEcaUpXpXoSKHbeX2VSs/edit#heading=h.xo83z7povj6l).
- *Select file*
    - For HackMD books use a unique filename for the book index note.
        - Important when the book index note has the same title as the first note in the book, listed in the book's index.
        - E.g.
            - Book index note for this guide: *hackmd-index.md*
            - First note in the book: *hackmd.md*
    - Can push files within directories (folders), e.g. `about/community-and-support.md`
    - Filename format
        - Important for URLs, programmability, and command line compatibility
        - Use lowercase and separate words with hyphens `-` instead of spaces (` `) or camel casing (camelCasing).
        - Resources
            - Google developer documentation style guide
                - [Filenames and file types](https://developers.google.com/style/filenames)
                - [Capitalization](https://developers.google.com/style/capitalization)
            - [What technical reasons exist for not using space characters in file names?](https://superuser.com/questions/29111/what-technical-reasons-exist-for-not-using-space-characters-in-file-names) *by superuser.com*

## Pull

- [Pull from GitHub](https://hackmd.io/s/link-with-github#Pull-from-Github)
- Can choose the branch to pull from
- Can choose the portion of pulled branch revisions to merge into the HackMD note

<p style="text-align: center; font-style: italic">This is not technical advice. Always read the official documentation and do your own research.</p>