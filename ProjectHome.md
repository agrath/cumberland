<br>

<b>Note:</b> A developer moved Cumberland to GitHub and added improvements.  <a href='https://github.com/zippy1981/cumberland'>Check it out!</a>

<br><br>

<hr />

Cumberland is a mapping framework for .Net.  It also includes a set of mapping tools that may be useful for people besides .NET developers.<br>
<br>
<hr />

<img src='http://cumberland.googlecode.com/files/9.png' align='right' />

<h1>News</h1>

<ul><li>July 28, 2009 - <a href='http://groups.google.com/group/cumberland-users/browse_thread/thread/ffdd20cfdd484db0'>0.4.2 released!</a>
</li><li>Mar. 5, 2009 - 0.4.1 released to fix issue <a href='http://code.google.com/p/cumberland/issues/detail?id=8&can=1'>#8</a>
</li><li>Feb. 28, 2009 - 0.4 has been released (<a href='http://code.google.com/p/cumberland/wiki/ReleaseNotes_For_0_4'>notes</a>)<br>
</li><li>Feb. 10, 2009 - I created a <a href='http://groups.google.com/group/cumberland-users'>google group</a> if you have questions, ideas, etc.<br>
</li><li>Feb. 6, 2009 - I have <a href='http://www.salmonsalvo.net/blog/?p=199'>blogged</a> about simple map creation with xml schema and Visual Studio.<br>
</li><li>January 22, 2009 - Cumberland 0.3 is released!  Read the <a href='ReleaseNotes_For_0_3.md'>release notes</a> for details on what's new.<br>
</li><li>December 9, 2008 - Cumberland 0.2 released!  New in this release are significant improvements to symbology, including labelling.  Support for creating tiles for TMS (OpenLayers) and Microsoft VirtualEarth.  And export to Keyhole Markup Language (kml) functionality.</li></ul>

<h1>Features</h1>

<ul><li>a geometry/shape API<br>
</li><li>a <a href='mapXmlFormat.md'>map xml format</a> and serialization API<br>
</li><li>a map rendering engine<br>
</li><li>supports the following data sources:<br>
<ul><li>Shapefiles (include reading .DBFs)<br>
</li><li>PostGIS<br>
</li><li>SQL Server 2008<br>
</li></ul></li><li>a pluggable architecture for adding third-party support for other data sources<br>
</li><li><a href='CoordinateSystems.md'>coordinate system transformation / Projection</a> (via <a href='http://proj.maptools.org/'>Proj.4</a>)<br>
</li><li><a href='BasicSymbology.md'>basic symbology</a>, including labelling and thematic mapping<br>
</li><li>a <a href='TileProviderWithAspNet.md'>tile provider class</a> for generating tiles for popular web mapping applications:<br>
<ul><li>Google Maps<br>
</li><li>VirtualEarth<br>
</li><li>Tile Map Service (TMS) - for use in OpenLayers<br>
</li></ul></li><li>runs on Windows, Linux, and Mac OSX.<br>
</li><li>export map to KML API<br>
</li><li>OGC Standards<br>
<ul><li>subset WellKnownText (WKT) parser/writer<br>
</li><li>subset WellKnownBinary (WKB) parser</li></ul></li></ul>

<blockquote><h2>Tools</h2></blockquote>

<ul><li><a href='shp2sqlserver.md'>shp2sqlserver</a> - loads a Shapefile into SQL Server 2008<br>
</li><li><a href='drawmap.md'>drawmap</a> - draws a map to an image<br>
</li><li><a href='tilepyramider.md'>tilepyramider</a> - generates a set of tiles for use in the aforementioned web mapping applications<br>
<ul><li><a href='http://www.salmonsalvo.net/Cumberland:GoogleMapsTest'>Google Maps demo</a>
</li><li><a href='http://salmonsalvo.net/Cumberland:_OpenLayers_Test'>OpenLayers demo</a> (<a href='http://salmonsalvo.net/Cumberland:_BaseMap_Test'>another</a>)<br>
</li><li><a href='http://salmonsalvo.net/Cumberland:_VirtualEarth_Test'>VirtualEarth demo</a>
</li></ul></li><li><a href='map2kml.md'>map2kml</a> - converts a map into a kml document</li></ul>

<h1>Additional Resources</h1>

<ul><li>API Documentation:<br>
<ul><li><a href='http://salmonsalvo.net/cumberland/docs/0.4/Cumberland'>0.4</a>
</li><li>Older: (<a href='http://salmonsalvo.net/cumberland/docs/0.3/Cumberland'>0.3</a>, <a href='http://salmonsalvo.net/cumberland/docs/0.2/Cumberland'>0.2</a>, <a href='http://salmonsalvo.net/cumberland/docs/0.1/Cumberland'>0.1</a>)<br>
</li></ul></li><li><a href='Roadmap.md'>Roadmap</a>
</li><li><a href='CreateASimpleApp.md'>"Create a simple application" tutorial</a>