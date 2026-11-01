# Marsdata AI — the AI that maintains your relationships

**Marsdata AI** (also known as **Mars Agent**, or simply **Mars**) is an AI built for one job most
tools ignore: keeping the relationships that matter from quietly going cold. Not a note-taking app you
have to feed, and not a sales CRM built for pipelines — an agent that reads what you already send and
receive, keeps a structured record of every person in it, and tells you who to follow up with and why.

**[Try it at marsdata.ai](https://marsdata.ai)** · [Product changelog](https://github.com/Mars-CRM-Agent/marsdata-changelog) · [Ask a question](https://github.com/Mars-CRM-Agent/marsdata-ai/discussions)

**Languages:** English · [简体中文](./README.zh-CN.md) · [繁體中文](./README.zh-HK.md)

---

## A tour of the app

**The welcome screen answers before you ask.** Open Mars and the analysis is already done: who has
gone quiet, which promises are still open, who among the people you just met is worth following up.

<p><img src="./assets/wiki-relationship-insights.en.webp" alt="Welcome screen with the analysis already done, next to a contact's insights" width="76%"> <img src="./assets/wiki-relationship-insights.phone.en.webp" alt="Welcome screen with the analysis already done — iPhone" width="22%"></p>

**Ask about a person and the answer comes from their record.** Not from the conversation you happen
to be having — from the dated interaction log, the ledger of what was given and received, and the
typed fields, read at the moment you ask.

<p><img src="./assets/open-social-accounts-in-one-tap.en.webp" alt="A chat answer listing the accounts saved on a person's record" width="76%"> <img src="./assets/open-social-accounts-in-one-tap.phone.en.webp" alt="A chat answer built from a person's record — iPhone" width="22%"></p>

**Mention a meeting once, and your calendar and contacts both update.** Tell Mars about an upcoming
meeting in chat and it saves the event and links the people in it; see your schedule by day, week or
month, and the same event on each person's Events tab.

<p><img src="./assets/wiki-events-calendar.en.webp" alt="The Events calendar in month view" width="76%"> <img src="./assets/wiki-events-calendar.phone.en.webp" alt="The Events calendar — iPhone" width="22%"></p>

**Every person is one structured record.** Facts Mars pulls from your conversations land in clear
groups — Basic Info, Family, Network, Business & Team, Tech & Tools, Mindset & Preferences — with the
person's conversations, events and insights one tab away.

<p><img src="./assets/wiki-contact-information-groups.en.webp" alt="A person's record with facts in information groups" width="76%"> <img src="./assets/wiki-contact-information-groups.phone.en.webp" alt="A person's record — iPhone" width="22%"></p>

**All of it stays browsable.** Every person you have told Mars about, in one list ordered by your
latest interaction, each with the line that says where the relationship currently stands.

<p><img src="./assets/wiki-relationship-list.en.webp" alt="The relationship list with one summary line per person" width="76%"> <img src="./assets/wiki-relationship-list.phone.en.webp" alt="The relationship list — iPhone" width="22%"></p>

*Screenshots of the live product on the web and iPhone, running on a demo account with fictional data.*

---

## The problem it solves

Everyone you meet who could matter — an investor introduced at a conference, a mentor who answered
your question, a customer who paid once — arrives through a chat app and then decays there. You
remember the person for a week. After a month you remember a name. After a quarter you have to scroll
back through a year of messages to reconstruct what you owe them and what they said they would do.

Relationship maintenance fails for a boring reason: the record-keeping cost is paid up front, every
time, by you. Marsdata moves that cost to the machine.

## What it actually does

### Every person becomes a structured record

Tell Mars about someone — or forward a conversation — and it builds one record per person: typed
fields, a dated interaction log, a ledger of what was given and received, and a full history of every
change. Each detail is its own field, so editing one changes only that one, and deleting one leaves
the person and everything else intact.

### It spots opportunities and risks before you miss them

As you chat or upload meeting transcripts, Mars picks out opportunities, risks and important signals
for the people involved. Each one sits on that person's Insights tab with its evidence chain — the
original quotes and the conversation they came from — and filters by type and status, so the
opportunity you need is not buried in the list.

<p><img src="./assets/filter-relationship-insights.en.webp" alt="A contact's Insights tab with the type filter open" width="76%"> <img src="./assets/filter-relationship-insights.phone.en.webp" alt="Filtering a contact's insights — iPhone" width="22%"></p>

*Live product · fictional demo data.*

### It reads the conversations you already have

Send a screenshot of a chat or a transfer and the facts inside settle into that person's record on
their own — including exchanges involving no money at all. You do not restate what already happened;
you forward it. Every fact keeps its source: a person's Conversations tab lists every chat and
meeting transcript that mentions them, one tap from the original words.

<p><img src="./assets/wiki-contact-conversations-history.en.webp" alt="A person's Conversations tab listing every chat that mentions them" width="76%"> <img src="./assets/wiki-contact-conversations-history.phone.en.webp" alt="A person's Conversations tab — iPhone" width="22%"></p>

*Live product · fictional demo data.*

### It answers instead of asking

The welcome screen opens with analysis already done: who has gone quiet, which promises are still
open, who among the people you just met is worth following up with. Mention a person with `@` in chat
and Mars reads their structured record — the fields, the recent interactions, the ledger — so a detail
you corrected a minute ago is reflected in the very next answer.

## What it can handle

| | |
|---|---|
| **Memory** | Five kinds of knowledge extracted automatically from conversation — relationships, memories, experiences, journals and skills — with no manual entry |
| **Inputs** | Fully multimodal: text, images, video, voice messages, and documents including PDFs and spreadsheets; paste a link or share a screenshot |
| **Multi-step work** | Describe a goal and Mars decomposes it into steps, executes them autonomously, and reports at each checkpoint; Deep Mode for thorough analysis of strategy questions |
| **Data sources** | Douyin and WeChat Channels livestream and short-video analytics, plus any website through its cloud browser |
| **Languages** | English, 简体中文, 繁體中文（香港）— across the app, the site and the relationship views |
| **Platforms** | Web on any modern browser, installable as a PWA, and a native iOS app |

## Privacy

All data is stored in your own private cloud space with per-user isolation. Mars follows the GDPR
standard for how data is collected, processed and protected, and never sells or shares your data,
person profiles, or conversation history with anyone.

Every screenshot in this repository is the live product running on a demo account. The data is
fictional and identifying values are masked. No real user's information appears anywhere here.

## Questions

Ask in **[Discussions](https://github.com/Mars-CRM-Agent/marsdata-ai/discussions)** — that is the
right place for "can it do X", "how does Y work", and "why did it answer Z". Answers are public so the
next person with the same question finds it.

Common ones are already answered in the **[FAQ](./FAQ.md)**. Bugs and feature requests go to
[Issues](https://github.com/Mars-CRM-Agent/marsdata-ai/issues/new/choose).

## Links

- **Product** — [marsdata.ai](https://marsdata.ai)
- **Changelog** — [what shipped, release by release](https://github.com/Mars-CRM-Agent/marsdata-changelog)
- **Pricing** — [marsdata.ai/pricing](https://marsdata.ai/pricing)
- **Privacy policy** — [marsdata.ai/privacy](https://marsdata.ai/privacy)
