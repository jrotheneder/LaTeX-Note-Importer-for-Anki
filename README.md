# LaTeX Note Importer for Anki
Add-on for the memory training program [Anki](https://apps.ankiweb.net/), allowing to import flash cards typed in LaTeX into Anki's database.
Usage instructions are available on a dedicated [GitHub page](https://tentativeconvert.github.io/LaTeX-Note-Importer-for-Anki/).  The project's [AnkiWeb page](https://ankiweb.net/shared/info/1199027445) features the add-on's unique identifier as well as ratings and reviews.


This fork differs from the original project in two points: 
* Html can code can be put into plain fields and used to generated clickable
   hyperlinks in Anki cards using the usual `<a href="url"> Link title </a>`
   syntax. This is useful for adding sources, further material etc. to cards.
* There is a new field type, `clozefield`, which can be used to generate [cloze
  cards](https://docs.ankiweb.net/editing.html#cloze-deletion)  from LaTeX
  source code. See `docs/cloze_examples.tex` for details and examples.  
