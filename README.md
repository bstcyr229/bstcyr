Hi, I'm Bryan St. Cyr 👋
Technical Project Manager in transition to AI development. I build real things, document the process honestly, and ship them publicly.
My background is operations and systems consulting. 

My background spans operations, education, and systems consulting. Across every role the work was the same — figure out why something isn't functioning and build the structure to fix it Now I'm adding the technical layer — Python, APIs, and applied AI — to do that work at a different scale and toward something bigger. The problems I care about are specific: a small business owner who needs real insight into where their time and money are actually going, a French-speaking immigrant in Denver who needs housing guidance in their own language, and eventually the kinds of systems that help humanity do things we've only dreamed about. The thread connecting all of it is the same — build something real, for real people, and get it right.

**🔨 What I'm Actually Building**

✅ **Project 1 — LingQ Language Stats Automation**

A Python script that pulls personal language learning data from the LingQ API and writes it to Google Sheets automatically.
What I learned: API authentication, working with the requests library, Google Sheets API via gspread, environment variables with python-dotenv, and GitHub Actions for scheduling.

GitHub Repo https://github.com/bstcyr229/lingq_stats_tracker

🔄 **Project 2 — ClickUp Time Intelligence Dashboard (In Progress)**

**A Streamlit dashboard that connects to the ClickUp API and visualizes billable vs. estimated vs. actual time across teams, assignees, and tasks.**

**The real problem it solves:** ClickUp's native reporting can tell you hours logged. It can't easily show you where your estimates are consistently wrong, which team members are over capacity, or what your actual billable efficiency looks like. This does.
**What's built so far**: Three dashboard views using dummy data are complete and deployed — team capacity view, assignee view, and task-level drill-down. Currently wiring up the live ClickUp API data pipeline to replace the dummy data layer.
The API work in progress: Multi-level hierarchy traversal (teams → spaces → folders → lists → tasks), joining task data with time entries from a separate endpoint using task ID as the join key, and separating billable vs. non-billable tracked time. The collect-first/aggregate-second pattern is the core architectural decision driving the data pipeline.
**What I've learned so far:** The ClickUp API and the ClickUp interface don't always agree. Time tracking data lives in a completely separate endpoint from tasks. Estimated time only appears on a task object if an estimate has actually been set. Documenting these gaps honestly has been as valuable as building the dashboard itself — and it's made for better LinkedIn content than a clean success story would have.
**Status:** Dummy data layer complete and deployed. Live API pipeline in active development.
🔗 Live App (Dummy Data coming soon) | GitHub Repo 

⏸️**Project 3 — Chez Toi (Paused)**

**A RAG-powered French-language housing navigator built for Denver's African francophone immigrant community.** Designed to answer questions about tenant rights, assistance programs, and neighborhood resources in French.
**Why this one matters:** I'm building it in collaboration with community organizations serving West African immigrants and French speaking immagrants in Denver. The technical problem is real. The people it serves are real. When my ancestors emmigrated to New Hampshire and Vermont from Quebec there was very little help for them this program means to solve this problem for people moving to Denver in 2026. Almost every French speaking immigrant that I have spoken to in Denver has stopped and taken the time to help me practice my French. This is my way of repaying that. Getting it right matters more than getting it done fast.
**Stack**: Python, LangChain, ChromaDB, SentenceTransformer (HuggingFace), PyPDF
**Status**: Community outreach in planned. Paused until Project 2 API pipeline is finished — the data engineering patterns I'm building there apply directly to the ingestion pipeline this project needs.

🧰 **Tech Stack**
**Languages**:     Python (intermediate — API integration, data pipelines, deployed applications)
               French (C1 — full professional proficiency, self-directed acquisition)
               Spanish (B1+ — developing production skills)

**Libraries**:     pandas, Streamlit, Altair, LangChain, ChromaDB, requests, python-dotenv

**Tools**:         VS Code, Git Bash, GitHub, Streamlit Community Cloud

**Platforms**:     ClickUp (Expert & Advanced AI Certified), Make.com (Intemediate Certified)

In **Progress**:   PMP Certification, RAG systems, LangChain agents

📍 **Where I'm Coming From**
I didn't start as a developer. I started as someone who kept running into the limits of no-code tools and decided to learn what was on the other side of that wall. Then AI made me genuinely curious — not just about what these systems could do, but about how they actually work, who they serve, and what kind of future they're building toward. That curiosity became a commitment.

I believe AI built well can do extraordinary things. It can help a francophone immigrant in Denver find housing in their own language. It can help a small business owner understand where their time is actually going. It can eventually help put people in space and solve problems we haven't fully named yet. But only if the people building it understand both the technology and the humans on the other side of it.

That's what I'm working toward. The projects here are what that looks like in practice — real problems, honest documentation of what broke and why, and deployed applications that actually work for real people.

I build in public on LinkedIn and document the process including the parts that don't work. If you want to follow along https://www.linkedin.com/in/bryanstcyr91/

🗺️**What's Next**

Building toward a 10-project portfolio across API integration, RAG systems, multi-agent workflows, and fine-tuned classification models. Each project builds on the last.
The goal by end of 2026: a portfolio that demonstrates the full stack from data pipelines to deployed AI applications — built on real problems, not tutorials.
