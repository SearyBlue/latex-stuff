---
title:  \LaTeX{} Cheatsheet
geometry: margin=1cm
---

# Document Classes

## Available Classes 

- **article**: 	For articles in scientific journals, presentations, short reports, program documentation, invitations, ...

- **IEEEtran**: 	For articles with the IEEE Transactions format.

- **proc**: 	A class for proceedings based on the article class.

- **report**: 	For longer reports containing several chapters, small books, thesis, ...

- **book**: 	For real books.

- **slides**: 	For slides. The class uses big sans serif letters.

- **memoir**: 	For changing sensibly the output of the document. It is based on the book class, but you can create any kind of document with it [1]

- **letter**: 	For writing letters.

- **beamer**: 	For writing presentations (see LaTeX/Presentations). 

<!-- 
\subsection*{Options}
\begin{itemize}
\item 10pt, 11pt, 12pt 	Sets the size of the main font in the document. If no option is specified, 10pt is assumed.
\item a4paper, letterpaper,... 	Defines the paper size. The default size is letterpaper; However, many European distributions of TeX now come pre-set for A4, not Letter, and this is also true of all distributions of pdfLaTeX. Besides that, a5paper, b5paper, executivepaper, and legalpaper can be specified.
\item fleqn 	Typesets displayed formulas left-aligned instead of centered.
\item leqno 	Places the numbering of formulas on the left hand side instead of the right.
\item titlepage, notitlepage 	Specifies whether a new page should be started after the document title or not. The article class does not start a new page by default, while report and book do.
\item twocolumn 	Instructs LaTeX to typeset the document in two columns instead of one.
\item twoside, oneside 	Specifies whether double or single sided output should be generated. The classes article and report are single sided and the book class is double sided by default. Note that this option concerns the style of the document only. The option twoside does not tell the printer you use that it should actually make a two-sided printout.
\item landscape 	Changes the layout of the document to print in landscape mode.
\item openright, openany 	Makes chapters begin either only on right hand pages or on the next page available. This does not work with the article class, as it does not know about chapters. The report class by default starts chapters on the next page available and the book class starts them on right hand pages.
\item draft 	makes LaTeX indicate hyphenation and justification problems with a small square in the right-hand margin of the problem line so they can be located quickly by a human. It also suppresses the inclusion of images and shows only a frame where they would normally occur. 
\end{itemize}

\end{document} -->