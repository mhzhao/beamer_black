# beamer_black

For some reason, the clock font size shows not reasonable when compiling by xelatex, it's ok to use lualatex to compile
TO show the time, open the slides using adobe acrobat reader, or other reader support javascript
Add section & page indicator on the top of the page, for the pages only give the info of current section 


Newest fixing
Fixed indicator spacing problem, but the maxium section supporting is 10 for indicator.
To show the indicator correctly, one need compile three times!!! 
pdflatex & lualatex compiling can give the correct time showing, but not xelatex
If interruptted during the compiling, fix your problem, then compile twice to show the progress indicator, if not work, try three times
