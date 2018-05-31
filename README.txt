Hi! This is a Thesis template for SBE Bogazici University (Sosyal Bilimler Enstitusu). This is how you do your design:


1) In main.tex you DO NOT touch anything EXCEPT for area surrounded by "EDITABLE AREA" tags.

2) In "pres" folder you DO NOT touch:
    -title.tex
    -declaration.tex
    -approval.tex

3) In "pres" folder you DO edit:
    -abstract.tex (english and turkish version of abstract)
    -acknowledgement.tex (whatever you want)
    -bibliography.tex (you follow the syntax as in examples provided)

4) In "figs" folder you SAVE figures. Then you reference them in text as "figs/figurename.jpg"

5) You DO NOT relocate figures! LaTeX automatically locates figures where it does, and you just reference them as "please see Figure XXX" etc.

6) In "chaps" and "apps" folders you open as much new files as you want. The syntax is "chap1.tex", "chap2.tex", "chap3.tex" etc. for chapters and "appa.tex", "appb.tex", "appc.tex", "appd.tex", "appe.tex" etc.

7) ALL OF YOUR EDITING IS DONE IN CHAPS AND APPS FOLDERS !!!! NOT IN "main.tex"!!

8) WHENEVER YOU ADD A NEW CHAPTER OR APPENDIX, you must remove "%" sign from main.tex's chapter/appendix list ("%\include{chaps/chap2.tex"). When you remove "%" the chapter will be deactivated, when you put % back it will be reactivated.

Good luck!
Ravshan S.K.