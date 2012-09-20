jQuery for Maven
=============
[![Build Status](https://secure.travis-ci.org/efsavage/jQuery-Maven.png?branch=master)](http://travis-ci.org/efsavage/jQuery-Maven)

This library gives you a way to drop [jQuery](http://jquery.com) into your project as a [Maven](maven.apache.org) dependency, which means you don't have to include these third party files in your own source control.

pom.xml
-------

Add this to the <dependencies> element of your pom.xml

		<dependency>
			<groupId>com.efsavage</groupId>
			<artifactId>jquery</artifactId>
			<version>1.8.1</version>
		</dependency>

Usage
-------
The file will "mount" itself at the following URL:

* /ext/jquery/js/jquery.js

Requirements
-------
This requires a Servlet 3.0 container, such as Jetty 8.

Minified vs. Full Versions
-------
The minified versions of the .js file is used by default, append ?min=false to see the full version.

Modifications
-------
The files served have not been modified in any way from their original distribution.

Other "Mavenized" Projects
-------
* [Bootstrap for Maven](https://github.com/efsavage/Bootstrap-Maven)
* [Backbone.js for Maven](https://github.com/efsavage/Backbone-Maven)

Changelog
-------
Note: See the [release notes](http://blog.jquery.com/2012/08/09/jquery-1-8-released/) for information about changes to the jQuery files themselves.

##1.8.1
* Updated to jQuery 1.8.1

##1.8.0
* Updated to jQuery 1.8.0

##1.7.2.1
* Moved files under /ext/jquery parent directory.

##1.7.2
* Updated to jQuery 1.7.2

