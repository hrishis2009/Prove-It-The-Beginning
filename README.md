![GitHub Downloads](https://img.shields.io/github/downloads/hrishis2009/Prove-It-The-Beginning/total) ![GitHub release (latest by date)](https://img.shields.io/github/v/release/hrishis2009/Prove-It-The-Beginning) [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

# Prove It?: *The Beginning*
A friendly introduction to mathematical proofs written by and for students and math competition enthusiasts.

<p align="center">
  <a href="https://github.com/hrishis2009/Prove-It-The-Beginning/releases/download/v1.1/Prove.It.The.Beginning.v1.1.pdf">
    <img src="https://img.shields.io/badge/Download_Latest_(v1.1)-2ea44f?style=for-the-badge" alt="Download Latest (v1.1)" width="400" height="60">
  </a>
</p>

Alternatively, access the book by going to [Releases](https://github.com/hrishis2009/Prove-It-The-Beginning/releases), selecting the latest version (v1.1), and selecting "Prove It? The Beginning v1.1.pdf".

Yet another alternative method is by going to [Releases](https://github.com/hrishis2009/Prove-It-The-Beginning/releases), downloading the source code ([zip](https://github.com/hrishis2009/Prove-It-The-Beginning/archive/refs/tags/v1.1.zip) / [tar.gz](https://github.com/hrishis2009/Prove-It-The-Beginning/archive/refs/tags/v1.1.tar.gz)), and compiling using a [LaTeX](https://www.latex-project.org/) distribution such as [MacTeX](https://www.tug.org/mactex/) or [MikTeX](https://miktex.org/).

From the ``src`` directory, run

```
latexmk -pdf main.tex
```
This build process has been tested primarily with ``latexmk`` and pdfLaTeX. Alternative compilers or build systems may need to install additional [dependencies](https://github.com/hrishis2009/Prove-It-The-Beginning/blob/main/DEPENDENCIES.md) or make minor adjustments to the build/compile process.


## About

I wrote this book because ***math is more than numbers***. In my school system (US), and many more around the world, mathematics is taught as a subject in which the primary goal is to solve for some variable $x$. Yet, mathematical proofs are a cornerstone of the field that students learn far too late. This is meant to serve as a friendly introduction to mathematical proofs without the need to take an Analysis class – proofs are commonly first taught in such classes in the US. It covers some basic techniques from logic and sets, to methods of direct and indirect proof, and ends with a "Potpourri of Proofs" ([LaTeX](https://github.com/hrishis2009/Prove-It-The-Beginning/blob/main/src/chapters/chapter5.tex)). 

Mathematics competitions further inspired me. Specifically, while earlier stages are primarily calculation-based, the [USA(J)MO](https://artofproblemsolving.com/wiki/index.php/United_States_of_America_Mathematical_Olympiad?srsltid=AfmBOoo8OMz1n0_P4K823kMM3zD7se1Ghu5FOxeGYNVjAhgXJNcKNE2P) (and the outlier [USAMTS](https://www.usamts.org/)) and further competitions are primarily proof-based. As such, I have made an attempt to demonstrate concepts of mathematical proof while also proving some common theorems/strategies used in competition mathematics (i.e., [AM-GM](https://artofproblemsolving.com/wiki/index.php/AM-GM_Inequality?srsltid=AfmBOopGuELuyHTrtG79eiuwbMnBN6Z4aXai4GHtQ0GWxs8WjgXnFRR0) or [Ptolemy's Theorem)](https://artofproblemsolving.com/wiki/index.php/Ptolemy%27s_theorem?srsltid=AfmBOortSZRCm6DDNukWteF_7JCQ3X1r0ltLfWvKxr_VT9WDYTId6Gfu). 

Above all, I hope it serves as a starting point to inspire many to learn about proof-based mathematics, enjoy it, and ultimately continue forward in their journey. I hope it brings challenges and encourages readers to pursue proof-based math, whether in research, competitions, class, or simply as a hobby for fun!

Thank you,

Hrishi S - *The author*

## Stats (v1.1)
- 238 pages
- 100+ Worked Examples and Problems
- 88 Hints (randomized)
- Full solutions
- A lot of fun!

## A Rough Sketch of the Table of Contents
Each is linked with the corresponding LaTeX source file.
- [Introduction / *Why Proofs?*](https://github.com/hrishis2009/Prove-It-The-Beginning/blob/main/src/chapters/chapter1.tex)
- [Logic and Sets](https://github.com/hrishis2009/Prove-It-The-Beginning/blob/main/src/chapters/chapter2.tex)
- [Direct Proof Techniques](https://github.com/hrishis2009/Prove-It-The-Beginning/blob/main/src/chapters/chapter3.tex)
- [Indirect Proof Techniques](https://github.com/hrishis2009/Prove-It-The-Beginning/blob/main/src/chapters/chapter4.tex)
- [Many Mixed Examples](https://github.com/hrishis2009/Prove-It-The-Beginning/blob/main/src/chapters/chapter5.tex)
- [Appendices](https://github.com/hrishis2009/Prove-It-The-Beginning/tree/main/src/chapters/appendices)
  - [Hints](https://github.com/hrishis2009/Prove-It-The-Beginning/blob/main/src/chapters/appendices/hints.tex)
  - [Solutions to Problem Sets](https://github.com/hrishis2009/Prove-It-The-Beginning/tree/main/src/chapters/appendices) (`apsX.tex`)
  - [Extra Resources](https://github.com/hrishis2009/Prove-It-The-Beginning/blob/main/src/chapters/appendices/resources.tex)


## Intended Audience

All readers new to mathematical proofs and curious about learning may benefit. I wrote this book assuming some basic (and some not-so-basic) prerequisites:
- Basic familiarity with arithmetic, algebra, geometry, and divisibility. In the US, this equates to coursework up to high school geometry. Though not having taken these courses will not mean the book is gibberish, just some examples/problems might be a little more difficult. I advise you to (carefully) use your resources!
- Some knowledge of modular arithmetic. This is not usually taught in school; [***Appendix C***](https://github.com/hrishis2009/Prove-It-The-Beginning/blob/main/src/chapters/appendices/resources.tex) contains a list of good handouts to get a good understanding.
- Significant ingenuity! The problems and examples are difficult, and increase in difficulty as the book goes on. This requires significant perseverance – the problem set is ***not*** easy. I have a hints appendix to help you move forward

The primary audience is students making the transition from solving mathematical problems to constructing mathematical proofs. This happens at different stages for different people, so it is very difficult to pin down a specific age group or other demographic. If you are interested in mathematical proofs and want to learn more in an accessible way, this book is for you!


## Contributing

Anyone is welcome to [contribute](https://github.com/hrishis2009/Prove-It-The-Beginning/blob/main/CONTRIBUTING.md). Feedback, LaTeX fixes, clarifications, suggestions for additional content, or any other improvements are appreciated.

In particular, reports of typographical errors, mathematical mistakes, unclear explanations, or issues with references are especially helpful.

Contributors may, with their consent, be acknowledged on a special contributors page in future editions of the book.

Please see [`CONTRIBUTING.md`](https://github.com/hrishis2009/Prove-It-The-Beginning/blob/main/CONTRIBUTING.md) for the Contributing License Agreement (CLA) and further details.

### Contribution Procedure

You may contribute by submitting a [Pull Request](https://github.com/hrishis2009/Prove-It-The-Beginning/pulls) or opening an [Issue](https://github.com/hrishis2009/Prove-It-The-Beginning/issues). I will try to review submissions promptly. If you just have feedback, feel free to open an Issue, go to the [Discussions](https://github.com/hrishis2009/Prove-It-The-Beginning/discussions), or to email me [hrishis2009@gmail.com](mailto:hrishis2009@gmail.com).


## License
This work is [licensed](https://github.com/hrishis2009/Prove-It-The-Beginning/blob/main/LICENSE.md) under CC BY-NC-SA 4.0.
