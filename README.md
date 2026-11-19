%-------------------------
% Resume in LaTeX
% License : MIT
%-------------------------

\documentclass[a4paper,11pt]{article}
\usepackage{latexsym}
\usepackage{xcolor}
\usepackage{float}
\usepackage{ragged2e}
\usepackage[empty]{fullpage}
\usepackage{wrapfig}
\usepackage{lipsum}
\usepackage{tabularx}
\usepackage{titlesec}
\usepackage{geometry}
\usepackage{marvosym}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\usepackage{cfr-lm}
\usepackage[T1]{fontenc}

\setlength{\multicolsep}{0pt}
\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\geometry{left=1.4cm, top=0.8cm, right=1.2cm, bottom=1cm}

\usepackage[most]{tcolorbox}
\tcbset{
    frame code={},
    center title,
    left=0pt,
    right=0pt,
    top=0pt,
    bottom=0pt,
    colback=gray!20,
    colframe=white,
    width=\dimexpr\textwidth\relax,
    enlarge left by=-2mm,
    boxsep=4pt,
    arc=0pt,
    outer arc=0pt,
}

\urlstyle{same}
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-7pt}]

%-------------------------
% Custom commands

\newcommand{\resumeItem}[2]{
  \item{
    \textbf{#1}{\hspace{0.5mm}#2 \vspace{-0.5mm}}
  }
}

\newcommand{\resumePOR}[3]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1}\hspace{0.3mm}#2 & \textit{\small{#3}}
    \end{tabular*}
    \vspace{-2mm}
}

