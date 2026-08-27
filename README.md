# ![Courier](asset/banner.jpg)

Local-first tools that put you — and your AI — in charge of your own accounts and data. Everything runs on your machine.

<table width="100%">
<tr>
<th width="50%">Apps</th>
<th width="50%">Extensions</th>
</tr>
<tr valign="top">
<td width="50%">

**[robco-term](https://github.com/overseers-desk/robco-term)** *(GUI)*
The terminal from the vault, made real: amber phosphor behind curved glass, and every machine you reach on its own numbered channel.

<hr/>

**[courier](https://github.com/overseers-desk/courier)** [![PyPI](https://img.shields.io/pypi/v/courier?logo=pypi&logoColor=white&label=PyPI)](https://pypi.org/project/courier/) *(CLI and MCP)*
Give your script or AI assistant access to your existing email over IMAP and SMTP: search, read, reply, send, and organise, with sensitive senders kept out of the model's view.

**[majordomo](https://github.com/overseers-desk/majordomo)** [![PyPI](https://img.shields.io/pypi/v/majordomo?logo=pypi&logoColor=white&label=PyPI)](https://pypi.org/project/majordomo/) *(CLI and MCP)*
Read Google Chat and report who holds which tasks across spaces and dates, including the Chat-created tasks the Tasks API cannot return.

<hr/>

**[crude](https://github.com/overseers-desk/crude)** *(CLI)*
CRUD-style command-line clients for your own records on the business services you run on, covering Xero, Airwallex, Clover, Rezdy, Deputy, and Facebook.

<hr/>

**[questlog](https://github.com/overseers-desk/questlog)** *(CLI and GUI)*
Find, read, and reopen past Claude Code sessions under `~/.claude/projects`, grouped by project with streamed full-text search.

**[scribe](https://github.com/overseers-desk/scribe)** *(CLI and GUI)*
A hotkey desktop tool that turns your voice or clipboard into text, optionally restyled by an LLM, then types, pastes, or copies the result.

**[warden](https://github.com/overseers-desk/warden)** *(CLI and GUI)*
Role-based access control for OneDrive and Dropbox. One policy file names your people, the groups they belong to and the folders each group may reach; warden holds both drives to it and repairs what drifted.

</td>
<td width="50%">

**[homebrew-od](https://github.com/overseers-desk/homebrew-od)**
The Homebrew tap that distributes the apps on the left (`brew tap overseers-desk/od`).

<hr/>

**[Heptad](https://github.com/overseers-desk/Heptad)**
A seven-level multilingual keyboard layout built on US QWERTY, adding accents, Greek letters, currencies, and math symbols with nothing to unlearn.

<hr/>

**[overseers-desk](https://github.com/overseers-desk/overseers-desk)**
This repo is the Claude Code marketplace for the plugins below. Add it once: `claude plugin marketplace add overseers-desk/overseers-desk`

**[skillbooks](https://github.com/overseers-desk/skillbooks)**
Every book read is a stat permanently raised. A Claude Code plugin of crafts your agent keeps: mail a human would send, drafts that survive a cold reader, claims traced to their source, code swept for what a refactor left behind, and the judgment to know which decisions are truly yours. Install: `claude plugin install skillbooks@overseers-desk`

**[magazines](https://github.com/overseers-desk/magazines)**
A Claude Code plugin of AI-run skills that drive your logged-in browser or a site's API, from LinkedIn and Instagram to award-flight search, plus dossier and person research. Install: `claude plugin install magazines@overseers-desk`

**[holotapes](https://github.com/overseers-desk/holotapes)** *(private)*
The Overseer's personal tapes for behaviour change to claude agents. There is no opt-in screen. Every bad habit it had now has a name, and it predicts which bad habit will trigger before doing anything, to avoid them. You can loot it over the Overseer's corpse, or [file an issue to ask for access](https://github.com/overseers-desk/overseers-desk/issues).

</td>
</tr>
</table>

Most command-line tools install from Homebrew (`brew tap overseers-desk/od`) and as Debian or Fedora packages; courier and majordomo also install from PyPI (`uvx courier`, `uvx majordomo`). See each tool's own README for the platforms it ships on.
