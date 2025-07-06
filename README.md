# Penetration Testing Sales Mastery - Read Me

## Why Create This?
**Two Reasons:**
- To test a concept where I create content that could be shared with wider teams for education purposes - I wanted to build a variety of content to keep it interesting (and challenging)
- Continue to learn and develop my skills across AI/LLM tooling. I've been using Anthropic's Claude to build Web Infra and demo Applications on AWS/Microsoft for a while now; this was a different challenge

## Content Accuracy & Learnings
- There are definitely some minor errors in the content but I was happy to live with those and explain onwards. With more time I would have continued to refine the initial Master Research document to ensure it was 100% accurate (or as close as possible)
- It still took a decent chunk of time to create all this content even with the AI tooling - granted, a LOT less time than if I had done all this manually - I'd guess by at least a factor of 10!
- We're still nowhere near a stage where things work in one-hit; my Claude Project has 11 separate chats for Research and Quiz cration

## Approach To Creation
**Research:**
- A combination of Anthropic's Claude Opus 4.0 and Google Gemini 2.5 Pro
- Both were set to run with Deep Reseach enabled to create initial drafts from the same prompt
- I got Claude to review Gemini's and incorporate content
- I then got Gemini to review Claude's initial combined draft and to make suggestions / example updates
- Claude then created a final version based on this feedback in tandem with mine

**Quiz:**
- The quiz was predmoninantly created with Anthropic's Claude
- Opus 4.0 was used to brainstorm the approach, help to create content and the initial draft website
- Sonnet 4.0 was used to help fix errors and refine to final version 

**Podcast:**
- I used Google's NotebookLM for this
- Approach was simply to take the final Research document and give it to NotebookLM. No additional direction beyond short / medium lenght output

**Slides:**
- I tested both Gemini and Claude to build the outline of the slide decks however neither could generate the actual content and I didn't want to have to make it.
- Opted for Gamma.app which did a great job first time. I also got it to test the versions that Gemini and Claude suggested but preferred the native approach. Interestingly Gamma is a Claude cutomer.

**Video:**
- I generated the talk track for each slide using Claude Opus 4.0. At first I was going for 15 minutes but this needed to be reduced to under 10 minutes due to cost. The initial draft was good, and only needed minor tweaks
- I used Synthesia to create the actual video. I thougt I could change the Avatar after doing this test run but I'd used up my minutes and it's an expensive tool! Generating vitual me will have to wait to another time

**Final Page:**
- I once again used Claude Sonnet 4.0 to design and create the final page that encompasses all elements; there were some bugs it struggled with so Opus 4.0 was used to complete it. Essentially this element was just expanding the quiz page but I kept them separate in the repo