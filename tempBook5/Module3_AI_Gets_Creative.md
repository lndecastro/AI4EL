# Module 3: AI Gets Creative — Images, Presentations, Music & Avatars

So far in this program, you have learned what AI is, how to talk to it, and how to use it for writing, data, and career tasks. In this class, we step into what many people find the most surprising, and most delightful, dimension of AI: **creation of visual and artistic assets**.

Until recently, generating a professional image, recording a piece of music, building a polished slide deck, or creating a speaking avatar required specialized software, significant time, and often years of training. Generative AI has fundamentally changed this. Today, anyone with a free account and a well-crafted prompt can produce visual content, music, and multimedia that would have been out of reach just a few years ago.

This class is about **exploring that creative frontier**, not as a passive observer, but as someone who creates, experiments, and makes thoughtful choices about when and how to use these tools.

> **The guiding idea of this class:** AI is a creative collaborator, not a replacement for your ideas. The most powerful creative AI outputs are the ones where a human, that is, you, provides the direction, taste, and judgment. AI supplies the execution.

## Learning Objectives

By the end of this class, you will be able to:

1. Explain how Generative AI produces creative content, such as images, music, presentations, interactive podcasts, and avatars, in plain language.
2. Write effective text prompts to generate images that match your intent.
3. Use an AI presentation tool to build a complete slide deck from an outline or description.
4. Experiment with AI music generation for personal and professional use.
5. Create and interact with AI podcasts.
6. Describe what AI avatars are and identify realistic, responsible use cases for them.
7. Apply a practical copyright and ethics framework to any creative AI output before using or sharing it.
8. Reflect on the boundary between human creativity and AI-assisted creation.

## Part I — AI and Creativity: A New Kind of Partnership

### 1.1 From Analysis to Creation: What Generative AI Produces

In Class 1, we introduced the idea that Generative AI, unlike traditional AI, does not just analyze or classify. It *creates*. It learns the underlying patterns in vast amounts of human-made content and uses those patterns to produce something new.

The table below, adapted from the AI Literacy Program, shows a broad landscape of what today's Generative AI can create:

| Input | Output | Tools You Can Use Today |
| :--- | :--- | :--- |
| Text description | **Image** | DALL·E (ChatGPT), Midjourney, Adobe Firefly, Canva AI, Gemini |
| Text description | **Music or audio** | Suno, Udio, MusicLM |
| Text outline or notes | **Presentation slides** | Gamma, Beautiful.ai, Copilot (PowerPoint), Canva AI |
| Text description | **Video clip** | Runway, Pika, Google Veo |
| Text script | **Talking avatar** | HeyGen, Synthesia, D-ID |
| Text description | **Interactive Podcast** | NotebookLM, Elevenlabs, Wondercraft |
| Text prompt | **Written content** | ChatGPT, Claude, Gemini, etc. |

:::{tip}
These tools do not think creatively, they recombine and interpolate patterns from enormous datasets of human-made content. What makes the output *creative* is the intention and judgment you bring to directing them.
:::

### 1.2 The Human-AI Co-Creation Mindset

Before we explore specific tools, it is worth establishing a mindset that will serve you well across everything in this class:

> **You are the director. AI is the production team.**

Think of yourself as a film director. You do not operate the camera, design the costumes, or compose the score yourself, but you provide the vision, make the decisions, and take responsibility for the final product. AI tools are the production team: fast, tireless, and highly capable, but entirely dependent on your direction.

This means:
- The *idea* comes from you.
- The *judgment* about whether the output is good, appropriate, and accurate comes from you.
- The *responsibility* for how the content is used comes from you.

A good creative AI workflow follows three steps:

**Generate → Evaluate → Refine.**

Rarely does the first output perfectly match your vision. Expect to iterate by adjusting your prompt, trying different options, and combining AI-generated elements with your own editing and judgment.

### 1.3 Copyright, Ethics, and Creative AI: What You Need to Know

Before generating any creative content with AI, there are important practical and ethical questions to understand. This is not meant to discourage you, instead it is meant to make you a thoughtful, responsible creator.

**Copyright and ownership:**

| Situation | What You Need to Know |
| :--- | :--- |
| **You generate an image with AI** | In most countries, AI-generated images cannot currently be copyrighted by the user. Always check the terms of service of the tool you use. Furthermore, there are many applications that do not accept the use of AI-generated images. Always check the terms of service. |
| **You generate music with AI** | Ownership varies by tool. Some platforms (e.g., Suno) retain rights to the audio; others allow commercial use. Read the terms carefully. |
| **You use AI to build a presentation** | The text, structure, and arrangement you create may be your intellectual property, but verify with the tool's terms of service. |
| **You generate content that resembles a real person** | This raises serious ethical and potentially legal concerns. Never create realistic images or voices of identifiable people without their consent. |
| **You train or fine-tune AI on someone else's art** | This is a rapidly evolving legal area. When in doubt, avoid using other artists' work as input without permission. |

**Ethical guardrails for this class:**

