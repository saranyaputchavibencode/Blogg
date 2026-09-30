# What Happens When AI Joins the Interview? AgentR blog rewrite

## 1. Style summary: patterns across all 30 AgentR blog posts

1. **Titles are claims, not topics.** Most are one or two short declarative sentences, often with a number or a twist: *"The Candidate Cleared Every Screen. The Candidate Wasn't Real."*, *"93% of Candidates Admit They Lied. Only 26% Were Ever Caught."* Question titles only show up on search-style explainers (*"Can AI Screening Be Audited for Bias?"*).
2. **Every post has a one- or two-sentence subtitle (lede)**, usually a stat plus a turn, or a crisp reframe: *"A number without a reason isn't a decision. It's a guess with better formatting."*
3. **The byline is fixed:** Prateek Porwal · date · X min read. Posts run about 800 to 2,500 words (3 to 11 min), and most land between 1,300 and 2,000.
4. **Openings are cold.** The first line is a scene, a story or a number, never "In this article…". Short standalone lines are used for punch: *"They never hear back."* / *"Your ATS gives a candidate a score of 84. What does that mean?"*
5. **Structure is 4 to 7 H2 sections, and each heading is itself an argument**, e.g. *"The interview isn't a check anymore. It's an attack surface."*, *"Every defense escalates in the wrong direction."* Sections are 2 to 5 prose paragraphs. Bullet lists and pull quotes are rare (only 2 of 30 posts use them). There are no TL;DR boxes and no "Key takeaways" boxes.
6. **The voice sounds like a sharp, skeptical insider.** It talks to the hiring team as "you" and uses "we" sparingly (*"We've written before about candidates who aren't real…"*). It leans on "It isn't X. It's Y." contrasts: *"You cannot out-proctor a teleprompter."* / *"That's a choice. Not a law of nature."*
7. **Hiring pain is described as a broken system, not as recruiters failing.** Recruiters are sympathetic, and the process or the tools are the villain: *"The screening stack did exactly what it was designed to do."*
8. **AgentR is kept out of the body.** In most posts it appears only in the last paragraph. That paragraph opens *"AgentR evaluates candidates on…"* and ends *"Let's talk."*
9. **The newer posts (Aug to Sep 2026) add a candid "Where AgentR fits, and where it doesn't" section** that names its limits: *"AgentR is also currently in private beta and hasn't published bias-audit data of its own…"* The explainer posts also end with **"Questions People Ask"** (H3 questions with 2 to 3 sentence answers) and a **"Related Reading"** line linking other posts.
10. **Claims are sourced and caveated.** Posts say where a number comes from and what it doesn't prove, e.g. *"a reason to read the exact percentages as directional rather than final."* Spelling is mixed British and US, and the newest posts lean US.

---

## 2. The rewritten post

**Title:** We Put AI on Both Sides of an Interview. Here's What Happened.
*(Search-friendly alternative, in the style of the explainer posts: "What Happens When AI Joins the Interview?")*

**Subtitle / meta description:** Candidates can now bring AI into the interview itself, not just the prep. Interviewers can bring it too. We ran one interview on AgentR to see what happens when both show up.

**Byline:** [Author] · [Date] · 7 min read

---

For most of the last few years, AI's job in hiring ended at the door.

Candidates used it to tighten a resume, research the company, run mock interviews and practice their answers until they sounded right. Then they walked into the interview on their own.

That's no longer how it works. AI now sits beside the candidate during the interview and takes part in it, in real time. And it can sit on the other side of the table too. Interviewers can now use AI as well.

So what actually happens when AI joins the interview?

We ran an experiment to find out. One realistic interview, run on AgentR, using the methods candidates already use. Here's what happened.

## Preparation was never the problem

AI changed interviews before the interview even started. Candidates use it to improve their resumes, research a company, do mock interviews, practice, and polish both their answers and the way they come across.

None of that is a problem. Preparation has always been part of the interview. A candidate who reads up on your company and rehearses their stories is doing exactly what candidates have always been told to do. AI just made the homework faster.

