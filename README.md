> [!CAUTION]
>
> # ⚠️ Unofficial Addons
>
> Addons published in this repository are created by members of the Korone community and are **not officially developed or supported by Korone**.
>
> Every addon is **reviewed and tested by the Korone team before publication** to ensure it is safe and follows the repository guidelines.

> [!WARNING]
>
> # Support Policy
>
> Do **not** ask for help with unofficial addons in general chats or by opening a support ticket.
>
> Questions, bug reports and support requests must be posted in the addon’s dedicated forum post.

# Korone Unofficial Addons

This repository contains community-created userscripts for Korone.

## Installing an Addon

1. Install one of the following userscript managers:

   * [**Violentmonkey**](https://violentmonkey.github.io/)
   * [**Tampermonkey**](https://www.tampermonkey.net/)

2. Click the Violentmonkey or Tampermonkey icon in your browser toolbar.

3. Open the userscript dashboard and click the **+** button to create a new userscript.

4. Inside the code editor, press **Ctrl + A** to select all existing content.

5. Paste the addon’s userscript code into the editor.

6. Save the userscript.

The addon should now run automatically on supported Korone pages.

---

# Submitting an Addon

To submit an addon, create a new directory using the following structure:

```text
AddonName/
├── README.md
├── AddonName.user.js
└── ...
```

Every addon directory must contain:

* One `README.md` file
* Exactly one JavaScript userscript file
* Any additional files required by the addon, such as CSS, JSON, images or other assets

The main JavaScript userscript may fetch or load additional files included in the same addon directory.

Do not include multiple userscript files, browser extensions, executables or unrelated files in your submission.

Once your addon is ready, open a **Pull Request** to this repository.

Your submission must follow all guidelines below.

# Addon Guidelines

* **No obfuscation is allowed.** Your addon must be fully open source and its code must remain readable.

* The addon must comply with Korone’s [**rules**](https://discord.com/channels/1411352883533844603/1411353153659600998) and [**Terms of Service**](https://www.pekora.zip/auth/tos).

* **Only userscripts are accepted.** Browser extensions, executables and other standalone software are not permitted.

* Every addon must include exactly **one JavaScript userscript file** and one `README.md` file.

* Additional files may be included when required by the addon.

* The main userscript may fetch or load additional files from its own addon directory.

* If your addon communicates with an external API or third-party service, such as Koromons, this must be clearly disclosed.

* Your addon must be original. Copied, stolen or “skidded” submissions are not allowed.

* Addons must not contain malicious, deceptive, privacy-invasive or otherwise harmful functionality.

* The addon must only request the permissions it genuinely needs.

* Any data collected, stored or transmitted by the addon must be clearly disclosed.

* The addon’s purpose, features and behavior must be documented clearly.

* The addon must not attempt to bypass Korone moderation, security measures, access controls or platform restrictions.

* The addon must not impersonate official Korone features, staff members or services.

* **Images are required.** You must provide clear screenshots or other relevant images showing the addon in use in all three of the following places:

  * The Pull Request
  * The addon’s `README.md`
  * The addon’s Discord forum post

* The images must clearly demonstrate the addon’s interface, features or visible behavior. Placeholder images, unrelated images or screenshots that do not show the addon functioning are not accepted.

Submissions that do not follow these requirements may be rejected or removed at any time.

# README Requirements

The addon’s `README.md` must include:

* The addon’s name
* A detailed description of what the addon is
* A clear explanation of what the addon does
* An explanation of how the addon works
* Installation instructions
* Usage instructions
* Any required userscript permissions
* Any external APIs or third-party services used
* Any applicable warnings or disclaimers
* Known limitations or compatibility requirements
* Clear screenshots or other relevant images showing the addon in use

The README must provide enough information for users and reviewers to understand the addon before installing it.

# Pull Request Requirements

The Pull Request must include:

* The addon’s name
* The submitter’s Discord User ID
* The submitter’s Korone profile URL
* A detailed description of the addon
* Any relevant disclaimers
* Clear screenshots or other relevant images showing the addon in use
* Confirmation that all repository rules and submission requirements have been followed

Pull Requests without the required information or images may be rejected without review.

# Updating an Addon

Every addon update requires a **new Pull Request**.

Do not update an approved addon without submitting the changes for review.

The new Pull Request must clearly explain:

* What was changed
* Why the update was made
* Whether any new permissions were added
* Whether any new external APIs or third-party services are used
* Whether the addon’s behavior, data handling or compatibility changed
* Any new warnings, limitations or disclaimers

The addon’s `README.md` must be updated whenever the update changes its features, behavior, installation steps, permissions, compatibility or disclosures.

After the update is approved, it must also be announced in the addon’s dedicated Discord forum post.

Updates that are published without review may result in the addon being removed and further action being taken against the author.

# Review Process

Submitted addons and updates are reviewed and tested by the Korone team before publication.

The team may request changes before approving a submission.

Approval does not make an addon official. Approved addons remain community-created and are provided without official Korone support.

Korone may reject, remove or request changes to any addon that violates these guidelines or creates a risk for users or the platform.

# Publishing an Approved Addon

If your addon is approved, you will be given access to publish it in the [**#unofficial-addons**](https://discord.com/channels/1411352883533844603/1527222118016745483) Discord forum.

Publishing a forum post is **required**. An approved addon must be posted in the forum before it can be considered fully published.

The forum post must include:

* A detailed description of what the addon is
* A clear explanation of what the addon does
* An explanation of how the addon works
* Installation and usage instructions
* Clear screenshots or other relevant images showing the addon in use
* Any external APIs or third-party services used
* Any permissions required by the userscript
* Any warnings, limitations or disclaimers users should know about
* A link to the addon’s directory or approved source code

The addon’s forum post will also be the required place for:

* Support questions
* Bug reports
* Feature requests
* Update announcements
* Compatibility information

Do not direct users to general chats or the Korone Support Center for addon-related assistance.
