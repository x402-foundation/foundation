# x402 Foundation Slack Guidelines
Slack is the primary real-time communication platform for the x402 Foundation community, complementing GitHub (for code and specs), mailing lists, and community calls. The x402 community includes protocol maintainers, implementers, financial institutions, cloud providers, wallet and agent-framework developers, and other participants – many of whom are commercial competitors. These guidelines exist to keep that collaboration productive, safe, and legally sound.

Slack chat is effectively public and searchable within the workspace. Don't post anything you wouldn't say on a recorded call. Be courteous and assume good faith.

## Code of Conduct
The x402 Foundation [Code of Conduct](https://lfprojects.org/policies/code-of-conduct/) applies across all Slack channels, DMs, and huddles, exactly as it applies to GitHub, mailing lists, and in-person events. 

## Joining the Workspace
- Join through the official community invite link published on x402.org and in the x402-foundation GitHub org.
- Employees of member organizations should join under an account that identifies them and their affiliation in their Slack profile; this matters for antitrust hygiene and technical trust (see: [LF’s Antitrust Policy](https://www.linuxfoundation.org/legal/antitrust-policy)).

## Admins and Moderators
- A public, centrally maintained list of Slack admins/moderators (name, organization, timezone) will live in the foundation repo.
- Reach admins by tagging @operations for public asks, or DM for anything sensitive.

## Workspace History and Retention
- The Slack workspace is not an official system of record. Substantive technical decisions (spec changes, approvals, etc.) must be captured in GitHub issues/PRs or meeting minutes. 
- The Foundation shall periodically clear the message history of the #general and #random channels at 90-day intervals to maintain focused and relevant discussions across the workspace.
- The Foundation shall periodically archive the workspace (no fixed interval required) and publish the archive location for members who need to reference historical discussion (if needed). 
- x402 sits inside the Linux Foundation's records framework, so check with LF IT/legal for any LF-wide records-retention policy before finalizing an interval.

## General Usage Guidelines
### Encouraged
- Following the Code of Conduct.
- Keeping discussion on-topic for the channel and putting discussions in the appropriate channels. For example, GitHub/PR-related conversation belongs in #github-discussions, technical protocol discussion in #tsc-public, and occasional social chatting which fosters a sense of community in #general. If applicable, anything topic-specific should be directed to our working group channels. 
- Helping other members by answering integration questions, reviewing proposals, and pointing people to docs.
- Posting reminders for working group meetings, community calls, and review deadlines.
- Light social chat, in moderation, and avoiding topics likely to be genuinely divisive or upsetting to a global membership (e.g., geopolitics).

### Prohibited
- Violations of the Code of Conduct.
- Spam and self-promotion, including unsolicited posting of blogs, personal projects, or vendor pitches outside designated channels.
- Unsolicited DMs! Don't message a member who hasn't invited it and whom you aren't approaching in an official project capacity. Default to public channels.
- No unapproved bots, apps, or automated agents connected to the workspace (including AI agents/scrapers) without prior approval from Slack admins. 
- Company-confidential or proprietary business discussion. Take it to your own company's channels.
- Financial or investment advice, and token/price speculation. x402 is a payments protocol, not an investment vehicle. Do not solicit, recommend, or promote specific tokens, exchanges, wallets, trading strategies, or “opportunities” tied to x402 or any other asset. Messages that look like financial solicitation should be reported and removed on sight – payments and crypto-adjacent communities are a common phishing/scam target.
- Impersonation and phishing. Never share seed phrases, private keys, or credentials in Slack, and never ask others to. Report suspected phishing (fake support DMs, fake "admin" accounts, fake airdrops) immediately by tagging ```@operations```.
- Antitrust-sensitive discussion. Because member organizations include competing companies, do not discuss competitively sensitive topics — pricing, fees charged to customers, market allocation, non-public roadmaps of a competitor, or agreements to act collectively outside the open standard-setting process. When in doubt, keep discussion to the technical merits of the protocol. [Standard guidance](https://lfprojects.org/policies/antitrust-policy/) for Linux Foundation collaborative projects.

## Channel Management
_Should a new channel exist?_
- It must relate to x402 (protocol, an SDK/implementation, a working group, a sub-project, or the surrounding ecosystem).
- The related project should already be public/open source before requesting a channel. 
- Channels should generally be public. Private channels are granted sparingly, mainly for code-of-conduct handling, active security coordination, or governing-committee business, and must include at least one Slack admin.
- Suggested naming: #x402-<topic> for protocol/spec topics, #wg-<name> for working groups, #<project> for a specific ecosystem project/SDK (max 2 channels per external project, e.g. #<project> and #<project>-dev), keeping names ≤ 21 characters (Slack's limit).
- Requesting a channel: open an issue or PR against the foundation repo describing the purpose and proposed owner. Two admin approvals required before creation.
- Delegating ownership: working group leads may be delegated authority over their own set of channels, following the same repo-based config pattern, so day-to-day requests don't all bottleneck on Foundation admins.

## Bots, Tokens, and Webhooks
READ BEFORE SUBMITTING A REQUEST

Bots, tokens, and webhooks are reviewed on a case-by-case basis with most requests being rejected due to security, privacy, and usability concerns. Bots and the like tend to make a lot of noise in channels. 

Any bot, OAuth app, token, or webhook connecting to the workspace requires approval from Slack admins.
Requests must state the requested scopes/permissions and their purpose, filed as a GitHub issue against the community repo for traceability.
Most requests should be default-deny; approved examples are typically limited to GitHub notifications, CI status, and Foundation-run community-management tooling.

## Reporting a Problem
- To report a message, users should type ```/Report```, which will send a private message to the LF staff to review and take action on the message.
- For anything urgent, tag @operations. 
- Sensitive matters: email conduct@x402.org directly.

## Consequences
Violations may result in a warning, message removal, temporary restriction, or account deactivation, up to removal of an organization’s participants for repeated or severe violations. Admins should document actions taken (e.g., a screenshot before removal) and report significant actions to the wider admin group if necessary. 
