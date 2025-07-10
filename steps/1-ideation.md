# 🎯 Step 1: Validate Your Idea

<div align="center">

![Time](https://img.shields.io/badge/⏱️_Time-30_minutes-blue?style=for-the-badge)
![Difficulty](https://img.shields.io/badge/📊_Level-Beginner-green?style=for-the-badge)
![Tools](https://img.shields.io/badge/🛠️_Tools-ChatGPT-orange?style=for-the-badge)

</div>

## 📖 Quick Navigation

<details>
<summary><b>📚 Table of Contents</b></summary>

### 🎯 Core Validation Workflow
1. **[Finding Your Destination](#-part-i-finding-your-destination)** (5 min)
   - [Who The Hell Am I?](#-prompt-1-who-the-hell-am-i) - Self-discovery for meaningful ideas
   - [What Should I Build?](#-prompt-2-what-should-i-build-in-2-hours) - Generate achievable 2-hour ideas

2. **[Market Research Deep Dive](#-part-ii-picking-your-flight-path)** (20 min)
   - [Pain Point Discovery](#-prompt-3-pain-point--market-gap-discovery) - Find real problems people discuss online
   - [Competitive Analysis](#-prompt-4-competitive-landscape--whitespace-analysis) - Map the competition landscape
   - [Customer Willingness to Pay](#-prompt-5-who-actually-cares-enough-to-pay) - Evidence of budget allocation

3. **[Reality Check](#-prompt-6-are-you-the-right-person-for-this)** (5 min)
   - [Founder-Market Fit](#-prompt-6-are-you-the-right-person-for-this) - Your unfair advantages
   - [Advanced Techniques](#-prompt-7-from-prompt-monkey-to-conversation-beast) - Persona interrogation & bulk analysis

### 💡 Pro Tips
- **[Deconstruct Your Idea](#-side-quest-deconstruct-your-idea)** - JTBD framework
- **[Pain Point Matrix](#-what-to-do-with-the-output)** - Prioritization tool
- **[Competitive Differentiation Matrix](#-competitive-differentiation-matrix)** - Whitespace visualization

</details>

---

Luke just covered some core concepts around validating an idea, but for tonight: where do we start? Here's some prompts to help you out:

---

## 🧭 Part I: Finding Your Destination

> **⏰ Time:** 5 minutes  
> **🎯 Goal:** Figure out what kind of thing you want to build

### 💡 Prompt 1: Who The Hell Am I?

Let's start with some self-discovery to surface ideas that are personally meaningful.

**📋 Instructions:**
1. Go to your LinkedIn profile
2. Copy your entire work history
3. Paste it into ChatGPT with this prompt:

<details>
<summary><b>🔍 Click for Prompt</b></summary>

```
This is my profile of my work history. Now ask me a few questions about my personal life to flesh out who I am as a person and what unique gifts I might have to give the world.
```

</details>

---

### 🚀 Prompt 2: What Should I Build in 2 Hours?

Once you've got a better sense of yourself, let's generate some achievable ideas.

<details>
<summary><b>🔍 Click for Prompt</b></summary>

```
I'm in an idea workshop and have two hours to flesh out a proof-of-concept idea that would be fun and interesting, let me learn some AI tools, and result in something I'd be proud to share with family, friends, or my professional network. Quiz me about my interests, strengths, and motivations. Then give me 3–5 creative but achievable ideas I could start building right now.
```

</details>

---

## 🔬 Part II: Picking Your Flight Path

> **💡 Key Insight:** AI is great at spotting patterns in big piles of text—but it's not a strategist and doesn't actually know anything. This is why we validate specific assumptions, not whole ideas.

<details>
<summary><b>📚 Understanding Clever Prompting</b></summary>

Think of AI like a mirror reflecting public internet chatter. If your customers aren't talking online, the mirror's either blank or misleading. So before digging into analysis, make sure you've got a good guess about where your audience hangs out.

Ideas like "an accounting app for landlords" are really a stack of smaller guesses: landlords hate current tools, taxes stress them out, they'd pay for better, they're reachable via X channel. Each of those can be tested. The prompts in this guide are scalpels, not hammers—meant to test one assumption at a time so you build real confidence before spending money or writing code.

</details>

### 🎯 Side Quest: Deconstruct Your Idea

**Transform your idea into clear, falsifiable hypotheses using the Jobs to Be Done (JTBD) framework.**

> **🔑 JTBD Format:** "When [situation], I want to [action], so I can [outcome]."

**Example:**
> "When I need to build a multi-step LLM workflow, I want a no-code tool to visually connect prompts and models, so I can prototype fast without coding."

---

## 📊 Prompt 3: Pain Point & Market Gap Discovery

![Tool](https://img.shields.io/badge/🛠️_Tool-ChatGPT_Deep_Research-purple?style=flat-square)
![Calls](https://img.shields.io/badge/📞_Free_Tier-5_calls-yellow?style=flat-square)

**🎯 Goal:** Uncover real, high-priority problems your target audience is actively talking about online.

<details>
<summary><b>🔍 Click for Prompt</b></summary>

```
Act as a specialist Market Researcher and Qualitative Data Analyst. Your mission is to validate whether a significant, painful problem exists for a specific user group by analyzing their online discussions. You will identify market gaps based on their expressed frustrations and unmet needs.

**My Business Context:**
*   **My Idea in One Sentence:** [see idea description]
*   **The 'Job to be Done' (JTBD):**
*   **Hypothesized Target Audience:**
*   **Hypothesized Digital 'Watering Holes':**

**Your Task (Execute in this order):**

1.  **Identify Primary Pain Points:** Based on my JTBD, scan the hypothesized 'watering holes' and the broader internet. Identify and list the top 5-7 most frequently discussed pain points, frustrations, or problems related to this job. For each pain point, provide at least one verbatim quote from a user that exemplifies the problem.
2.  **Analyze Existing Workarounds:** For each identified pain point, describe the current solutions or workarounds that users mention. What tools are they "hacking" together (e.g., "I use Audacity for editing, Google Drive for storage, a spreadsheet for my release schedule, and PayPal for donations")? What are the expressed frustrations with these makeshift systems?
3.  **Surface 'Missing Feature' Signals:** Find specific discussions where users express a desire for functionality that does not exist or is poorly implemented in current tools. Look for phrases like "I wish could just..." or "Why isn't there a simple tool that does [X and Y]?". These are direct signals for market gaps.
4.  **Synthesize Market Gaps:** Based on your analysis in steps 1-3, write a summary paragraph identifying the top 3 potential market gaps. A market gap is an unmet or underserved need. Frame it as: "While numerous tools exist for podcasters, there appears to be a significant gap for a solution that specifically addresses [Pain Point 1] and [Pain Point 2] in a [adjective, e.g., 'simple,' 'automated,' 'integrated'] way."
5.  **Format the Output:** Present your findings in a structured report with clear headings for each section. Use markdown for formatting, especially for quoting users.

Before you begin, ask me to concisely describe my idea, e.g., "A simple, all-in-one platform for podcasters to manage production, distribution, and monetization."
```

</details>

### 📈 What To Do With The Output

Use a **Pain Point Matrix** to categorize and prioritize issues:

![Pain Point Matrix](https://github.com/user-attachments/assets/96fb0093-66a2-4bc2-95ee-69fb646877dc)

This turns AI output into clear, prioritized insight you can act on or share.

---

## 🏆 Prompt 4: Competitive Landscape & Whitespace Analysis

![Tool](https://img.shields.io/badge/🛠️_Tool-ChatGPT_w/_Web_Search-purple?style=flat-square)

**🎯 Goals:**
- Map key competitors
- Break down their strategy
- Find exploitable gaps in: Product, Pricing, Positioning

<details>
<summary><b>🔍 Click for Prompt</b></summary>

```
Act as a Senior Strategy Consultant and Market Analyst. Your task is to conduct a thorough analysis of the competitive landscape for my startup idea, with the ultimate goal of identifying strategic "whitespace" for a new entrant.

**My Business Context:**
*   **My Idea:**
*   **The 'Job to be Done' (JTBD):**
*   **Known Competitors:**

**Your Task:**

1.  **Identify & Profile Competitors:** If I provided a list, analyze those competitors. If not, identify the top 3-5 companies that currently serve the same JTBD. For each, provide a brief profile covering their primary product offering, their stated target audience (e.g., enterprise, SMBs, specific verticals), and their core value proposition.
2.  **Detailed SWOT Analysis:** For each competitor, conduct a detailed SWOT analysis (Strengths, Weaknesses, Opportunities, Threats). Be specific and use evidence where possible. For example, a 'Strength' could be "Extensive integration library with over 300 apps." A 'Weakness' could be "User reviews on Capterra frequently complain about the steep learning curve and poor customer support for lower-tier plans".
3.  **Product & Pricing Teardown:** For each competitor, analyze and describe their core product features and their complete pricing model. Detail the different pricing tiers, the key features unlocked at each tier, and any usage-based limits. How do they justify their pricing? What is the primary metric for their pricing (per-seat, per-contact, flat fee)?
4.  **Marketing & Messaging Analysis:** Analyze the tone of voice, key marketing messages, and imagery on each competitor's homepage. What specific pain points do they emphasize in their copy? What benefits do they promise? What is the core Unique Selling Proposition (USP) they are trying to communicate?
5.  **Synthesize the "Competitive Whitespace":** After analyzing all competitors, write a summary paragraph that identifies the "competitive whitespace." This is the clear, defensible opportunity for a new player. Frame your answer precisely: "The competitive landscape for [Your Market] is dominated by [e.g., complex, feature-rich platforms for sales teams]. However, there is a clear whitespace for a product that is, targets the underserved niche of, and is priced with a [e.g., flat monthly fee, freemium model, usage-based pricing] that aligns with this segment's needs.

Before you get started, ask me about my idea, my 'Job to be Done' (JTBD), and my Known Competitors.
```

</details>

### 📊 Competitive Differentiation Matrix

Use this table to highlight whitespace:

| Vector of Comparison     | Competitor A | Competitor B | Competitor C | Your Idea |
|--------------------------|--------------|--------------|--------------|-----------|
| Target Audience          |              |              |              |           |
| Core USP                 |              |              |              |           |
| Pricing Model            |              |              |              |           |
| Key Weakness (Reviews)   |              |              |              |           |
| Marketing Tone           |              |              |              |           |

---

## 💰 Prompt 5: Who Actually Cares Enough to Pay?

![Tool](https://img.shields.io/badge/🛠️_Tool-GPT--4-purple?style=flat-square)

**🎯 Goal:** Figure out who *really* has this problem—and who's already spending money or time to solve it.

<details>
<summary><b>🔍 Click for Prompt</b></summary>

```
Act as a Customer Insights Analyst and Market Researcher. Your primary objective is to synthesize a detailed Ideal Customer Profile (ICP) from public online data. Your secondary, and most critical, objective is to find concrete evidence of this ICP's willingness to pay for a solution to their problem.

**Your Task:**

1.  **Synthesize the Ideal Customer Profile (ICP):** Based on the language, roles, and context of the discussions in the provided communities, create a detailed ICP. Structure your response with the following sub-headings:
    *   **Demographics:** What can you infer about their professional role (e.g., "Senior Product Manager," "Solo Etsy Seller"), industry, and the size of the company they work for?
    *   **Psychographics:** What are their primary goals (e.g., "achieve a promotion," "increase their freelance income," "look more professional to clients")? What do they appear to value (e.g., "efficiency and time-saving tools," "beautiful design," "powerful analytics")?
    *   **Watering Holes:** Confirm or expand the list of online places where they actively discuss their work and tooling.
    *   **"Before" Scenario:** In a short paragraph, describe their life *before* the JTBD is solved. What specific frustrations and anxieties do they feel? Use their own words where possible.
    *   **"After" Scenario:** In a short paragraph, describe their desired outcome. What does success and relief look like for them after the job is done perfectly?
2.  **Find "Willingness to Pay" Signals:** This is the most critical part of your analysis. Scour the same online sources for any language that indicates a budget or a quantifiable financial pain associated with the problem. Search for specific evidence such as:
    *   **Mentions of Cost & Time:** "I'm wasting at least 5 hours a week on manual data entry," "This one mistake cost us a client," "I'd gladly pay up to $50/month for a tool that automates this."
    *   **Budget Discussions:** "What are you all using for [X]? My team's budget is around $100/seat." "Looking for a cheaper alternative to [Competitor]."
    *   **Frustration with Existing Tool Pricing:** "I can't believe [Competitor] charges an extra fee for that basic feature." "Their enterprise plan is totally unaffordable for a small business like mine."
    *   **Hiring for the Job:** Evidence of job postings on platforms like Upwork, Fiverr, or industry-specific job boards where people are paying freelancers to manually perform the "job" your product would automate.
3.  **Summarize the Evidence:** Provide a 1-2 paragraph summary of the evidence for willingness to pay. Conclude by rating the strength of this evidence as **Weak**, **Moderate**, or **Strong**, and provide a brief justification for your rating.

Before you begin, you need context! To get it, ask me to restate my Jobs-To-Be-Done, to list the top 2-3 most severe pain points I discovered from the previous prompt, and to list the 'watering holes' where I found the richest discussions of these pain points.
```

</details>

### 💵 Key Signals to Look For:
- ⏰ "This wastes X hours a week" (time = money)
- 😤 "$50/month for that?!" (pricing complaints)
- 💸 "My team's budget is $100/user" (budget convos)
- 👷 Hiring humans to solve the problem manually (Upwork/Fiverr posts)

---

## 🔍 Prompt 6: Are You the Right Person for This?

**🎯 Goal:** A gut check - is this your idea to run with?

<details>
<summary><b>🔍 Click for Prompt</b></summary>

```
Act as a seasoned Startup Coach and skeptical Venture Capitalist. I am a founder evaluating my personal fit with a potential business idea. Your role is to guide me through a structured self-reflection by asking me a series of probing, Socratic questions.

**Your Instructions:**
*   Do not provide answers, suggestions, or praise. Your only role is to ask the questions from the list below.
*   Ask me only **one question at a time**.
*   Wait for my complete response before you ask the next question in the sequence.
*   After I have answered all the questions, you will then synthesize my answers into a final, objective summary of my Founder-Market Fit, structured with two sections: "Potential Strengths & Unfair Advantages" and "Potential Gaps & Blind Spots."

**Begin the questioning now. Ask me the first question.**

---
*(The LLM will then initiate a turn-by-turn conversation, asking the following questions in order):*

1.  "Have you personally and repeatedly experienced the specific problem you are trying to solve for your target customer? Describe one of those situations in detail, including how it made you feel."
2.  "Why are you, specifically, the right person to solve this problem? What unique insight or perspective do you possess that an intelligent outsider might be missing?"
3.  "Beyond your personal experience with the problem, what specific skills, credentials, or expertise do you have that are directly relevant to building, marketing, or selling this solution?"
4.  "Describe your existing professional and personal network. Do you already know at least 10 people who fit your Ideal Customer Profile? Do you have connections to potential advisors, partners, or employees in this industry?"
5.  "On a scale of 1 to 10, where 1 is 'mild interest' and 10 is 'deep obsession,' how passionate are you about this specific problem and this specific customer group? Would you still be excited to work on this in five years, even if it's a difficult struggle?"
6.  "Let's talk about your 'unfair advantage.' Imagine that tomorrow, ten other smart, well-funded teams decide to tackle this exact same idea. Why would you be the one to win?"
7.  "Now that you have answered all the preceding questions, please provide a summary analysis of my Founder-Market Fit. Structure the analysis with two distinct sections: 'Potential Strengths & Unfair Advantages' and 'Potential Gaps & Blind Spots,' based solely on the content of my responses."

Before beginning, ask me to provide needed Business Context by concisely describing my idea and my target customer.
```

</details>

---

## 🎭 Prompt 7: From Prompt Monkey to Conversation Beast

**🎯 Goal:** Real validation isn't a one-shot prompt—it's a full interrogation.

<details>
<summary><b>🔍 Click for Prompt</b></summary>

```
You are to adopt a persona for the remainder of our conversation. Do not break character.

**Your Persona:** You are, a who has been in business for. Your primary struggle is. You are feeling [Emotion, e.g., "overwhelmed and unprofessional"]. You value [Values, e.g., "simplicity and clear communication"].

I am a researcher trying to understand your daily workflow. I am going to ask you some questions. Please answer them from Sarah's perspective, based on the characteristics described above.

Do you understand the instructions?
```

</details>

### 🔎 Must Do: Interrogate the Output

That first LLM reply? It's a sketch. Follow-up prompts should demand receipts:
- "Strong brand recognition"? → Find three real-world citations
- "Clunky UI"? → Scrape 10 bad reviews and give me top 5 complaints

---

## 📊 Prompt 8: Scrape, Feed, Analyze

**🎯 Goal:** Unlock god mode with bulk review analysis

<details>
<summary><b>🔍 Click for Prompt</b></summary>

```
Act as a Senior Data Analyst. I am pasting the raw text from [Number, e.g., "250"] customer reviews for my competitor, [Competitor Name]. The data is in a messy format. Your task is to read and analyze all of this text and then generate a structured report that answers the following questions:

1.  **Praised Features:** What are the top 5 most frequently praised features or aspects of the product?
2.  **Common Complaints:** What are the top 5 most common complaints or sources of frustration?
3.  **Pricing & Value:** Are there any mentions of pricing, value for money, or the cost being too high or a great deal?
4.  **Customer Support:** What is the general sentiment regarding their customer support? Provide example quotes for both positive and negative experiences.
5.  **Hidden Gems:** Are there any surprising or unexpected use cases or benefits that customers mention?

Please present the output in a clean, well-organized format with clear headings for each section.
```

</details>

---

<div align="center">

### 🚀 Ready for Step 2?

Once you've validated your idea, move on to [**Step 2: Define Your MVP**](./2-sketch.md) →

</div>