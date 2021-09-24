# lingvo
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5165145.svg)](https://doi.org/10.5281/zenodo.5165145)

**Dictionaries for (Old) Church Slavonic, Old Russian, Slavonic linguistics, Danish, German, Yiddish and Tigrinya.**

**For use in [ABBYY Lingvo](https://abbyy.store/lingvo-6-multi/) (commercial), [GoldenDict](http://goldendict.org/) (free)** and in a number of mobile dictionary apps.

Find more information on the individual dictionaries in the corrsponding TXT-files.

Before installing the dictionaries, make sure that the individual .DSL files are UTF-16LE (BOM) encoded (and not UTF-8). You can change this manually with any good text editor.
Consider using the file [`lingvo-dictionaries_UTF16LE-BOM.zip` from Zenodo](https://doi.org/10.5281/zenodo.5165145), where the individual files are encoded correctly.

## Old Cyrillic font
In order to use the Old Cyrillic font "[Monomakh](https://sci.ponomar.net/fonts.html#fonts-for-academic-work)" within articles, the search box and the wordlist on dictionaries with the language "Church Slavic", copy following attached files:

`_FONT_CONFIG_old_cyrillic/article-style.css`

`_FONT_CONFIG_old_cyrillic/qt-style.css`

into the GoldenDict folder:

Linux:		`~/.goldendict`

Windows:	`%APPDATA%\GoldenDict`

The Old Cyrillic font "Monomakh" will be retrieved from the internet, so there is no font installation necessary.

If you need the font also outside of GoldenDict, you need to work offline or in case of problems, [install the font locally](https://sci.ponomar.net/fonts.html#fonts-for-academic-work) (Monomakh Unicode font).

## Other dictionary sources
[Download similar Lingvo dictionaries here](http://lingvodics.com/dics/view/Church-Slavic)

## Issues
2021-09-24 ― `qt-style.css` seems not to work on every Linux installation (Ubuntu 18.04)


