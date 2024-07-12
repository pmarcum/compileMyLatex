# compileMyLatex
Automatically compiles .tex files in the repository when a change in the files is detected.

If you use BibMan as your reference manager, then BibMan will install compileMyLatex into your designated repository automatically.  To manually install compileMyLatex in your repository without using BibMan, go to your github repository, click on "Actions" in the top menu, then "set up a workflow yourself", then copy/paste the contents of the compileMyLatex.yml script into the editor (will get a default title of "main.yml", which you can change to "compileMyLatex").  After copy/pasting, hit "commit changes", and the workflow will be ready to execute as soon as a change to a .tex or .bib file in your repository is detected. 

UPDATES

* v07122014  07/12/2024
  - first commit