- ✅ Generate original creative content for personal, educational, or professional use.
- ✅ Experiment, explore, and have fun with creative tools.
- ⚠️ Be transparent when sharing AI-generated content, especially in professional or public contexts.
- ❌ Do not generate realistic images or audio of real, identifiable people without consent.
- ❌ Do not use AI-generated content to deceive, mislead, or misrepresent.
- ❌ Do not claim AI-generated work as entirely your own in contexts where that would be dishonest (academic submissions, professional portfolios).

:::{note}
When in doubt, disclose. Saying *"I created this with AI assistance"* is a sign of transparency and integrity, not weakness.
:::

## Part II — AI-Generated Images

### 2.1 How Image Generation Works

You type a prompt and the AI generates an image that matches it. The AI was trained on hundreds of millions of images paired with text descriptions, so it has learned the visual patterns associated with an enormous range of subjects, styles, moods, and compositions.

The most widely used image generation technology today is called **diffusion**: the AI starts from random visual noise and gradually refines it, step by step, into a coherent image that fits your description. Think of it like a photograph slowly developing in a darkroom, guided by your words.

### 2.2 The Major Image Generation Tools

| Tool | Access | Best For |
| :--- | :--- | :--- |
| **DALL·E** (inside ChatGPT) | Free / Paid (ChatGPT Plus) | Quick generation; easy to use; integrated with ChatGPT |
| **Adobe Firefly** | Free (with Adobe account) | Professional, commercially safe images; integrates with Photoshop and Canva |
| **Canva AI** (Magic Media) | Free / Paid | Social media graphics, presentations, and marketing materials |
| **Gemini** (Google) | Free | Image generation integrated with Google tools |
| **Grok** (xAI / X) | Free / Paid (X Premium) | Creative and photorealistic images; integrated with X (formerly Twitter) |
| **Midjourney** | Paid (subscription) | High-quality artistic and stylized images; popular with designers |
| **Microsoft Designer** | Free (Microsoft account) | Image generation integrated with Microsoft 365 tools |

:::{tip}
**Recommendation for beginners:** Start with **DALL·E inside ChatGPT** or **Canva AI**. Both are free, easy to access, and produce high-quality results without any setup.
:::

### 2.3 Prompting for Images: Describing What You Want

Image prompting is different from text prompting. Instead of instructions, you are writing a *description of what you want to see*. The more vivid and specific your description, the more precise the result.

**The anatomy of an effective image prompt:**

| Element | What It Does | Example |
| :--- | :--- | :--- |
| **Subject** | What is the main focus of the image? | *"a golden retriever puppy"* |
| **Setting** | Where is it? What is the environment? | *"sitting on a sunlit porch in a Florida neighborhood"* |
| **Style** | What visual style do you want? | *"watercolor painting"* / *"professional photograph"* / *"flat design illustration"* |
| **Mood or lighting** | What feeling or atmosphere? | *"warm, golden hour light"* / *"moody and dramatic"* |
| **Composition** | Any specific framing or angle? | *"close-up portrait"* / *"wide landscape shot"* |
| **Color palette** | Any specific colors? | *"soft pastel tones"* / *"black and white"* |

**From weak to strong — image prompt example:**

*Weak prompt:*
```
A dog on a porch.
```

*Strong prompt:*
```
A golden retriever puppy sitting on a sunlit wooden porch in a quiet 
Florida suburban neighborhood, surrounded by potted tropical plants. 
Warm golden hour light. Professional lifestyle photograph. 
Shallow depth of field, soft background blur.
```

The second prompt gives the AI enough specific detail to generate something genuinely close to what you envision.

**Useful style keywords to know:**

- *Photorealistic*: looks like a real photograph
- *Watercolor*: soft, painted look with visible brushstrokes
- *Flat design*: simple, bold colors with no shadows (common in app icons and infographics)
- *Oil painting*: rich textures, painterly feel
- *Minimalist*: clean, simple, lots of white space
- *Vintage / retro*: aged look, old color palettes
- *Cinematic*: dramatic lighting, movie-like framing

### 2.4 Activity 1: Generate Your First Image

**Goal:** Experience image generation and learn through iteration.

