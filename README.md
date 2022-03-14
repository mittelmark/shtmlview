## shtmlview

The shtmlview package provides a pure Tcl/Tk widget to display basic HTML and
Markdown files. The package requires a installation of the tcllib packages
*snit* and optional *Markdown* if Markdown files should be displayed.
To support as well jpeg files the Tcl library *tkimg* should be installed.

* [Manual](http://htmlpreview.github.io/?https://github.com/mittelmark/DGTcl/blob/master/lib/shtmlview/shtmlview.html) - 
* [Download](https://downgit.github.io/#/home?url=https://github.com/mittelmark/shtmlview/tree/master/shtmlview).

The file `shtmlview.tcl` can be used not only as Tcl package but as well as a
standalone application to view Markdown and HTML files directly. Here an usage
line to display an HTML file.

```
tclsh shtmlview.tcl filename.html
```
Here an image where the standalone application is used to browse the Tcl/Tk documentation:

![Tcl manual tkcmd](img/shtmlview-tkcmd.png)

To see for more options execute `tclsh shtmlview.tcl --help` in your terminal.

