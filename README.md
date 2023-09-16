# Biblio

This repository contains the continuously updated BibTeX file for my research projects.

## Description

The `library.bib` file in this repository is exported and updated automatically using the Better BibTeX plugin for the Zotero reference manager. 

Every time I add a new citation to my Zotero library, the change will be reflected here, ensuring the most recent version of my bibliography is always available for my projects.

## Usage

To use this bibliography in your markdown project, use the pandoc command with `--bibliography` option pointing to the `library.bib` file:

```shell
pandoc yourfile.md --bibliography=/path_to_your_bibtex_file/library.bib --citeproc -o output.pdf
```
