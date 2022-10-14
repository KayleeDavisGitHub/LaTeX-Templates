
# LaTeX-Templates

### Table of contents
<!--ts-->
  * [What's TeXMaker?](#What's-TeXMaker?)
  * [What's Here?](#What's-Here)
    * [Memo](#Memo)
    * [BibTex and Tables of Contents](#BibTex-and-Tables-of-Contents)
    * [Index](#Index)
    * [Example .rnw](#Example-rnw)
    * [Math, Tables, and Figures](#Math-Tables-and-Figures)
    * [Dark LaTeX Slides](#Dark-LaTeX-Slides)
  * [Journal Standards](#Journal-Standards)
  * [Other Resources](#Other-Resources)
  * [Licensing](#Licensing)
<!--te-->


#### What's TeXMaker?
LaTeX can all be ran and built through the program [TeXMaker](http://www.xm1math.net/texmaker/). Which, when files are loaded, look like this:

  ![ ](https://raw.githubusercontent.com/KayleeDavisGithub/LaTeX-Templates/master/Latex.png)
  
On the left of TeXMaker we have some useful buttons that will add the code for various symbols into the black coding box in the middle of the screen. To the right we have the .pdf viewer to see our output when we compile. To compile our code into our .pdf we can use `Quick Build` opitions and other compiling options that we can manage through `Options -> Configure TexMaker`. The coding examples listed here will often include these needed specifications at the top of each coding section in the "preamble."
 
#### What's here?
Various LaTeX templates and materials. Here you will find the .tex files to learn various things you can do in LaTeX. Each .tex file will have detailed instructions in the preamble for beginners to understand some of the intuition behind LaTeX (and to more easily customize each format). Feel free to borrow this code and make it your own! 

#### Memo
The LaTeX Memo format is the bare-bones format for writing quick papers or letters. It is a simple .pdf output that can be used for homework assignemnts, medium length papers, or rough-draft articles. It includes some footnote formatting, section formatting, and font formatting. I use this as a first-pass at about 90% of the things I write.

This memo .tex above goes into details on the packages I've used. To save on clutter, elsewhere comments are removed or condensed.

#### BibTex and Tables of Contents
The Bibtex .tex file should be downloaded into the same area as the .bib file. To make a .bib file on your own, simply save a new file from TeXMaker as a .bib (you can format these .bib files in LaTeX or any simple text editor like [Notepad(++)](https://notepad-plus-plus.org/) ). 

Once these are in the same location, follow the complilation instructions on the top of the .tex file to properly tell LaTeX to compile the document in a specified order. This .tex file provides instructions on a customized table of contents and sections/subsections. 

The .tex document ends with a few notes on customizing bibliographies. The .bib file, if opened, provides similar details. This is a great beginning document to get started in using .bib files, and creating easy bibliographies with easily changable citation formatting. 

#### Index 
The LaTeX index file is a neat example of guided note-taking where I grabbed "notable quotes" from various readings; yet, as this document grows it may be difficult to find quotes per topic! Indexing can help since an organized table of contents may not account for multiple topics within a quote, and would be taxing to shuffle around quotes. 

The index file begins with a quick introduction to quick-building in LaTeX since the compiling process would include making a latex index file. Consider placing this file into its own folder for your own notes since the associated files can add a lot of clutter to say /documents. The index file includes hyperlinks on the page number to jump to a section where the quote is (or whatever you're indexing). 

After compiling, consider opening these index files that are made in Notepad or Notepad++, this should provide some intution on how LaTeX adds seperate files to generate an index, and how these indexes can be formatted for more advanced or organized indices. 

#### Example.rnw
What if we need to add code neatly to our LaTeX documentation? I would consider building programming language not in TeXMaker but in R's "sweave" document option. This will build a .rnw (meaning R "no web") document which looks very similar to LaTeX! Change your R setting to change from "sweave" to `knitr` and launch a new .rnw to begin using the .rnw just like you would LaTeX. This makes adding code easy and ensures reproducability. 

I've included a example lab assignment I've created labeled "Example.rnw" launch this with RStudio to see how .rnw's works. To customize your code output in .rnw see the various templates [here](http://animation.r-forge.r-project.org/knitr/) and how to implement them [here]( https://github.com/yihui/knitr/blob/master/inst/examples/knitr-themes.Rnw). I've included some customization for you to consider.

#### Math, Tables, and Figures.
This is a LaTeX example for building various equations, tables, and figures (including theory plots). This is, arguably, one of the main contributions of a code-based editor. In this document I tried to include a lot of examples for you to tear apart and use yourself elsewhere. 

#### Dark LaTeX Slides
This folder has a complex customized dark LaTeX format and a simple .tex dark LaTeX slides format. Both use `beamer`. I prefer dark slides with simple content and these mostly get me through any presentation I have to make. The output is a .pdf and can be viewed in full-screen mode and ran similarly to a Microsoft presentation. 

#### CV
If you're looking for LaTeX inspiration, check out [Awesome-CV](https://github.com/posquit0/Awesome-CV).


### Journal Standards:

Some adacademic journals do not allow LaTeX submissions depending upon the academic field and type of journal. For political science and communication research, I have a helpful refrence list below:

| Journal | Takes .pdf? | Helpful Sources |
| :--- | :---: | --- |
| Science | Yes | How to submit articles and format documents in LaTeX found [here](http://www.sciencemag.org/site/feature/contribinfo/prep/TeX_help/scifile.pdf).  |
| APSR | Yes | LaTeX template [here](https://www.overleaf.com/latex/templates/american-political-%20science-review-aspr-submission-%20template/fxffppspqczt#.WftFOmhSxPa). |
| APSA | Yes | guidelines for submission can be found [here](https://ajps.org/guidelines-for-manuscripts/).|
| JOP   | Yes |   |
| PA (Political Analysis) | Yes | May take .tex files also.  |
| Political Communication | Yes | "Prefers" Word [as found here](http://www.tandfonline.com/action/authorSubmission?show=instructions&journalCode=upcp20). |
| Journal of Communication | No | Guidelines can be found [here](http://onlinelibrary.wiley.com/journal/10.1111/(ISSN)1460-2466/homepage/ForAuthors.html) |
| Communication Research | No | Guidelines can be found [here](https://us.sagepub.com/en-us/nam/journal/communication-research#submission-guidelines) |
| Social Networks | Yes | Guideline .pdf  guide can be found [here](https://www.journals.elsevier.com/social-networks/policies) |

Of course even if a journal doesn't take .pdf submissions it doesn't mean we cannot utilize LaTeX! We can still make slides, improve workflow, manage our CV, and build our bibliographies and other research materials within LaTeX. 

If you must have a .doc for a publication or other reason, consider a free online converter found [here](http://pdf2doc.com/). Simply upload your .pdf and download your Word .doc. Be warned that a lot of the benefits gained from LaTeX (Math, tables, figures, complex formatting) do not transfer over well into Word. I have tested my "Memo" LaTeX formatting in the converter and it transfers over fairly well. 

### Other Resources
Some helpful resources:

APA Manuscript Package: https://github.com/crsh/papaja 

RStudio citation add-in help: https://github.com/crsh/citr

Overleaf (https://www.overleaf.com/): Free, cloud-based collaborative writing and publishing with Latex. It includes a visual editor, and there are hundreds of pre-loaded templates available.
 
Tables Generator (http://www.tablesgenerator.com/latex_tables#): You can draft of my manuscript in Word before preparing it in Latex, and this tool makes it easier to convert Word tables.  Just copy, paste, and clean up the resulting code.
 
Bibtex export style for Endnote (http://endnote.com/downloads/style/bibtex-export): Use Endnote to manage references.  With this output style, you can save my cites in a Latex-friendly format.

Better Bib(La)TeX Zotero extension: https://github.com/retorquere/zotero-better-bibtex

### Licensing
The content of this project itself is licensed under the [Creative Commons Attribution 3.0 license](https://creativecommons.org/licenses/by/3.0/us/deed.en_US). Please check licensing information for underlying LaTeX and R source coding. Be sure to cite package and coding content creators when applicable. 
