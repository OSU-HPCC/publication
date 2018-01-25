# HPCC Publications
A series of scripts that generates a list of publications for the HPCC website.

## Requirements
- Linux environment that runs `make`.
- Working Python 3 distribution installed in `/usr/bin/python3`
- Working Bash installation installed in `/bin/bash`
- Optional: If the user wants the final list in a `.docx` format instead of a markdown format, they need to have Pandoc installed.

> For a non-standard installation of the above software, the user will need to update the script shebangs.

## Usage
1. To add new publications to the list open `articles.csv` in your favorite spreadsheet program and add a new row with the appropriate entries.
2. Save the changes (make sure you overwrite `articles.csv` and maintain the csv format.
3. Type `make pubs` into the command line.
4. Hit enter.
5. The scripts will create a (optionally two) new file called `pubs.md` (optionally `pubs.docx`) with the formatted list of publication arranged both alphabetically and by year.
