# GreekPresentations
Make Greek presentations with pandoc + markdown + beamer/latex


# Steps
the command:
pandoc -t beamer source.md  -o pres.pdf --pdf-engine=xelatex -V mainfont="Noto Sans:style=Bold Italic"

The font (Noto Sans:style=Bold Italic in this case) needs to support the language. To find fonts that support Greek use the following command:
fc-list :lang=el
