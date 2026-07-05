---
type: concept
tags: [ai, productivity, marketing, lead-generation, real-estate]
sources: ["[[AI for Real Estate Professionals — Intelligence Briefs and Client Avatars (Thomas Heimann)]]", "[[Azulio — AI CRM and Digital Farming (Matt Kemps and Rob Poulton)]]", "[[Niche Finder Live Training — Gogo's AI Second Brain (Gogo Bethke)]]", "[[GoGetEm Roundtable — Revenue Share Mechanics and the Niche Finder (June 2026)]]", "[[eXp Tools Update — The Hub, my eXp, Mira AI and TeamGogo Map (Kristy Waker)]]", "[[AI Leverage — Build Your Personal AI System (Thomas Heimann)]]", "[[The AI Stack Top Agents Don't Talk About — Azulio CRM Deep Dive (Matt Kemps and Rob Poulton)]]", "[[ChatGPT is a Conversation. Claude is a Command Center. (Carrie Soave)]]", "[[Master Your Copywriting & AI Brand Voice (Gogo Bethke)]]"]
updated: 2026-07-05
---

# AI for Real Estate

How Gogo Bethke and #teamgogo guest experts apply AI — assistants, custom GPTs, agents, and "second brains" — to marketing, lead generation, and operations.

## Core Idea

AI is moving from chatbots you operate to agents that operate for you. The agents who adopt it early and feed it good inputs ("garbage in, garbage out") get a compounding, hard-to-catch lead. [[Gogo Bethke]] herself built the [[TeamGogo map]] and a website using Claude, and runs her own AI "second brain."

## Frameworks / Tools

### Three eras of AI ([[Thomas Heimann]])
1. **Chatbots** — you do the work.
2. **Custom agents** — you guide the work (e.g., Claude Cowork).
3. **Agentic AI** — agents do the work and hand off to each other ("swarms").

### The three foundation documents ([[Thomas Heimann]])
- **Personal Intelligence Brief** — who you are, values, story, voice. Heimann built his by dictating hours of his life story on walks (Plaud recorder), transcribing, and having AI distill it — grew from 3 to ~30 pages; re-versioned every ~3 months. "The intelligence brief becomes the backbone."
- **Business Intelligence Brief** — brand, market, USP, systems. **One per business** (investment properties, title, AI business) so context doesn't become a "mishmash."
- **Client Avatar** — a named persona with backstory, financials, fears, desires, aspirations; the fears/desires are the "psychological buttons you push in your messaging." Build a *separate* avatar for buyers vs. sellers, even per-listing. **Avatar-building workflow (3 steps)**: (1) market-intelligence report for the area (3-yr trends) → (2) ideal-customer identification → (3) synthesize into the avatar. Deployed inside a custom GPT/project.

### Projects segregate memory ([[Thomas Heimann]])
- Both ChatGPT and Claude **Projects** are blank slates that see only their uploaded files and their own chats — businesses/health/personal never co-mingle. Upload briefs + avatar into a project to give it context.
- **Markdown over Word for machines**: download briefs in *both* `.docx` (humans) and `.md` (AI) — markdown uses far fewer tokens and parses more easily. This "markdown = token efficiency" principle recurs across every guest expert.

### Model selection & cost economics ([[Thomas Heimann]])
- **DeepSeek** V4 (Pro/Flash) is claimed at ~Claude Opus quality for ~1% of the cost. Reserve Opus for high-level consulting; run the 99% of routine agent work on cheap models. Heimann runs ~6 agents (incl. Hermes, Meet Sarah) on DeepSeek for **$142 for all of May**. He also invested $30K in local hardware (~2 TB memory) to run local LLMs with no API fees.

### Model selection
- Claude **Sonnet** for fast everyday work/content, **Opus** for high-level reasoning/big decisions, **Haiku** for simple fast tasks. Use ChatGPT/Claude "Projects" to segregate memory and avoid confusion.

### Gogo's "second brain" / Niche Finder
- The [[Niche Finder]] is Gogo's AI second brain — her ~15 years of trainings, podcasts, and content embedded and linked to Claude. A 10-question form returns a niche statement, Instagram bios, top-8 marketing ideas, an SEO plan, a 12-week blog calendar, and a day-by-day 90-day plan ($24/report). New reality: AI search (ChatGPT, etc.) now reads social posts, not just websites — so niche-keyword discipline on socials drives AI recommendations.

