June 2, 2013 by Yves Lucet

To produce a thesis WITHOUT index and glossary use ubc_2010_spring_doe_jane.tex
To produce a thesis WITH index and glossary use ubc_2010_spring_doe_jane-index-glossary.tex 

NOTE: The template works with pdflatex NOT with latex. If you use .eps pictures and compile with latex .tex->.dvi->.ps->.pdf the template is currently not compiling i.e. you are on your own.

The followings need separate tools to be setup:
- bibliography: bibtex
- index: makeindex [optional]
- glossary: makeglossaries [optional]
These tools are installed with any LaTeX distribution.

If you use TeXnicCenter, makeindex and bibtex are already setup. makeglossaries is easily added. See instructions at
http://www.latex-community.org/index.php?option=com_content&view=article&id=263%3Aglossaries-nomenclature-lists-of-symbols-and-acronyms&catid=55%3Alatex-general&Itemid=112
There is an ERROR in the instructions:
- use makeglossaries.exe in C:\Program Files\MiKTeX 2.9\miktex\bin\x64
- the option is "%tm" NOT "%bm"

Afterwards it all works!