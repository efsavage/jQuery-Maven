Bootstrap for Maven
=============

This library gives you a way to drop [jQuery](http://jquery.com) into your project as a [Maven](maven.apache.org) dependency, which mens you don't have to include these third party files in your own source control.

pom.xml
-------

Add this to the <dependencies> element of your pom.xml

		<dependency>
			<groupId>com.efsavage</groupId>
			<artifactId>jquery</artifactId>
			<version>1.7.2</version>
		</dependency>

Usage
-------
The file will "mount" itself at the following URL:

* /ext/js/jquery.js

Requirements
-------

This requires a Servlet 3.0 container, such as Jetty 8.

Minified vs. Full Versions
-------

The minified versions of the .js file is used by default, append ?min=false to see the full version.

Modifications
-------

The files served have not been modified in any way from their original distribution.