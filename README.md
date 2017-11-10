### LaTeX-Templates

## What's here?
Various LaTeX Templates and Tutorials. Here you will find the .tex files to learn various programs and intutions in LaTeX. Each .tex file will have detailed instructions in the preamble for beginners to understand some of the intuition behind LaTeX (and to more easily customize each format). For a quick-view of what you will learn, see the associated .pdf. 

Built in [TeXMaker](http://www.xm1math.net/texmaker/). 

Questions? Feel free to email me at MailKyleDavis@gmail.com

## Memo
The LaTeX Memo format is the bare-bones format for writing quick papers or letters. It is a simple .pdf output that can be used for homework assignemnts, medium length papers, or rough-draft articles. It includes some footnote formatting, section formatting, and font formatting. 

This memo .tex goes into details on the packages I've used. To save on clutter, elsewhere comments are removed or condensed.

## BibTex and Tables of Contents
The Bibtex .tex file should be downloaded into the same area as the .bib file. To make a .bib file on your own, simply save a new file from TeXMaker as a .bib (you can format these .bib files in LaTeX or any simple text editor like [Notepad(++)](https://notepad-plus-plus.org/) ). 

Once these are in the same location, follow the complilation instructions on the top of the .tex file to properly tell LaTeX to compile the document in a specified order. This .tex file provides instructions on a customized table of contents and sections/subsections. 

The .tex document ends with a few notes on customizing bibliographies. The .bib file, if opened, provides similar details. These files are defaulted to the American Political Science Review publication standards. 

## Index 
The LaTeX index file is a neat example of guided note-taking where I grabbed "notable quotes" from various readings; yet, as this document grows it may be difficult to find quotes per topic! Indexing can help since an organized table of contents may not account for multiple topics within a quote, and would be taxing to shuffle around quotes. 

The index file begins with a quick introduction to quick-building in LaTeX since the compiling process would include making a latex index file. Consider placing this file into its own folder for your own notes since the associated files can add a lot of clutter to say /documents. The index file includes hyperlinks on the page number to jump to a section where the quote is (or whatever you're indexing). 

After compiling, consider opening these index files that are made in Notepad or Notepad++, this should provide some intution on how LaTeX adds seperate files to generate an index, and how these indexes can be formatted for more advanced or organized indices. 

## R From .rnw
What if we need to add code neatly to our LaTeX documentation? I would consider building programming language not in TeXMaker but in (in the case of R) R's "sweave" document. This will build a .rnw (meaning R "no web") document which looks very similar to LaTeX! Change you R setting to change from "sweave" to `knitr` and launch a new .rnw to begin using the .rnw just like you would LaTeX. This makes adding code easy and ensures reproducability. 

If you're interested, I've included how these R sections are formatted in a LaTeX output which is ran to give you the .pdf (this is all done under the hood in R from .rnw ("sweave")). These files are a great way to present code in an organized way for readers to clearly sepearate code from text. These are also great for doing quantiative homework assignments or reports more broadly. 

I've included a example lab assignment I've created labeled "Example.rnw" launch this with RStudio to see how .rnw's works. To customize your code output in .rnw see the various templates [here](http://animation.r-forge.r-project.org/knitr/) and how to implement them [here]( https://github.com/yihui/knitr/blob/master/inst/examples/knitr-themes.Rnw). 


## Math, Tables, and Figures.
This is a LaTeX example for building various equations, tables, and figures (including theory plots). This is, arguably, one of the main contributions of a code-based editor. 

## Dark LaTeX Slides
This folder has a complex customized dark LaTeX format and a simple .tex dark LaTeX slides format. Both use `beamer`.

## Simple CV
A simplified working CV example that can be customized. If you're looking for inspiration, check out [Awesome-CV](https://github.com/posquit0/Awesome-CV).


## Other Resources:
The journal "Science" has a pdf on how to submit articles and format documents in LaTeX found [here](http://www.sciencemag.org/site/feature/contribinfo/prep/TeX_help/scifile.pdf). 

Other political science journals accept LaTeX submissions or .pdf submissions. This includes the American Political Science Review who list an easy LaTeX template [here](https://www.overleaf.com/latex/templates/american-political-%20science-review-aspr-submission-%20template/fxffppspqczt#.WftFOmhSxPa). The American Political Science Association journal doesn't care, their guidelines for submission can be found [here](https://ajps.org/guidelines-for-manuscripts/). The Journal of Politics accepts .pdf and nearly every methodological journal (like Political Analysis) will accept the .tex submission as well. Journals like "Political Communication" accept .pdf files but "prefer" Word [as found here](http://www.tandfonline.com/action/authorSubmission?show=instructions&journalCode=upcp20).

Overall, many top journals accept .pdf documents. For journals that have not caught up they either will catch up with technology or you can simply convert your .pdf to a Word document any time. On their end, many journals and publishing houses use LaTeX to format submissions anyways. 


