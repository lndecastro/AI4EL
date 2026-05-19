# Class 2: AI as Your Daily Assistant — Emails, Documents & Spreadsheets

In Class 1, you learned what AI is, how it works, and wrote your first prompts. You discovered that the quality of your input shapes the quality of the output. Now it is time to put that understanding to work on the tasks that fill most people's professional and personal lives: writing and responding to emails, making sense of long documents, navigating spreadsheet data without needing to be a data expert, tailoring your CV to a specific job opportunity, writing a cover letter, and creating a personal page.

By the end of this class, you will have used AI to complete tasks you face every week, and you will walk away with a personal **Prompt Library** of tested, ready-to-use templates.

> **The central idea of this class:** AI is not a magic button. It is a skilled assistant that responds to how clearly you communicate. The better you get at expressing your needs, the more value AI delivers.

## Learning Objectives

By the end of this class, you will be able to:

1. Apply different prompt patterns to get more targeted, useful responses from AI.
2. Use context engineering to adapt AI's tone, role, and output to your specific situation.
3. Use AI to draft, rewrite, summarize, and improve emails for different purposes and audiences.
4. Use AI to summarize long documents, reports, and articles quickly and accurately.
5. Ask AI to explain, analyze, and simplify spreadsheet data without writing a single formula.
6. Evaluate AI-generated written content critically before using or sharing it.
7. Build a reusable personal Prompt Library for daily communication tasks.

## Part I — Prompt Literacy: Communicating Like a Pro

In Class 1, you learned the main ingredients of a strong prompt: **Role, Context, Task, Input data, and Output format**. Now we go one level deeper into the *patterns* of prompting that give you consistent, high-quality results across any task.

### 1.1 Prompt Patterns: Choosing the Right Approach

A **prompt pattern** is a reusable structure you can adapt to different situations. Think of them like sentence templates for communicating with AI. You do not need to memorize all of them, you just need to know which one fits the job.

**The five most useful prompt patterns for everyday tasks:**

| Pattern | When to Use It | Example |
| :--- | :--- | :--- |
| **Instructional** | Simple, clear tasks with a single output | *"Summarize this email thread in three bullet points."* |
| **Role-Based** | You want a specific tone, expertise, or perspective | *"Act as a professional editor. Improve the tone of this email."* |
| **Chain-of-Thought** | Complex tasks where reasoning matters | *"Think step by step. First identify the main issue in this complaint, then suggest a response."* |
| **Few-Shot** | You want the AI to match a specific style or format | *"Here is an example of the tone I want: [example]. Now write a similar email for this situation: [situation]."* |
| **Iterative** | You want to refine the output through conversation | Start with a draft, then: *"Make it shorter." / "Change the tone to be warmer." / "Add a call to action."* |

:::{tip}
You do not need to pick just one pattern. The most powerful prompts often combine several, for example, a *role-based* prompt with *chain-of-thought* reasoning and a specific *output format*.
:::

### 1.2 Context Engineering: Giving AI the Full Picture

**Prompt engineering** is about how you phrase your instruction. **Context engineering** goes further, it is about everything that *surrounds* your instruction: the role you assign, the background you provide, the audience you define, and the constraints you set.

Think of the difference this way:

> Prompt engineering is choosing the right words.  
> Context engineering is making sure the AI understands the whole situation before it starts.

**The key elements of context:**

| Element | What It Does | Example |
| :--- | :--- | :--- |
| **Role** | Defines who the AI is acting as | *"You are a patient and professional customer service representative..."* |
| **Audience** | Defines who will read the output | *"...writing to a frustrated customer who has been waiting two weeks for a refund."* |
| **Purpose** | Clarifies the goal | *"The goal is to acknowledge the issue, apologize sincerely, and offer a clear next step."* |
| **Tone** | Sets the emotional register | *"Keep the tone warm, empathetic, and professional, never defensive."* |
| **Constraints** | Sets limits on length, content, or style | *"Keep the email to three short paragraphs. Do not promise a specific timeline."* |

**Context engineering in action — a before and after:**

*Without context:*
```
Write an apology email to a customer.
```

*With context:*
```
You are a customer service representative for a small online retail business.
A customer named Maria ordered a birthday gift two weeks ago and it has not arrived.
She has emailed twice and is understandably frustrated.
Write a professional, warm, and sincere apology email that:
- Acknowledges the delay and her frustration without making excuses
- Confirms you are investigating the shipment status
- Offers her a 15% discount on her next order as a goodwill gesture
- Keeps the tone empathetic and never defensive
- Is no longer than three short paragraphs
```

The second version gives the AI everything it needs to produce something genuinely useful, not just a generic apology.

### 1.3 Meta-Prompting: Let AI Create and/or Improve Your Prompts

One of the most powerful and underused techniques is **meta-prompting**: asking AI to help you write or improve a prompt before you use it.

This is especially helpful when you know what you want to accomplish but are not sure how to phrase it.

**Meta-Prompt Template — Create a Prompt from Scratch:**
```
I want to use AI to help me with the following goal:
[DESCRIBE WHAT YOU WANT TO ACCOMPLISH]

My audience is: [WHO WILL READ OR BENEFIT FROM THE OUTPUT]
The tone should be: [FORMAL / FRIENDLY / PERSUASIVE / INFORMATIVE / ETC.]
The format I need is: [EMAIL / LIST / PLAN / SUMMARY / SOCIAL POST / ETC.]
Any important details or constraints: [LENGTH, STYLE, THINGS TO INCLUDE OR AVOID]

Based on this, write me a strong, ready-to-use prompt I can give to an AI tool.
```

**Example**: A small business owner wants to use AI to announce a new product on social media but doesn't know how to start.

**Using the meta-prompt**:
```
I want to use AI to help me write a prompt with the following goal:
Announce a new product on social media.

My audience is: local customers in Southwest Florida, mostly 30–55 years old
The tone should be: excited, friendly, and a little playful
The format I need is: a short social media post (Instagram/Facebook)
Any important details or constraints: the product is a new tropical fruit smoothie at
my café, I want to include a call to action, keep it under 100 words, and use 2–3 emojis
```

**Meta-Prompt Template — Improve a Weak Prompt:**
```
Here is a prompt I wrote:

[PASTE YOUR PROMPT HERE]

My goal is: [DESCRIBE WHAT YOU ARE TRYING TO ACHIEVE]
My audience is: [DESCRIBE WHO WILL READ THE OUTPUT]

Please rewrite this prompt to make it more effective. 
Explain what you changed and why.
```

