# HVL-Bachelor-latextemplate
Latex template for bachelor thesis at HVL.

## How to use references
The references are stored in the file `references.bib`. To add a reference, simply add a new entry in the file. The entry should have the following format:
```LaTeX
@article{author_year,
  author = {Author, First and Author, Second},
  title = {Title of the article},
  journal = {Journal},
  year = {Year},
  volume = {Volume},
  number = {Number},
  pages = {Pages},
  doi = {DOI},
  url = {URL}
}
```

Simple chrome extension to get a reference from a website: https://chrome.google.com/webstore/detail/bibtex-entry-from-url/mgpmgkhhbjgkpnanlmlhibjfgpdpgjec

To cite the reference in the text, use `\cite{author_year}`. The reference will be automatically added to the bibliography.