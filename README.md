# ai-engineer-journey

##Project List

1. "Smart Inbox Triager"
Build a tool that connects to a Gmail inbox (Gmail API, OAuth), pulls the last 100 emails, and uses an LLM to: classify each (urgent / FYI / newsletter / spam / personal), generate a 1-line summary, and suggest a draft reply for the urgent ones. Frontend in Next.js (your React skills, finally paying off). Deploy on Vercel. Use your own inbox as the demo.

2. "Codebase Companion" — a RAG system over a real open-source codebase (pick one you actually want to understand: maybe Next.js, FastAPI, or LangChain itself). Index the code with proper chunking strategies for code (not naive 500-char chunks), embed with a real model, retrieve, answer questions like "where is auth handled?" or "show me how X is implemented." Compare 3 retrieval strategies (naive, hybrid BM25+vector, with reranking) and write a blog post on the results.

3. "PR Reviewer Agent" — a GitHub bot that, when you open a PR, posts a code review comment. Uses an agent loop (read the diff, decide which files to inspect deeper, look up related code, check for common issues, suggest improvements). Deploy as a GitHub App. Open-source it.

4. AI for healthcare