The problem starts when AI stops being the coach and joins the interview itself.

## The questions change once the help is live

Once AI is in the room, the questions get harder.

What happens when a candidate gets help during the interview?

What happens when the answers sound completely natural and human, but a human isn't the one arriving at them?

What happens when the interviewer can't tell the difference?

And what happens when it can?

Those are the questions we wanted to watch play out on a real interview, not argue about in the abstract.

## The experiment: one interview, run the way AgentR runs it

The setup was simple. AgentR conducted the interview the way it normally would. Then we introduced the different ways candidates use AI assistance and outside help, one at a time, and watched what each one looked like from both sides of the call.

This is one interview, not a study. It shows how the system behaves when someone tries these methods. It isn't a detection rate, and we're not presenting it as one.

## The ways candidates bring help into the room

> **[EDITOR NOTE: The draft says "a few have interview clips and a few won't" but doesn't list the scenarios. Fill in one block per scenario you actually ran. The examples in brackets are only prompts. Delete any you didn't test. Outcome text is left blank on purpose so no results are invented.]**

**[Scenario 1, e.g. a hidden AI overlay that reads the question and writes the answer.]** [What the candidate did, in one or two sentences.]
[CLIP: candidate-side view]
[What happened.]

**[Scenario 2, e.g. a phone or second device just out of frame.]** [What the candidate did.]
[CLIP or "No clip for this one": say why]
[What happened.]

**[Scenario 3, e.g. someone else in the room, or on another call, feeding answers.]** [What the candidate did.]
[CLIP / no clip]
[What happened.]

**[Scenario 4, e.g. pasting the question into a chatbot in another tab.]** [What the candidate did.]
[CLIP / no clip]
[What happened.]

## What happens when AI sits on the interviewer's side

The answer to candidates using AI isn't pretending it doesn't exist. It's using AI to beat them at their own game.

So here's the other half of the experiment: the clips where AgentR flags what's happening. Watch them next to the candidate-side clips above and you'll notice something. On the candidate's side, all you see is someone trying to use the tool. The interview carries on looking normal to them. The flagging happens on our side, where the hiring team sees it.

[CLIP: hiring-team view showing the flag]

That split is deliberate. AgentR doesn't show the candidate which checks are running, and it doesn't hand the recruiter a raw, signal-by-signal log either. What the hiring team gets is a plain read of the session: clean, a minor flag, an elevated concern, or a confirmed anomaly. A single soft signal, like a glance away, gets logged but isn't enough on its own to count against anyone.

The reason this matters when the answer itself sounds perfect: a fluent answer isn't the same as a demonstrated one. Sounding right in the moment is exactly what a copilot is good at. So the interview is built to make that harder. Follow-up questions build on the candidate's own previous answer, and some sections ask them to sketch a system while talking it through. Underneath that, AgentR Guard watches the machine rather than the answers. An overlay built to hide from a screen share is still a window running on the computer.

## The interview was never going to stay AI-free

AI in the interview isn't something to plan for someday. Candidates are already bringing it in, and interviewers can already bring it too. Pretending otherwise just means the only side using it is the one being assessed.

Preparing with AI is fine. It always was. What matters is whether the answer in the room is coming from the person you're about to hire, and whether you'd know if it wasn't.

## Where AgentR fits, and where it doesn't

AgentR runs structured interviews built from the role. When interview integrity is switched on, it watches the session for signs of outside help in two ways: through how the interview itself is designed, and through Guard, a desktop app that checks the candidate's machine for the length of the session. Guard can also run alongside an interview a person conducts on the call software you already use. When something is found, the session pauses and gets marked for a person to review.

What it doesn't do: make the decision. A flag is a prompt for the hiring team to look, not a rejection, and the call stays with a person. It also doesn't turn one experiment into a guarantee. The interview above shows how the system behaves against the methods we tried. It isn't a benchmark, and new tools will keep appearing. AgentR is also currently in private beta.

