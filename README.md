# LaTeX-Template for Bachelor- and Masterthesis at Mannheim Technical University of Applied Sciences
 
## General Notes
* __This template is just a sample!__ Please adapt it to the requirements of your scientific advisor (i.e. adapt citation style, page margins etc.)
* __Always use the latest version of this template!__
* The template is written for a thesis in German, but can be adapted easily to other languages.
* **Using this template requires basic knowledge of LaTeX! Please get used to it *before* you start writing!**


## Installation Instructions

### Prerequisites

First, you'll need a working LaTeX installation or Online-Plattform. Please find one to suit your needs, e.g.: 

* Online-Platform: [Overleaf](https://www.overleaf.com)
* Windows-User: [MikTex](http://www.miktex.org)
* Mac-User: [MacTex](http://www.tug.org/mactex/index.html)
* Linux-User: [TexLive](http://www.tug.org/texlive/) (included in most Linux distributions)

Next, you'll need a LaTeX Editor you're comfortable with (Overleaf-Users can skip this section since the editor is already included in Overleaf). Any text editor (e.g. vi/vim, emacs, atom, sublime etc.) will do the job. Here are two specialized LaTeX editors tested with the template:

* [TexStudio](http://www.texstudio.org) (Platform-Independent)
* [TexShop](http://pages.uoregon.edu/koch/texshop/) (Mac only)

### Template Installation

Clone/download the template to your machine and unpack it to a directory of your choice (in case of zip-Download).
The template itself is pure LaTeX with only four template-specific commands which are _not_ LaTeX-Standard [(see below)](#markdown-header-template-specific-commands).
The template files are commented quite well and it also includes an instruction chapter which explains the basic usage of the template (actually, the instruction chapter is in German).
Citation examples are included in the `bibliography.bib`-File (Article, Book, Online Reference).

**Important:** Instead of BibTeX, the template uses the newer BibLaTeX/Biber combination. Please adjust your environment accordingly when you get strange errors referring to the bibliography, since most editors default to BibTeX.

## Explanation of the template
The file `master.tex` is the TeX root file which can be compiled directly. All other `.tex`-Files are incuded from here. Read the comments in the file carefully, since you'll likely
need some modifications here (e.g. for disabling unused stuff like the *List of Algorithms* etc.).

The file `config.tex` includes relevant
packages and does some configuration stuff. Nearly every property or characteristic can be configured/modified here, beginning from page layout, header and footer, citaion style etc.). *Please also read the comments in the file catefully and - if needed - read the package documentations at [CTAN](http://www.ctan.org)!*

## template-specific commands
- `\ThesisTitle{Max Mustermann}` sets the Author to *Max Mustermann*,
- `\ThesisAuthor{Ein Testtitel}` sets the Title to *Ein Testtiitel*

Titlepage, abstract and statutory declaration will be filled with these information
.
