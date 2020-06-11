---
layout: post
author: Aditya Wagh
lang: en-US
title:  An intuitive introduction to LATEX  
date: 2019-December-25 15:10:00
excerpt: An easy to understand and quick introduction to latex.
categories: [latex]
---
![Image](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse4.mm.bing.net%2Fth%3Fid%3DOIP.ogs9xLnBgjkvrmqnWO1qbwHaEf%26pid%3DApi&f=1)![Image](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse4.mm.bing.net%2Fth%3Fid%3DOIP.ogs9xLnBgjkvrmqnWO1qbwHaEf%26pid%3DApi&f=1)

 \\(\small\LaTeX\\) is a document preparing system for high quality typesetting. It is used for Articles, Presentations, Books, Reports, Research papers scientific and technical documents, law-texts, scorecards bills, letters and a lot of other things! It is best used for uniform formatting of the documents. All we have to worry about is the content, the formatting is taken care by  \\(\small\LaTeX\\)

{% include toc.html %}
## Creating documents in  \\(\small\LaTeX\\)

For creating  documents, we need a  \\(\small\TeX\\) Distribution and a text editor. There are a variety of \\(\small\TeX\\) distributions that are available both offline and online. According to your preference you can use any one of them. I have linked a few of them below.

|---|---|
|![linux logo](https://img.icons8.com/color/48/000000/linux.png) Linux   |  Check your Linux distributions software source for a \\(\small\TeX\\) distribution including  \\(\small\LaTeX\\) . You can also install the current [TeX Live distribution](https://www.tug.org/texlive) directly -- in fact this may be advisable as many Linux distributions only contain older versions of \\(\small\TeX\\) Live, see [Linux TeX Live package status](https://repology.org/metapackage/texlive/versions) for details.  |
|![mac os logo](https://img.icons8.com/color/48/000000/mac-logo.png) Mac OS  | The [MacTeX](http://www.tug.org/mactex/) distribution contains everything you need, including a complete \\(\small\TeX\\) system with  \\(\small\LaTeX\\) itself and editors to write documents.  |
|![windows logo](https://img.icons8.com/color/48/000000/windows-10.png) Windows  | Check out the [MiKTeX](http://miktex.org/) or [proTeXt](http://www.tug.org/protext/) or [TeX Live](http://www.tug.org/texlive) distributions; they contain a complete \\(\small\TeX\\) system with  \\(\small\LaTeX\\) itself and editors to write documents.  |
|![globe logo](https://img.icons8.com/color/48/000000/globe--v1.png) Online  |  LaTeX online services like [Papeeria](http://papeeria.com/), [Overleaf](https://www.overleaf.com/), [ShareLaTeX](https://www.sharelatex.com/), [Datazar](https://www.datazar.com/), and [LaTeX base](https://latexbase.com/) offer the ability to edit, view and download  \\(\small\LaTeX\\) files and resulting PDFs. |

## Understanding Basics
  
### Command format

Every command in  \\(\small\LaTeX\\)  starts with a backslash, followed by command name, the optional arguments (if any) in square brackets and the required arguments in curly brackets.  

```latex
\command[optional argument]{required argument}
\command{required argument}[optional argument]
```

#### Environments

In \\(\small\LaTeX\\)  we always work in environments like this.

```
\begin{environment} ... \end{environment}
```

##### Examples:
```
\begin{document} ... \end{document}  
\begin{equation} ... \end{equation}
\begin{tabular} ... \end{tabular}
```


