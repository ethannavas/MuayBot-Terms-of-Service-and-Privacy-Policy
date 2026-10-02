# MuayBot legal pages — publication draft

Includes styled, mobile-friendly HTML pages and editable Markdown copies. This is a policy draft based on the reviewed MuayBot-Advanced source, not legal advice or a guarantee of Discord verification.

## Before publishing

1. Replace [OPERATOR NAME], [SUPPORT EMAIL], and [PUBLICATION DATE] in every file. Use the actual person or legal entity operating the service, an actively monitored public email, and the actual effective date. Do not use invented contact details.
2. Review each statement against your real operation, including providers, access, payment arrangements, and deployment country. Obtain jurisdiction-specific advice if needed. Add any applicable legal bases, controller details, local disclosures, and transfer arrangements based on the actual business; these facts cannot be inferred from the code.
3. Remove the draft notice from both HTML pages and Markdown copies only after review. Keep both formats consistent when editing; the HTML pages are what GitHub Pages serves.
4. Establish a manual deletion/correction process covering database rows, audit records, deliveries, game state, and backups. Removing a guild does not automatically delete its data. Set and follow a documented retention and backup schedule. The policy is an operational commitment, not an implementation of deletion functionality.
5. Protect the full database and backups with encryption at rest provided by the host or filesystem. The bot encrypts RCON secrets only. Discord's Developer Terms also require safeguards for API data; publishing a policy alone does not address this.
6. Add a visible link to the policy and support contact in the bot's help/profile. Keep the policy URLs current in the Developer Portal.
7. These terms describe manual memberships, no automatic card billing, and no cash wagering. Revisit policies and implementation before introducing a payment processor, recurring billing, or materially different features.

## Publish using GitHub Pages

1. Sign in to GitHub and create a new public repository named `muaybot-legal`.
2. Upload the CONTENTS of this folder into the repository root, not the ZIP itself. Commit the files to `main`.
3. Open repository Settings → Pages.
4. Under Build and deployment, select Deploy from a branch, then `main` and `/ (root)`. Save.
5. Wait for deployment and open the URL shown by GitHub. Confirm both pages open without a login and show your actual contact details.
6. Use the published URLs in Discord's Developer Portal Terms of Service URL and Privacy Policy URL fields:
   - https://YOUR-GITHUB-USERNAME.github.io/muaybot-legal/terms.html
   - https://YOUR-GITHUB-USERNAME.github.io/muaybot-legal/privacy.html

Replace YOUR-GITHUB-USERNAME with your actual GitHub account name. These are templates, not live links. This package does not create a repository or publish anything. Only upload these policy files; never upload your bot token, environment configuration, database, or server credentials.

## Sources reviewed October 2, 2026

- Discord Developer Terms, especially Section 5: https://support-dev.discord.com/hc/en-us/articles/8562894815383-Discord-Developer-Terms-of-Service
- Discord Developer Policy: https://support-dev.discord.com/hc/en-us/articles/8563934450327-Discord-Developer-Policy
- GitHub Pages publishing: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Policies were drafted independently for MuayBot. They do not claim affiliation with KAOS or Helios.
