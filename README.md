# Overseer's Desk

Local-first tools that put you — and your AI — in charge of your own accounts and data. Everything runs on your machine.

<table>
<tr>
<th>For you and your AI</th>
<th>Meta projects</th>
</tr>
<tr valign="top">
<td>

**[mailroom](https://github.com/overseers-desk/mailroom)** *(CLI and MCP)*
Give your script or AI assistant access to your existing email over IMAP and SMTP: search, read, reply, send, and organise, with sensitive senders kept out of the model's view.

**[majordomo](https://github.com/overseers-desk/majordomo)** *(CLI and MCP)*
Read Google Chat and report who holds which tasks across spaces and dates, including the Chat-created tasks the Tasks API cannot return.

**[crude](https://github.com/overseers-desk/crude)** *(CLI)*
CRUD-style command-line clients for your own records on sites without a usable public API, covering ATDW, Skål, Rezdy, Deputy, Sonas, Xero, Airwallex, Clover, and Facebook.

**[questlog](https://github.com/overseers-desk/questlog)** *(CLI and GUI)*
Find, read, and reopen past Claude Code sessions under `~/.claude/projects`, grouped by project with streamed full-text search.

**[scribe](https://github.com/overseers-desk/scribe)** *(CLI and GUI)*
A hotkey desktop tool that turns your voice or clipboard into text, optionally restyled by an LLM, then types, pastes, or copies the result.

**[OneDrive-ACL-Manager](https://github.com/overseers-desk/OneDrive-ACL-Manager)** *(CLI and GUI)*
Audit and revoke OneDrive sharing across whole folder trees: see who can access what, and remove access recursively.

</td>
<td>

**[homebrew-ot](https://github.com/overseers-desk/homebrew-ot)**
The Homebrew tap that distributes the left side tools (`brew tap overseers-desk/ot`).

**[skillbooks](https://github.com/overseers-desk/skillbooks)**
A Claude Code plugin of AI-run skills that drive your logged-in browser or a site's API, from LinkedIn and Instagram to award-flight search, editorial review, and dossier building. **This repository is its marketplace:** `claude plugin marketplace add overseers-desk/overseers-desk`, then `claude plugin install skillbooks@overseers-desk`.

**[Heptad](https://github.com/overseers-desk/Heptad)**
A seven-level multilingual keyboard layout built on US QWERTY, adding accents, Greek letters, currencies, and math symbols with nothing to unlearn.

</td>
</tr>
</table>

Most command-line tools install from Homebrew (`brew tap overseers-desk/ot`) and as Debian or Fedora packages. See each tool's own README for the platforms it ships on.
