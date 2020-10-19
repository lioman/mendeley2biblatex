=================
Mendeley2Biblatex
=================

**This package is not maintained any more.**

This package converts a mendeley database to a biblatex file

It is based on a `script <https://github.com/fbianco/mendeley2bibtex>`_ written by François Bianco, University of Geneva

Installation
------------
    pip install mendeley2biblatex

Usage
-----

First locate your database. On Linux systems it is:

    ls ~/.local/share/data/Mendeley\ Ltd./Mendeley\Desktop/your@email.com@www.mendeley.com.sqlite

The package only reads your database, but to avoid any loss it is **recommended** to  work on a copy of your database

Then run mendeley2biblatex on your file with

    mendeley2bibtex -o mendeley.bib mendeley.sqlite

To see all options use
    mendeley2biblatex -h
