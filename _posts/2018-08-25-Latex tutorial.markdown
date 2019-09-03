---
layout: post
title:  LATEX tutorial
date: 2018-08-25 15:10:00
description: An easy to follow and comprehensive tutorial for $$\LaTeX$$
categories: [tutorials]
---

# **Introduction to $$\small\LaTeX$$**
---  
### What is $$\LaTeX$$ ?

$$\small\LaTeX$$ is a document preparing system for high quality typesetting. It is used for Articles, Presentations, Books, Reports, Research papers scientific and technical documents, law-texts, scorecards bills, letters and a lot of other things!

It is best used for uniform formatting of the documents. All we have to worry about is the content, the formatting is taken care by $$\small\LaTeX$$

# **Creating documents in $$\small\LaTeX$$**
---  
For creating  documents, we need a $$\small\TeX$$ Distribution and a text editor. There are a variety of $$\small\TeX$$ distributions that are available both offline and online. According to your preference you can use any one of them. I have linked a few of them below.

- <img src="https://img.icons8.com/windows/32/000000/linux.png" style="vertical-align:middle"> Linux  
Check your Linux distributions software source for a TeX distribution including $$\small\LaTeX$$. You can also install the current [TeX Live distribution](https://www.tug.org/texlive) directly -- in fact this may be advisable as many Linux distributions only contain older versions of TeX Live, see [Linux TeX Live package status](https://repology.org/metapackage/texlive/versions) for details.

- <img src="https://img.icons8.com/windows/32/000000/mac-os.png" style="vertical-align:middle"> Mac OS  
The [MacTeX](http://www.tug.org/mactex/) distribution contains everything you need, including a complete TeX system with $$\small\LaTeX$$ itself and editors to write documents.

- <img src="https://img.icons8.com/windows/32/000000/windows8.png" style="vertical-align:middle"> Windows  
Check out the [MiKTeX](http://miktex.org/) or [proTeXt](http://www.tug.org/protext/) or [TeX Live](http://www.tug.org/texlive) distributions; they contain a complete TeX system with $$\small\LaTeX$$ itself and editors to write documents.

- <img src="https://img.icons8.com/windows/32/000000/globe.png" style="vertical-align:middle"> Online  
LaTeX online services like [Papeeria](http://papeeria.com/), [Overleaf](https://www.overleaf.com/), [ShareLaTeX](https://www.sharelatex.com/), [Datazar](https://www.datazar.com/), and [LaTeX base](https://latexbase.com/) offer the ability to edit, view and download $$\small\LaTeX$$ files and resulting PDFs.

# **Understanding Basics**
---  
**Command format in LaTeX**

```latex
\command[optional argument]{required argument}
\command{required argument}[optional argument]
```  

Every command in $$\small\LaTeX$$ starts with a backslash, followed by command name, the optional arguments (if any) in square brackets and the required arguments in curly brackets.  

**Environments in LaTeX**<br/>
```latex
\begin{environment}
...
...
\end{environment}
```  

In $$\small\LaTeX$$ we always work in environments like this.  

```latex
Examples:
\begin{document} ... \end{document}
\begin{equation} ... \end{equation}
\begin{tabular} ... \end{tabular}
```  
Believe it or not, if you clearly understood the above basics, then half of the job is done.