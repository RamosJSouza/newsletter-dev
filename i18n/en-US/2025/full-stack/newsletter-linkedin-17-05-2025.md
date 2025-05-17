***"Survival is the best performance measure."*** – Vicki TenHaken

**In this edition:** PostgREST, Figma Sites (controversy!) and LangGraph.js. + Programming jokes!

## **Editorial(??)**

Why is this edition super short? Because I'm deeply immersed in my "Open to Work" project ([https://www.linkedin.com/feed/update/urn:li:activity:7328169928056815616/](https://www.linkedin.com/feed/update/urn:li:activity:7328169928056815616/)) — and I discovered something important:

💡 *"Working only on third-party projects is great... until you realize you don't have your own portfolio to showcase your skills!"*

So, let's fix that! I'm building a system in Node.js + React from scratch, with:

✔️ Best practices (tests, clean code, documentation)
✔️ All open-source (for you to peek at the code and give feedback!)
✔️ Real case (no generic "TODO app")

Next week brings hot updates! 🍿 But for today, enjoy this light edition — and get ready for the next one, which comes with *code, screenshots, and maybe even a public deploy!*

Happy reading! (And tell me: have you been through this too? Maybe we can exchange ideas!)

## **Database**

PostgREST 13: RESTful API for Postgres Databases. A standalone web server that turns your Postgres database directly into a RESTful HTTP API. Version 13.0 brings:

* To-many *spread* relationships ([docs](https://docs.postgrest.org/en/v13/references/api/resource_embedding.html#spread-to-many-relationships)): simplifies complex queries with nested joins.
* Automatic tsvector conversion ([docs](https://docs.postgrest.org/en/v13/references/api/tables_views.html#automatic-tsvector-conversion)): full-text search in text and JSON fields *ready to use*.

Real-World Scenarios for Devs:

1. Quick MVP Create a REST API for your frontend (React/Vue) in minutes, without writing backend code.
2. Advanced Search Implement complex filters and full-text search (e.g., e-commerce) directly via URL.
3. Lightweight Microservices Expose specific parts of the database as standalone endpoints (e.g., reports).
4. Low-Code Tool Integration Connect Power BI, Airtable, or Zapier to Postgres without developing intermediate APIs.

Tip: Ideal for prototyping or systems with business rules centralized in the database. 🚀 LINK: [https://docs.postgrest.org/en/v13/](https://docs.postgrest.org/en/v13/)

## **Figma's AI-powered Website Creation Tool**

Figma [recently announced *'Figma Sites'*](https://frontendfoc.us/link/169291/62e4c7e6b7), a way to quickly publish your Figma designs directly to the web — but the response from front-end developers has been *quite mixed*, with many comparisons to the bloated output of platforms like Dreamweaver and Microsoft Frontpage.

Though still in beta, there has been some criticism of the [div-heavy code](https://frontendfoc.us/link/169292/62e4c7e6b7) it's producing.

* [Figma launches AI-powered tools for website creation](https://frontendfoc.us/link/169293/62e4c7e6b7) — Ivan Mehta
* [The true path to garbage code: Figma sites](https://frontendfoc.us/link/169294/62e4c7e6b7) — Joe Dolson
* [Don't publish your designs to the Web with Figma sites…](https://frontendfoc.us/link/169295/62e4c7e6b7) — Adrian Roselli
* [Figma Sites is worse than you think](https://frontendfoc.us/link/169296/62e4c7e6b7) — Kevin Powell

---

What's the difference between a commit and a relationship? *At least the commit has a clear message.*

## **AI with Node, React, etc... or JavaScript projects**

Getting started with LangGraph.js? Explore "awesome-langgraphjs"!

Want to use LangGraph.js but don't know where to start? The "awesome-langgraphjs" repository brings together an incredible list of open source projects and YouTube videos made with or for LangGraph.js!

Find everything from production-ready multi-agent systems to full-stack chat applications: 👉 [https://github.com/bracesproul/awesome-langgraphjs](https://github.com/bracesproul/awesome-langgraphjs)

If you know of or have an open source project using LangGraph.js, contribute with a PR to add the link!

## **AND TO FINISH... (IT'S WEEKEND!)**

What's the lazy dev's favorite framework? *"Sofa.js" — because they just want to lie down.*

*Have a great weekend!*
