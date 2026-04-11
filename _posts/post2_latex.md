---
layout: post
title: "Getting Started with LaTeX"
---

LaTeX is a high-quality typesetting system widely used for producing scientific and technical documents. Unlike standard word processors, LaTeX allows you to focus on content while it handles formatting automatically.

## Why use LaTeX?

- **Professional output** : Produces beautifully formatted PDFs with consistent typography
- **Mathematics made easy** : Handles complex mathematical equations and formulas effortlessly
- **Automatic referencing** : Manages citations, cross-references, tables of contents, and bibliographies
- **Version control friendly** : Uses plain text files, making it perfect for Git

## Basic syntax example

```latex
\documentclass{article}
\usepackage{amsmath}

\title{My First Document}
\author{Fongang Jules Ferry}
\date{\today}

\begin{document}

\maketitle

\section{Introduction}
This is my first document written in LaTeX.

\section{Math Example}
The quadratic formula is:
\[
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
\]

\end{document}