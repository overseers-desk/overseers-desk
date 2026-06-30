# Overseer's Desk

Local-first tools that put you — and your AI — in charge of your own accounts and data. Everything runs on your machine.

<table width="100%">
<tr>
<th width="50%">Apps</th>
<th width="50%">Extensions</th>
</tr>
<tr valign="top">
<td width="50%">

**[courier](https://github.com/overseers-desk/courier)** *(CLI and MCP)*
Give your script or AI assistant access to your existing email over IMAP and SMTP: search, read, reply, send, and organise, with sensitive senders kept out of the model's view.

**[majordomo](https://github.com/overseers-desk/majordomo)** *(CLI and MCP)*
Read Google Chat and report who holds which tasks across spaces and dates, including the Chat-created tasks the Tasks API cannot return.

<hr/>

**[crude](https://github.com/overseers-desk/crude)** *(CLI)*
CRUD-style command-line clients for your own records on sites without a usable public API, covering ATDW, Skål, Rezdy, Deputy, Sonas, Xero, Airwallex, Clover, and Facebook.

<hr/>

**[questlog](https://github.com/overseers-desk/questlog)** *(CLI and GUI)*
Find, read, and reopen past Claude Code sessions under `~/.claude/projects`, grouped by project with streamed full-text search.

**[scribe](https://github.com/overseers-desk/scribe)** *(CLI and GUI)*
A hotkey desktop tool that turns your voice or clipboard into text, optionally restyled by an LLM, then types, pastes, or copies the result.

**[OneDrive-ACL-Manager](https://github.com/overseers-desk/OneDrive-ACL-Manager)** *(CLI and GUI)*
Audit and revoke OneDrive sharing across whole folder trees: see who can access what, and remove access recursively.

</td>
<td width="50%">

**[homebrew-od](https://github.com/overseers-desk/homebrew-od)**
The Homebrew tap that distributes the apps on the left (`brew tap overseers-desk/od`).

<hr/>

**[overseers-desk](https://github.com/overseers-desk/overseers-desk)**
This repo is the Claude Code marketplace for the plugins below. Add it once: `claude plugin marketplace add overseers-desk/overseers-desk`

**[skillbooks](https://github.com/overseers-desk/skillbooks)**
A Claude Code plugin of AI-run skills that drive your logged-in browser or a site's API, from LinkedIn and Instagram to award-flight search, editorial review, and dossier building. Install: `claude plugin install skillbooks@overseers-desk`

**[holotapes](https://github.com/overseers-desk/holotapes)** *(private)*
Slash commands for document management, mail, and office workflows. Install: `claude plugin install holotapes@overseers-desk`

<hr/>

**[Heptad](https://github.com/overseers-desk/Heptad)**
A seven-level multilingual keyboard layout built on US QWERTY, adding accents, Greek letters, currencies, and math symbols with nothing to unlearn.

</td>
</tr>
</table>

Most command-line tools install from Homebrew (`brew tap overseers-desk/od`) and as Debian or Fedora packages; courier also installs from PyPI (`uvx courier`). See each tool's own README for the platforms it ships on.