**Step 1 — Access an image generation tool**  
Go to [chatgpt.com/images](https://chatgpt.com/images) (free, uses DALL·E) or [canva.com/ai](https://canva.com/ai) → Magic Media, or [designer.microsoft.com](https://designer.microsoft.com).

**Step 2 — Try a simple prompt first**
```
A cozy coffee shop on a rainy afternoon.
```
Observe the result. What did AI decide about style, color, and mood that you did not specify?

**Step 3 — Add detail and specificity**  
Now try a richer version of the same scene:
```
A cozy independent coffee shop interior on a rainy afternoon. 
Warm amber lighting from hanging Edison bulbs. 
Wooden tables, steaming mugs, and large rain-streaked windows 
showing a blurred city street outside. 
Photorealistic style. No people in the image.
```

**Step 4 — Try a practical use case**  
Think of something you could genuinely use an image for:
- A social media post for a community event
- A background for a presentation slide
- A greeting card illustration
- A logo concept for a small business or hobby

Write a prompt for that specific use case and generate it.

**Step 5 — Request changes and see AI adapt**  
Take the image you generated in Step 3 and ask the AI to change one element of the scene. 
You are not starting over, you are refining. Try prompts like these:

*Change the weather:*
```
Change the scene to a bright sunny morning. 
Keep everything else the same.
```
*Change the season:*
```
Make it a snowy winter evening outside the window instead of rain. 
Keep the warm interior lighting.
```
*Change the mood or time of day:*
```
Change the lighting to late evening. 
Add a candle on each table for a more intimate atmosphere.
```

Notice how much, or how little, the AI carries over from the original image. Does it preserve the details you wanted to keep? This is how real users work with AI image tools: not by starting from scratch every time, but by iterating toward the result they need.

**Step 6 — Reflect**
- How did adding detail change the output?
- Did the AI interpret anything differently than you expected?
- When you requested changes in Step 5, what did the AI keep, change, or lose?
- Is the result something you would actually use? What would you change?

:::{warning}
AI image generators can occasionally produce images with distorted hands, inconsistent text, or unintended content. Always review before sharing. If a generated image looks "almost right," try refining your prompt with more specific detail.
:::

## Part III — AI for Presentations

### 3.1 Why AI Presentation Tools Are a Game-Changer?

Creating a presentation has traditionally required three separate skills: organizing your ideas, designing slides that look professional, and deciding what to put on each one. AI presentation tools collapse all three into a single, guided process, often producing a complete, designed deck in a few minutes.

This does not mean the result is ready to present without your input. It means you skip the blank-slide problem entirely and start from something you can refine, rather than something you have to build from scratch.

### 3.2 Some Major AI Presentation Tools

| Tool | Access | What Makes It Distinctive |
| :--- | :--- | :--- |
| **Gamma** (gamma.app) | Free / Paid | Best overall for speed and design quality; generates full decks from a prompt or outline |
| **Canva AI** | Free / Paid | Strong design templates; integrates with existing Canva workflows |
| **Beautiful.ai** | Paid | Sophisticated design automation; good for professional business decks |
| **Copilot in PowerPoint** | Paid (Microsoft 365 Copilot) | AI assistance inside familiar PowerPoint; ideal if you already use Microsoft 365 |
| **Google Slides + Gemini** | Free (Google Workspace) | AI assistance inside Google Slides for Workspace users |
| **Tomeapp.ai** | Free / Paid | Story-driven presentations with a narrative focus |

:::{tip}
Start with **Gamma**, as it is free, requires no design experience, and produces fast and impressive results from a simple text description.
:::

### 3.3 How AI Builds a Presentation

Most AI presentation tools follow this workflow:

**Step 1 — You describe what you need**  
Either in a text prompt (*"Create a 6-slide presentation about the benefits of volunteering in your local community"*) or by pasting an outline, a document, or even bullet points.

**Step 2 — AI generates a structured deck**  
The tool creates a slide-by-slide structure with titles, content, and visual design. Slides are organized logically based on your input.

**Step 3 — AI selects or generates visuals**  
Most tools automatically add images, icons, or illustrations to complement each slide's content.

**Step 4 — You review, edit, and refine**  
This step is critical. Review every slide. Edit any content that is inaccurate, generic, or does not sound like you. Replace placeholder images that do not fit. Add your own examples, data, or stories.

**Step 5 — Export and present**  
Most tools export to PDF, PowerPoint, or Google Slides.

### 3.4 Prompt Templates for AI Presentations

**Template 1 — Build from a topic:**
```
Create a [X]-slide presentation about [topic].
Audience: [describe who will see it — colleagues, community members, students, etc.]
Purpose: [inform / persuade / train / inspire]
Tone: [professional / friendly / educational / conversational]
Include: an opening slide, [specific sections you want], and a closing slide 
with key takeaways or a call to action.
```

**Template 2 — Build from your own content:**
```
I have the following notes and bullet points. 
Please turn them into a structured [X]-slide presentation.
Organize the content logically, write clear slide titles,
and suggest one image or visual concept for each slide.
Here are my notes:
[PASTE YOUR NOTES OR OUTLINE]
```

**Template 3 — Improve an existing presentation:**
```
Here is the content from my current presentation.
Please review it and suggest:
1. A more compelling title for each slide
2. Any content that could be cut to reduce clutter
3. A stronger opening slide that immediately engages the audience
[PASTE YOUR CURRENT SLIDES' TEXT]
```

### 3.5 Activity 2: Build a Presentation with AI

**Goal:** Experience AI-assisted presentation creation from prompt to polished deck.

**Step 1 — Choose your topic**  
Pick something you might genuinely present: a project update, a community initiative, a hobby, a simple how-to, or anything you know well.

**Step 2 — Go to Gamma.app**  
Visit [gamma.app](https://gamma.app) and create a free account. Click "New AI" and choose "Presentation."

**Step 3 — Enter your prompt**  
Using Template 1 as a guide, write a clear description of what you need. Be specific about audience, tone, and what you want on each slide.

**Step 4 — Review the generated deck**  
Go through every slide. For each one, ask:
- Is this content accurate?
- Does it reflect what I actually want to say?
- Is this how I would say it?
- Does the image or visual fit?

**Step 5 — Make at least three edits**  
Change a title, rewrite a bullet point in your own voice, replace an image, or add a personal example. This step is crucial; it is what makes the presentation *yours*.

**Reflect:**
- How long did the full process take, compared to building slides from scratch?
- What did AI get right without being told?
- What required your correction or personal touch?
- Would you use this tool again? For what situations?

:::{warning}
AI-generated presentations often use generic language and stock imagery. They are strong starting points but weak final products without your editing. Never present AI-generated slides without reading every word first, as errors and inaccuracies do appear.
:::

### 3.6 Activity 3: Prompt a Presentation

**Goal:** Use Claude to generate a complete, slide-by-slide presentation from a single detailed prompt, then refine it through conversation.

**Step 1 — Choose your topic**

Pick something you might genuinely present: a project update, a community initiative, a hobby, a simple how-to, or anything you know well. You will use this same topic throughout the activity.

**Step 2 — Open Claude and write your presentation prompt**

Go to [claude.ai](https://claude.ai) and start a new conversation. Use the template below as your starting point. Fill in the blanks before you send it.

**Full Presentation Prompt**
```
"Please create a complete slide-by-slide presentation on the topic of **[your topic]**.
The audience is **[describe your audience, for example: coworkers, community members, students, neighbors]**.
The tone should be **[choose one or two: friendly, professional, inspiring, informative, conversational]**.
The presentation should have **[number, e.g., 6–8]** slides and last approximately **[time, e.g., 10 minutes]**.

For each slide, please provide:
- A clear slide title
- Three to five bullet points or a short paragraph of content
- A brief speaker note suggesting what I might say out loud

Start with a title slide and end with a closing or call-to-action slide."
```

**Step 3 — Review Claude's output**

Read through every slide carefully. For each one, ask yourself:

- Is this content accurate and true to my topic?
- Does it reflect what I actually want to say?
- Is this how I would naturally say it, or does it sound generic?
- Are the speaker notes helpful and realistic?
- Is anything missing, off-topic, or awkward?

**Step 4 — Refine your Presentation**

If the model generated the PPTX file for you, you can download and refine it as you wish.

**Step 5 — Make the presentation yours**

Go back through every slide and make at least three personal edits:

- Replace a bullet point with a specific example from your own experience.
- Rewrite a sentence in your own voice, the way you would actually say it.
- Add, remove, or reorder a slide based on what feels right for your audience.
- Adjust any wording that sounds too formal, too casual, or just "not like you."

This step is not optional. AI-generated content reflects a general voice, not yours. Editing is how you take ownership of the material.

**Reflect:**

- How did the quality of the model first output compare to what you expected?
- Which follow-up prompts made the biggest difference?
- What did the model handle well without being told?
- What required your personal knowledge or judgment to fix?
- How does working with a general-purpose LLM compare to building slides from scratch? To using a dedicated tool like Gamma?
- In what situations would you use this approach in the future?

:::{warning}
Claude generates text based on patterns and general knowledge, but it does not know your audience, your organization, or your personal style unless you tell it. Always verify facts, names, and specific figures before presenting. A polished-sounding slide is not the same as an accurate one. Read every word before you stand in front of an audience.
:::

## Part IV — AI Music and Audio

### 4.1 What AI Music Tools Can Do

AI music generation tools create original audio, instrumentals, songs with lyrics, ambient soundscapes, and more, from a text description. You do not need to play an instrument, read music, or have any audio production skills.

Modern tools like **Suno** and **Udio** can generate a two-minute song, complete with vocals, melody, and instrumentation, in less than 30 seconds, and for free.

**What you can create:**
- Background music for presentations, videos, or events
- A simple jingle for a small business or community organization
- Ambient sound for focus or relaxation
- Experimental creative pieces for personal enjoyment
- A personalized birthday or celebration song

### 4.2 Some Major AI Music Tools

| Tool | Access | What It Does |
| :--- | :--- | :--- |
| **Suno** (suno.com) | Free / Paid | Full songs with vocals and instrumentation from a text prompt; extremely easy to use |
| **Udio** (udio.com) | Free / Paid | High-quality music generation; strong for varied genres |
| **MusicLM** (Google) | Via Google Labs | Research-grade music generation; accessible through Google tools |
| **Mubert** | Free / Paid | AI-generated royalty-free background music for videos and content |
| **Soundraw** | Paid | Customizable AI music for creators and content producers |

### 4.3 Prompting for Music: Describing What You Want to Hear

Music prompts describe the *sound, mood, genre, and feel* of what you want, not instructions for how to compose it.

**Useful descriptive elements for music prompts:**

| Element | Examples |
| :--- | :--- |
| **Genre** | Jazz, classical, pop, lo-fi, folk, gospel, electronic, bossa nova |
| **Mood** | Uplifting, melancholic, energetic, peaceful, dramatic, playful |
| **Tempo** | Slow and gentle, mid-tempo, fast and driving |
| **Instruments** | Piano, acoustic guitar, strings, brass, synthesizer |
| **Vocals** | Instrumental only, female vocals, male vocals, choral |
| **Setting or use** | Background music for a presentation, party music, study music |

**Example music prompts:**

*For a community event:*
```
Uplifting and warm acoustic folk music, gentle guitar and light percussion,
moderate tempo, feel-good and community-spirited, no vocals, 
suitable as background music for a neighborhood gathering.
```

*For a fun birthday song:*
```
A playful, catchy birthday song in a pop style. 
Happy and celebratory lyrics about turning another year older.
Upbeat tempo, bright piano melody, clapping rhythm.
```

*For focus while working:*
```
Calm lo-fi instrumental music. Soft piano, light ambient textures,
slow tempo, no sudden changes, peaceful and focused.
```

### 4.4 Activity 4: Create an AI Music Piece

**Goal:** Generate an original piece of audio from a text description.

**Step 1 — Visit Suno**  
Go to [suno.com](https://suno.com) and create a free account. You receive a set of free generation credits each day.

**Step 2 — Describe your music**  
Click "Create" and type a prompt describing what you want to hear. You can describe the genre, mood, instruments, and any lyrics or theme.

Try one of these to start:
Option A: 
```
"Cheerful tropical acoustic music, ukulele and light percussion, 
no vocals, perfect for a summer event."
```
Option B: 
```
"An uplifting gospel-inspired song about community and coming together, 
soulful female vocals, piano and choir."
```
Option C: 
```
"Lo-fi jazz instrumental, mellow and relaxed, late night coffee shop 
atmosphere, saxophone and piano."
```

**Step 3 — Listen and evaluate**
- Does it match the mood you imagined?
- Is there anything you would change about the description to get a different result?
- Can you think of a real situation where you might use music like this?

**Step 4 — Try a second generation with a refined prompt**  
Adjust one or two elements in your description and generate again. Compare the two outputs.

:::{warning} 
Always check the **terms of service** of the music tool you use before sharing or publishing AI-generated music. Free tiers of some tools (including Suno's basic plan) may restrict commercial use. For personal and educational use, this is generally not a concern.
:::

## Part V — AI Avatars and Synthetic Voices

### 5.1 What AI Avatars Are

An **AI avatar** is a realistic digital human, that is, a video of a person speaking, generated entirely by AI from a text script or audio input. You provide the words; the AI creates a lifelike video of a human figure reading them.

Similarly, **AI voice tools** can clone a voice or generate a new synthetic voice that sounds natural and human, reading any text you provide.

These technologies are genuinely impressive, and they come with significant ethical responsibilities.

### 5.2 Some Avatar and Voice Tools

| Tool | Access | What It Does |
| :--- | :--- | :--- |
| **HeyGen** (heygen.com) | Free trial / Paid | Generates realistic avatar videos from a text script; multiple avatar styles |
| **Synthesia** (synthesia.io) | Free trial / Paid | Professional avatar video creation; widely used in corporate training |
| **D-ID** (d-id.com) | Free trial / Paid | Animates still photos to speak; generates avatar videos |
| **ElevenLabs** (elevenlabs.io) | Free / Paid | High-quality AI voice generation and voice cloning |
| **Murf AI** (murf.ai) | Free / Paid | AI voiceovers for presentations and videos |

### 5.3 Realistic Use Cases

**Where avatars and AI voices are genuinely useful:**

- **Training videos**: create professional instructional content without recording yourself on camera.
- **Presentation narration**: add a voiceover to your slides without recording a live audio track.
- **Multilingual content**: generate the same content in multiple languages without a human translator recording it.
- **Accessibility**: convert written content to spoken audio for audiences who prefer or need it.
- **Personal projects**: create a narrated story, a digital greeting, or a fun creative project.

**Where to be cautious:**

- ❌ Creating a realistic avatar or voice of a real, identifiable person without their consent. This is a serious ethical violation and potentially illegal in many jurisdictions.
- ❌ Using AI avatars to impersonate someone in a professional or public context.
- ❌ Generating synthetic media designed to deceive viewers into thinking they are watching a real person.

:::{warning}
💡 **The deepfake problem:** AI-generated videos of real people saying things they never said, known as *deepfakes*, represent one of the most serious misuse risks of this technology. Being able to *identify* AI-generated video (look for unnatural blinking, odd lip sync, or perfect-but-somehow-wrong faces) is becoming an important general literacy skill.
:::

### 5.4 Activity 5: Explore an AI Avatar or Voice Tool

**Goal:** Experience what AI avatar and voice technology can produce and develop a critical eye for evaluating synthetic media.

**Option A — Create a simple avatar video (HeyGen or Synthesia):**  
Visit [heygen.com](https://heygen.com) or [synthesia.io](https://synthesia.io) and use the free trial.
1. Choose an avatar from the available options (do not use real people).
2. Type a short script, e.g. your name, a greeting, and one sentence about a topic you care about. Feel free to prompt the script to be used by the avatar.
3. Generate the video and watch it.

**Option B — Generate an AI voice narration (ElevenLabs or Murf):**  
Visit [elevenlabs.io](https://elevenlabs.io) (free tier available).
1. Choose a voice from the options.
2. Type a short paragraph, e.g. a description of your town, a tip you would share with a friend, or a personal introduction. Feel free to prompt the script to be used by the avatar.
3. Generate and listen.

**Reflect on both options:**
- How realistic does the result feel to you?
- What tells you (if anything) that this is not a real person?
- What are two legitimate uses of this technology you can imagine?
- What is one misuse scenario that concerns you?

## Part VI — AI for Real-Life Creative Projects

Everything you have practiced in this class, including generating images, building presentations, creating music, and exploring avatars, comes together when you apply it to real, meaningful projects. In this section, you will work on two hands-on creative challenges that many people encounter in everyday and professional life: a digital event invitation and building a brand from scratch.

These activities are more open-ended than earlier ones. There is no single right answer. The goal is for you to practice directing AI through a multi-step creative project and to experience the full creative loop of **Generate → Evaluate → Refine**.

### 6.1 Activity 6: Create a Digital Birthday Party Invitation

**Goal:** Use AI to design and produce a beautiful, interactive digital birthday party invitation, ready to share via link, email, or social media.

A digital invitation is a perfect creative AI project: it has a clear purpose, a real audience, a specific set of content (date, time, place, RSVP), and room for personality and visual creativity. You can choose to create this as an **interactive webpage**, a **designed graphic**, or a **structured document**, whichever best suits your needs.

**Step 1 — Define the invitation details**

Before prompting AI, decide on the basics:
- **Whose birthday is it?** (Use a real name, a nickname, or make one up for practice.)
- **What is the theme or vibe?** (Elegant, tropical, kids' party, cozy gathering, surprise party, outdoor barbecue, etc.)
- **What are the key details?** Date, time, location, dress code (if any), RSVP contact.
- **What format do you want?** A styled HTML webpage, a printable card graphic, or a social media post?

:::{tip}
Having clear answers to these questions before you start will dramatically improve your AI outputs. Do not skip this step, as it is the "director's brief" that guides everything that follows.
:::

**Step 2 — Generate a written invitation text**

Start by asking AI to write the invitation copy:

```
Please write a fun, warm, and creative birthday party invitation for the following event:

Name: [Name]
Theme/vibe: [e.g., tropical luau, elegant garden party, surprise 80s party]
Date: [Date]
Time: [Time]
Location: [Address or venue name]
RSVP: [Contact method — phone, email, or "None for practice"]
Special note: [e.g., "Surprise party — please don't tell!", "Kids welcome", "Casual dress"]

Write the invitation in a tone that matches the theme. 
Include a catchy headline, the key event details, 
and a fun closing line that encourages people to come.
```

**Step 3 — Generate the interactive digital invitation as a webpage**

Once you have the text, use this prompt to create a fully designed, interactive HTML invitation:

```
Using the invitation text below, please create a complete, 
beautiful HTML webpage for a digital birthday party invitation.

Design requirements:
- Visually match the theme: [describe your theme again, i.e. colors, mood, imagery style]
- Include animated or decorative elements appropriate to the theme 
  (e.g., floating confetti, subtle sparkle effect, or a festive background pattern)
- Display all event details clearly: name, date, time, location, RSVP
- Include a simple RSVP section with "Yes, I'll be there! 🎉" and 
  "Sorry, I can't make it 😢" buttons that show a friendly confirmation message when clicked
- Mobile-friendly layout (works well on both phone and desktop)
- No external images required; use CSS, emoji, and inline design only
- Everything should be in one self-contained HTML file

Invitation text:
[PASTE YOUR INVITATION TEXT FROM STEP 2]
```

> 💡 **What you get:** A single `.html` file you can open in any browser, share as an attachment, or host on a free platform like GitHub Pages, Netlify Drop, or Google Sites.

**Step 4 — Optionally generate a matching visual**

Use an image generation tool (ChatGPT, Grok, Adobe Firefly, or Canva AI) to create a matching banner or background image for your invitation:

```
Create a festive illustration for a birthday party invitation with a [theme] theme.
Style: [watercolor / flat design / photorealistic / cartoon]
Colors: [describe the palette that matches your invitation]
Include: [any specific elements, e.g. balloons, flowers, tropical plants, vintage patterns, etc.]
No text in the image. Horizontal format, suitable as a website banner.
```

**Step 5 — Review and personalize**

Open the HTML file in your browser. Ask yourself:
- Does it feel right for the person and the occasion?
- Is all the information accurate and clearly readable?
- Does the design match the theme you had in mind?

Make at least two edits, such as change a color, adjust the wording, or add a personal touch.

**Reflect:**
- How long did the full process take?
- What did AI get right about the theme and design without being told?
- What would you have done differently with the design if AI had not been involved?
- Can you think of other events where a quick AI-generated digital invitation would save you significant time?

### 6.2 Activity 7: Plan a Company with AI — Brand Identity and Website

**Goal:** Use AI to move through three stages of building a new business or organization: strategic planning, visual identity, and website creation.

This activity is one of the most expansive in the program, and one of the most practical. Whether you are dreaming of starting a business, building a side project, launching a community organization, or just exploring what is possible, AI can take you from a simple idea to a complete brand and online presence in a single session.

You will work through three stages: **Plan → Brand → Build.**

> 💡 **This activity is deliberately open-ended.** Use a real business idea you have been thinking about, a passion project, a community initiative, or a completely imagined concept. The process is the same regardless.

#### Stage 1 — Plan: Define the Core Components of Your Company

**Start with this prompt:**

```
I want to start a [type of business or organization]. 
Here is what I have in mind so far: [1–3 sentences describing your idea].

Please help me define the following foundational components:

1. Business name: Suggest 5 creative, memorable name options that reflect 
   the nature and values of this business. For each, explain the reasoning.
2. Mission statement: One sentence that captures what the business does 
   and why it matters.
3. Vision statement: One sentence about the long-term impact or aspiration.
4. Core values: 3–5 values with a one-line explanation each.
5. Target audience: Who are the ideal customers or clients? 
   Describe them in plain terms (age range, needs, lifestyle, goals).
6. Key products or services: List 3–5 core offerings with a one-line description each.
7. Unique value proposition: In one sentence, what makes this business 
   different from others in the same space?
```

Review the output, pick the name you like best, and move to Stage 2.

#### Stage 2 — Brand: Create the Visual Identity

With your business concept defined, use AI to develop a complete **visual identity** - the look, feel, and visual language of your brand.

**Prompt 1 — Brand personality and color palette:**
```
Based on this business concept: [paste your mission, audience, and value proposition from Stage 1]

Please create a complete brand personality and visual identity guide including:

1. Brand personality: Describe the brand in 5 adjectives and explain 
   what they mean for how the brand should look and communicate.
2. Color palette: Suggest a primary color, a secondary color, 
   and an accent color. For each, provide the hex code, the name, 
   and explain why it fits this brand.
3. Typography suggestion: Recommend a heading font and a body text font 
   (use Google Fonts options). Explain the choice.
4. Logo concept: Describe in words a logo concept that fits this brand — 
   the symbol or mark, the style, and how the name would appear alongside it.
5. Visual style guide: In 3–4 sentences, describe the overall visual direction 
   (photography style, illustration style, layout feel) for this brand.
```

**Prompt 2 — Generate a logo concept image:**

Take the logo description from the AI's response and use it to generate a visual with an image tool:

```
Create a minimalist logo for a company called "[Your Business Name]".
[Paste the logo concept description from the AI's brand guide.]
Clean white background. Professional, modern style.
Include the company name in the logo in [your chosen font style].
```

:::{note}
AI image tools sometimes struggle with precise text in logos. If the text does not render correctly, generate the icon/symbol separately and add the business name using Canva, Google Slides, or any basic design tool.
:::

#### Stage 3 — Build: Create the Company Website

With your brand identity in place, use AI to build a complete one-page company website.

**Prompt:**
```
Using the brand information below, please create a complete, 
professional one-page company website as a single HTML file.

Brand information:
- Business name: [name]
- Mission: [mission statement]
- Target audience: [description]
- Products/services: [list]
- Unique value proposition: [statement]
- Color palette: Primary: [hex], Secondary: [hex], Accent: [hex]
- Brand personality: [adjectives]

Website sections to include:
1. Hero section: business name, tagline, and a prominent call-to-action button
2. About section: who we are and what we stand for (2–3 sentences)
3. Services/Products section: the 3–5 key offerings with a short description each
4. Why Us section: 3 short points highlighting the unique value proposition
5. Contact section: a simple contact form (name, email, message fields) 
   and placeholder contact details
6. Footer: business name, copyright year, and navigation links

Design requirements:
- Use the brand colors throughout (header, buttons, accents)
- Clean, modern, mobile-responsive layout
- Professional typography matching the brand personality
- Smooth scroll navigation
- All in one self-contained HTML file, no external dependencies
```

**Review and refine:**
- Does the website accurately represent the business idea?
- Does the design feel consistent with the brand personality?
- What would you change, add, or remove?

Use follow-up prompts to make specific adjustments:
```
Please add a customer testimonials section between the Services and Why Us sections.
Make the hero section background use a subtle gradient of our primary and secondary colors.
```

**Full Activity Reflection:**
- What surprised you about how quickly AI could produce a business concept and brand?
- Which stage — planning, branding, or building — did AI handle most impressively?
- Which stage required the most of your own judgment and editing?
- How would this compare to hiring a freelancer or agency to do the same work?
- What are the risks of using AI-generated brand materials without involving a professional designer?

:::{note}
**A note on professional use:** For a real business, AI-generated brand materials are an excellent starting point, but professional designers bring strategic thinking, cultural nuance, and refinement that AI cannot fully replicate. Use AI to explore and prototype; bring in professionals when it really counts.
:::

## Part VII — Putting Creative AI in Perspective

### 7.1 What Distinguishes Human Creativity from AI Generation?

This is one of the most important questions of our time, and there is no single right answer. But it is worth thinking about carefully.

AI can produce:
- Images that are technically flawless and visually striking.
- Music that follows established harmonic and rhythmic patterns.
- Presentations that are well-structured and professionally designed.
- Videos of humans speaking any words you provide.

What AI cannot produce, at least not yet, and perhaps not ever, is:

- **Genuine intention**: the reason behind the creation, the message you are trying to send.
- **Lived experience**: the personal history, emotion, and perspective that give creative work meaning.
- **Ethical judgment**: the ability to decide what *should* be created, not just what *can* be created.
- **Accountability**: the willingness to take responsibility for what the work communicates and how it is received.

> The most powerful creative uses of AI are the ones where your intention is clear, your judgment shapes the output, and the final result carries your voice, even if AI generated the first draft.

### 7.2 A Practical Creative AI Ethics Checklist

Before sharing any AI-generated creative content — publicly, professionally, or personally — run through this quick check:

- [ ] **Accuracy**: Does the content accurately represent what I claim it does?
- [ ] **Consent**: Does any content involve real people? Do I have their consent?
- [ ] **Transparency**: Am I being honest about the role AI played in creating this?
- [ ] **Ownership**: Have I checked the tool's terms of service for commercial or public use?
- [ ] **Harm**: Could this content mislead, deceive, demean, or harm anyone?
- [ ] **Purpose**: Is this the right tool and the right approach for this particular goal?

If you can check all six boxes with a clear conscience, you are using creative AI responsibly.

### 7.3 Reflection

> What surprised you most about what AI can create today?  
> Where do you see yourself using any of these creative tools in the next month — personally or professionally?  
> What does it mean for something to be *your* creative work if AI generated the first draft — or most of it?  
> Where do you think the line should be drawn between useful AI assistance and problematic AI replacement in creative fields?

These are not abstract philosophical questions — they are practical ones that more and more professionals, educators, artists, and organizations are wrestling with right now. Developing your own thoughtful position on them is part of becoming a confident, responsible AI user.

### 7.4 What Is Coming in Class 4

Our final class brings everything together, and adds one critical layer that ties the whole program together: **knowing when to trust AI, how to protect yourself, and how to build habits that last**.

In Class 4, you will:
- Apply a **verification-first framework** to any AI output, creative or otherwise.
- Learn what to keep private and how your data is used by AI tools.
- Build your **personal AI toolkit** — a curated set of tools, prompts, and habits tailored to your life.
- Leave with a **Personal AI Action Plan**: three concrete habits you will start this week.

## 📋 Class 3 Summary Checklist

Before you move on, confirm that you can do the following:

- [ ] Describe, in plain language, how AI generates images, music, and video from text prompts.
- [ ] Write an effective image prompt using subject, setting, style, mood, and composition.
- [ ] Use an AI presentation tool to generate a structured slide deck from a prompt or outline.
- [ ] Generate a short AI music piece using descriptive prompts for genre, mood, and instruments.
- [ ] Describe at least two legitimate use cases for AI avatars or synthetic voice tools.
- [ ] Apply the six-point creative AI ethics checklist before sharing AI-generated content.
- [ ] Articulate in your own words what distinguishes human creative intent from AI generation.
- [ ] Use AI to create a themed, interactive digital invitation as a self-contained HTML webpage.
- [ ] Use AI to define the core components of a business (name, mission, values, audience, services).
- [ ] Use AI to generate a brand identity guide including color palette, typography, and logo concept.
- [ ] Use AI to build a complete one-page company website from a brand brief.

## 📘 Further Reading

- **Mollick, E. (2024).** *Co-Intelligence: Living and Working with AI.* Portfolio/Penguin. *(Chapter 5 addresses AI and creative work in depth.)*
- **Dendritic Institute. (2025).** *AI Literacy Program — Module 4: Generative AI and Large Language Models.* FGCU AI Academy. *(Full treatment of how generative models create content.)*
- **Dendritic Institute. (2025).** *AI Literacy Program — Module 7: Foundational Models and General-Purpose LLMs.* FGCU AI Academy. *(Comparative overview of all major AI platforms covered in this class.)*
- **Adobe. (2024).** *Content Credentials: Understanding AI-Generated and Edited Content.* adobe.com/content-credentials.
- **Creative Commons. (2024).** *AI and Copyright: What Creators Need to Know.* creativecommons.org.
- **Suno AI. (2024).** *Terms of Service and Creator Rights.* suno.com/terms.
- **Synthesia. (2024).** *Ethical AI Policy for Avatar Creation.* synthesia.io/ethical-policy.
- **Partnership on AI. (2023).** *Responsible Practices for Synthetic Media.* partnershiponai.org.

```{note}
*Class 3 is part of the AI for Everyday Life Program, offered by the Dendritic Institute for Human-Centered AI & Data Science at Florida Gulf Coast University. All hands-on activities in this class can be completed using free tiers of the tools listed. No design, music, or technical background is required.*
```
