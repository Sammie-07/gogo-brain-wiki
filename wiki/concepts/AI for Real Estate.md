---
type: concept
tags: [ai, productivity, marketing, lead-generation, real-estate]
sources: ["[[AI for Real Estate Professionals — Intelligence Briefs and Client Avatars (Thomas Heimann)]]", "[[Azulio — AI CRM and Digital Farming (Matt Kemps and Rob Poulton)]]", "[[Niche Finder Live Training — Gogo's AI Second Brain (Gogo Bethke)]]", "[[GoGetEm Roundtable — Revenue Share Mechanics and the Niche Finder (June 2026)]]", "[[eXp Tools Update — The Hub, my eXp, Mira AI and TeamGogo Map (Kristy Waker)]]", "[[AI Leverage — Build Your Personal AI System (Thomas Heimann)]]", "[[The AI Stack Top Agents Don't Talk About — Azulio CRM Deep Dive (Matt Kemps and Rob Poulton)]]", "[[ChatGPT is a Conversation. Claude is a Command Center. (Carrie Soave)]]", "[[Master Your Copywriting & AI Brand Voice (Gogo Bethke)]]", "[[The Circle Coaching — Niche Ownership, AI Execution Layer and Full-Service Delegation (de-identified)]]", "[[The Circle Coaching — Listings-First, the Open-House Two-Buyer System and the Value Ladder (de-identified)]]", "[[Optimizing Your Google Business Profile for Real Estate Agents (Kalie Kinsella)]]", "[[The Circle Coaching — Genius Zone, Delegation Systems and Building the Right Team (de-identified)]]", "[[AI SEO and Google Ranking for Listings (Kirby Chan)]]", "[[The Circle Coaching — Consistency, Partnership Dissolution, Team Profitability and Golden Handcuffs (de-identified)]]", "[[The Five Ingredients to Lead Nurture Success in Lofty (Adam Gillespie)]]"]
updated: 2026-08-13
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

## AI as an Execution Layer & the Second Brain (Circle coaching)

*Source: de-identified [[The Circle|Circle]] coaching (NDA — no member specifics). [[Gogo Bethke]]'s generalizable teaching only.*

### AI as an execution multiplier

Use Claude/AI not as a chatbot but as the layer that *executes* what you'd otherwise never get to:
- **Dictate a raw story → get the 5 bullets** that hit the point, then talk to camera from those bullets for a **<90-second reel**. Talk from the heart with a few bullet points; don't script.
- **Strategy doc → a batch of niche SEO blog articles** (e.g., a 12-week batch, one keyword-targeted post per week) to rank locally.
- **Generate "expert" Q&A questions** when live questions aren't coming in organically — seed a recurring Instagram Live Q&A so it never stalls.

### Two publishing guardrails + prompt discipline

1. **Read it / make it sound like you.** Anything you put out represents you.
2. **Remove the AI signature** — strip the tells (em dashes, buzzwords, uniform paragraph lengths).
3. **Prompt discipline:** give full context on the goal *first*, or AI will justify your existing framing instead of doing the reframing work you actually need.

### The AI "second brain"

Gogo built an AI "second brain" trained on **~15 years** of her knowledge *and* her voice; members chat with it any time for after-hours questions. Two access models illustrate the economics:
- The [[Niche Finder]] runs **free via your own AI** (with provided prompt verbiage) — or **paid via her trained brain**, priced because it consumes *her* data.
- Members are encouraged to **build their own AI brain** by feeding it their own coaching transcripts — your transcripts become your compounding asset.

### Shared-drive default for team AI output

When a team runs one AI account, **set a shared-drive folder as the default save location** so the whole team gets automatic access with no per-file requests — and have assistants join the setup call to implement it.

### Contract diffing & backwards planning

Two more uses that put AI to work in the back office. **Diff contracts:** paste your own version *and* the attorney's returned draft into an AI assistant and ask it to **"tell me the differences so I don't miss it"** — it surfaces every change between the two so nothing slips through on a redline you'd otherwise skim. And use AI for **backwards business-planning prompts** — hand it the take-home target and let it work back to the required transactions, agent count, and activities (the same reverse-engineering logic Gogo applies to team economics; see [[Real Estate Teams]]).

## AI Search & "Search Everywhere Optimization" (Kalie Kinsella)

*Source: [[Optimizing Your Google Business Profile for Real Estate Agents (Kalie Kinsella)]]. [[Kalie Kinsella]] ("That Google Girl"), #teamgogo / GoGet'Em training.*

**Gemini and AI search changed how buyers search.** Instead of two-word queries, people now type **long, specific prompts** into Gemini and AI-powered search — bundling **relocation + new construction + commute time + lifestyle** into a single ask. To surface in those results, a profile must show **hyper-local, service-specific proof**, not generic "top realtor" claims. When AI answers a real estate question, **Google checks the [[Google Business Profile]] first, then the website, then the reviews** — so the whole trust chain has to be consistent and complete.

**"SEO" now means "Search Everywhere Optimization"** (credited to trainer Ryan McClure): being on one platform isn't enough when AI models pull signals from everywhere.

