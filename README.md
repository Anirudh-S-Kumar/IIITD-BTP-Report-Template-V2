# IIIT BTP Report Template V2
This is a $\LaTeX$ template for BTP reports at IIIT Delhi. This is a overhaul of the template given on the [BTP page](https://www.iiitd.ac.in/academics/btech/btp) of IIIT Delhi website. A lot of inspiration has been taken from [this](https://github.com/apoorvkh/cvpr-latex-template) CVPR template.

## Usage
- Create a new repository using this template.
- Add relevant details about the project in `metadata.tex`, like title, authors, advisor, etc.
- Lipsum text is used in the template, replace it with your own text.
- Abstract, Acknowledgements, etc. can be edited in `front` folder.
- Chapters can be added in `chapters` folder.
- Figures can be added in `figures` folder.
- Bibliography can be added in `ref.bib` file.
- Styles can be edited in `reportSty.sty` folder, particular areas of interest are marked with comments.

## Compilation
- The simplest way to compile the report is to use [Overleaf](https://www.overleaf.com/).
- If you want to compile locally, you can use `latexmk` or `pdflatex` to compile `main.tex` file.