## Questions People Ask

### Is it cheating to use AI to prepare for an interview?

No. Researching the company, running mock interviews, practicing answers and polishing a resume with AI are all preparation, and preparation has always been part of interviewing. The line is crossed when AI takes part in the interview itself.

### Can an interviewer tell when a candidate is using AI during the interview?

Not always, and that's the problem. Answers can sound completely natural and human even when a human isn't arriving at them. That gap is what the experiment above was built to show.

### Does the candidate see it when AgentR flags something?

No. In the clips, the candidate's side only shows the attempt, and the flag appears on the hiring team's side. Candidates are told what's being watched before the interview starts, but not which specific checks are active.

### Does a flag mean the candidate gets rejected?

No. A flag pauses the session and marks it for a person to review. AgentR never rejects anyone on its own, and it doesn't treat normal nervousness or an unusual setup as cheating.

### Does this only work on AgentR's own interviews?

No. Guard can run alongside an interview a human conducts on the call software you already use. The conversation stays yours, and only the machine is checked.

If your interviews still assume the only people on the call are the ones you can see, let's talk.

## Related Reading

More on where AI is changing the interview: A Dropout Raised $15M to Cheat Your Interview. He Is Half Right.; Your Agent Applied. Their Agent Rejected It. No Person Was in the Room Either Time.; and The Candidate Cleared Every Screen. The Candidate Wasn't Real.

---

## 3. What changed from the original, and why

- **New title and a subtitle.** The blog mostly uses declarative titles ("…Here's What Happened."), plus a one-to-two sentence lede under the title. I kept your question as the search-friendly alternative.
- **Cold, punchy opening.** "For most of the last few years, AI's job in hiring ended at the door" sets up your "prep → live participation" point in the blog's scene-first style. Your "So what actually happens…" / "We ran an experiment" / "Here's what happened" beats are kept almost word for word.
- **Your content is split into H2 sections whose headings make an argument**, which is the blog's standard (4 to 7 of them per post).
- **Your four questions are kept word for word** and set as standalone lines. The blog uses one-line paragraphs for rhythm rather than bullet lists.
- **Added "This is one interview, not a study."** *(Added and flagged.)* The newer posts always caveat evidence, and AgentR's own product pages say "how the system behaves, not a benchmark". It stops a single run from reading as a detection rate.
- **Scenarios are left as clearly marked placeholders.** Your draft didn't list them, so I suggested likely ones in brackets and left every outcome blank rather than invent results. Swap in what you actually ran.
- **"Beat their own game" became "beat them at their own game"** (the idiom). Your point that the candidate side only shows the attempt while the flag appears on AgentR's side is kept and made explicit.
- **Added a short explanation of *how* the flags work.** *(Added and flagged.)* This covers the categorical reads, no flag from a single soft signal, divided attention, novel follow-ups, and Guard watching the machine. All of it is taken from agentr.global/ai-cheating-prevention and /fairer-interviews, with nothing new claimed. Please check it against the product as it stands.
- **Added a closing section ("The interview was never going to stay AI-free")** *(added and flagged)*, because posts end on a sharp takeaway line.
- **"About AgentR" became "Where AgentR fits, and where it doesn't"**, matching the newest posts. That section names limits (the human makes the call, it's not a guarantee, private beta) so AgentR isn't oversold. **Confirm that private beta is still accurate.**
- **"FAQs" became "Questions People Ask"**, with H3 questions and short answers, as in the explainer posts. Every answer is drawn from your draft or AgentR's product pages.
- **Added the one-line "let's talk" CTA and a "Related Reading" line** *(added and flagged)*. Both are standard endings on the blog, and the links point to existing posts on the same topic.
- **No stats added.** Your draft has none, and I didn't import any. If you want one, the Cluely post already cites sourced figures on AI-assisted interviews that you could reference.
- US spelling throughout, to match the newest posts. None of the banned words ("genuinely", "honestly", "straightforward") are used.
