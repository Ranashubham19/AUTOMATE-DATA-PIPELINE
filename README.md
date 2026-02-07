%-------------------------
% Shubham Rana - Python Tech Intern Resume
% Targeted for Vitti Capital
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}

\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.01\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{document}

%----------HEADING----------
\begin{center}
    {\Huge \scshape Shubham Rana} \\ \vspace{1pt}
    \small \raisebox{-0.1\height}\faPhone\ +91-8091392311 ~ \href{mailto:ranashub8898@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{ranashub8898@gmail.com}} ~ 
    \href{https://linkedin.com/in/shubham-rana-a31357252}{\raisebox{-0.2\height}\faLinkedin\ \underline{linkedin.com/in/shubham-rana}} ~
    \href{https://github.com/Ranashubham19}{\raisebox{-0.2\height}\faGithub\ \underline{github.com/Ranashubham19}}
    \vspace{-4pt}
\end{center}

%-----------PROFESSIONAL SUMMARY-----------
\section{Professional Summary}
\begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
        B.Tech Computer Science student with strong Python command and hands-on experience in automation scripts, data pipelines, and internal tools. Proficient in Pandas, NumPy, REST APIs, SQL, and Git. Detail-oriented with ownership mindset. Built production-ready Python systems processing 50,000+ records with comprehensive documentation.
    }}
\end{itemize}
\vspace{-14pt}

%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Lovely Professional University}{August 2022 -- June 2026}
      {Bachelor of Technology in Computer Science and Engineering}{CGPA: 8.7/10.0}
    \resumeSubheading
      {Dayanand Anglo Vedic School, Himachal Pradesh}{April 2021 -- March 2022}
      {Higher Secondary Education (Class XII)}{Percentage: 89\%}
  \resumeSubHeadingListEnd
\vspace{-12pt}

%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {GE Digital}{January 2025 -- July 2025}
      {Software Development Intern - Python \& Automation Focus}{Hyderabad, India}
      \resumeItemListStart
        \resumeItem{Built Python automation scripts for data extraction, transformation, and reporting reducing manual work by 60\%}
        \resumeItem{Integrated REST APIs using requests library; standardized JSON outputs with error handling and logging}
        \resumeItem{Created data pipelines with Pandas to ingest, clean, and store data in PostgreSQL; used Git with structured branching and documentation}
      \resumeItemListEnd
      
    \resumeSubheading
      {Self-Initiated Projects}{August 2023 -- January 2024}
      {Python Development \& Data Engineering}{Personal Portfolio}
      \resumeItemListStart
        \resumeItem{Developed Python tools for data processing, API integration, and automation with clean OOP design and data validation}
    \resumeItemListEnd
    
  \resumeSubHeadingListEnd
\vspace{-16pt}

%-----------PROJECTS-----------
\section{Technical Projects (GitHub Portfolio)}
    \vspace{-5pt}
    \resumeSubHeadingListStart
    
      \resumeProjectHeading
          {\textbf{Automated Data Collection Pipeline} $|$ \emph{Python, Google API, YouTube API, Tkinter, SMTP}}{March 2025 -- June 2025}
          \resumeItemListStart
            \resumeItem{Built automated data pipeline using Google Image API and YouTube API to collect and download 100+ images/videos per API call for ML/DL workflows}
            \resumeItem{Developed Tkinter GUI for user interaction; implemented email automation using SMTP to send collected datasets as compressed attachments}
            \resumeItem{Applied image preprocessing (resizing, grayscaling) and video compression; packaged pipeline with proper error handling and API credential management}
          \resumeItemListEnd
          \vspace{-13pt}
          
      \resumeProjectHeading
          {\textbf{REST API Integration \& Alert System} $|$ \emph{Python, requests, JSON, cron, FastAPI}}{Jul 2024 -- Dec 2024}
          \resumeItemListStart
            \resumeItem{Integrated REST APIs using requests library; handled authentication, rate limiting, and error responses with proper logging}
            \resumeItem{Built FastAPI service for threshold-based alerts with cron scheduling; maintained on GitHub with structured commits and documentation}
          \resumeItemListEnd
          \vspace{-13pt}
          
      \resumeProjectHeading
          {\textbf{Data Analytics Dashboard} $|$ \emph{Python, Pandas, NumPy, SQL, Jupyter, CSV}}{Jan 2024 -- Jun 2024}
          \resumeItemListStart
            \resumeItem{Created analytics utilities processing 10,000+ records with Pandas; performed data cleaning, aggregation, and statistical analysis}
            \resumeItem{Built notebook-based dashboard with reproducible outputs; implemented SQL queries (SQLite) and wrote SOPs for stakeholders}
          \resumeItemListEnd
          
    \resumeSubHeadingListEnd
\vspace{-15pt}

%-----------TECHNICAL SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Python (Strong Command)}{: Data structures, file handling, OOP, exception handling, logging, production scripts} \\
     \textbf{Data Engineering}{: Pandas, NumPy, data pipelines, ETL, data validation, CSV/JSON handling} \\
     \textbf{APIs \& Web}{: REST APIs (requests), JSON, FastAPI, Flask, API integration} \\
     \textbf{Databases}{: SQLite, PostgreSQL, MySQL, SQL queries} \\
     \textbf{DevOps \& Tools}{: Git/GitHub, Docker, cron, CI/CD, AWS basics, clean code, documentation}
    }}
 \end{itemize}
 \vspace{-16pt}

%-----------ACHIEVEMENTS-----------
\section{Achievements \& Strengths}
    \begin{itemize}[leftmargin=0.15in, label={}]
        \small{\item{
            \textbf{Problem Solving \& GitHub}{: Solved 1,000+ coding problems; Active GitHub with documented Python projects and clean commit history} \\
            \textbf{Ownership \& Detail}{: Independently built Python systems with full accountability; consistent data validation, error handling, and logging} \\
            \textbf{Finance Interest}{: Self-learning financial markets and trading systems; Ready for technical interviews and coding tasks}
        }}
    \end{itemize}
\vspace{-10pt}

\end{document}
