CBF - Community Build Framework
===============================



About
-----


Focused on a multi-project/ multi-environment scenario, the Community Build
Framework (CBF) is the way to setup and deploy Pentaho based applications.


If you work in several projects at the same time, or have to switch among
several environments (production, development, etc.), or need to customize the
Pentaho server (using different databases, changing the L&F, applying different
security types, etc.), CBF is the right tool for you.


CBF is an ant build file (build.xml). Check more extended documentation in
http://cbf.webdetails.org


Features
--------

 Focused on a multi-project/ multi-environment scenario, here are the main characteristics:

* Ability to switch from totally different projects on the fly
* Supports multiple environments (eg: development, production, worker1, worker2...)
* No changes to the original files that could get overwritten in a upgrade
* Supports multiple platform versions
* Simplifies version upgrades
* Debug-friendly
* VCS (Version Control System)-friendly
* Supports all kind of different customization in different projects, from using different databases to different security types
* Supports patches to the source code for fine-grain customization
* Supports deploy to local/remote machines
* OS independent


Requirements
------------

We will need:
* A shell (if on windows, cygwin or equivalent is required)
* Clean directory to host your CBF installation
* Jdk 1.6
* Ant 1.7
* Tomcat 6.0.x (for pentaho 3.7 or before, tomcat 5.5 is required)
* Svn client
* RSync / ssh to do remote deploy

License
-------

CBF is licensed under the [MPLv2](http://www.mozilla.org/MPL/2.0/) license.
