Resume
=========================

A **one-page / multi-page**, **two asymmetric column** resume template in **LaTeX** that caters to anyone looking to build a **beautiful, professional-looking** Resume / Curriculum Vitae.


Only **OpenFonts** have been used which are free, open-source fonts - *Lato* and *Raleway* (and their various variants).

It is licensed under the Apache License 2.0.

### Motivation

Common LaTeX resume-builders such as [**moderncv**](http://www.latextemplates.com/template/moderncv-cv-and-cover-letter)  and the [**friggeri-cv**](https://github.com/afriggeri/cv) look great if you're looking for a multi-page resume with numerous citations, but usually imperfect for making a thorough, single-page one. A lot of companies today search resumes based on [keywords](http://www.businessinsider.com/most-big-companies-have-a-tracking-system-that-scans-your-resume-for-keywords-2012-1) but at the same time require/prefer a one-page resume, especially for undergraduates. 

This template attempts to **look clean**, highlight **details**, be great even on a **single page**, and allow useful **LaTeX templating**.


### Dependencies

Compiles only with **XeTeX** and required **BibTex** for compiling publications and the .bib filetype.


### Availability

1. OpenFonts version - [as a direct download](https://github.com/deedydas/Deedy-Resume/raw/master/OpenFonts/deedy_resume-openfont.pdf)
2. **Overleaf**.com (formerly **WriteLatex**.com) - [compilable online](https://www.writelatex.com/templates/deedy-resume/sqdbztjjghvz#.U2H9Kq1dV18)

### Changelog
#### v1.2
 1. Added publications in place of societies.
 2. Collapsed a portion of education.
 3. Fixed a bug with alignment of overflowing long last updated dates on the top right. 

#### v1.1
 1. Fixed several compilation bugs with \renewcommand
 2. Got Open-source fonts (Windows/Linux support)
 3. Added Last Updated
 4. Moved Title styling into .sty
 5. Commented .sty file.


### Known Issues:

1. Overflows onto second page if any column's contents are more than the vertical limit
2. Hacky space on the first bullet point on the second column.
3. Hacky redefinition of \refname to omit 'References' text for publications in the MacFonts version.


### Source

Originally written by Debarghya Das [GitHub/Deedy](https://github.com/deedy)

Forked from his template at [Deedy-Resume](https://github.com/deedy/Deedy-Resume)
