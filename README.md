## shtmlview

### Description

The shtmlview package provides a pure Tcl/Tk widget to display basic HTML and
Markdown files. The package requires an installation of the tcllib packages
*snit* and, optional, *Markdown* if Markdown files should be displayed. To
support as well jpeg files the Tcl library *tkimg* should be installed. This
widget is not a web browser it will not work with http(s) addresses and only
relative filenames for images and links should be used. The widget supports as
well base64 encoded images embedded directly into HTML pages.

* [Manual](http://htmlpreview.github.io/?https://github.com/mittelmark/shtmlview/blob/master/shtmlview/shtmlview.html)
* [Download](https://downgit.github.io/#/home?url=https://github.com/mittelmark/shtmlview/tree/main/shtmlview)

### Standalone Application

The file `shtmlview.tcl` can be used not only as Tcl package but as well as a
standalone application to view Markdown and HTML files directly. Here an usage
line to display an HTML file.

```
tclsh shtmlview.tcl filename.html
```
Here an image where the standalone application is used to browse the Tcl/Tk documentation:

![Tcl manual tkcmd](img/shtmlview-tkcmd.png)

To see for more options execute `tclsh shtmlview.tcl --help` in your terminal.

### See also

* [Wikipage on Tclers Wiki](https://wiki.tcl-lang.org/page/shtmlview)
* [tkhtml(1)](https://github.com/wjoye/tkhtml1)
* [tkhtml3](http://tkhtml.tcl.tk/index.html)

### TODO's

* [x] svg file and inline data support using svgconvert [https://github.com/mittelmark/svgconvert/](https://github.com/mittelmark/svgconvert/) !
* [x] more investigations into the existing css functionality, keept it or throw it a away  (thrown away, we should keep it minimal)
* [ ] removal of forms part (thrown away - no chance to implement a web browser)
* [ ] edit/view button to switch between view and edit mode to directly edit and save for instance a Markdown document
* [ ] help megawidget with TOC and index search such as dgHelpBrowser
