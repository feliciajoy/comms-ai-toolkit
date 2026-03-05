# Comms AI Toolkit

**Claude-powered communications workflow tools for media monitoring, briefing generation, message tracking, and rapid response.**

Built by [Felicia Joy](https://www.chicagobooth.edu/research/roman/who-we-are/phd-students/felicia-joy) — Behavioral Scientist, PhD Candidate at Chicago Booth, and former EVP at Edelman.

---

## The Problem

Communications teams at fast-moving organizations run on workflows that are manual, fragmented, time-intensive, and dependent on tools that tend to lack interoperability. Press clips get reviewed but aggregate insights may not be obvious. Briefing docs get assembled under pressure from scattered sources. Coverage data sits in dashboards that tell you what happened but not what it means or what to do next. And when a story breaks, the response chain depends on whoever happens to be watching.

These are not only technology problems. They are also **workflow design problems** — and solving them requires understanding both the technical automation layer and the human behavioral layer that determines whether tools are robustly used.

## The Approach

This toolkit applies a behavioral science methodology to Claude-powered communications automation:

1. **Decompose** existing workflows into their constituent behavioral steps
2. **Identify** the precise points where AI creates the most value
3. **Design** technical specifications to automate those steps using Claude
4. **Script** implementation intentions that integrate new tools into existing daily behavioral routines so adoption is durable, not aspirational

Each tool below includes both the technical architecture and a behavioral adoption design because a tool unused or inadequately used is not a solution.

---

## Tools

### 1. Message Pull-Through Tracker
**Status: In Development**

Measures how effectively an organization's key narratives appear in earned media coverage. Unlike keyword-matching tools, this uses Claude to assess whether journalists understood and conveyed the intended narrative, not just whether they repeated specific words.

**How it works:**
- Define 5-6 key organizational narratives with supporting message pillars
- Ingest press coverage (articles, transcripts, broadcast mentions)
- Claude analyzes each piece for narrative presence, prominence, framing, and sentiment
- Outputs a structured pull-through scorecard with trends over time

**Behavioral adoption design:**
- Integrates into existing weekly coverage review meetings rather than creating a new workflow
- Output format designed to match how comms leaders already consume data (executive summary + detail)
- Trigger: when the weekly coverage report is generated, pull-through analysis runs automatically

---

### 2. Daily Press Clips Digest
**Status: In Development**

Replaces the manual morning routine of logging into MuckRack or Cision, scanning dozens of articles, and deciding what matters. Delivers a formatted, prioritized briefing, with aggregate insights, to Slack each morning -- including developments on the journalists behind the news.

**How it works:**
- Monitors defined source list via RSS feeds, news APIs, relevant Substacks
- Claude filters for relevance, categorizes by topic, tags sentiment, and assesses priority
- Generates a formatted morning briefing with executive summary, categorized clips, and recommended actions
- Pushes to Slack on a daily schedule

**Behavioral adoption design:**
- Delivered to the channel the team already checks first thing in the morning
- Format mirrors existing briefing conventions so there is no learning curve
- Trigger: automated daily delivery at a set time, replacing the manual scan

---

### 3. Spokesperson Briefing Generator
**Status: In Development**

Produces comprehensive spokesperson prep documents by synthesizing background materials, recent coverage, reporter context, and key messages into a single briefing.

**How it works:**
- Inputs: reporter name, outlet, topic, interview format, recent coverage context, key messages
- Claude generates a complete prep doc including reporter background and past coverage tendencies, anticipated questions (friendly and hostile), key messages with bridging language, landmines to avoid, and suggested sound bites
- Output formatted as a clean, printable document an executive can review in 10 minutes

**Behavioral adoption design:**
- Replaces the most stressful manual workflow in comms: the last-minute briefing scramble
- Designed for the moment of highest motivation to adopt (interview prep under time pressure)
- Trigger: when a media engagement is confirmed, the briefing generation process kicks off

---

### 4. Rapid-Response Monitoring System
**Status: Architecture Phase**

Configurable alert system that notifies the right team members the moment a high-priority story breaks, with context and suggested initial response framing.

**Architecture:**
- Continuous monitoring of defined source list and social channels
- Claude assesses severity, categorizes by topic and stakeholder impact
- Routes alerts to specific team members based on configurable rules (beat, severity, region)
- Includes initial context summary and suggested response framing

**Behavioral adoption design:**
- Alert routing matches existing team responsibilities rather than requiring new ownership structures
- Severity calibration prevents alert fatigue (the primary failure mode of monitoring systems)
- Trigger: story publication or significant social mention above severity threshold

---

### 5. Internal Communications Workflow Tool
**Status: Architecture Phase**

Streamlines drafting, review, and distribution of all-hands content, FAQs, and leadership messages.

**Architecture:**
- Template-driven content generation with Claude for first drafts
- Structured review workflow with version tracking
- Multi-channel distribution (email, Slack, intranet) from a single interface

---

### 6. Comms Automation Playbook
**Status: In Development**

A living document that captures the methodology, decisions, and outcomes for every tool built — designed to be replicable by other teams.

For each tool, the playbook documents:
- **What** was built and why
- **How** the existing workflow was decomposed
- **Where** AI intervention creates the most value
- **How** the behavioral adoption layer was designed
- **What** impact the tool has had on team throughput and outcomes
- **How** the approach can be adapted for other functions

---

## Methodology

This work is informed by research on implementation intentions (Gollwitzer, 1999), choice architecture (Thaler & Sunstein, 2008), and my own doctoral research on conversational receptiveness in organizational contexts at the University of Chicago Booth School of Business.

The core principle: **sustainable workflow change is not about willpower or training alone — it is about designing the environment and the system so the new behavior becomes the path of least resistance.**

---

## About

I am a behavioral scientist and communications strategist building AI-powered systems that transform how organizations operate. My PhD research at Chicago Booth uses NLP and experimental methods to study how language shapes organizational outcomes. Before Booth, I worked in corporate communications and management consulting, advising Fortune 500 C-suite leaders.

- [Chicago Booth Profile](https://www.chicagobooth.edu/research/roman/who-we-are/phd-students/felicia-joy)
- [LinkedIn](https://linkedin.com/in/feliciajoy)
