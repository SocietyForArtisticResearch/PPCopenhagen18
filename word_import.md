---
title: "Import of external formats in graphical editor"
author: Casper Schipper & Luc Döbereiner
date: December 13, 2018
transition: fade
---

# Current

* Copy/paste directly from Word
   	
# Challenges

* images are not copied with the text
* alignment issues with tall text tools
* styling breaks
* fonts are copied, are visible to author, but cause trouble with other users (!)
* footnotes are imported, but not as RC footnotes, hyperlinks do not work 

# Current remedies

* split everything by hand
* use only plain text
* use separate tools for each section [text-tool help](https://guide.researchcatalogue.net#text-tool)

# Goal

* automatically translating the word doc into graphical editor slices
* enable rethinking the material in the new graphic & non-linear context
* get clean HTML in flexible slices

# Solution

* in Simple Media, a Word / Odt file can be uploaded, which is converted to HTML, text & picture tools.
* text is subdivided into __separate__ tools (based on the position of images in the text, as well as headers)
* all tools are numbered in the order of their occurrence in the original 
* footnotes of the original document are also converted to RC-Auto-Footnotes. 