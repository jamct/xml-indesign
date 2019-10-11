---
title: Großer Titel
subtitle: Das ist eine Unterüberschrift
magazine_title: InDesign-Beispielheft
category: Technik
edition: 01/2019
author: Klaus Mustermann
editor: kmu
teaser: Dies ist ein n Markdown geschriebener Artikel. Er wird von Pandoc konvertiert und als XML geladen.
lead_image:
  source: placeholder3.jpg
  credits: Ein Fotograf 
images:
  - {source: placeholder2.jpg, caption: "Sie sehen eine Wand, die als Platzhalter dient.", credits: ""}
  - {source: placeholder1.jpg, caption: "Eine weitere Wand, die nur den Platz freihält.", credits: ""}
boxes:
  - {title: "Wichtig zu wissen", content: "Pandoc can convert between numerous markup and word processing formats, including, but not limited to, various flavors of Markdown, HTML, LaTeX and Word docx. For the full lists of input and output formats, see the --from and --to options below. Pandoc can also produce PDF output: see creating a PDF, below.", credits: "" }  
quotes:
  - {content: "Es ist was faul im Staate Dänemark", credits: "Hamlett"}
...
Pandoc understands a number of useful markdown syntax extensions, including document metadata (title, author, date); footnotes; tables; definition lists; superscript and subscript; strikeout; enhanced ordered lists (start number and numbering style are significant); running example lists; delimited code blocks with syntax highlighting; smart quotes, dashes, and ellipses; markdown inside HTML blocks; and inline LaTeX. If strict markdown compatibility is desired, all of these extensions can be turned off.

### Pandoc

LaTeX math (and even macros) can be used in markdown documents. Several different methods of rendering math in HTML are provided, including MathJax and translation to MathML. LaTeX math is converted (as needed by the output format) to unicode, native Word equation objects, MathML, or roff eqn.

Pandoc includes a powerful system for automatic citations and bibliographies, using pandoc-citeproc (which derives from Andrea Rossato’s citeproc-hs). This means that you can write a citation like
Pandoc is a Haskell library for converting from one markup format to another, and a command-line tool that uses this library.

Pandoc can convert between numerous markup and word processing formats, including, but not limited to, various flavors of Markdown, HTML, LaTeX and Word docx. For the full lists of input and output formats, see the --from and --to options below. Pandoc can also produce PDF output: see creating a PDF, below.

Pandoc’s enhanced version of Markdown includes syntax for tables, definition lists, metadata blocks, footnotes, citations, math, and much more. See below under Pandoc’s Markdown.

Pandoc has a modular design: it consists of a set of readers, which parse text in a given format and produce a native representation of the document (an abstract syntax tree or AST), and a set of writers, which convert this native representation into a target format. Thus, adding an input or output format requires only adding a reader or writer. Users can also run custom pandoc filters to modify the intermediate AST.

### Spannende Details

LaTeX math (and even macros) can be used in markdown documents. Several different methods of rendering math in HTML are provided, including MathJax and translation to MathML. LaTeX math is converted (as needed by the output format) to unicode, native Word equation objects, MathML, or roff eqn.

Pandoc includes a powerful system for automatic citations and bibliographies, using pandoc-citeproc (which derives from Andrea Rossato’s citeproc-hs). This means that you can write a citation like

### Noch mehr Details

LaTeX math (and even macros) can be used in markdown documents. Several different methods of rendering math in HTML are provided, including MathJax and translation to MathML. LaTeX math is converted (as needed by the output format) to unicode, native Word equation objects, MathML, or roff eqn.

Pandoc includes a powerful system for automatic citations and bibliographies, using pandoc-citeproc (which derives from Andrea Rossato’s citeproc-hs). This means that you can write a citation like
