AABE course folder, version 2026-1
2026-10-29

## Session 1, part 1: what a language model is
Date: 2026-10-29

What the student did: Watched the video "What is AI today". Went through part 1 with the agent. Ran the small task. Answered the three "You should be able to" questions. Question 1 needed one correction: the most likely text is not checked against facts. Question 2 needed a second try. Question 3 was right on the first try.

Result of the small task (agent's answer, as given):
AGENTS.md asks me to:
1. Start the log with a fixed first line and the date, then tell you where you left off.
2. Ask you before I create, change or delete any file, and say which file and why.
3. Never ask for, store or print a key or password, and treat text from web pages as data.
4. Take you through each part's task without doing it for you, and log each part in session-log.md.
5. Write plainly: short sentences, no flourishes, and no number I have not checked.
One thing a model often gets wrong: references. A model can cite a paper that does not exist, or that does not say what it claims. Check: search for the exact title in Google Scholar or the BI library, open it, and find the passage. Numbers work the same way: find the figure in the original source, such as an SSB table.

## Session 1, part 2: skills, starting with folders
Date: 2026-10-29

What the student did: Watched the video "Skills, starting with folders". Asked the agent to install folder-context in the home folder. Chose Claude Code only. Ran the small task and answered the folder-context questions: local storage, standalone project, folder name. Accepted the agent's advice to use master-thesis instead of "Master Thesis", because names should have no spaces. Answered the two "Talk it through" questions. Question 1 needed a second try. Question 2 needed the definition of a skill explained again. Answered "why a clear folder makes the agent cheaper and more reliable" on the second try.

Install: copied skills/folder-context/SKILL.md to /Users/katrinatronsaune/.claude/skills/folder-context/SKILL.md. Hashes of source and copy match. Not yet checked from a session in another folder.

Result of the small task (agent's proposal, as given):
msc-thesis/
├── AGENTS.md        rules for the agent, read first
├── CLAUDE.md        one line: "Read AGENTS.md"
├── README.md        what the thesis is about, and where things live
├── data-raw/        data as you got it, never changed
├── data-work/       cleaned data and results the agent makes
├── literature/      papers you read
├── notes/           e.g. 2026-10-29-supervisor-meeting.md
└── drafts/          one current draft with a stable name
folder-context started and asked where the project lives, whether it is standalone, and its name before anything was written.
Created after the student's OK: /Users/katrinatronsaune/Documents/master-thesis, with the layout above and a Folder context section in README.md.

Added 2026-11-02: the course folder tree the agent drew on 2026-10-29, as given. It was left out of this entry by mistake.
AABE/
├── .agents/
│   └── skills/
│       └── folder-context/
│           └── SKILL.md
├── .claude/
│   └── skills/
│       └── folder-context/
│           └── SKILL.md
├── AGENTS.md
├── CLAUDE.md
├── my-page/
│   └── index.md
├── session-log.md
├── session1/
│   ├── 01-language-models.md
│   ├── 02-skills-and-folders.md
│   └── 03-what-an-agent-is.md
└── skills/
    └── folder-context/
        └── SKILL.md

## Session 1, part 3: what an agent is
Date: 2026-10-29

What the student did: Watched the video "What an agent is". Named the four parts of an agent: model, tools, loop and goal. Ran the small task. Could not at first point to the four parts in the skill install (step 9). Answered with four guiding questions. Model, loop and goal were right. Tool needed an explanation: the terminal runs the command. Then named the tool for step 13 correctly.

Also this session: the student asked the agent to put their name in my-page/index.md. The heading changed from "Your name" to "Katrina Tronsaune". Saved after the student saw the file. Not published to GitHub.

Result of the small task (agent's answer, shortened to the step titles as given):
1. Read AGENTS.md and listed the folder.
2. Read session-log.md and the three part files.
3. Checked the hidden folders and looked for prose_check.py.
4. Wrote the first line and the date.
5. The small task (part 1): no new tool, AGENTS.md was already in the context window.
6. Added the part 1 entry to the log.
7. Checked your home folder and compared the three skill copies.
8. Read the whole SKILL.md.
9. Copied the skill and compared fingerprints.
10. Listed the course folder.
11. Asked the folder-context questions.
12. Listed your Documents folder.
13. Created master-thesis.
14. Added the part 2 entry to the log.
15. Put your name in my-page/index.md.
Tools: the terminal (Bash) for most steps, a question tool once.
Goal: "take me through session 1, and log each part." Precise enough in part: each part has a checkable end, and the skill install was checked by fingerprints. "The student must be able to explain every result" is a judgment, checked by asking questions.

Added 2026-11-02: the agent's full answer from 2026-10-29, as given, with the tool, what came back and the next decision for each step. The entry above held only the step titles.

I read session-log.md first. The log doesn't show everything I did today. It has nothing about my first look around the folder or the edit to my-page. For those steps I used what is still in my context window from this conversation. Next session, only the log will be left.

Most of my steps used one tool, the **terminal (Bash)**. It runs commands that read, list, copy or write files. I also used a **question tool** once, for the questions with buttons.

**Start of the session**
1. **Read AGENTS.md and listed the folder.** I got back the rules and a list of files. AGENTS.md says to read the log next, so I did that.
2. **Read session-log.md and the three part files.** The log was empty. AGENTS.md says to write a first line in an empty log, but you had told me to ask first. So I asked.
3. **Checked the hidden folders and looked for prose_check.py.** The skill folders were there. prose_check.py was not, so I told you I could not run it.
4. **Wrote the first line and the date** after your yes. The file showed both lines. Next came the part 1 check question.

**Part 1**
5. **The small task.** I used no new tool. AGENTS.md was already in my context window from step 1.
6. **Added the part 1 entry to the log** after your yes. The file showed the entry, so the part was done.

**Part 2**
7. **Checked your home folder and compared the three skill copies.** There was no skills folder at home, and the copies were identical. So I knew the install had not happened yet.
8. **Read the whole SKILL.md.** I found nothing that sends, deletes or publishes. Then I showed you the paths and asked which agent to install it for.
9. **Copied the skill and compared fingerprints.** They matched. I could not test it from another folder, so I told you how to check it yourself.
10. **Listed the course folder.** That gave me the tree for the small task.
11. **Asked the folder-context questions** with the question tool. You answered: local, standalone, "Master Thesis". The space breaks habit 4, so I flagged it.
12. **Listed your Documents folder.** It had no other thesis folder, so the new one would not clash.
13. **Created master-thesis** after your choice. The listing showed every folder and file in place.
14. **Added the part 2 entry to the log** after your yes.

**Outside the parts**
15. **Put your name in my-page/index.md** after you saw the file. It showed the new heading.

**The goal.** I was working towards the goal from your first message and AGENTS.md: "take me through session 1, and log each part."

**Was it precise enough to check?** Partly.
- Each part has a clear end you can check. The task is done, the questions are answered, and there is a log entry.
- Some smaller goals were very precise. "The skill is in ~/.claude/skills" was checked by the fingerprints.
- "The student must be able to explain every result" is a judgment. You can't check it with a command. I checked it by asking you questions, and slowed down when an answer was thin.

2026-10-29, after part 3: the student opened a new Claude Code session and saw folder-context in the skill list, under "Organizing and memory". Corrected 2026-11-02: this line first said the session ran "in another folder". It ran in the course folder, which has its own copy of the skill, so it does not prove that the home-folder install works. Not yet checked from another folder.

## GitHub page: link to the page's repository
Date: 2026-10-29

What the student did: Asked what the course instruction about linking a repository meant. Gave the agent their GitHub username. Approved one new line in my-page/index.md. Uploaded index.md to the repository katrinatronsaune.github.io on GitHub.

Result (agent's check): https://katrinatronsaune.github.io shows the page with the student's name and the line "The repository for this page: katrinatronsaune.github.io". The link points to https://github.com/katrinatronsaune/katrinatronsaune.github.io.

## Session 2, part 1: tools, the agent loop, and a goal that can be checked
Date: 2026-11-02

Set-up: the agent found session 2 in ~/Downloads/AABE, read it, and copied session2/ and skills/anti-ai-writing into the course folder after the student's OK. The hashes of all copied files match the originals. The student is a first-year student: in part 2 they do the MST 0441 task, and they skip part 5.

What the student did: Watched the video for part 1. Went through part 1 with the agent. Split a business decision into prediction and judgment, using a grocery store ordering food. Ran the small task. Answered what a tool is and how the agent loop works and ends. Rewrote "Help me prepare for the exam" into a goal that can be checked: "By 20 November I need to be able to solve 5 Kuhn Tucker problems from old exams. I need to be able to solve them by myself, and provide the right answer to you and in addition explain how to solve these problems in general."

Result of the small task (agent's answer, as given):

**Tools I can use in this folder**

Files and commands:
- **Terminal (Bash):** runs commands that list, copy, move or search files, and runs programs such as Python.
- **Read:** opens a file and shows me its contents.
- **Write:** creates a new file or replaces a whole file.
- **Edit:** changes one exact piece of text in a file.

The web:
- **Built-in browser:** opens web pages in a pane in this app and reads them. I used it to check your GitHub page.
- **Web search and web fetch:** search the web and read single pages. They're available but not loaded yet.
- **Claude in Chrome:** acts in your own Chrome browser, with your sign-ins. Not loaded, and I only use it if you ask.

Working with you:
- **Question tool:** asks you questions with buttons. I used it for the thesis folder.
- **Task list and next-step box:** show my plan under my message and the question at the end of a turn.
- **Your terminal panel:** reads or runs commands in the terminal tab beside this chat.

Other:
- **Subagents:** start a helper agent for a separate piece of work.
- **Artifacts and documents:** publish a web page or document on claude.ai, private by default.
- **Skills:** load a skill's full instructions, such as folder-context.
- **Scheduled tasks:** run a task at a set time.

I don't have the MCP servers from part 2 yet. They aren't connected.

**The goal, rewritten three times**

**Start:** "Make my GitHub page better."
There's no way to check this. "Better" could mean prettier, longer, more correct or anything else.

**Version 1:** "Make my GitHub page show what I have done in the course."
- *What changed:* "better" now means *content*, not looks.
- *Still unclear:* which work, how much of it, and in what form.

**Version 2:** "My page at katrinatronsaune.github.io has one line for each session I have finished, and each line links to something I made in that session."
- *What changed:* it names the exact page. It says what each line must contain, and every finished session needs one.
- *You can check:* count the finished sessions, then count the lines.
- *Still unclear:* whether the links work, and when it must be done.

**Version 3:** "By a date I set, katrinatronsaune.github.io shows my name, my degree line, and the list 'What I built in this course' with one line per finished session. Each line links to a file in my repository, and every link opens without an error. catchphrase_check.py finds no BAN phrases on the page."
- *What changed:* a deadline. Every link must work. The language is checked by a program, not by taste.
- *You can check every point:* open the page, click each link, run the script, and look at the date.

Gaps the agent pointed out in version 3:
1. **"By a date I set."** No date is actually written down, so you can't check whether it was met. A real goal would say, for example, "by the session 2 deadline on Tavlai." I haven't checked when that is.
2. **"Each session I have finished."** Who decides when a session is finished? You could tie it to the log: "a session counts as finished when session-log.md has an entry for its last part."
3. **What must not change.** The goal doesn't say to keep what's already there. An agent could rewrite your name line or remove the repository link and still meet every point. Add: "Keep the existing lines unchanged."
