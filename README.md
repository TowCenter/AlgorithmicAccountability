.tex file manually created from .pdf

+ added linebreaks (\\) at end of each footnote ref to improve rendering in html & markdown results

generate html w/pandoc:

pandoc PostIndustrialJournalism.tex -o PostIndustrialJournalism.html

Create CMS-ready files:
python CreateRightRail.py PostIndustrialJournalism.html


generate md w/pandoc:

pandoc PostIndustrialJournalism.tex -o PostIndustrialJournalism.md

Generate GitBook files:
python CreateRightRail.py PostIndustrialJournalism.html

OH CHARMS, YOU WORK LIKE THIS!!! :)