\newcommand{\resumeSubheading}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#4}} \\
        \textit{\footnotesize{#3}} & \footnotesize{#2}\\
    \end{tabular*}
    \vspace{-2.4mm}
}

\newcommand{\resumeProject}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#3}} \\
        \footnotesize{\textit{#2}} & \footnotesize{#4}
    \end{tabular*}
    \vspace{-2.4mm}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

\renewcommand{\labelitemi}{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*,labelsep=0mm]}
\newcommand{\resumeHeadingSkillStart}{\begin{itemize}[leftmargin=*,itemsep=1.7mm, rightmargin=2ex]}
\newcommand{\resumeItemListStart}{\begin{justify}\begin{itemize}[leftmargin=3ex, rightmargin=2ex, noitemsep,labelsep=1.2mm,itemsep=0mm]\small}

\newcommand{\resumeSubHeadingListEnd}{\end{itemize}\vspace{2mm}}
\newcommand{\resumeHeadingSkillEnd}{\end{itemize}\vspace{-2mm}}
\newcommand{\resumeItemListEnd}{\end{itemize}\end{justify}\vspace{-2mm}}

\newcommand{\cvsection}[1]{%
\vspace{2mm}
\begin{tcolorbox}
    \textbf{\large #1}
\end{tcolorbox}
    \vspace{-4mm}
}

\newcolumntype{L}{>{\raggedright\arraybackslash}X}%
\newcolumntype{R}{>{\raggedleft\arraybackslash}X}%
\newcolumntype{C}{>{\centering\arraybackslash}X}%

%---- End of Packages and Functions ------

\newcommand{\name}{Shivans Kumar Sinha}
\newcommand{\course}{B.Tech in Computer Science and Engineering}
\newcommand{\phone}{9818144309}
\newcommand{\emaila}{7105sks@gmail.com}

\begin{document}
\fontfamily{cmr}\selectfont

%----------HEADING-----------------

\begin{tabularx}{\linewidth}{L r}
  \textbf{\Large \name} & {\raisebox{0.0\height}{\footnotesize \faPhone}\ +91-\phone}\\
  \course & \href{mailto:\emaila}{\raisebox{0.0\height}{\footnotesize \faEnvelope}\ {\emaila}} \\
  {Jawaharlal Nehru University, New Delhi} & \href{https://github.com/Shivanssinha}{\raisebox{0.0\height}{\footnotesize \faGithub}\ {GitHub Profile}} \\
  & \href{https://leetcode.com/u/SHIVANS_SINHA/}{\raisebox{0.0\height}{\footnotesize \faCode}\ {LeetCode Profile}} \\
  % Uncomment once your portfolio is live (change the URL if yours differs):
  % & \href{https://shivanssinha.github.io}{\raisebox{0.0\height}{\footnotesize \faGlobe}\ {Portfolio}} \\
  % Add LinkedIn later:
  % & \href{YOUR_LINKEDIN_URL}{\raisebox{0.0\height}{\footnotesize \faLinkedin}\ {LinkedIn Profile}} \\
\end{tabularx}

%-----------EDUCATION-----------
\section{\textbf{Education}}
\resumeSubHeadingListStart

    \resumeSubheading
      {DonyPolo Public School}{Percentage: 92\%}
      {Class X, Central Board of Secondary Education (CBSE)}{2022}

    \resumeSubheading
      {The Indian Public School}{Percentage: 91\%}
      {Class XII, Central Board of Secondary Education (CBSE)}{2024}

    \resumeSubheading
      {Jawaharlal Nehru University, New Delhi}{CGPA: 7.55/10}
      {B.Tech in Computer Science and Engineering}{Expected 2028}

\resumeSubHeadingListEnd
\vspace{-5.5mm}

%-----------EXPERIENCE-----------------
\section{\textbf{Experience}}
\resumeSubHeadingListStart

    \resumeSubheading
      {Sprix}{}
      {Business Management Associate}{May 2026 -- Oct 2026}

      \resumeItemListStart
        \item {Managed communication and the sales pipeline between school administrators and parents, supporting smooth onboarding and client retention.}
        \item {Served as the point of contact for client feedback, translating school and parent requirements into actionable inputs for internal teams, and negotiated partnerships with educational institutions to expand adoption.}
      \resumeItemListEnd

\resumeSubHeadingListEnd
\vspace{-5.5mm}

%-----------PROJECTS-----------------
\section{\textbf{Personal Projects}}
\resumeSubHeadingListStart

    \resumeProject
      {TravelMind -- AI-Powered Travel Recommendation Platform}
      {Python, FastAPI, PostgreSQL, Docker, Nginx, ChromaDB, SentenceTransformers, JavaScript}
      {2026}
      {}

      \resumeItemListStart
        \item {Built a full-stack travel platform over 521 Indian destinations, containerized with Docker Compose (FastAPI, PostgreSQL, Nginx) and secured with Google OAuth and JWT cookie sessions.}
        \item {Designed a two-stage ranking engine: TF-IDF keyword search with field boosting shortlists destinations, then 8 weighted signals (vibe, semantic similarity, budget, distance, season, group type, popularity, duration) re-rank them.}
        \item {Implemented a RAG pipeline with section-aware chunking (${\sim}$4,500 chunks) stored in ChromaDB using \texttt{all-MiniLM-L6-v2} embeddings; L2-normalized vectors reduce cosine similarity to fast NumPy dot products (sub-2\,ms).}
        \item {Streamed LLM itineraries over SSE with Groq and automatic Gemini and no-LLM fallbacks, grounding output in retrieved facts to reduce hallucination.}
      \resumeItemListEnd
    \vspace{-2mm}

    \resumeProject
      {Fitness Tracker -- Full-Stack Workout \& Nutrition Tracker}
      {React.js, Vite, Python, FastAPI, MySQL, SQLAlchemy, JWT, Recharts}
      {2026}
      {\href{https://github.com/Shivanssinha/Fitness_Tracker}{\raisebox{0.0\height}{\footnotesize \faGithub}\ GitHub}}

      \resumeItemListStart
        \item {Built a full-stack workout and nutrition tracker with a React and Vite client, a FastAPI REST API (20+ endpoints), JWT authentication with bcrypt hashing, and per-user data isolation on MySQL.}
        \item {Designed a normalized MySQL schema (6 tables) with foreign keys, cascade and restrict rules, CHECK and UNIQUE constraints, composite indexes, and a SQL view for weekly training volume.}
        \item {Wrote analytics in raw SQL: window functions (ROW\_NUMBER, LAG) for personal records and progression, a CTE-based gaps-and-islands query for workout streaks, and correlated subqueries for live goal progress.}
        \item {Implemented atomic workout saving with SQLAlchemy transactions (commit and rollback on failure) and built Recharts dashboards for weekly volume and exercise progress.}
      \resumeItemListEnd
    \vspace{-2mm}

\resumeSubHeadingListEnd
\vspace{-5.5mm}

%-----------TECHNICAL SKILLS-----------------
\section{\textbf{Technical Skills}}
\begin{itemize}[leftmargin=0.05in, label={}]
    \small{\item{
     \textbf{Languages}{: C++, Java, JavaScript, Python, SQL, MIPS Assembly} \\
     \textbf{Backend \& AI/RAG}{: FastAPI, REST APIs, Node.js, Express.js, SentenceTransformers, ChromaDB} \\
     \textbf{Frontend}{: React.js, Vite, HTML5, CSS3, Tailwind CSS} \\
     \textbf{Databases \& Tools}{: PostgreSQL, MySQL, Firebase, Git, Docker, Nginx, Figma} \\
     \textbf{Coursework}{: Database Management Systems, Computer Architecture, Digital Electronics} \\
    }}
\end{itemize}
\vspace{-16pt}

\setlength{\footskip}{4.08003pt}

\end{document}