### Claude as a Command Center ([[Carrie Soave]])
"ChatGPT is a conversation, Claude is a command center." ChatGPT answers and generates but *you* copy-paste — you are the bottleneck; it is assistance, not infrastructure. Claude "adds infrastructure" and takes action inside your apps.
- **Five layers of Claude**: (1) Claude chat + connectors + skills; (2) Claude in Chrome (browser extension that sees/clicks what you would); (3) [[Claude Cowork]] (desktop AI employee with full file-system access); (4) Claude Dispatch (control Cowork from your phone); (5) Claude Code (terminal agentic coding). Most people only know layer 1.
- **Autonomy Spectrum (L0–L3)**: **L0** chatbot (type/respond, copy-paste — where most people live); **L1** assistant (connectors read data, draft outputs); **L2** agentic (Cowork + Dispatch plan/execute/deliver multi-step work); **L3** fully autonomous (scheduled agents running without you; AI as governance layer).
- **Operators vs. Spectators**: operators build scale without headcount, own infrastructure, let AI execute while they govern, and compound leverage; spectators rent tools, patch gaps, react, and manually copy-paste. "I don't teach AI. I build operators."
- **Cowork folder structure**: a `Claude Cowork` folder with `about me`, `outputs`, `projects`, `templates` subfolders. The `about me` folder holds markdown files (about me, org chart, writing style) that Claude generates by interviewing you; good outputs become reusable templates.
- **Global instructions** (Cowork-tab settings): e.g. "before every task read every file in about-me.md; never read outputs/templates unless pointed to a specific file" — because every unnecessary read costs tokens/money. **Markdown = token efficiency** (fewer characters, prevents context rot).
- **Connectors** (100+: Gmail, Drive, Calendar, Slack, HubSpot, Close, Stripe, Canva, Figma, full Microsoft suite, etc.) let Claude auto-pull the right data source and act *inside* another app.
- Cost-of-manual-work math: 15+ hrs/week on AI-handleable tasks ≈ $78K/yr, over $200K with lost deals. "Markets reward infrastructure, not effort." "You're either going to build AI or you will work for AI."

### Custom-GPT brand voice & prompt formula ([[Gogo Bethke]], from Master Your Copywriting)
- [[Kristy Waker]] built a shareable **custom GPT ("My AI Brand Voice")** on Gogo's account: paste 3–5 pieces of your own writing (emails, posts, Zoom transcripts) via "Fast-Track Voice Setup," or a ~20-question "Guided Interview" if you have no content, → outputs a brand-voice profile you paste into ChatGPT → Personalization → Custom Instructions so every chat writes in your voice.
- **Lou's prompt formula**: give it *who I am / what I do / where / who I target / my tone / their pain points*. "Write a warm, story-driven listing for a 3/2 bungalow in Logan Square for first-time buyers who care about walkability and natural light" beats "write a listing for a 3-bed house."
- **AI tells to strip out**: em dashes (the "AI signature"), buzzwords (leverage, optimize, unlock your potential), uniform paragraph lengths, "in today's fast-paced world," "in conclusion." Humans mix sentence lengths, use contractions, add opinions/stories/local references.
- **3-step human-edit workflow**: (1) give context/audience/tone/goal → (2) generate rough draft → (3) human-edit for readability, voice, specificity, and a single explicit CTA. Gogo prompts by voice ("I hit the microphone, I talk to it like it's my best friend"), and **maintains the GPT over time** — correcting it live ("no, I'd never say that") so it keeps learning. See [[Social Media and Email Marketing]] and [[Personal Branding]].

### Agentic CRM / digital farming ([[Azulio]])
- **Per-listing AI agents**: each yard sign carries a QR code tied to a property-specific agent that knows square footage, floor plans, builder, MUD/PID status, and the showing calendar — a buyer texts/calls it and books directly. **Per-lead-source agents** adjust conversation by type (FSBO, cash buyer, new construction) from a different knowledge base each.
- **Agentic AI-to-AI transfers**: a call hands off between agents with separate knowledge bases (an FSBO agent transferring to a cash-offer specialist); the human just gets a notification. **Conversation memory**: a lead resurfacing months later is remembered with prior context; fields auto-populate.
- **Digital farming** replaces postcards: branded neighborhood property sites fed IDX + closings, with a tool that **strips out CSS so Claude/GPT read only the keywords** — indexed by AI models within 5 min–5 hrs and surfacing as free organic leads with no ad spend.
- **Outbound AI voice** ([[ElevenLabs]]) needs a TCPA opt-in (now allowed on a Meta lead form); cited ~60% answer / ~82% appt-set. Speed-to-lead under 15 seconds via iMessage. Built on [[GoHighLevel]]; #teamgogo pricing $5.95/$9.95/mo.

### eXp's native AI ([[eXp Realty]])
- **Mira** — eXp's AI assistant (built on ChatGPT, eXp-exclusive) in my eXp and the Hub; answers natural-language questions about your own production, downline, and revenue share (privacy by design — can't pull other agents' numbers).

## Gogo's Take

> "I built a whole website, all of that, which blew my mind... but I used up all of mine, and then Monday my team was like, oh, you were in the wrong cloud... So how do you know what does what?" — Gogo Bethke

AI is a force multiplier, not a replacement: "if you can put that human element back into the game, you're gonna be the agent who wins." But beware shiny-object syndrome — pick the tools that compound, and feed them good inputs.

## Related

- [[Thomas Heimann]]
- [[Carrie Soave]]
- [[Azulio]]
- [[Claude Cowork]]
- [[Niche Finder]]
- [[Social Media and Email Marketing]]
- [[Lead Generation]]
- [[Productivity]]
- [[Personal Branding]]
