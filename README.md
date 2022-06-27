# cornellNotes
A LaTeX package for generating a packet for handwritten notes in the Cornell note taking system. My contributions were moving the code into a reusable package, adding the ability to set the name, date, how many pages to generate, and what page number to begin numbering.

# To use
Download the package and mwe into a directory, compile with PdfLaTex.

Include the package using `\usepackage{cornellNotes}`.

Set the subject line using `\renewcommand{\cornellNotesSubject}{#1}`.

Set the date using `\renewcommand{\cornellNotesDate}{#1}`.

Set the page count start in the optional command `#1` and the number of pages in `#2` using `\cornellNotesPacket\[#1\]{#2}`.

# Shameless plug
For more thorough description including current limitations, please refer to my blog, [jakubkonkol.com](https://jakubkonkol.com/?p=684).

# Acknowledgements
The original template was posted by [sgmoye on stackexchange](https://tex.stackexchange.com/questions/70570/cornell-notes-a-lyx-or-latex-solution-needed).

Doing the repeating bit using [Joseph Wright's answer on stackexchange](https://tex.stackexchange.com/questions/16189/repeat-command-n-times).
