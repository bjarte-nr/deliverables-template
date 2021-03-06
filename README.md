
#H2020 Deliverable LaTeX Template (specialized for the [PriMa project](https://www.prima-itn.eu/))

This template was adapted from SINet template
[](https://github.com/PalmaITEM/deliverables-template), 
which again was adapted from the netCommons project template [](http://www.netcommons.eu).

## Usage

The file **main.tex** should be your master document, where you can include/remove chapters in your document.

You should also edit the file **title.tex** for defining deliverable specific options. In particular:

1. the deliverable title (`\newcommand{\DelTitle}{Title of this deliverable}`)
2. the deliverable number  (`\newcommand{\DelNumber}{DX.X (DYY)}`)
3. and, optionally, a deliverable version (`\newcommand{\DelVersion}{0.X/1.0}`)

Note: The number in parenthesis after the deliverable number, `(DYY)`, is a running number and may be found [here](https://sharepoint.utwente.nl/Project/PriMa/_layouts/15/start.aspx#/Lists/Deliverables/AllItems.aspx).

## Issues

The template has some problematic issues -- help apreciated!

* The footer is supposed to have a some lines of text to the left of the logo
* The Chapter titles lack space between the number and the text, e.g., "1.Introduction". (This seems to be a side-effect of the package "sectsty" that is used to get color in headings.)



## License

Distributed under a Creative Commons license. See ``LICENSE`` for more information.
