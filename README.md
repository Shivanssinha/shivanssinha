<h1 align="center">Shivans Kumar Sinha</h1>
<p align="center">
  Backend developer building APIs, SQL databases and RAG pipelines<br>
  B.Tech Computer Science and Engineering, Jawaharlal Nehru University (expected 2028)
</p>

<p align="center">
  <a href="mailto:7105sks@gmail.com"><img src="https://img.shields.io/badge/Email-7105sks@gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://linkedin.com/in/shivans-sinha-616534360"><img src="https://img.shields.io/badge/LinkedIn-Shivans%20Sinha-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://leetcode.com/u/SHIVANS_SINHA/"><img src="https://img.shields.io/badge/LeetCode-SHIVANS__SINHA-FFA116?style=flat&logo=leetcode&logoColor=white" alt="LeetCode"></a>
  <!-- Add once your portfolio is live:
  <a href="https://shivanssinha.github.io"><img src="https://img.shields.io/badge/Portfolio-shivanssinha.github.io-0c1220?style=flat&logo=googlechrome&logoColor=white" alt="Portfolio"></a> -->
</p>

---

## About

I build the backend side of applications: REST APIs, relational databases and search that run in Docker. My recent work covers a RAG-powered travel recommender and a full-stack fitness tracker with a SQL-heavy MySQL backend. I am looking for backend and SDE internships and full-time roles, and I solve DSA problems on LeetCode.

## Projects

### TravelMind: AI-powered travel recommendation platform
`Python` `FastAPI` `PostgreSQL` `Docker` `Nginx` `ChromaDB` `SentenceTransformers` `JavaScript`

- Full-stack platform over 521 Indian destinations, containerized with Docker Compose (FastAPI, PostgreSQL, Nginx) and secured with Google OAuth and JWT cookie sessions.
- Two-stage ranking engine: TF-IDF keyword search with field boosting shortlists destinations, then 8 weighted signals (vibe, semantic similarity, budget, distance, season, group type, popularity, duration) re-rank them.
- RAG pipeline with section-aware chunking (about 4,500 chunks) in ChromaDB using `all-MiniLM-L6-v2` embeddings. L2-normalized vectors reduce cosine similarity to NumPy dot products (sub-2 ms).
- LLM itineraries streamed over SSE with Groq, with automatic Gemini and no-LLM fallbacks, grounded in retrieved facts to reduce hallucination.

<!-- TODO: add the TravelMind repo link here, e.g. [View the code](https://github.com/Shivanssinha/YOUR_REPO) -->

### Fitness Tracker: full-stack workout and nutrition tracker
`React.js` `Vite` `Python` `FastAPI` `MySQL` `SQLAlchemy` `JWT` `Recharts`

- React and Vite client with a FastAPI REST API (20+ endpoints), JWT authentication with bcrypt hashing, and per-user data isolation on MySQL.
- Normalized MySQL schema (6 tables) with foreign keys, cascade and restrict rules, CHECK and UNIQUE constraints, composite indexes and a SQL view for weekly training volume.
- Analytics in raw SQL: window functions (`ROW_NUMBER`, `LAG`) for personal records and progression, a CTE-based gaps-and-islands query for workout streaks, and correlated subqueries for live goal progress.
- Atomic workout saving with SQLAlchemy transactions (commit and rollback on failure) and Recharts dashboards for weekly volume and exercise progress.

[View the code](https://github.com/Shivanssinha/Fitness_Tracker)

## Skills

| | |
|---|---|
| **Languages** | C++, Java, JavaScript, Python, SQL, MIPS Assembly |
| **Backend and AI** | FastAPI, REST APIs, Node.js, Express.js, SentenceTransformers, ChromaDB |
| **Databases and tools** | PostgreSQL, MySQL, Firebase, Git, Docker, Nginx, Figma |
| **Frontend** | React.js, Vite, HTML5, CSS3, Tailwind CSS |
| **Coursework** | Database Management Systems, Computer Architecture, Digital Electronics |

## Education

| | | |
|---|---|---|
| **B.Tech, Computer Science and Engineering**, Jawaharlal Nehru University, New Delhi | CGPA 7.55 / 10 | Expected 2028 |
| **Class XII**, The Indian Public School (CBSE) | 91% | 2024 |
| **Class X**, DonyPolo Public School (CBSE) | 92% | 2022 |
