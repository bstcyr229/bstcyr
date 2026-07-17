Hi, I'm Bryan St. Cyr, 
I build real things that solve business problems, document the process honestly, and ship them publicly.

My background is operations and systems consulting. 

My background spans operations, education, and systems consulting. Across every role the work was the same, figure out why something isn't functioning and build the structure to fix it. Now I'm adding the technical layer, Python, APIs, and applied AI, to do that work at a different scale and toward something bigger. The problems I care about are specific: a small business owner who needs real insight into where their time and money are actually going, using AI to more rapidly and accurately respond to business challenges, then eventually the kinds of systems that help humanity do things we've only dreamed about. The thread connecting all of it is the same, build something real, for real people, and get it right.

My Learning Philosophy
The goal of this portfolio is to master Python through project-based learning. I utilize two primary methodologies to ensure deep comprehension:

- Applied Iteration (AI-Guided): I work through project challenges using an AI tutor configured to the Socratic method. This process is designed to push back when I hit conceptual plateaus and requires periodic summaries to ensure "productive struggle" leads to genuine retention.

- Conceptual Mapping (NotebookLM): I curate open-source resources into structured modules, such as Data Structures or Algorithms, to bridge the gap between practical implementation and Computer Science theory.

I believe that there is no long-term business value in shipping code that you do not fundamentally understand. My focus here is not just on the final product, but on the mastery of the process.

**🔨 What I'm Building**

✅ **Project 1 — LingQ Language Stats Automation**

**A Python script that pulls personal language learning data from the LingQ API and writes it to Google Sheets automatically.***

**The real problem it solves:**: LingQ is great, its one of hte main reasons why I can speak French today, however it does not allow you to set your own goals and track them so I wanted to export my stats into google sheets so I can better visualize the data.

What I learned: API authentication, working with the requests library, Google Sheets API via gspread, environment variables with python-dotenv, and GitHub Actions for scheduling.

🔗 GitHub Repo https://github.com/bstcyr229/lingq_stats_tracker

✅ **Project 2 — ClickUp Time Intelligence Dashboard**

**A Streamlit dashboard that connects to the ClickUp API and visualizes billable vs. estimated vs. actual time across teams, assignees, and tasks.**

**The real problem it solves:** ClickUp's native reporting can tell you hours logged. But almost every client I had during my time at Kolme Group wanted to be able to better visualize how their teams were spending their time, especially when it comes to hours logged vs billalbe hours logged. ClickUp can't easily show you where your estimates are consistently wrong, which team members are over capacity, or what your actual billable efficiency looks like. This does.

**What I've learned so far:** The ClickUp API and the ClickUp interface don't always agree. Time tracking data lives in a completely separate endpoint from tasks. Estimated time only appears on a task object if an estimate has actually been set. Documenting these gaps honestly has been as valuable as building the dashboard itself and validates my learning method thus far. On the CS theory front, I'm realizing that all that I have been reading about Big O notation has suddenly become clear after examining this project with all of it's nested loops. The lack of algorithimic efficency here makes this project a prime candidate for my first refactor project. 

🔗 Github Repo https://github.com/bstcyr229/clickup-time-dashboard


✅ **Project 3 — ClickUp Dashboard RAG Agent**

**A RAG Agent that enahnces the Streamlit powered ClickUp Time Intellegence Dashboard**

**The Real Problem That It Solves**
This code bridges the operational data accessibility gap for executive decision-makers by replacing rigid reporting interfaces and raw spreadsheets with an intuitive natural language search. Instead of forcing leadership to manually navigate complex software to calculate project health, it transforms fragmented time-tracking data, resource estimates, and billable metrics into a queryable knowledge base that answers conceptual business questions. Furthermore, by strictly binding the language model’s responses to verified local data and enforcing an explicit "never guess" directive, it eliminates the risk of AI hallucination, providing a trusted pipeline for high-stakes operational reporting.

**What I've Learned from This Progject** 
The script establishes a fully functioning, self-contained Retrieval-Augmented Generation (RAG) backend pipeline wrapped in a basic web interface. It successfully hooks into an external dashboard module to ingest live ClickUp data, flattens tabular task metrics (such as team member IDs, billable hours, and timelines) into text chunks with preserved metadata, and persists them into a local ChromaDB vector database using native Google Gemini embeddings. The system is fully wired to capture user text input, execute a semantic top-10 query against the vector store, pass that context directly to the high-efficiency gemini-3.1-flash-lite model for strict factual synthesis, and utilize Streamlit resource-caching to ensure the entire extraction and database connection architecture runs efficiently without redundant re-execution.

🔗https://github.com/bstcyr229/ClickUp_RAG_Agent

🚧 **Project 4 - Refactor Project #3 **

**The Real Problem That It Solves**
Right now project #3 which combines my ClickUp Time Intellgence Dashboard and a native RAG agent works, but there are some performance issues that I would like to improve on by implementing the following changes.

1. Restructure the code using Object Oriented Programming Principles
2. Refactor Performance using Big O Notation as a standard
3. Making the Program more Robust via Error Handling and Unit Tests
4. Create an Eval Harness to Evaluate RAG Agent Performance

🔗 In Progress

🧰 **Tech Stack**
**Languages**:     Python (intermediate — API integration, data pipelines, deployed applications)
               French (C1 — full professional proficiency, self-directed acquisition)
          

**Libraries**:     pandas, Streamlit, Altair, LangChain, ChromaDB, requests, python-dotenv

**Tools**:         VS Code, Git Bash, GitHub, Streamlit Community Cloud

**Platforms**:     ClickUp (Expert & Advanced AI Certified), Make.com (Intemediate Certified)

In **Progress**:   PMP Certification, RAG systems, LangChain agents

📍 **Where I'm Coming From**
I didn't start as a developer. I started as someone who kept running into the limits of no-code tools and decided to learn what was on the other side of that wall. Then AI made me genuinely curious, not just about what these systems could do, but about how they actually work, who they serve, and what kind of future they're building toward. That curiosity became a commitment.

I believe AI built well can do extraordinary things. It can help a francophone immigrant in Denver find housing in their own language. It can help a small business owner understand where their time is actually going. It can eventually help put people in space and solve problems we haven't fully named yet. But only if the people building it understand both the technology and the humans on the other side of it.

That's what I'm working toward. The projects here are what that looks like in practice — real problems, honest documentation of what broke and why, and deployed applications that actually work for real people.

I build in public on LinkedIn and document the process including the parts that don't work. If you want to follow along https://www.linkedin.com/in/bryanstcyr91/

🗺️**What's Next**

Building toward a 10-project portfolio across API integration, RAG systems, multi-agent workflows, and fine-tuned classification models. Each project builds on the last.
The goal by end of 2027: a portfolio that demonstrates the full stack from data pipelines to deployed AI applications, built on real problems, not tutorials that facilitates real knowledge of programming and AI.
