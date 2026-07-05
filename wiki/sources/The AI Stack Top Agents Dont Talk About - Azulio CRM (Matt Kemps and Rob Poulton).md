---
type: source
original: "[[Clippings/The AI Stack Top Agents Dont Talk About - Azulio CRM (Matt Kemps and Rob Poulton).md]]"
author: "[[Matt Kemps]]"
published: —
ingested: 2026-07-05
tags: [ai, crm, lead-generation, real-estate-teams]
---

# The AI Stack Top Agents Don't Talk About — Azulio CRM Deep Dive

> [[Matt Kemps]] and [[Rob Poulton]], co-founders of [[Azulio]], demo their [[GoHighLevel]]-built AI real estate CRM for [[Gogo Bethke]]'s #teamgogo community — custom per-listing AI agents, agentic AI-to-AI transfers, conversation memory, digital farming, and AI social posting.

## Key Takeaways

- [[Azulio]] is a "done-with-you" AI real estate SAS platform built on the back end of [[GoHighLevel]], with "master mode" real estate tooling layered on top; the Azulio team builds out the CRM, automations, AI agents, website, IDX, and calendar for the agent rather than handing over a bare CRM.
- **Speed-to-lead under 15 seconds** through high-trust channels like iMessage; the pitch is that most teams lose in the gap between lead arrival and first real conversation, not from bad leads. Claimed outcomes: 400%+ ROI, ~40 hours saved per week per team.
- **Custom AI agents by listing**: each yard sign carries a [[GoHighLevel]] QR code tied to a property-specific AI agent that knows square footage, floor plans, builder, MUD/PID status, video location, and the agent's showing calendar; a buyer can text or call it and book a showing directly with the listing agent.
- **Custom AI agents by lead source**: the AI adjusts its conversation by lead type — FSBO, cash buyer, new construction, "Austin homes with pools" — pulling from a different knowledge base per source.
- **Agentic AI = AI-to-AI transfers**: a call can hand off seamlessly between agents with separate knowledge bases (e.g. an FSBO agent "Ren" transferring to cash-offer specialist "Jessica"), with business infrastructure built around the transfer; the human gets a notification that a cash offer went out without touching the conversation.
- **Conversation memory**: if a lead resurfaces months later, the AI remembers who they are, their lead type, and prior context, and continues the conversation. Fields (e.g. property address) auto-populate on the contact record.
- **Automation/AI coordination**: Azulio never fires a scheduled automation text on top of a live AI conversation — any response to Azulio turns off the drip workflow so the AI alone works the conversation and the consumer isn't double-messaged.
- **Digital farming** replaces postcards/door-knocking: agents get branded neighborhood property websites (fed IDX, recent closings, agent branding) and a tool that strips out **CSS** so [[Claude]] and GPT read only the keywords — the site is consumed by AI models within 5 minutes to 5 hours of going live and surfaces as free organic leads with no ad spend.
- **Website visitor tracking / skip tracing**: Azulio captures anonymous visitors (no form fill), skip-traces email/phone, checks DNC status, records a full session replay of cursor movement (desktop and mobile), device/browser/timestamp, event counts, and even finds the visitor's LinkedIn — surfacing leads to refer out via the [[teamgogo Map]].
- **Outbound AI calling** requires a TCPA opt-in; a recent [[GoHighLevel]] change allows the opt-in to live on a Meta lead form. Metrics cited: **~60% answer rate, ~82% appointment-set rate**. On a cell connection most people can't tell it's AI now.
- **Voice AI** uses [[ElevenLabs]] as the preferred provider — selectable voice, language, accent, gender, and a high-quality MP3 filter; top-converting voice is "Jessa." Full call transcripts and recordings are retained; team leads can listen to live calls for coaching and see dialer metrics (whether reps make their scheduled calls).
- **AI social media management** (Hootsuite-like, included in base tier): one post scheduled across all connected channels with per-channel customization (GBP, Facebook, Instagram, LinkedIn, TikTok, Snapchat), AI-written copy, social listening for trending hashtags, and unified stats.
- **Personal iMessage/Siri assistant**: every user gets an assigned agentic AI they text or dictate to via Siri that creates contacts, assigns tags/pipelines, blocks calendar time, and does market research — "life's too short to open another app."
- **Pricing (team go discount)**: **$5.95/mo** for everything except digital farming; **$9.95/mo** with digital farming. Retail is **$16.95/mo with a $5,000 setup fee** — the setup fee and retail pricing are waived for #teamgogo (mention "team go"). Setup takes **3–4 weeks**; results in **30–60 days** (~90-day outer bound). Weekly training: Azulio training Wednesdays 11am CST, open AI training Thursdays 11am CST.

## Quotes

> "CRM is a four-letter word. Starts with an F. And it's not fun." — [[Rob Poulton]]

> "You don't want to be chasing the tech. Remember last year it was ChatGPT, now it's [[Claude]], now it's Claude Code or Claude Co-work. It's going to be something else next year. Truth is, you all shouldn't really care... what you want to do is help folks connect." — [[Rob Poulton]]

> "Most teams are not losing because of bad leads. They're losing in the gap between the lead arriving and the first real conversation. We built Azulio to eliminate that gap." — [[Rob Poulton]] (from bio)

> "I spent a total of 15 minutes actually doing work to get... 5.8 million in volume." — [[Matt Kemps]]

> "It doesn't feel like a cold call now because I know what they did and what they were interested in... I'm not guessing." — [[Matt Kemps]]

> "Let the conversation and the automation of the day-to-day process be generated by AI, but you should show up as a human. Those agents who can do that part of the job are going to win every day." — [[Gogo Bethke]]

## Wiki Pages Updated
- [[entities/Azulio]] — deepen: full feature set (per-listing & per-lead-source agents, agentic transfers, conversation memory, digital farming, voice/social/iMessage AI), pricing ($5.95/$9.95 team-go vs $16.95 + $5k retail), setup timeline (3–4 wks), metrics (60% answer / 82% appt), GoHighLevel foundation, ElevenLabs voice
- [[entities/Matt Kemps]] — CEO/co-founder of Azulio; team lead of Lone Wolf Realty Group (EXP), North Austin/Georgetown, top-1% by volume; teaches Thursday open AI training
- [[entities/Rob Poulton]] — co-founder of Azulio; ex-senior director at CoreLogic (built Core AI), prior Microsoft turnaround and Clear Capital/Freddie Mac uptime work; agent-attraction sponsor at EXP
- [[concepts/AI for Real Estate]] — agentic AI-to-AI transfers, conversation memory, CSS-stripping for AI model indexing, digital farming, speed-to-lead
- [[concepts/Lead Generation]] — digital farming via AI-indexed keyword pages, anonymous-visitor skip tracing, outbound AI calling with TCPA opt-in, open-house pixel capture
