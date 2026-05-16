# Class 2: AI as Your Daily Assistant — Emails, Documents & Spreadsheets

In Class 1, you learned what AI is, how it works, and wrote your first prompts. You discovered that the quality of your input shapes the quality of the output. Now it is time to put that understanding to work on the tasks that fill most people's professional and personal lives: writing and responding to emails, making sense of long documents, and navigating spreadsheet data without needing to be a data expert.

By the end of this class, you will have used AI to complete tasks you face every week — and you will walk away with a personal **Prompt Library** of tested, ready-to-use templates.

> **The central idea of this class:** AI is not a magic button. It is a skilled assistant that responds to how clearly you communicate. The better you get at expressing your needs, the more value AI delivers — every single time.

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

In Class 1, you learned the four ingredients of a strong prompt: **Role, Context, Task, and Format**. Now we go one level deeper — into the *patterns* of prompting that give you consistent, high-quality results across any task.

### 1.1 Prompt Patterns: Choosing the Right Approach

A **prompt pattern** is a reusable structure you can adapt to different situations. Think of them like sentence templates for communicating with AI. You do not need to memorize all of them — you just need to know which one fits the job.

**The five most useful prompt patterns for everyday tasks:**

| Pattern | When to Use It | Example |
| :--- | :--- | :--- |
| **Instructional** | Simple, clear tasks with a single output | *"Summarize this email thread in three bullet points."* |
| **Role-Based** | You want a specific tone, expertise, or perspective | *"Act as a professional editor. Improve the tone of this email."* |
| **Chain-of-Thought** | Complex tasks where reasoning matters | *"Think step by step. First identify the main issue in this complaint, then suggest a response."* |
| **Few-Shot** | You want the AI to match a specific style or format | *"Here is an example of the tone I want: [example]. Now write a similar email for this situation: [situation]."* |
| **Iterative** | You want to refine the output through conversation | Start with a draft, then: *"Make it shorter." / "Change the tone to be warmer." / "Add a call to action."* |

> 💡 **Key insight:** You do not need to pick just one pattern. The most powerful prompts often combine several — for example, a *role-based* prompt with *chain-of-thought* reasoning and a specific *output format*.

### 1.2 Context Engineering: Giving AI the Full Picture

**Prompt engineering** is about how you phrase your instruction. **Context engineering** goes further — it is about everything that *surrounds* your instruction: the role you assign, the background you provide, the audience you define, and the constraints you set.

Think of the difference this way:

> Prompt engineering is choosing the right words.  
> Context engineering is making sure the AI understands the whole situation before it starts.

**The key elements of context:**

| Element | What It Does | Example |
| :--- | :--- | :--- |
| **Role** | Defines who the AI is acting as | *"You are a patient and professional customer service representative..."* |
| **Audience** | Defines who will read the output | *"...writing to a frustrated customer who has been waiting two weeks for a refund."* |
| **Purpose** | Clarifies the goal | *"The goal is to acknowledge the issue, apologize sincerely, and offer a clear next step."* |
| **Tone** | Sets the emotional register | *"Keep the tone warm, empathetic, and professional — never defensive."* |
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

The second version gives the AI everything it needs to produce something genuinely useful — not just a generic apology.

### 1.3 Meta-Prompting: Let AI Improve Your Prompts

One of the most powerful — and underused — techniques is **meta-prompting**: asking AI to help you write or improve a prompt before you use it.

This is especially helpful when you know what you want to accomplish but are not sure how to phrase it.

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

The meta-prompt transformed a one-line instruction into a fully engineered prompt — and the resulting email was ready to use with minimal editing.

> 💡 **Try this:** Next time you feel stuck on how to ask AI something, type: *"Help me write a better prompt to accomplish this goal: [your goal]."* AI will ask you clarifying questions or suggest an improved prompt directly.

### 1.4 🛠️ Activity 1: Prompt Pattern Practice

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

> ⚠️ **Watch Out:** Always re-read AI-generated emails before sending. Check for anything that does not sound like you, any factual details the AI may have invented, or any commitments you did not intend to make. You are responsible for what you send — AI is the drafter, not the decision-maker.

### 2.3 🛠️ Activity 2: Draft a Real Email

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

### 2.4 AI for Documents: Reading, Summarizing, and Creating

Beyond email, AI is extraordinarily useful for working with longer-form written content — reports, articles, meeting notes, policy documents, proposals, and more.

**What AI can do with documents:**

**Summarizing** — Perhaps the most immediately useful skill. Instead of reading a 20-page report to find the three things that matter to you, you can paste it into an AI chat and ask for what you need:

```
Summarize this document in five bullet points, focusing on the key 
recommendations and any action items for [your role or department].
```

**Extracting specific information** — Instead of scanning for details:
```
Read the document below and answer these three questions:
1. What is the proposed budget for this project?
2. What is the implementation timeline?
3. Who is listed as responsible for each phase?
[PASTE DOCUMENT]
```

**Turning notes into documents** — If you have rough meeting notes or bullet points, AI can turn them into a polished document:
```
I have rough notes from a meeting below. Please turn them into a professional 
meeting summary that includes: attendees, key decisions, action items, and next steps.
Format it clearly with headings.
[PASTE NOTES]
```

**Explaining confusing language** — Legal, medical, or technical documents often feel impenetrable:
```
Please explain the following paragraph in plain, everyday English.
Assume I have no background in [law / medicine / finance].
[PASTE PARAGRAPH]
```

### 2.5 🛠️ Activity 3: Talk to a Document

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

> ⚠️ **Watch Out:** AI can "hallucinate" when summarizing — occasionally adding details that are not in the original. Always check that a summary accurately reflects the source, especially before forwarding it to others.

## Part III — AI for Spreadsheets: No Formulas Required

