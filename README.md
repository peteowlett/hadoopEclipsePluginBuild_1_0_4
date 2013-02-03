hadoopEclipsePluginBuild_1_0_4
==============================

An updated build.xml and manifest files to build a working eclipse plugin for hadoop.

I built this because the current build.xml and manifest distributed with Hadoop 1.0.4 source fails to include some mandatory library references. This JAR should work, but you best bet is to look at the delta between these files and the sources from Apache, then build to your local version (Hadoop is highly version dependent).

Good luck

Pete Owlett
Feb 2013
