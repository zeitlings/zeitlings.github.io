# LaTeX for Philosophers

<div id="markdown-toc" style="font-size: 14px">

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

<p style="font-size:16px">Contents</p>

- [LaTeX for Philosophers](#latex-for-philosophers)
	- [1. LaTeX fundamentals](#1-latex-fundamentals)
		- [1.1 Install LaTeX](#11-install-latex)
		- [1.2 Editors](#12-editors)
			- [1.2.1 Overleaf](#121-overleaf)
	- [2. Pandoc and Markdown](#2-pandoc-and-markdown)
	- [3. LaTeX Guides](#3-latex-guides)
		- [3.1 LaTex for Logicians](#31-latex-for-logicians)
		- [3.2 Prepare your Thesis with LaTeX](#32-prepare-your-thesis-with-latex)
</div>

<!-- /TOC -->


It's best to acquaint yourself as early as possible with LaTeX, as it is the most reliable, most adjustable solution and simply most pleasing to the eyes way to write your papers or thesis. You can consider LaTeX the default standard of good practice. Nonetheless, journals still tend ask for word files these days. For an easy way to convert your file back, see what _Pandoc_ can do for you.

##  1. LaTeX fundamentals
### 1.1 Install LaTeX

> LaTeX (/ˈlɑːtɛx/ LAH-tekh or /ˈleɪtɛx/ LAY-tekh; a shortening of Lamport TeX) is a document preparation system. When writing, the writer uses plain text as opposed to the formatted text found in WYSIWYG [...] The writer uses markup tagging conventions to define the general structure of a document (such as article, book, and letter), to stylise text throughout a document (such as bold and italics), and to add citations and cross-references. 
>
> @ [Wikipedia](https://en.wikipedia.org/wiki/LaTeX)

For ``*.pdfs`` to be compiled from your ``*.tex`` files it relies on several dependencies to be installed on your computer. They are provided by the [Tex User Group (TUG)](http://www.tug.org/interest.html#free) for free. For example, Mac users can install [MacTeX](https://www.tug.org/mactex/). Windows and Linux users can install the dependencies with [MiKTeX](https://miktex.org/download) or use [TeX Live](https://www.tug.org/texlive/). Check the TUG for alternatives. On [https://www.latex-project.org/](https://www.latex-project.org/) you can find general information. 

### 1.2 Editors

You can find a list of free editors to write in on [www.tug.org](http://www.tug.org/interest.html#packages). Such include GitHubs open source editor [Atom](https://atom.io/) or [TeX Studio](https://texstudio.org/). A list of commercial applications can be found [here](http://www.tug.org/interest.html#vendors). A rather user friendly and reasonably priced example is [Texpad](https://texpad.com/) for mac. They also provide an iOS option for mobile editing. (I have no affiliation to them.)


#### 1.2.1 Overleaf
Overleaf deserves a special mention. It is an online, in-browser LaTeX-editor that makes your project accessible from anywhere, given that there is a wifi connection. They offer a free plan that should cover most of your needs. You can share your files with people to collaborate on your project directly in the browser window. However, it doesn't work well with mobile devices as of yet.
[www.overleaf.com](https://www.overleaf.com?r=34b37c99&rm=d&rs=b)

## 2. Pandoc and Markdown

Sometimes you might want to write in Markdown and later integrate your output into your LaTeX file, e.g. when you're on the road. [Pandoc](https://pandoc.org/) lets you convert different kinds of formatting into another. To use its full potential, this requires some fiddling with the command line. For a quick and simple way to specifically convert Markdown into LaTeX or vice versa you could try my [Alfred Workflow](https://github.com/zeitlings/alfred-latex-md) to do just that.

If you're still looking for a Markdown editor I'd recommend the charming cross platform, open source editor [**Typora**](https://typora.io/). There are a lot of them out there and ultimately really any editor will do. [Here's a Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

**Links:**  
[https://pandoc.org/](https://pandoc.org/) (Markup conversion)  
[https://typora.io/](https://typora.io/) (Markdown editor)  
[https://github.com/zeitlings/alfred-latex-md](https://github.com/zeitlings/alfred-latex-md) (LaTeX ⟷ Markdown Alfred Workflow)  
[https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) (Markdown Cheatsheet)


## 3. LaTeX Guides
### 3.1 LaTex for Logicians
[http://www.logicmatters.net/latex-for-logicians/](http://www.logicmatters.net/latex-for-logicians/)

> These pages give a brief guide to resources of interest to logicians, philosophers and others using LaTeX to produce papers or presentations, teaching materials, theses or books, and perhaps wanting to include logical matter such as natural deduction proofs.


### 3.2 Prepare your Thesis with LaTeX
[http://www.koksvik.net/latex.php](http://www.koksvik.net/latex.php)

> This page provides instructions for how to prepare your thesis with LaTeX. It also provides a number of template files which can be used to produce a thesis with relative ease. The page was last updated on 24 September 2012.