For many people, spreadsheets are one of the most intimidating parts of professional life. AI changes this equation significantly — because you no longer need to know Excel syntax or formula logic to get useful analysis from your data.

### 3.1 What AI Can Do with Spreadsheet Data

| Task | Example Prompt |
| :--- | :--- |
| **Explain what the data means** | *"I have sales data by region and month. Tell me what patterns or trends stand out."* |
| **Create or fix formulas** | *"I need a formula to calculate the average of column B, but only for rows where column A says 'Florida'."* |
| **Summarize data in plain language** | *"Summarize these numbers in two sentences a non-technical manager could understand."* |
| **Spot anomalies or outliers** | *"Look at this data and tell me if anything looks unusual or unexpected."* |
| **Suggest how to visualize it** | *"What type of chart would best represent this data? Why?"* |
| **Write a narrative from numbers** | *"Turn this table of monthly expenses into a short written paragraph for a report."* |

### 3.2 Two Ways to Use AI with Spreadsheets

**Method 1 — Paste data directly into an AI chat**  
For small datasets (a few dozen rows), you can copy and paste data directly into the chat window. Most AI tools handle tabular data well when pasted as plain text.

```
Here is my data:

Month     | Revenue ($) | Expenses ($) | Profit ($)
January   | 42,000      | 31,500       | 10,500
February  | 38,500      | 29,800       | 8,700
March     | 51,200      | 34,100       | 17,100
April     | 47,800      | 33,200       | 14,600

Please answer the following:
1. Which month had the highest profit margin (profit as a % of revenue)?
2. Is there a trend in expenses over these four months?
3. Write a two-sentence summary suitable for a monthly report.
```

**Method 2 — Upload the file (ChatGPT, Claude, or Gemini with file support)**  
Paid versions of most major AI tools allow you to upload Excel or CSV files directly. The AI can then read, analyze, and answer questions about the full dataset without you needing to paste anything.

### 3.3 Prompt Templates for Spreadsheet Tasks

**Template 1 — Explain this data to me:**
```
I am going to paste/share a table of data below.
I am not a data expert. Please explain:
1. What this data appears to be tracking
2. The two or three most interesting patterns or findings
3. Anything that looks unusual or worth investigating further
[PASTE DATA OR UPLOAD FILE]
```

**Template 2 — Write a formula:**
```
I am using [Excel / Google Sheets].
I need a formula that [describe what you need it to calculate].
My data is in columns [describe which columns contain what].
Please give me the formula and explain in plain language what each part does.
```

**Template 3 — Turn numbers into a written summary:**
```
Here is a table of data: [PASTE DATA]
Please write a short paragraph (3–4 sentences) summarizing the key findings 
in plain language for a non-technical audience.
Do not use jargon. Do not list every number — focus on what matters most.
```

**Template 4 — Spot problems in the data:**
```
Please review the following data and flag anything that looks:
- Missing or incomplete
- Unusually high or low compared to the rest
- Inconsistent with what the data should logically show
[PASTE DATA]
```

### 3.4 🛠️ Activity 4: AI Meets Your Spreadsheet

**Goal:** Use AI to extract insight from a table of data without writing any formulas.

**Option A — Use your own data:**  
Find a spreadsheet you work with regularly — expense tracking, sales figures, a budget, or any table you have. Copy and paste a small section (no confidential data) into an AI chat.

**Option B — Use this sample dataset:**

Copy and paste the following into an AI chat:

```
Employee    | Department  | Sales Q1 ($) | Sales Q2 ($) | Sales Q3 ($)
Alice       | North       | 52,000       | 48,500       | 61,200
Bob         | South       | 41,300       | 43,100       | 39,800
Carol       | North       | 67,400       | 71,200       | 68,900
David       | East        | 29,500       | 31,000       | 27,400
Eva         | South       | 55,800       | 58,400       | 62,100
Frank       | East        | 38,200       | 35,900       | 41,700
```

**Try these prompts in sequence:**
1. *"Who had the highest total sales across all three quarters?"*
2. *"Which department performed best overall? Show your reasoning."*
3. *"Is there anyone whose sales are declining? Should that be a concern?"*
4. *"Write a two-sentence summary of this team's performance for a quarterly report."*
5. *"What type of chart would best visualize this data, and why?"*

**Reflect:**
- Did AI answer all questions correctly? (Check the math manually on at least one.)
- Did it offer any insight you would not have spotted yourself?
- What would you do differently if this were real business data?

> ⚠️ **Watch Out:** Always verify AI-generated calculations. AI can make arithmetic errors — particularly with percentage calculations or when the dataset is ambiguous. Use AI for insight and direction; use the spreadsheet itself for final verified numbers.

## Part IV — Putting It All Together: Your Personal Prompt Library

One of the most valuable outcomes of this class is building a **personal Prompt Library** — a collection of tested prompts you can reuse and adapt whenever you need them.

### 4.1 Assessing Prompt Quality

Before saving a prompt to your library, run it through this five-point check — adapted from the AI Literacy Program:

| Criterion | Question to Ask |
| :--- | :--- |
| **Relevance** | Did the AI's response actually address what I needed? |
| **Completeness** | Did it cover everything I asked, or did it miss parts? |
| **Clarity** | Is the output clear, readable, and well-structured? |
| **Accuracy** | Are the facts, figures, and claims correct? (Verify!) |
| **Format** | Did the output come in the format I requested? |

If a prompt scores poorly on any criterion, refine it and test again before saving it. A prompt library is only useful if the prompts in it actually work.

### 4.2 🛠️ Activity 5: Build Your Prompt Library Starter

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

**Step 5:** Save your three final prompts somewhere accessible — a notes app, a document, or a dedicated folder. You now have the beginning of a Prompt Library.

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
