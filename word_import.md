---
title: "Import of external formats in graphical editor"
author: Casper Schipper & Luc Döbereiner
date: December 13, 2018
transition: fade
---

# Current

* Copy/paste directly from Word
   	
# Challenges

* Images are not copied with the text
* Alignment issues with tall text tools
* Styling breaks
* Fonts are copied, are visible to author, but cause trouble with other users (!)
* Footnotes are imported, but not as RC footnotes, hyperlinks do not work 

# Current remedies

* Split everything by hand
* Use only plain text
* Use separate tools for each section [text-tool help](https://guide.researchcatalogue.net#text-tool)

# Goal

* Automatically translating the word doc into graphical editor slices
* Enable rethinking the material in the new graphic & non-linear context
* Get clean HTML in flexible slices

# Solution

* In Simple Media, a Word / Odt file can be uploaded, which is converted to HTML, text & picture tools
* Text is subdivided into __separate__ tools (based on the position of images in the text, as well as headers)
* All tools are numbered in the order of their occurrence in the original 
* Footnotes of the original document are also converted to RC-Auto-Footnotes. 
