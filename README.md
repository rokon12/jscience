# jscience
An update and re-mavenization of jscience.

While a great project, JScience has not been maintained in many years and was built against very old versions
of the geoapi and javolution.  This version of geoapi conflicts with newer versions and the similar API provided
by geotools.  To make it harder to use, the version of JScience on maven central was built with the dependencies
included.

In this update used the source from jscience.org and the pom file from maven central as
a starting point.  In it, the version of Javolution was updated and the gt-opengeo was used in place of geoapi.
The pom was updated to use the newer versions of maven plugin and build a jar which does not contain dependencies.

Ryan
