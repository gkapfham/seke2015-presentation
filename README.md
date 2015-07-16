# seke2015-presentation

This repository contains the LaTeX source code and additional resources for a presentation that I, [Gregory M.
Kapfhammer](http://www.cs.allegheny.edu/sites/gkapfham), helped to develop and [Cody
Kinneer](https://github.com/kinneerc) gave at the 27th International Conference on Software Engineering and Knowledge
Engineering (SEKE 2015).  The presentation's source code uses a wide variety of LaTeX packages, such as `beamer` and
`pgftikz`, in order to create each slide.  I have developed a custom theme for the display of the slides and the use of
progressive revealing of technical diagrams.

You are welcome to use these slides as inspiration for your own presentation. If you find this example useful, could I
trouble you to star this repository and then acknowledge it in your own presentation slides? If you would like to learn
more about my research program, then you can checkout my
[gkapfham/research-bibliography](https://github.com/gkapfham/research-bibliography).

You can type the following command if you want to clone this repository:

```shell
git clone https://github.com/gkapfham/seke2015-presentation.git
```

Then, if you want to compile the presentation to a PDF, you should type the following commands.

```shell
cd seke2015-presentation
pdflatex kinneer_seke.tex
pdflatex kinneer_seke.tex
```

Please note that this has been tested on an Ubuntu 15.04 workstation running a very recent version of LaTeX that was
manually installed using the TeXLive installer. It is worth noting that you can also compile the paper using other LaTeX
development tools, such as `latexmk`. Additionally, you may find that the placement of certain `pgftikz` diagrams
requires manual adjustment depending on your LaTeX development environment and other settings. If you are unable to
compile the presentation with your development tools and your execution environment, then please open a new issue and I
will attempt to resolve your concerns.