**Example:** A participant in a community organization wants AI to help write a fundraising email but is not sure how to prompt it:

*Their original prompt:*
```
Write a fundraising email.
```

*After using the meta-prompt:*
```
You are a warm and persuasive nonprofit communications writer.
Write a fundraising appeal email for a local food bank serving Lee County, Florida.
The email is addressed to past donors who gave between $25 and $100 last year.
The goal is to inspire a repeat gift before the end of the fiscal year.
Include: a compelling opening with a specific story or statistic, a clear call to action 
with a donation link placeholder, and a warm, grateful closing.
Tone: heartfelt, urgent but not pushy. Length: 250–300 words.
```

The meta-prompt transformed a one-line instruction into a fully engineered prompt, and the resulting email was ready to use with minimal editing.

:::{tip}
Next time you feel stuck on how to ask AI something, type: *"Help me write a better prompt to accomplish this goal: [your goal]."* AI will ask you clarifying questions or suggest an improved prompt directly.
:::

### 1.4 Activity 1: Prompt Pattern Practice

**Goal:** Experience how different prompt patterns produce different responses to the same task.

**The task:** Ask AI to help you write a short professional bio for yourself (or an imaginary persona).

**Round 1 — Instructional:**
```
Write a short professional bio for me.
```

**Round 2 — Role-Based:**
```
You are a professional copywriter specializing in personal branding.
Write a compelling 100-word professional bio for [name], 
who works as a [job title] with [X] years of experience in [field].
Tone: confident, approachable, and human.
```

**Round 3 — Iterative refinement:**
After reading Round 2's output, give one follow-up instruction:
```
Make it sound less formal and more conversational.
```
Then another:
```
Add a sentence about what this person is passionate about outside of work.
```

**Reflect:**
- Which round produced the most useful result?
- How much did each follow-up instruction change the output?
- What does this tell you about how AI conversations work?

## Part II — AI for Emails and Written Communication

Email is where most people spend a significant portion of their workday. It is also one of the areas where AI offers the most immediate, practical value.

### 2.1 What AI Can Do with Email

AI can help with virtually every stage of email communication:

| Task | What AI Does | When It Helps |
| :--- | :--- | :--- |
| **Drafting from scratch** | Writes a complete email from your bullet points or description | When you are staring at a blank screen |
| **Rewriting and improving** | Adjusts tone, clarity, length, and professionalism | When your draft feels off but you cannot say why |
| **Changing tone** | Shifts from casual to formal, assertive to diplomatic, etc. | When you need to communicate delicately |
| **Summarizing threads** | Extracts the key points from a long email chain | Before joining a conversation or replying to a complex thread |
| **Responding to difficult emails** | Helps you reply calmly and constructively to criticism or conflict | When you are emotional and need a more measured response |
| **Translating or simplifying** | Converts technical or legal language into plain English | When you receive something confusing |

### 2.2 Prompt Templates for Common Email Tasks

The following templates are your **Prompt Library** for emails. Copy, paste, and fill in the brackets.

**Template 1 — Draft an email from bullet points:**
```
Act as a professional business writer.
I need to send an email to [recipient and their role].
The purpose of the email is to [describe the goal].
Here are the key points I want to include:
- [Point 1]
- [Point 2]
- [Point 3]
Tone: [professional / friendly / formal / direct]
Length: [short / medium / no more than X sentences]
```

**Template 2 — Improve an existing draft:**
```
Please improve the following email draft.
Make it more [professional / concise / warm / persuasive].
Keep the meaning the same but improve the tone and clarity.
Here is my draft:
[PASTE YOUR DRAFT]
```

**Template 3 — Respond to a difficult email:**
```
I received the following email and need help writing a calm, professional response.
My goal is to [acknowledge / apologize / push back / clarify / decline].
Important constraints: [do not mention X / keep it brief / do not commit to a deadline].
Here is the email I received:
[PASTE THE EMAIL]
```

**Template 4 — Summarize an email thread:**
```
I am going to paste a long email thread below.
Please summarize it in bullet points, covering:
1. The main issue or topic being discussed
2. Who is involved and what each person's position is
3. Any decisions that were made
4. Any open questions or next steps
Here is the thread:
[PASTE THE THREAD]
```

**Template 5 — Translate tone (formal ↔ casual):**
```
Rewrite the following email in a [more formal / more casual / more empathetic] tone.
Keep all the key information but adjust the language and style.
Email:
[PASTE EMAIL]
```

:::{important}
Always re-read AI-generated emails before sending. Check for anything that does not sound like you, any factual details the AI may have invented, or any commitments you did not intend to make. You are responsible for what you send. AI is the drafter, not the decision-maker.
:::

### 2.3 Activity 2: Draft a Real Email

**Goal:** Use AI to complete an actual email task from your life.

**Choose one of the following scenarios (or use a real situation of your own):**

- **Scenario A:** You need to follow up on a job application you submitted two weeks ago with no response.
- **Scenario B:** A colleague gave you feedback that you disagree with, and you want to respond thoughtfully without creating conflict.
- **Scenario C:** You need to decline a meeting invitation politely because you are overloaded with work this week.
- **Scenario D:** You need to ask your landlord (or a service provider) to resolve an issue that has been ignored for weeks.

**Steps:**
1. Choose your scenario and write three bullet points describing what you want to communicate.
2. Use Template 1 from the Prompt Library to ask AI to draft the email.
3. Read the result. Identify one thing to change.
4. Use Template 2 or write a follow-up instruction to refine it.
5. Read the final version. Would you send this? What, if anything, would you change?

**Discussion questions:**
- What did AI get right on the first attempt?
- What did it get wrong or miss?
- How many rounds of refinement did it take to get something you would actually use?

### 2.4 AI Tools for Email Management

Managing a busy inbox can feel overwhelming, but AI tools are making it much easier. Whether you want to quickly summarize a long email thread, get help writing a reply, or automatically sort out the messages that actually matter, there is now a tool designed to do exactly that. The options range from AI assistants already built into Gmail and Outlook (so nothing new to install) to dedicated apps that completely transform how you experience email. The table below gives you a side-by-side look at the most popular tools available, so you can find the best fit for your needs and comfort level.

**Comparison Table**

