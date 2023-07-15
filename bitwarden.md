---
title: 🛡 Bitwarden
tags: build
description: Bitwarden
image: https://pbs.twimg.com/profile_banners/3540691454/1535710532/1500x500
---

<h1 style="text-align: center;">🛡 Bitwarden</h1>

<p style="text-align: center;
          font-style: italic"><a href="https://bitwarden.com" target="_blank">bitwarden.com</a></p>

# About

*Open-source password and credentials manager.*

#### Download

- [bitwarden.com/download](https://bitwarden.com/download)

#### Open-source

- [bitwarden.com/open-source](https://bitwarden.com/open-source/)
- Can self-host the app on a server

#### Community and support

- Twitter: [@bitwarden](https://twitter.com/bitwarden)
- Reddit: [r/Bitwarden](https://www.reddit.com/r/Bitwarden)
- Forum: [community.bitwarden.com](https://community.bitwarden.com/)
- Support: [bitwarden.com/contact](https://bitwarden.com/contact)


#### Development

- [Contributing](https://contributing.bitwarden.com/)
- GitHub: [github.com/bitwarden](https://github.com/bitwarden)
- [APIs](https://bitwarden.com/help/bitwarden-apis/)

#### Partnerships

- [DuckDuckGo macOS Browser Integration](https://bitwarden.com/help/duckduckgo-macos-browser-integration/)

#### External reviews

- [Best Password Manager in 2023](https://www.cnet.com/tech/services-and-software/best-password-manager) *by CNet*
- [The Best Password Managers for 2023](https://www.pcmag.com/picks/the-best-password-managers) *by PCMag*

# Features

#### Vault

- *See [Vault Items](https://bitwarden.com/help/managing-items/)*
- Item types
    - Username and passwords
    - Notes
    - Credit cards
    - Identities
- Attachments opportunities
    - Desktop
        - Show attachment field on *Add Item* view: Currently only shows on *Edit Item* view.
    - Web
        - Show attachment field on *Add Item* view: Currently only shows for current items in the overflow menu (3 vertical dots).
    - Mobile (Android)
        - Show attachment field on *Add Item* view: Currently only shows for current items in the overflow menu (3 vertical dots).
        - View attachment data on mobile: Currently cannot view or download attachments.

#### Multi-factor authentication (MFA)

- Yubikey support: [Using Bitwarden with Yubico](https://bitwarden.com/resources/using-bitwarden-with-yubico/?amp)
- [Recovery Codes](https://bitwarden.com/help/two-step-recovery-code/)

#### One-time passcodes

- [Bitwarden Authenticator (TOTP)](https://bitwarden.com/help/authenticator-keys/)

#### Password tools

- Generator: [bitwarden.com/password-generator](https://bitwarden.com/password-generator)
- Strength test: [bitwarden.com/password-strength](https://bitwarden.com/password-strength)

#### Backups

- Steps: [Export Vault Data](https://bitwarden.com/help/export-your-data/#export-a-personal-vault)
    - Note: Backups don't include attachments and password history.
- [How to Create and Store a Backup of Your Bitwarden Vault](https://bitwarden.com/resources/guide-how-to-create-and-store-a-backup-of-your-bitwarden-vault/)

#### Social recovery

- [Emergency Access](https://bitwarden.com/help/emergency-access/#use-emergency-access)
- Available in the web app: *Profile* (Top-right button in the menu) > *Account settings > Emergency access*

#### Active sessions

- Opportunity: *See [Account access history](https://community.bitwarden.com/t/account-access-history/118) on Bitwarden forum*

#### Certifications

- [Security FAQs](https://bitwarden.com/help/security-faqs/) > *[Q: What is Bitwarden compliant with? What certifications do you have?](https://bitwarden.com/help/security-faqs/#q-what-is-bitwarden-compliant-with-what-certifications-do-you-have)*

#### Shortcuts

- *See [Keyboard Shortcuts](https://bitwarden.com/help/keyboard-shortcuts/)*
- Opportunities
    - Functions to add
        - Edit an item: <kbd>CMD</kbd> + <kbd>E</kbd>
        - Create a new folder: <kbd>CMD</kbd> + <kbd>D</kbd> (D for directory)
        - Delete an item: <kbd>SHIFT</kbd> + <kbd>#</kbd>
    - Add to guide
        - Save an item: <kbd>ENTER</kbd> or <kbd>RETURN</kbd>

#### See vault item counts

- Open the mobile app > See item counts by *Type and Folders.*

#### KDF iterations

- KDF: Key derivation functions
- Warning message: "Low KDF iterations. Update your encryption settings to meet new security recommendations and improve account protection."
- *See [KDF Algorithms](https://bitwarden.com/help/kdf-algorithms)*

# Apps

## Desktop app

- [Get Started with Desktop Apps](https://bitwarden.com/help/getting-started-desktop/)
- Opportunities
    - Auto-fill credentials.
        - [🔍 Auto-type/Autofill for logging into other desktop apps](https://community.bitwarden.com/t/auto-type-autofill-for-logging-into-other-desktop-apps/158) *on Bitwarden forum 2023-01-28*
        - [Can bitwarden desktop auto-fill desktop apps?](https://www.reddit.com/r/Bitwarden/comments/fg1yu2/can_bitwarden_desktop_autofill_desktop_apps/) *on r/Bitwarden 2020-03-09*
        - [Bitwarden autofill desktop apps](https://www.reddit.com/r/Bitwarden/comments/mzjuga/bitwarden_autofill_desktop_apps/) *on r/Bitwarden 2021-04-27*

## Browser add-on and extension

- [bitwarden.com/browser-start](https://bitwarden.com/browser-start)
- Useful options
    - *Settings*
        - *Unlock with biometrics*
        - *Vault timeout*
- Auto-fill
    - [Auto-fill Logins in Browser Extensions](https://bitwarden.com/help/auto-fill-browser/)

## Mobile app

- Auto-fill
    - [Auto-fill Logins on Android](https://bitwarden.com/help/auto-fill-android/)
        - Auto-fill service
            - Uses the Android Autofill Framework
        - Use inline autofill
            - Uses the keyboard
            - Defaults to the Auto-fill overlay if the keyboard does not support inline autofill
        - Use accessibility
            - Required for draw-over
        - Use draw-over
            - For older apps that don't support the Android Autofill Framework
    - [Auto-fill Logins on iOS](https://bitwarden.com/help/auto-fill-ios/)

<p style="text-align: center; font-style: italic">This is not technical advice. Always read the official documentation and do your own research.</p>