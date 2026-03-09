# My Resume

**Archiving repo due to Latex and Github Actions issues. Latest resume is at overleaf.com .**

Built in Latex based on template [Jake's Resume](https://github.com/jakegut/resume).

## Usage
**BUG**: Github Action isn't working.

Github Action is setup to generate PDF from Latex - simply change the Latex code and then push to Github. PDF generation workflow will run automatically. Once it's done, go to Artifacts section of the Github Action to download the generated PDF.

**NOTE:** Github Actions workflow is setup so that PDF generation action will only run if *software_engineer.tex* Latex source code changes.

Alternatively, install locally on Debian-based linux distros:

- `sudo apt install texlive texlive-latex-extra texlive-fonts-recommended texlive-fonts-extra texlive-science texlive-plain-generic tex4ht latex2html texlive-full`
- *Optional*: Install Latex visual editor: `sudo apt install -y texlive-xetex`
- Convert to pdf: `pdflatex software_engineer.tex`
- *Optional* Convert to HTML: `hlatex software_engineer.tex`