> "It's no longer search engine optimization. It's search everywhere optimization. If you're not everywhere, you're kind of nowhere on a digital level." — Kalie Kinsella

**Google now ranks confidence and validity, not businesses.** Its ~June 2026 local relaunch runs roughly **30× more verification checks**, so the AI-era ranking currency is a **legitimate, consistent, actively-fed identity** across profiles. This is the same shift behind Gogo's [[#Gogo's "second brain" / Niche Finder|Niche Finder]] insight that **AI search now reads social posts, not just websites** — niche-keyword discipline everywhere is what earns the AI recommendation. The execution playbook lives in [[Lead Generation#Google Business Profile — Build It, Prove It, Feed It (Kalie Kinsella)|Build it, Prove it, Feed it]]; the consistency rules in [[Personal Branding#Brand Syndication for Search (Kalie Kinsella)|brand syndication]].

## Keyword Responder & Team Dashboard (Circle coaching)

*Source: [[The Circle Coaching — Genius Zone, Delegation Systems and Building the Right Team (de-identified)]]. Private [[The Circle|Circle]] coaching, de-identified — Gogo's generalizable teachings only.*

Two small automations that punch above their weight:

### Automated DM / keyword responder

An automated DM/keyword responder **captures inbound "buy" / "sell"** intent — including **typos and near-misses** of those words — and **routes each lead** to the right destination (buyer calendar vs. seller calendar). Because real people misspell, the trigger set has to be forgiving, not literal. **Test it with the team first:** trigger every keyword variation yourself and confirm the full sequence fires before you rely on it in the wild. (Same buyer/seller split and end-to-end testing discipline as the [[Lead Generation#Buyer/Seller Keyword Auto-Capture|keyword auto-capture]] play.)

### Team dashboard + automated weekly progress summary

Run the team on a **shared dashboard** and wire an **automated weekly progress summary to the leader** so status arrives without anyone chasing it. The point isn't surveillance — it's **momentum**: the summary **celebrates the small completed tasks** (booked the CPA meeting, filed the LLC, scheduled the weekend opens), because visible small wins are what keep people moving.

> "The little things are the make-it-or-break-it."

This is the AI/systems side of the same accountability loop described in [[The Circle#The team-dashboard momentum loop (de-identified)]].

## AI SEO & Getting Cited by AI / GEO (Kirby Chan)

*Source: [[AI SEO and Google Ranking for Listings (Kirby Chan)]]. [[Kirby Chan]] (Toronto-area agent; "AI SEO Boot Camp"), #teamgogo / [[GoGet'Em Community]] guest training.*

This is the offense to [[#AI Search & "Search Everywhere Optimization" (Kalie Kinsella)|Kalie Kinsella's]] defense: where Kinsella makes your [[Google Business Profile]] consistent enough to be *trusted* by AI search, [[Kirby Chan]] engineers the content the AI actually *reads and cites*. Both answer the same shift — AI now reads everything, not just your website.

### Google's "Helpful Content" update — helpfulness beats authority

Google's ranking currency moved from authority/backlinks to **genuine helpfulness plus reader behavior** (dwell time / low bounce). Consequences:
- A new, thin site can **outrank Zillow/Redfin** on a specific query if the article actually helps the reader and holds them on the page.
- **AI-written content is not penalized** — Google doesn't care who (or what) authored it; it rewards whether the content helps and whether readers stay. This unlocks AI-scale content production without SEO risk.
- The play: **"Google real estate"** — own the SERP for one keyword cluster (e.g., "Richmond Hill downsizing") across website, blogs, videos, and AI-Overview citations, one niche service page at a time.

### Parasite SEO — write for the machines, not the humans

**"Parasite SEO":** post daily self-promoting content ("best/top agent in [city]") on high-authority third-party platforms — **LinkedIn, Rate My Agent**, etc. No human reads these posts. But **ChatGPT, Gemini, and Claude crawl them and cite you** when a user asks "who's the best agent in [city]."

> "Who's going to read it? Nobody. AI reads it." — Kirby Chan

Guardrail: don't scam the system (fake reviews, bought links). *"It's not worth scamming Google. They're too powerful — if they ban your page, it's all gone."*

### GEO — be the agent the AI recommends

The funnel goal is **GEO (Generative Engine Optimization): get cited by AI.** Buyers increasingly ask ChatGPT/Gemini/Claude for an agent and **call directly without ever visiting a website** — *"ChatGPT told me to call you."* Being the AI-recommended name is the new page-one. This is the same reality behind Gogo's [[#Gogo's "second brain" / Niche Finder|Niche Finder]] insight (AI search reads social posts) and Kinsella's trust chain (Google checks GBP → website → reviews before it answers).

### The AI video pipeline (~5 min/video)

Video production collapses to an assembly line: **[[Carrie Soave|Claude]] writes the script → [[HeyGen]] AI twin (or Captions.ai) voices/reads it → an AI editor adds B-roll.** ~5 minutes per finished video.

> "You don't make videos anymore. You go to AI, and AI makes your videos. AI is your ultimate director of operations." — Kirby Chan

**Brand-protection rule:** run the AI-twin videos on **separate niche Instagram accounts**, so your **main personal brand stays 100% real** (a human on camera). The AI twin scales the niche funnels; it never impersonates you on your primary brand.

### Foreign-language SEO — compete where no one is

Write content — and stand up a separate site / [[Google Business Profile]] / Instagram — **in a second language** (Portuguese, Chinese, etc.) for **near-zero competition** and far faster ranking. AI writes and voices it for you.

> "If you speak a different language, start writing content in that language. There's no competition there." — Kirby Chan

## Back of House vs. Front of House — the Human in the Loop (Adam Gillespie)

*Source: [[The Five Ingredients to Lead Nurture Success in Lofty (Adam Gillespie)]]. [[Adam Gillespie]] (Denver eXp Realtor + AI/CRM coach, 2024 Inman AI Award), a #teamgogo / [[GoGet'Em Community]] guest hosted by [[Alexis Carrera]].*

Adam is "one of AI's biggest fans" (certified prompt engineer; certified in AI ethics, ML, and LLMs) and yet **refuses to let AI talk to his leads.** The doctrine:

> "AI is not your relationship creator, you are… AI should be back of house. Most agents want the AI in the front of the house." — Adam Gillespie

- **The restaurant model:** AI belongs in the *back of house* (the repetitive, mundane work); the human is *front of house* (meeting clients, building relationships, closing). Agents chasing AI voice dialers and chatbots have it backwards.
- **The public does not want AI, even though you do.** Entrepreneurs like AI because they see what it does for the business; "the rest of society thinks it's the end of the world." The only two industries where AI voice answering is *welcome* are cable and cell-phone companies "because nobody likes to talk to them." *"If you don't want to be contacted by AI, why should your clients want to be contacted by AI?"*
- **The counter-trend:** since 2022, the human craving for human touch is claimed to be the highest in 50 years — so a real human on the phone is a *differentiator*, not a cost.
- **The empty-metric tell:** when someone brags "my Lofty AI contacted X people and had Y conversations," ask how many became appointments → signed agencies → closed deals. "They never respond, because the answer is zero."
- **The workflow:** use AI to *write the messaging* in your voice, let the automation *initiate* the response, then **jump in as the human in the loop** the moment a lead raises their hand — enforced in the CRM by the [[Lead Generation#The 5-Ingredient Nurture System — "Success Pie" (Adam Gillespie)|auto-pause rule]] that stops every automation the instant a real conversation starts. This is the same "show up as a human, let AI run the day-to-day" conclusion [[Gogo Bethke]] draws about the [[Lead Generation#AI-Powered Lead Generation — Azulio Stack (Matt Kemps and Rob Poulton)|Azulio stack]].

## Clone Yourself — the Personal AI Execution Layer (Adam Gillespie)

*Source: [[The Five Ingredients to Lead Nurture Success in Lofty (Adam Gillespie)]].*

The high-leverage move isn't using the CRM's canned AI — it's **cloning yourself into a custom GPT** trained on your voice, story, and goals (Adam has run his since ~2022). What his clone does:
- **Drafts long replies "cussing and sounding just like me"** in ~3 minutes instead of 20–30 (e.g., responding to a prospect's 5-page email from the call transcript + the email).
- Writes **blogs and YouTube scripts** (any non-tutorial video on his channel "was written with my AI clone"), and runs **SWOT analyses** on his businesses — no canned responses because "it knows everything about me, what my real goals are."
- The payoff is **compounded time savings** — the same "buy back your time" thesis as the [[Productivity]] leverage hierarchy.

**Custom GPTs also erase the language barrier in nurture.** Adam runs **duplicate smart plans tagged by language** (English/Spanish) that fire the right one off a tag, plus a custom GPT trained on **informal Russian** and **[[HeyGen]]** video translation to serve a repeat client in his own language: "please communicate the way you want to communicate. I got you." (Same clone-your-voice principle as [[Kristy Waker]]'s "My AI Brand Voice" GPT in the [[#Custom-GPT brand voice & prompt formula (Gogo Bethke), from Master Your Copywriting|brand-voice section]] above — and exactly what [[Alexis Carrera]] is mid-build on via [[Claude]] + ChatGPT to attach to her own Lofty.)

**Vibe-coding custom tools.** Adam built a **branded mortgage calculator** (pulls average tax/insurance by zip via a free API, embedded Calendly CTA) by vibe-coding it on ChatGPT and dropping it into Lofty's custom-HTML — escaping the template look while keeping a lead-capture call to action. Decks built in **Gamma.app** from a single prompt (~5 min).

## Related

- [[Thomas Heimann]]
- [[Adam Gillespie]]
- [[Kalie Kinsella]]
- [[Kirby Chan]]
- [[Carrie Soave]]
- [[Azulio]]
- [[Claude Cowork]]
- [[Niche Finder]]
- [[Social Media and Email Marketing]]
- [[Lead Generation]]
- [[Productivity]]
- [[Personal Branding]]
