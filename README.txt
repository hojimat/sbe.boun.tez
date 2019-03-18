Hi! This is a Thesis template for SBE Bogazici University (Sosyal Bilimler Enstitusu). This is how you do your design:

0) If it ain't broken, don't fix it!

1) In main.tex you DO NOT touch anything EXCEPT for areas surrounded by "EDITABLE AREA" tags.

2) Any new settings/libraries/packages are written in "thesettings.sty", NOT in "main.tex"

3) In "pres" folder you DO NOT touch:
    -title.tex
    -declaration.tex
    -approval.tex
    -bibliography.tex

4) In "pres" folder you DO edit:
    -abstract.tex (english and turkish version of abstract)
    -acknowledgement.tex (whatever you want)
    -references.bib (you follow the syntax as in examples provided)

5) In "figs" folder you SAVE figures. Then you reference them in text as "figs/figurename.jpg"

6) All of your EDITING is done in "chaps/" and "apps/" folders, NOT in "main.tex"! But COMPILING THE LaTeX is done in "main.tex"

7) In "chaps" and "apps" folders you open as much new files as you want. The syntax is "chap1.tex", "chap2.tex", "chap3.tex" etc. for chapters and "appa.tex", "appb.tex", "appc.tex", "appd.tex", "appe.tex" etc.

8) Whenever you add a new chapter or appendix, you must remove "%" sign from main.tex's chapter/appendix list ("%\include{chaps/chap2.tex"). When you remove "%" the chapter will be deactivated, when you put "%" back it will be reactivated.

9) The references within text are done using command "\textcite{codename}" where "codename" is the label you gave in "/pres/references.bib". Usually, it's in format "\textcite{einstein91}", but you can change the codename as you wish.


9a) "\textcite" cites like "Author (1999)"
9b) "\parencite" cites like "(Author, 1999)"
9c) "\cite" cites like "[1]"

9d) If there are 3 or more author, the first citation will be "Author1, Author2, and Author3 (1999)", and the next time it will automatically cite "Author1 et al. (1999)"

So, DON'T try to modify it!


Good luck!
Ravshan S.K.

For questions:
rsk@ravshansk.com