| Tool | Website | Best For | Works With | Key Features | Free Option | Approx. Cost |
|------|---------|----------|------------|--------------|-------------|--------------|
| **Google Gemini** | [gemini.google.com](https://gemini.google.com) | Gmail users who want AI built in | Gmail | Thread summarization, reply drafting, inbox organization | ✅ Yes (included with Gmail) | Free / Google One AI Premium ~$20/mo |
| **Microsoft Copilot** | [copilot.microsoft.com](https://copilot.microsoft.com) | Outlook & Microsoft 365 users | Outlook, Teams, Word | Email drafting, thread summaries, tone coaching, cross-app context | ✅ Yes (basic) | Included in Microsoft 365 plans |
| **Superhuman** | [superhuman.com](https://superhuman.com) | Professionals with high email volume | Gmail, Outlook | Fast inbox triage, AI reply drafting in your tone, auto follow-ups, mobile app | ❌ No | ~$30/month |
| **Shortwave** | [shortwave.com](https://shortwave.com) | Gmail users wanting a cleaner experience | Gmail only | Auto-bundles threads by topic, prioritizes urgent emails, AI writing assistant, scheduled sending | ✅ Limited free plan | From ~$9/month |
| **SaneBox** | [sanebox.com](https://sanebox.com) | Anyone overwhelmed by inbox clutter | Any email client (IMAP) | Smart sender filtering, SaneLater folder, SaneBlackHole (block senders), no-reply reminders, daily digest | ❌ No | From ~$3.49/month |
| **Unboxd** | [unboxd.ai](https://unboxd.ai) | People who want a daily email briefing | Gmail, Outlook, IMAP | Categorizes emails into Action Items / Highlights / FYIs, daily priority briefing, deadline extraction | ❌ No | Paid (pricing on site) |
| **Clean Email** | [clean.email](https://clean.email) | Decluttering a messy or overgrown inbox | Gmail, Outlook, IMAP | Smart filters, bulk actions, unsubscribe tool, automation rules, runs quietly in background | ✅ Limited free trial | From ~$9.99/month |
| **Notion Mail** | [mail.notion.so](https://mail.notion.so) | Notion users who want email + tasks together | Gmail only | Inbox filtered like a database, email sequences, project-linked drafts, task integration | ✅ Free (with Notion account) | Included with Notion |
| **Lindy** | [lindy.ai](https://lindy.ai) | Power users & small business owners | Outlook, Gmail, 1,600+ apps | Full email automation, CRM sync, meeting scheduling, no-code workflow builder | ✅ Limited free plan | From ~$49/month |

**Quick Guide: Which Tool Is Right for You?**

| Your Situation | Recommended Tool |
|----------------|-----------------|
| I use Gmail and don't want to install anything new | Google Gemini |
| I use Outlook at work | Microsoft Copilot |
| I get 100+ emails a day and need speed | Superhuman |
| My inbox is full of junk and old subscriptions | SaneBox or Clean Email |
| I want a daily summary of what matters | Unboxd |
| I already use Notion for my work | Notion Mail |
| I want to automate my whole email workflow | Lindy |

### 2.5 AI for Documents: Reading, Summarizing, and Creating

Beyond email, AI is extraordinarily useful for working with longer-form written content, such as reports, articles, meeting notes, policy documents, proposals, and more. To illustrate, consider the paper about the use of Transfer Learning in Bioinspired Algorithms authored by Rita Xavier and Dr. Leandro de Castro, published in the Artificial Intelligence Reviews: [Download the paper](.Data/TLBIA_AIR.pdf)

**What AI can do with documents:**

**Summarizing** - Perhaps the most immediately useful skill. Instead of reading a 20-page report to find the three things that matter to you, you can paste it into an AI chat and ask for what you need:

```
Summarize this document in five bullet points, focusing on the key 
recommendations and any action items for [your role or department].
```

**Extracting specific information** - Instead of scanning for details:
```
Read the document attached and answer these three questions:
1. What is transfer learning?
2. What are bioinspired algorithms?
3. What are the main uses of bioinspired algorithms in transfer learning?
```

**Turning notes into documents** - If you have rough meeting notes or bullet points, AI can turn them into a polished document. To illustrate, upload the following meeting notes into your AI model and prompt it to create a meeting summary based on these notes. [Download the notes](.Data/MeetingNotes.txt)

```
I have rough notes from a meeting attached. Please turn them into a professional 
meeting summary that includes: attendees, key decisions, action items, and next steps.
Format it clearly with headings.
```

**Explaining confusing language** - Legal, medical, or technical documents often feel impenetrable:
```
Please explain the following paragraph in plain, everyday English.
Assume I have no background in [law / medicine / finance].
[PASTE PARAGRAPH]
```

*Example Paragraph 1 — Legal (Lease Agreement)*
```
"Notwithstanding any other provision of this Agreement, Tenant shall indemnify, defend, and hold harmless Landlord and its respective officers,
directors, employees, agents, successors, and assigns from and against any and all claims, damages, losses, costs, and expenses, including
reasonable attorneys' fees, arising out of or related to Tenant's use or occupancy of the Premises, any breach or default by Tenant under this
Agreement, or any act or omission of Tenant or Tenant's agents, employees, contractors, or invitees."
```

*Example Paragraph 2 — Medical (Patient Discharge Instructions)*
```
"Patient presents with a diagnosis of moderate non-erosive gastroesophageal reflux disease (GERD) with associated dysphagia. Treatment protocol
includes initiation of a proton pump inhibitor (PPI) regimen administered once daily prior to the first meal. Patient is advised to maintain
head-of-bed elevation of no less than 30 degrees, avoid consumption of known lower esophageal sphincter (LES) relaxants including caffeine, alcohol,
and high-fat foods, and to follow up with a board-certified gastroenterologist within four to six weeks for re-evaluation and potential esophageal manometry."
```

### 2.6 Activity 3: Talk to a Document

**Goal:** Experience AI as a document assistant using a real or sample document.

**Option A — Use your own document:**  
Find any document you have been meaning to read: a report, an article, a policy document, a long email, or even a set of meeting notes. Paste its text into an AI chat.

**Option B — Use a sample article:**  
Go to any news website and copy the full text of an article on any topic that interests you.

**Once you have the text, try these prompts in sequence:**

```
1. "Summarize this in 5 bullet points."
2. "What is the single most important takeaway from this?"
3. "Are there any claims in this document that I should verify 
   independently before sharing it with others?"
4. "Write a two-sentence summary I could use to share this with 
   a colleague who has no time to read it."
```

**Reflect:**
- How accurate was the summary compared to your own reading?
- Did AI miss anything important?
- Did it add anything that was not actually in the document?

:::{warning}
AI can "hallucinate" when summarizing, occasionally adding details that are not in the original. Always check that a summary accurately reflects the source, especially before forwarding it to others.
:::

### 2.7 AI Tools for Document Processing and Creation

Whether you need to understand a dense document, polish a rough draft, or create content from scratch, there is now an AI tool designed for exactly that job. Some tools focus on improving what you have already written, correcting grammar, adjusting tone, and tightening sentences, while others help you generate new content quickly from a simple prompt or outline. And a growing category of tools specializes in helping you actually understand complex documents, like research papers or legal texts, by answering your questions in plain, everyday language. The table below covers some of the most popular and useful options available, so you can find the right fit for how you write and what you work with most.

:::{note}
This table is neither expected to be exhaustive nor comprehensive. A web search may reveal many other tools useful for your document context and you are advised to do such search if you want to have a more specific sample of tools potentially applicable to your context.
:::

**Comparison Table**

| Tool | Website | Best For | Works With | Key Features | Free Option | Approx. Cost |
|------|---------|----------|------------|--------------|-------------|--------------|
| **Notion AI** | [notion.so](https://notion.so) | People who already organize their work in Notion | Notion pages and uploaded files | Summarize, draft, translate, and explain content; pulls context from your own existing notes and documents | ✅ Yes (add-on) | Notion AI add-on ~$10/mo per user |
| **Grammarly** | [grammarly.com](https://grammarly.com) | Anyone who wants to write more clearly and confidently | Browser extension, Word, Google Docs, most email clients | Real-time grammar and spelling, tone detection, clarity suggestions, rewriting help, 100 AI prompts/mo on free plan | ✅ Yes (basic) | Premium ~$12/mo (billed annually) |
| **NotebookLM** | [notebooklm.google.com](https://notebooklm.google.com) | Understanding and researching documents from your own sources | PDFs, Google Docs, websites, YouTube links | Upload your sources and ask questions; generates summaries, audio "podcast" overviews of documents, and deep research reports | ✅ Yes (generous free tier) | Plus ~$20/mo |
| **Wordtune** | [wordtune.com](https://wordtune.com) | Improving and rephrasing sentences you have already written | Browser extension, Google Docs, most web editors | Rewrites and rephrases sentences, adjusts tone (formal or casual), expands or shortens text, summarizes long content | ✅ Yes (10 rewrites/day) | Unlimited ~$9.99/mo (billed annually) |
| **SciSpace** | [scispace.com](https://scispace.com) | Reading academic papers, research reports, or any complex document | PDFs, research papers, web articles | Explains difficult papers in plain language, lets you ask questions about any document, highlights and annotates, literature search | ✅ Yes (limited) | From ~$12/mo |
| **Reword** | [reword.co](https://reword.co) | Bloggers and content teams who want AI to write in their own voice | Web app, connects to most content management systems (CMS) | Trains on your existing articles to learn your style, collaborative AI co-writer, research assistance, SEO-optimized article drafting | ❌ No (14-day free trial) | From ~$39/mo |
| **Surfer** | [surferseo.com](https://surferseo.com) | Creating blog posts and articles that rank well on Google | Web app, Google Docs integration | Real-time content scoring as you write, keyword and competitor analysis, content outlines built from top-ranking pages | ❌ No | From ~$69/mo (billed annually) |
| **Rytr** | [rytr.me](https://rytr.me) | Quick, affordable content for everyday writing tasks | Web app, browser extension | 40+ templates (blog posts, emails, product descriptions, social posts), 20+ tone options, 30+ languages, plagiarism checker | ✅ Yes (10,000 characters/mo) | Saver ~$9/mo / Unlimited ~$29/mo |
| **Jasper** | [jasper.ai](https://jasper.ai) | Marketing and business teams creating branded content at scale | Web app, Google Docs extension, browser | Brand voice training, 50+ professional templates, long-form content editor, team collaboration, AI image generation | ❌ No (7-day free trial) | Creator ~$49/mo |
| **Writesonic** | [writesonic.com](https://writesonic.com) | SEO-focused blogs, marketing copy, and high-volume content | Web app, WordPress integration | 80+ templates, built-in SEO and keyword tools, AI blog writer, ChatSonic chatbot with web access | ✅ Yes (limited) | From ~$20/mo |

<p>
**Quick Guide: Which Tool Is Right for You?**

| Your Situation | Recommended Tool |
|----------------|-----------------|
| I want to catch grammar mistakes and write more clearly | Grammarly |
| I need to understand a research paper or complex document without a technical background | SciSpace |
| I have uploaded documents and want to ask questions and get summaries from them | NotebookLM |
| I want to rephrase or rewrite a sentence without changing its meaning | Wordtune |
| I already organize my notes and projects in Notion | Notion AI |
| I write blog posts or articles and want AI help that sounds like *me* | Reword |
| I need to write short content fast — emails, social posts, product descriptions | Rytr |
| I create content for a business or marketing team with a consistent brand voice | Jasper |
| I want my blog posts to rank higher in Google search results | Surfer |
| I need a flexible tool for SEO blogs and marketing copy with built-in keyword data | Writesonic |

## Part III — AI for Spreadsheets

Spreadsheets make many people nervous. Between the formulas, the columns, and the endless rows of numbers, it can feel like you need a degree in accounting just to keep track of your own finances. The good news is that AI changes this completely.
In this section, you will learn how to use AI as your personal spreadsheet assistant, not just to read and analyze data you already have, but to build useful tools from scratch, starting with something very practical: your own personal finance tracker.
By the end of Part III, you will be able to ask AI to build a spreadsheet for you, populate it with real-life numbers, generate a plain-language financial summary, analyze any table of data, and write formulas without knowing a single line of syntax.
No spreadsheet experience required.

### 3.1 Build Your Personal Finance Tracker with AI

One of the most powerful things you can do with AI is ask it to create tools you never knew how to build. A personal finance tracker is a perfect example. Most people know they *should* have one. Very few actually do, because setting one up from scratch feels too complicated.
With AI, you can have a complete, working financial tracker in minutes, simply by describing what you need.
In this section, you will ask AI to build a two-tab spreadsheet designed to give you a full picture of your financial year:

- **Tab 1 — Cash Flow:** A monthly log of all money coming in and going out, organized by category, housing, food, transportation, savings, and more.
- **Tab 2 — Monthly Summary:** A consolidated view, month by month, showing your total income, total expenses, and your net result (what was left over). Think of it as your personal Profit and Loss statement.

Together, these two tabs give you something most people have never had: a clear, organized view of where their money actually goes.

**The Prompt: Create My Finance Tracker**

Use the following prompt in any AI tool that supports spreadsheet creation or file downloads. Copy it exactly, or adjust the categories to match your own situation.

```
Please build a personal finance spreadsheet for me with two tabs.

TAB 1 — CASH FLOW:
- Rows represent income and expense categories (listed below)
- Columns represent the 12 months of the year (January through December)
- Add a "Total" column at the far right of each row
- At the bottom, add three summary rows:
    Total Income (sum of all income rows for each month)
    Total Expenses (sum of all expense rows for each month)
    Net (Total Income minus Total Expenses for each month)

Categories to include:

INCOME
  Salary / Regular Pay
  Freelance or Side Income
  Other Income

HOUSING
  Rent or Mortgage
  Utilities (electricity, water, gas)
  Internet and Phone

FOOD
  Groceries
  Dining Out / Takeout

TRANSPORTATION
  Car Payment or Lease
  Fuel / Gas
  Public Transit or Rideshare

HEALTH
  Health Insurance
  Medications and Copays
  Gym or Fitness

PERSONAL
  Clothing and Personal Care
  Subscriptions (streaming, apps, etc.)
  Entertainment and Hobbies

SAVINGS AND DEBT
  Savings Contribution
  Credit Card Payments
  Student Loan or Other Loan Payments

OTHER
  Gifts and Donations
  Unexpected / Miscellaneous

TAB 2 — MONTHLY SUMMARY:
- One row per month (January through December), plus a "Full Year" total row at the bottom
- Columns: Month | Total Income | Total Expenses | Net
- Pull these numbers automatically from Tab 1 using formulas
- Apply a simple color rule: green background if Net is positive, red if Net is negative

Please format the spreadsheet with clear headers, bold totals rows, 
and currency formatting ($) throughout. Make it easy to read and use.
```

:::{tip}
**Which AI tool should I use?** If you are using a paid version of ChatGPT (Plus), Claude (Pro), or Google Gemini Advanced, you may be able to download the spreadsheet directly as an Excel or Google Sheets file. If your tool does not offer file downloads, it will likely give you a table you can copy and paste into a blank spreadsheet.
:::

### Activity: Build and Populate Your Own Finance Tracker

**Goal:** Use AI to create and fill in a personal finance spreadsheet with approximate numbers that reflect your real life, then see your full year at a glance.

This activity has three steps.

**Step 1 — Create the spreadsheet**

Copy the prompt above into your AI tool and run it. Once you have the spreadsheet (either downloaded or pasted into a blank file), take a moment to look it over. Notice the two tabs, the categories, and the layout. You do not need to fill anything in yet.

**Step 2 — Tell AI about your financial life**

Now you will have a short conversation with AI to help it fill in the numbers. You do not need to be precise; round estimates are perfectly fine. The goal is to populate a realistic year so you can see how everything works together.

Use this prompt to get started:

```
I want you to fill in my personal finance spreadsheet with approximate 
numbers based on my real life. I will answer a few questions below. 
Please use the answers to populate all 12 months in the Cash Flow tab 
and the Monthly Summary tab. Use round numbers and tell me any 
assumptions you make.

My answers:

1. My approximate monthly take-home income (after taxes) is:
   [type your answer here]

2. My monthly housing cost (rent or mortgage + utilities) is roughly:
   [type your answer here]

3. I spend approximately this much on food per month (groceries + eating out):
   [type your answer here]

4. My regular transportation costs each month are roughly:
   [type your answer here]

5. I have these recurring debt or loan payments each month:
   [type your answer here — or write "none"]

6. I try to save approximately this much per month:
   [type your answer here — or write "I don't currently save regularly"]

7. Some months cost more than others. For example:
   [describe any seasonal patterns — e.g., "December is expensive for gifts,"
   "August I pay for school supplies," or "I take a vacation in June"]

8. Anything else about my finances I should know about:
   [add anything else, or write "nothing else"]

Please fill in all 12 months realistically based on these answers.
```

:::{note}
You do not need to share your real numbers. This activity works just as well with approximate figures or even invented ones. The goal is to learn the process, how to build, populate, and work with a spreadsheet through conversation with AI.
:::

**Step 3 — Review and adjust**

Once AI has filled in the spreadsheet, read through it and make corrections in plain language. For example:

- *"Change my rent from $1,200 to $1,450 starting in March."*
- *"Add a one-time expense of $800 in July for a vacation."*
- *"I don't have a car payment, remove that row or set it to zero."*

Keep adjusting until the numbers feel roughly right. You are not trying to be perfect, you are learning how to work with AI as a financial tool.

**Reflection questions:**

- Does the Monthly Summary tab show months where you spend more than you earn? Were you surprised?
- Were there any expense categories you had not thought about?
- How might this spreadsheet change how you think about your spending?

### The Prompt: Your Personal Financial X-Ray

Once your spreadsheet is populated, use the following prompt to generate a plain-language summary and visualization recommendations for your financial year.

```
Based on the financial data in my spreadsheet, please do three things:

1. Write a "Financial X-Ray", that is, a plain-language paragraph of 5 to 6 sentences 
   that summarizes my financial year. Include:
   - Which months were my strongest and weakest financially
   - Whether I am generally saving, breaking even, or overspending
   - My single largest expense category
   - One observation or insight I might not have noticed on my own

2. Recommend 3 types of charts that would make this data easy to visualize, 
   and explain what each one would show. For example:
   - A bar chart comparing total income vs. total expenses by month
   - A pie chart showing my expense breakdown by category
   - A line chart tracking my monthly net result over the year

3. If you can generate the charts directly, please do so.
   If not, give me step-by-step instructions for how to create them 
   in Excel or Google Sheets, simple enough for a beginner.
```

**What to look for in the output:**

- Does the Financial X-Ray feel accurate to your situation?
- Did AI notice anything you had overlooked?
- Which chart feels most useful for your goals?

:::{tip}
Save your Financial X-Ray paragraph somewhere you can find it later. It makes a great starting point if you ever want to set a savings goal, talk to a financial advisor, or simply reflect on the year.
:::

### 3.2 What AI Can Do with Spreadsheet Data

Building a spreadsheet from scratch is just one way AI can help. Once you have data, whether it came from AI, from your job, or from a file someone sent you, AI can help you make sense of it without you needing to know any formulas or technical skills.

Here is a quick overview of the most useful things AI can do with spreadsheet data.

| What you need | Example prompt |
| :--- | :--- |
| **Understand what the data is showing** | *"I have sales data by region and month. What patterns or trends stand out?"* |
| **Create or fix a formula** | *"I need a formula that calculates the average of column B, but only for rows where column A says 'Florida'."* |
| **Summarize numbers in plain language** | *"Summarize these figures in two sentences a non-technical manager could understand."* |
| **Find anything unusual** | *"Look at this data and tell me if anything looks unusual, unexpected, or worth investigating."* |
| **Suggest the right chart** | *"What type of chart would best represent this data, and why?"* |
| **Turn numbers into a written narrative** | *"Turn this table of monthly expenses into a short paragraph I can include in a report."* |

The key insight here is simple: you no longer need to know *how* to do things in a spreadsheet. You just need to know what you *want*. Then you ask.

### 3.3 Two Ways to Use AI with Spreadsheet Data

When you have data you want AI to analyze, there are two practical methods depending on how much data you have and which AI tool you are using.

**Method 1 — Paste Data Directly into the Chat**

For smaller datasets, such as a few dozen rows or fewer, you can copy your data directly from a spreadsheet and paste it into the AI chat window. Most AI tools handle tabular data well when it is pasted as plain text.

This works best when:

- You have a manageable amount of data (not thousands of rows)
- You want a quick answer without uploading a file
- You are working with a free version of an AI tool

Here is an example of what that looks like in practice:

```
Here is my data:

Month     | Revenue ($) | Expenses ($) | Profit ($)
January   | 42,000      | 31,500       | 10,500
February  | 38,500      | 29,800       | 8,700
March     | 51,200      | 34,100       | 17,100
April     | 47,800      | 33,200       | 14,600

Please answer the following:
1. Which month had the highest profit margin (profit as a percentage of revenue)?
2. Is there a visible trend in expenses across these four months?
3. Write a two-sentence summary suitable for a monthly report.
```

**Method 2 — Upload the File Directly**

Paid versions of most major AI tools (ChatGPT Plus, Claude Pro, Gemini Advanced) allow you to upload Excel or CSV files directly. The AI reads the entire file and can answer questions, generate summaries, and spot patterns across the full dataset, without you needing to copy or paste anything.

This works best when:

- Your dataset is large (hundreds of rows or more)
- You want to analyze the full file without summarizing it first
- You are working with data that has multiple columns or complex structure

:::{tip}
When uploading a file with sensitive information, remove or replace any real names, ID numbers, or personal data before sharing it with an AI tool. Use placeholder names like "Employee A" or generic labels like "Region 1" instead.
:::

### 3.4 Prompt Templates for Spreadsheet Tasks

The following templates are ready to use. Copy them, fill in the bracketed sections with your own details, and paste them into any AI chat.

**Template 1 — Explain This Data to Me**

```
I am going to share a table of data below.
I am not a data expert. Please explain:
1. What this data appears to be tracking
2. The two or three most interesting patterns or findings
3. Anything that looks unusual or worth investigating further

[PASTE YOUR DATA HERE]
```

**Template 2 — Write a Formula for Me**

```
I am using [Excel / Google Sheets].
I need a formula that [describe what you want it to calculate].
My data is in columns [describe which columns contain what information].

Please give me the formula and explain in plain language what each part does,
so I understand how it works.
```

**Template 3 — Turn Numbers into a Written Summary**

```
Here is a table of data:

[PASTE YOUR DATA HERE]

Please write a short paragraph (3 to 4 sentences) summarizing the key findings
in plain language for a non-technical audience. Do not use jargon. 
Do not list every number — focus only on what matters most.
```

**Template 4 — Find Problems in the Data**

```
Please review the following data and flag anything that looks:
- Missing or incomplete
- Unusually high or low compared to the rest of the dataset
- Inconsistent with what the data should logically show

[PASTE YOUR DATA HERE]
```

### 3.5 Activity: AI Meets Your Spreadsheet

**Goal:** Use AI to extract insight from a table of data, no formulas, no calculations, no spreadsheet skills required.

**Option A — Use Your Own Data**

Find a spreadsheet you already work with, e.g. expense tracking, sales figures, a budget, a project list, or any table of numbers. Copy and paste a small section (a few rows is enough) into an AI chat and ask a question about it.

Remember: remove or replace any confidential or personally identifying information before sharing.

**Option B — Use This Sample Dataset**

If you do not have a spreadsheet handy, use the table below. Copy and paste it into an AI chat and work through the prompts that follow.

```
Employee    | Department  | Sales Q1 ($) | Sales Q2 ($) | Sales Q3 ($)
Alice       | North       | 52,000       | 48,500       | 61,200
Bob         | South       | 41,300       | 43,100       | 39,800
Carol       | North       | 67,400       | 71,200       | 68,900
David       | East        | 29,500       | 31,000       | 27,400
Eva         | South       | 55,800       | 58,400       | 62,100
Frank       | East        | 38,200       | 35,900       | 41,700
```

**Try These Prompts in Sequence**

Work through these one at a time, reading the AI's response before moving to the next:

1. *"Who had the highest total sales across all three quarters?"*
2. *"Which department performed best overall? Show your reasoning."*
3. *"Is there anyone whose sales are consistently declining? Should that be a concern?"*
4. *"Write a two-sentence summary of this team's performance for a quarterly report."*
5. *"What type of chart would best visualize this data, and why?"*

### Reflect

After completing the prompts, take a moment to think about what happened:

- Did AI answer all the questions correctly? (Check the math manually on at least one answer.)
- Did it offer any insight you would not have spotted yourself?
- What would you do differently if this were real business data?

:::{warning}
**Always verify AI-generated calculations.** AI can make arithmetic errors — especially with percentage calculations or when data is ambiguous. Use AI to find patterns and generate ideas. Use the spreadsheet itself to confirm the final numbers before making any decisions based on them.
:::

## Part IV — Putting It All Together: Your Personal Prompt Library

One of the most valuable outcomes of this class is building a **personal Prompt Library**, a collection of tested prompts you can reuse and adapt whenever you need them.

### 4.1 Assessing Prompt Quality

Before saving a prompt to your library, run it through this five-point check, adapted from the AI Literacy Program:

| Criterion | Question to Ask |
| :--- | :--- |
| **Relevance** | Did the AI's response actually address what I needed? |
| **Completeness** | Did it cover everything I asked, or did it miss parts? |
| **Clarity** | Is the output clear, readable, and well-structured? |
| **Accuracy** | Are the facts, figures, and claims correct? (Verify!) |
| **Format** | Did the output come in the format I requested? |

If a prompt scores poorly on any criterion, refine it and test again before saving it. A prompt library is only useful if the prompts in it actually work.

### 4.2 Activity 5: Build Your Prompt Library Starter

**Goal:** Leave this class with at least three tested, personally useful prompts.

**Step 1:** Choose three tasks from your own professional or personal life where AI could save you time or effort. Examples:
- Drafting weekly update emails to your team
- Summarizing meeting notes
- Explaining medical or legal documents in plain language
- Writing follow-up emails after networking events
- Turning expense data into a short report narrative

**Step 2:** For each task, write a prompt using the templates from this class or your own approach.

**Step 3:** Test each prompt in an AI tool. Rate it on the five-point quality check.

**Step 4:** Refine each prompt once based on what you observe.

**Step 5:** Save your three final prompts somewhere accessible, such as a notes app, a document, or a dedicated folder. You now have the beginning of a Prompt Library.

## Part V — AI for Your Career: Professional Pages, CVs, and Cover Letters

The skills you have built in this class — drafting documents, working with pasted content, and using prompt templates — come together powerfully when applied to career tasks. In this section, you will use AI to create two high-value professional outputs: a personal professional page and a tailored CV with a cover letter.

Both activities use your **LinkedIn profile as a starting point**, so AI has your real background to work with — no need to type everything from scratch.

> **Why LinkedIn PDF?** Your LinkedIn profile is likely the most complete, up-to-date record of your professional life. Exporting it as a PDF gives AI a structured, rich input that it can transform into polished professional outputs.

---

### 5.1 How to Export Your LinkedIn Profile as a PDF

Before starting either activity in this section, you need to save your LinkedIn profile as a PDF. Here is how:

1. Go to [linkedin.com](https://linkedin.com) and sign in.
2. Click your profile photo or your name to open **your profile page**.
3. Click the **"More"** button (or **"Resources"** on some versions) just below your name and headline.
4. In the dropdown menu, select **"Save to PDF"**.
5. Your browser will download a PDF file of your complete LinkedIn profile — typically named something like `Profile.pdf`.
6. Save this file somewhere you can find it easily (your Desktop or Downloads folder).

> 💡 **Tip:** The LinkedIn PDF includes your summary, work experience, education, skills, and any recommendations or certifications. The more complete your LinkedIn profile, the better the AI outputs will be. Take a few minutes to update it before exporting.

> ⚠️ **Privacy note:** You will be uploading this PDF to an AI tool. Avoid using AI tools on shared or public computers for this task. Review the privacy settings of the tool you choose — most major platforms (ChatGPT, Claude, Gemini) do not use uploaded documents to train their models, but it is always good practice to verify.

---

### 5.2 🛠️ Activity 6: Create Your Personal Professional Page

**Goal:** Use AI to transform your LinkedIn PDF into a polished, formatted personal professional page — suitable as a personal website, a PDF bio, or a professional portfolio introduction.

A **personal professional page** is a single-page document (or webpage) that presents you clearly and compellingly to potential clients, collaborators, employers, or community partners. Think of it as a curated "about me" — more narrative and personal than a CV, but more structured and professional than a social media profile.

---

**Step 1 — Export your LinkedIn PDF** (see Section 5.1 above)

**Step 2 — Upload the PDF to an AI tool**

Open [chatgpt.com](https://chatgpt.com), [claude.ai](https://claude.ai), or [gemini.google.com](https://gemini.google.com). Use the file upload button (usually a paperclip or attachment icon in the chat input) to attach your LinkedIn PDF.

> 💡 **Free tiers work for this task.** All three tools listed support PDF uploads on their free tiers. If you do not see a file upload option, try the web version rather than the mobile app.

**Step 3 — Use this prompt template:**

```
I have uploaded my LinkedIn profile as a PDF. 
Please use it to create a personal professional page for me.

The page should include:
1. A compelling professional headline (one sentence that captures who I am and what I do)
2. A short professional summary (3–4 sentences, written in first person, warm and confident)
3. My key areas of expertise (3–5 bullet points, one sentence each)
4. A brief career highlights section (3–4 of my most significant roles or achievements)
5. My education (concise, just institution and degree/field)
6. A short "what I'm currently focused on" or "what I'm looking for" closing section
7. My contact information placeholder (e.g., "[email]", "[LinkedIn URL]")

Tone: Professional, warm, and human. Not overly formal. 
Format: Clean and readable, suitable for a one-page website or professional portfolio.
Length: No longer than one page when formatted normally.
```

**Step 4 — Review and personalize**

Read through the AI-generated page carefully:
- Does the summary actually sound like you?
- Are there any inaccuracies or details that were misread from the PDF?
- Is there anything important about you that AI missed?

Make at least three edits to bring your own voice into the content.

**Step 5 — Optional: Request an HTML version**

If you want a webpage you can share or host, try this follow-up prompt:
```
Now please format this as a clean, modern HTML page I can open in a browser.
Use a simple, professional design with a white background, readable fonts, 
and soft accent colors. No external dependencies — everything inline.
```

**Reflect:**
- How accurate was AI's interpretation of your professional background?
- What did it emphasize that you would not have thought to highlight yourself?
- How long did this take compared to writing a professional bio from scratch?

---

### 5.3 🛠️ Activity 7: Tailor Your CV and Write a Cover Letter for a Specific Job

**Goal:** Use your LinkedIn PDF and a real job posting to have AI produce a tailored CV and a polished cover letter email — ready to review and send.

This is one of the highest-value career applications of AI. Generic CVs and cover letters rarely stand out. AI can analyze both your background and the specific requirements of a job posting, then craft documents that align the two — in minutes.

---

**Step 1 — Export your LinkedIn PDF** (see Section 5.1 if you have not already done so)

**Step 2 — Find and download a job posting**

Find a real job posting you are interested in — or a realistic example role. 

- Copy the **full text** of the job posting (job title, responsibilities, required skills, qualifications, and any other details).
- Save it in a text document or keep it ready to paste into the AI chat.

> 💡 **Where to find job postings:** LinkedIn Jobs, Indeed, Glassdoor, your company's own careers page, or any sector-specific job board. For this activity, even a sample posting works — the key is practicing the process.

**Step 3 — Upload your LinkedIn PDF and paste the job posting**

In your AI chat, upload your LinkedIn PDF, then use this prompt:

```
I have uploaded my LinkedIn profile as a PDF. 
Below I am also pasting the full text of a job posting I want to apply for.

Please do the following:

TASK 1 — TAILORED CV
Create a tailored CV that highlights the parts of my background most relevant 
to this specific role. 
- Use a clean, professional format with clear sections: 
  Summary, Key Skills, Work Experience, Education, and Certifications (if any).
- In the Summary section, write 2–3 sentences that connect my background 
  directly to the role's requirements.
- In the Skills section, mirror the language and keywords from the job posting 
  wherever they are genuinely reflected in my experience.
- In the Experience section, emphasize achievements and responsibilities 
  that align with what this role requires.
- Do not invent or exaggerate anything. Only use what is in my profile.

TASK 2 — COVER LETTER (EMAIL FORMAT)
Write a professional cover letter in email format, ready to paste into an 
email application.
- Subject line: clear and professional, referencing the role and my name.
- Opening paragraph: hook the reader with a strong, specific reason 
  why I am a compelling fit for this role.
- Middle paragraph(s): connect 2–3 specific aspects of my background 
  to the key requirements of the role. Be specific, not generic.
- Closing paragraph: express genuine enthusiasm, confirm availability, 
  and include a clear call to action (e.g., inviting an interview).
- Tone: confident, professional, and human. Not stiff or overly formal.
- Length: 3–4 short paragraphs. Under 300 words total.

Here is the job posting:
[PASTE THE FULL JOB POSTING TEXT HERE]
```

**Step 4 — Review both documents carefully**

This step is critical. Before using either document:

- **Check every claim.** AI should only include things from your actual background, but verify that dates, titles, and descriptions are accurate.
- **Read the cover letter aloud.** Does it sound like a real person wrote it? Does it sound like *you*?
- **Look for keyword alignment.** The CV should use terminology from the job posting where it genuinely matches your experience.
- **Check the tone.** Is it confident without being arrogant? Professional without being stiff?

**Step 5 — Refine with follow-up prompts**

Use these follow-up prompts to improve specific sections:

```
The cover letter opening feels too generic. 
Please rewrite it with a more specific, compelling hook that references 
[something specific about the company or the role].
```

```
The Skills section in the CV is too long. 
Please trim it to the 8 most relevant skills for this role.
```

```
Rewrite the Work Experience bullets for my most recent role to be 
more achievement-focused (using numbers or outcomes where possible).
```

**Reflect:**
- How well did AI identify the alignment between your background and the role?
- What did it include that you would not have thought to highlight?
- What did it get wrong or overstate that you had to correct?
- How does this compare to writing a CV and cover letter from scratch?

> ⚠️ **Important reminder:** Always review and edit AI-generated application materials before submitting them. You are responsible for the accuracy of everything in your CV. AI is your drafting assistant — you are the one whose name goes on the document.

---

## Part VI — Reflection and Wrap-Up

### 6.1 The Verification-First Mindset

Everything we practiced today — emails, summaries, spreadsheet analysis — produces AI output that is a **starting point**, not a finished product.

Before you use any AI-generated content:

- **Re-read it.** Does it sound like you? Does it say what you intended?
- **Check the facts.** Any specific claim, number, or name should be verified.
- **Consider the audience.** Is the tone and content appropriate for the person who will receive it?
- **Take ownership.** Once you send or share AI-assisted content, it represents you — not the AI.

This mindset — verify before you act — is not about distrust. It is about staying in control, which is exactly where you belong.

### 6.2 Reflection

> Which of today's use cases — emails, documents, or spreadsheets — do you think will save you the most time in the next month?  
> Has anything we practiced today changed how you think about the role of writing and communication in your work?  
> Where is the line between using AI to help you communicate and losing your own voice in the process?

There are no wrong answers. These are the kinds of questions thoughtful AI users return to regularly as the technology becomes a bigger part of daily life.

### 6.3 What Is Coming in Class 3

In our next class, we step into the creative side of AI. You will:

- Generate **images** from text descriptions for personal and professional use.
- Build **AI-assisted presentations** in minutes.
- Experiment with **AI music** tools and **AI avatars**.
- Learn the copyright and ethical considerations that come with creative AI tools.

No artistic talent required. Curiosity is all you need.

## 📋 Class 2 Summary Checklist

Before you move on, confirm that you can do the following:

- [ ] Name and apply at least three prompt patterns (instructional, role-based, iterative).
- [ ] Use context engineering to set role, audience, tone, and constraints in a prompt.
- [ ] Use a meta-prompt to let AI improve a weak prompt.
- [ ] Draft or improve an email using an AI prompt template.
- [ ] Summarize a long document using AI with a single prompt.
- [ ] Use AI to analyze a simple table of data and extract plain-language insights.
- [ ] Apply the five-point quality check to evaluate an AI output.
- [ ] Save at least three tested prompts to a personal Prompt Library.
- [ ] Export your LinkedIn profile as a PDF and use it as input for an AI professional page.
- [ ] Use AI to tailor a CV to a specific job posting and generate a cover letter email.

## 📘 Further Reading

- **Mollick, E. (2024).** *Co-Intelligence: Living and Working with AI.* Portfolio/Penguin. *(Chapter 3 is especially relevant to using AI for writing and communication.)*
- **Prompt Engineering Guide. (2024).** promptingguide.ai — a free, comprehensive reference for all prompt patterns covered in this class.
- **White, J. et al. (2023).** *A Prompt Pattern Catalog to Enhance Prompt Engineering.* arXiv:2302.11382.
- **Dendritic Institute. (2025).** *AI Literacy Program — Module 5: Fundamentals of Prompt Engineering.* FGCU AI Academy.
- **Dendritic Institute. (2025).** *AI Literacy Program — Module 6: Context Engineering.* FGCU AI Academy.
- **Google. (2024).** *Prompting Essentials.* Google Workspace Learning Center. workspace.google.com.
- **Microsoft. (2024).** *Getting Started with Copilot in Microsoft 365.* support.microsoft.com.

```{note}
*Class 2 is part of the AI for Everyday Life Program, offered by the Dendritic Institute for Human-Centered AI & Data Science at Florida Gulf Coast University. All hands-on activities can be completed using free AI tools. No spreadsheet expertise or technical background is required.*
```
