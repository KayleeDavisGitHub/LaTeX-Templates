# LaTeX-Templates
Various LaTeX Templates and Tutorials. Here you will find the .tex files to run in LaTeX (I prefer TeXMaker too) and what the .pdf ought look like once compiled. Each .tex file will have detailed instructions in the preamble of each format for begginers to LaTeX to be able to understand some of the intuition behind LaTeX (and to more easily customize each format). 

Questions? Feel free to email me at MailKyleDavis@gmail.com

# Memo
The LaTeX Memo format is the bare-bones format for writing quick papers or letters. It is a simple .pdf output that can be used for homework assignemnts, medium length papers, or rough-draft articles. It includes some footnote formatting, section formatting, and font formatting. 

# Index 
The LaTeX Index file is a neat example of guided note-taking where I grabbed "notable quotes" from various readings; yet, as this document grows it may be difficult to find quotes per topic! Indexing can help since an organized table of contents may not account for multiple topics within a quote, and would be taxing to shuffle around quotes. 

The index file begins with a quick introduction to Quick-Building in LaTeX since the compiling process would include making a latex index file. Consider placing this file into its own folder for your own notes since the associated files can add a lot of clutter to say /documents. The index file includes hyperlinks on the page number to jump to a section where the quote is (or whatever you're indexing). 

After compiling, consider opening these index files that are made in Notepad or Notepad++, this should provide some intution on how LaTeX adds seperate files to generate an index, and how these indexes can be formatted for more advanced or organized indices. 

# R From .rnw
What if we need to add code neatly to our LaTeX documentation? I would consider building programming language not in TeXMaker but in (in the case of R) R's "sweave" document. This will build a .rnw (meaning R "no web") document which looks very similar to LaTeX! Change you R setting to change from "sweave" to "knitr" and launch a new .rnw to begin using the .rnw just like you would LaTeX. This makes adding code easy and ensures reproducability. 

If you're interested, I've included how these R sections are formatted in a LaTeX output which is ran to give you the .pdf (this is all done under the hood in R from .rnw ("sweave")). These files are a great way to present code in an organized way for readers to clearly sepearate code from text. These are also great for doing quantiative homework assignments or reports more broadly. 