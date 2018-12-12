BDML source pack
====

**Main repository:** [BDML Git repository](https://github.com/borasoftware/bdml)

**License:** [AGPL](https://borasoftware.com/licenses/bdml-license.html)

**Documentation:** [BDML](https://borasoftware.com/specifications/bdml.html)

BDML is a feature complete XML based technical writing markup language with
the aim of providing the smallest set of schema elements and the easiest
learning curve.

The BDML source pack contains:
* the bdml.xsd definition;
* the BdmlHtml.xsl XSLT 1.0 transform;
* a set of example CSS stylesheets;
* syntax highlighting Javascript files.

How to use the BDML source pack:
* download a copy of the source pack;
* copy the 'bdml' folder to your source repository inside the documentation folder;
* create a hierarchy of BDML documentation files that reference BdmlHtml.xsl;
* reference the bdml-html.css CSS file / syntax highlighting files and/or your
  own CSS / Javascript in your BDML documentation files;
* view the BDML pages by:
    - directly loading the BDML files in your browser; or
    - creating a build step that transforms the BDML hierarchy into an HTML
      hierarchy via an XSLT 1.0 processor.

If directly loading local BDML files, browser local XSLT file loading will be
need to be enabled. Direct loading is not supported in IE/Edge browsers.


See the [Balau library](https://github.com/borasoftware/balau) for an example
of usage:
  * [AOT Balau documentation](https://borasoftware.com/doc/balau/latest/manual/index.html)
  * [JIT Balau documentation](https://borasoftware.com/doc/balau-bdml/latest/manual/index.bdml)
