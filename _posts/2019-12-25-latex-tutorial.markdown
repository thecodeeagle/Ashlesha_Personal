---
layout: post
author: Aditya Wagh
lang: en-US
title: An intuitive introduction to LATEX
date: 2019-December-25 15:10:00
excerpt: An easy to understand and quick introduction to latex.
categories: [latex]
---

![Image](/assets/images/post-images/latex.jpg)

\\(\small\LaTeX\\) is a document preparing system for high quality typesetting. It is used for Articles, Presentations, Books, Reports, Research papers scientific and technical documents, law-texts, scorecards bills, letters and a lot of other things! It is best used for uniform formatting of the documents. All we have to worry about is the content, the formatting is taken care by \\(\small\LaTeX\\)

{% include toc.html %}

## Creating documents in \\(\small\LaTeX\\)

For creating documents, we need a \\(\small\TeX\\) Distribution and a text editor. There are a variety of \\(\small\TeX\\) distributions that are available both offline and online. According to your preference you can use any one of them. I have linked a few of them below.

<table>
<tr>
    <td class="text-center"><img src="https://img.icons8.com/color/48/000000/linux.png">Linux</td>
    <td>Check your Linux distributions software source for a \(\TeX\) distribution including  \(\small\LaTeX\) . You can also install the current <a href="https://www.tug.org/texlive">TeX Live distribution</a> directly -- in fact this may be advisable as many Linux distributions only contain older versions of \(\small\TeX\) Live, see <a href="https://repology.org/metapackage/texlive/versions">Linux TeX Live</a> package status for details. </td>
</tr>
<tr>
    <td class="text-center"><img src="https://img.icons8.com/color/48/000000/mac-logo.png">Mac OS</td>
    <td>The <a href="http://www.tug.org/mactex">MacTeX</a> distribution contains everything you need, including a complete \(\small\TeX\) system with  \(\small\LaTeX\) itself and editors to write documents.</td>
</tr>
<tr>
    <td class="text-center"><img src="https://img.icons8.com/color/48/000000/windows-10.png">Windows</td>
    <td>Check out the <a href="http://miktex.org/">MiKTeX</a> or <a href="http://www.tug.org/protext/">proTeXt</a> or <a href="http://www.tug.org/texlive">TeX Live</a> distributions; they contain a complete \(\small\TeX\) system with  \(\small\LaTeX\) itself and editors to write documents.</td>
</tr>
<tr>
    <td class="text-center"><img src="https://img.icons8.com/color/48/000000/globe--v1.png">Online</td>
    <td>LaTeX online services like <a href="http://papeeria.com/">Papeeria</a>, <a href="https://www.overleaf.com/">Overleaf</a>, <a href="https://www.sharelatex.com/">ShareLaTeX</a>, <a href="https://www.datazar.com/">Datazar</a>, and <a href="https://latexbase.com/">LaTeX base</a> offer the ability to edit, view and download  \(\small\LaTeX\) files and resulting PDFs.</td>
</tr>
</table>

## Understanding Basics

There are two fundamental things when dealing with \\(\small\LaTeX\\)

-   Command Format
-   Environments

We will discuss them one by one.

#### Command format

Every command in \\(\small\LaTeX\\) starts with a backslash, followed by command name, the optional arguments (if any) in square brackets and the required arguments in curly brackets.

```latex
\command[optional argument]{required argument}
\command{required argument}[optional argument]
```

#### Environments

In \\(\small\LaTeX\\) we always work in environments like this.

```
\begin{environment} ... \end{environment}
```
