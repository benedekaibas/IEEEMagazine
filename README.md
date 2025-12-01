# IEEEMagazine
Submission for the IEEE Magazine for Software Engineering

latex -> copy it later to the proper latex file:
\documentclass{IEEEcsmag}

\usepackage[colorlinks,urlcolor=blue,linkcolor=blue,citecolor=blue]{hyperref}
\expandafter\def\expandafter\UrlBreaks\expandafter{\UrlBreaks\do\/\do\*\do\-\do\~\do\'\do\"\do\-}
\usepackage{upmath,color}


\jvol{XX}
\jnum{XX}
\paper{8}
\jmonth{Month}
\jname{Publication Name}
\jtitle{Publication Title}
\pubyear{2021}

\newtheorem{theorem}{Theorem}
\newtheorem{lemma}{Lemma}


\setcounter{secnumdepth}{0}

\begin{document}

\sptitle{Article Type: Description  (see below for more detail)}

\title{Title: An Empirical Study on Static Analyzer Toolsets to Reduce False Positives, False Negatives in Python Type Checkers}

\author{Benedek Kaibas}
\affil{Allegheny College, PA, 16335, USA}

\author{Dr. Gregory M. Kapfhammer}
\affil{Allegheny College, PA, 16335, USA}

\markboth{THEME/FEATURE/DEPARTMENT}{THEME/FEATURE/DEPARTMENT}

\begin{abstract}\looseness-1The rapid ascent of Python as a dominant programming language has necessitated a reliance on static type checkers to mitigate runtime exceptions in large-scale software systems. While established tools like Mypy and Pyright, alongside emerging high-performance alternatives such as Pyrefly and Zuban, are now integral to continuous integration pipelines, their reliability remains largely unverified against the language’s rapidly evolving feature set. This article presents an empirical study addressing the critical trade-off between soundness and completeness in Python static analysis. We introduce Pytifex, a novel automated framework that bridges the gap between theoretical fuzzing and real-world software defects. Unlike traditional methods that rely on random code generation, Pytifex leverages a data-driven approach by mining closed GitHub issue reports specifically labeled as false positives and false negatives. It systematically refines and mutates these "seed" examples to generate high-level, adversarial test cases designed to expose regressions and soundness gaps. By subjecting both mature and nascent type checkers to this targeted differential testing, our research highlights significant discrepancies in error reporting and offers a robust methodology for reducing false diagnostics. This work provides tool maintainers with actionable insights to fortify their inference engines, ultimately enhancing the stability and correctness of the Python type-checking ecosystem.
\end{abstract}

\maketitle




\end{document}

