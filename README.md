# DiMPAH OER: Digital Historical Research on European Historical Newspapers with the NewsEye Platform

Focused on historical newspapers, the richest historical records of their time, this course consists of two parts. First, you will receive knowledge on the challenges and biases in the use and analysis of large collections of digitised historical documents, with contents tailored to both CS and non-CS students. Then, all students will form interdisciplinary groups, for hands-on projects in digital humanities, jointly exploring research questions in teams formed of humanities and computer science students. Students will effectively learn how much they can benefit from each other’s skills, and for instance gain an understanding of the grey areas of search (e.g., due to misrepresented documents), and of the various blackboxes that typically are artificial intelligence methods.

## Usage

### Building the book

If you'd like to develop on and build the DiMPAH IO4 Digital Historical Research on European Historical Newspapers with the NewsEye Platform book, you should:

- Clone this repository and run
- Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
- (Recommended) Remove the existing `dimpah_io4/_build/` directory
- Run `jupyter-book build dimpah_io4/`

A fully-rendered HTML version of the book will be built in `dimpah_io4/_build/html/`.

### Hosting the book

The html version of the book is hosted on the `gh-pages` branch of this repo. A GitHub actions workflow has been created that automatically builds and pushes the book to this branch on a push or pull request to main.

If you wish to disable this automation, you may remove the GitHub actions workflow and build the book manually by:

- Navigating to your local build; and running,
- `ghp-import -n -p -f dimpah_io4/_build/html`

This will automatically push your build to the `gh-pages` branch. More information on this hosting process can be found [here](https://jupyterbook.org/publish/gh-pages.html#manually-host-your-book-with-github-pages).

## Contributors

This repository is maintained as part of the EU Erasmus+ [DiMPAH project](https://lnu.se/en/research/searchresearch/research-projects/project-digital-methods-platform-for-arts-and-humanities/)

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
