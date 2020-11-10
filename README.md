## What is this?
This is a template for thesis papers in LaTeX in the format required
by my (former) school. All references to myself or my school have
been removed and it's possible to build papers from this template
that leave such information out (called "public builds").

This was implemented to preserve my privacy and to allow future users
of this template to publish their papers without compromising their
privacy.

## How do I use this?
1. __Prerequisites__

  - a good TeX/LaTeX editor (TeXstudio is recommended)
  - TeX Live (or something similar) with some extensions; On Debian:
    - texlive
    - texlive-bibtex-extra
    - texlive-lang-german
    - texlive-xetex

2. __Setup__

In TeXstudio go to "Options > Configure TeXstudio", then "Build" and
select "XeLaTeX" in the "Default Compiler" dropdown. Select "Biber"
in the "Default Bibliography Tool" dropdown.

Click on "Commands". If the "XeLaTeX", "BibTeX" or "Biber" entries
have "&lt;unknown&gt;" in their text boxes, click "Restore Default" next to
them. Exit the options window.

In the menu bar click on "Bibliography" and select "BibLaTeX" in the
"Type: ..." entry.

3. __Gitignored Files__

Copy the file `sample-private.tex` to a file called `private.tex` and
fill in the real values.

Copy the `school-header.png` and `summary.pdf` files you should have
recieved from your instructor into this folder. If you have not
recieved these files, contact your instructor or the author of this
template.

4. __Write! Write! Write!__

You can now start writing your paper in the `thesis-paper.tex` file.
There's already a sample chapter where you're supposed to add your
content. Remove it if you want to. If your paper is very long you
might want to split it into multiple files that you then `\include`
in the main file.

LaTeX can be fiddly at first and the template can be a bit
overwhelming. Don't be afraid to change it though: The template isn't
"elegant", it's just a bunch of hacks. Feel free to pile your own on
top. Google a lot!

If you have questions that you weren't able to answer using internet
research, reach out to your instructor or the author of the template.

Note that you have to build the paper twice in order for the table of
contents to update unless you use the `build` script.

## Links
If you're reading this from somewhere else: The Git repository for
this template is hosted at https://github.com/T0astBread/thesis-paper-template.

An application of this template can be found at https://github.com/T0astBread/thesis.
