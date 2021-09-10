# Thesis Template for Bachelor's and Master's Theses at the QU Lab

This thesis template provides one possible structure on how to create a thesis at the Quality and Usability Lab.
Additionally, the documents includes useful information on how to structure, write, do references, etc.

## How to use it

### Overleaf

For the usage in Overleaf, download the repository first by clicking on <kbd>Code</kbd> and then <kbd>Download ZIP</kbd>

Then, on the overleaf website click on <kbd>New Project</kbd>, <kbd>Upload Project</kbd> and then select the zip archive.

### Using it locally

First, download or clone the repository. With latex installed, run

```
pdflatex main; bibtex main; pdflatex main; pdflatex main
```

This builds your document, including references and bibtex citations. The newly created document is called `main.pdf` and is located in the root folder.
