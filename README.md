This is my university lab report template from back in 2015.

I'm using this as a basis of future Automated reporting and as such I've updated to be more relevent

# Features of Template
- Title Page
- Table of contents
- Sections and subsections
- Figures/Images
- Equations
   - Single Line
   - Multi line
   - with and without labels
- Bullet point List
- Tables
- Code Block
- Text highlighting
- Referencing/component labels
   - Sections
   - Figures
   - Equations
   - References/Bibliography
- Appendices (sections labeled as letters rather than integers)

# Files
template.tex - The template itself
template.pdf - The output from the template
Bibliography.bib - The Sample Bibliography
mcode.sty - MATLAB code style package
plainnat.bst - natbib Bibliography style

# Opening
I'm now a VSCode Convert, and as such I use VSCode along with the following extensions to compile.
- Latex Workshop

For those interested, it is nice to know that LaTeX Workshop supports docker containers for running latex.

# Running
on pop-os, I needed to install tex via https://tug.org/texlive/quickinstall.html as the packages were not included in the apt install, and the recommendation from TexLive was to not use the apt version due to latex packages being installed in "user mode". Note by default this installs a "full" installation. I didn't investigate how to limit the amount of packages to minimal or recommended.

I also needed to add `/usr/local/texlive/2024/bin/x86_64-linux/` to /etc/environment (could have used bashrc).