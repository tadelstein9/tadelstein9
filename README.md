## Tom Adelstein

After I started Bynari, every Outlook specialist I asked said a company could not keep its Outlook calendars on an IMAP server. My engineers and I built one, with help from a SourceForge developer who ported Open DCE, and Winnebago replaced Microsoft Exchange with it for $20,000 against a $100,000 quote. I wrote the method up in *Linux Journal* as "Understanding and Replacing Microsoft Exchange."

I build the infrastructure a small organization runs on computers it owns.

### A lab you can build

I built a lab in Paris, Texas, where each computer does a single job. A Dell Inspiron 5567 plays the clerk's desk, an OptiPlex 9020 keeps the Git repositories and backups, an OptiPlex 7080 runs the command center, and a Precision 3640 runs the language model. The playbooks, roles and runbooks that built it sit in **[hands-on-linux-infrastructure-lab](https://github.com/tadelstein9/hands-on-linux-infrastructure-lab)**, under the MIT license, so you can run the same steps on your own hardware.

### Tools for writers who use AI

A writer who drafts with a model needs to find what it added. **[editor-flags](https://github.com/tadelstein9/editor-flags)** reads a draft and flags the habits a model leaves behind: the floating past perfect, the chip of a sentence, the thing that acts like a person. It reports and leaves every change to the writer. **[naturalizer](https://github.com/tadelstein9/naturalizer)** scores a draft against the writer's own measured rates, because I tested a popular checker on 143,189 words of published human prose and six of its eight checks flagged the people more often than the model. **[md-in-chrome](https://github.com/tadelstein9/md-in-chrome)** opens a markdown file in Chrome, lets you fix it on the page, and saves an edit copy beside the original. **[overlap-check](https://github.com/tadelstein9/overlap-check)** shows the same words in two files you already have.

### Memory for coding agents

A coding agent holds only what fits in its context window, so I gave mine a database. **[two-tier-memory](https://github.com/tadelstein9/two-tier-memory)** keeps a short index in the prompt and the full record in SQLite with full-text search, and the agent queries it before it rebuilds something it lost. **[eos](https://github.com/tadelstein9/eos)** turns a Claude Code session into a document your team can read, then checks it against what happened.

### Two books in pre-publication

I have two Linux books in pre-publication. In ***Hands-On Linux Infrastructure***, an engineer takes consulting engagements from a city, a county, a school and a hospital in Texas, and in each chapter brings a public office's existing computers up to the State's cybersecurity standard. I ran every command in it on the lab above. In ***You Didn't Know Linux***, I start the reader where I started in 1997, wanting Linux without knowing the commands, and walk through the problems I solved after the experts called them unsolvable.

### Where I write

Writing about Linux runs through my whole career. I wrote about 300 articles on it, many of them for *Linux Journal*, and O'Reilly published my *Linux System Administration*. I write now at **[Advance](https://tomadelstein.substack.com)**, from real runs in the lab. The latest piece shows how one fwupd command kept an older Dell booting Linux after Microsoft's 2011 Secure Boot certificate expired. Reply to any piece there and the note reaches me.
