# webtech-markdown

This project is a homework for the Web Technolgies course at DE PTI.

## Dependencies

* make
* [texlive](https://www.tug.org/texlive/) or [miktex](https://miktex.org/)
* [pandoc](https://pandoc.org/)

## Build

### HTML

It should run if you have all the deps.
If you use miktex, there's a possibility that you'll be prompted to install some packages (by miktex), like table handling etc.

### PDF

Pdf generation relies on a local pdf generator. I used miktex and didn't bother with setting up PATH etc.
Please modify the makefile according to your config (Modify the **PDF_ENG** according to your setup).