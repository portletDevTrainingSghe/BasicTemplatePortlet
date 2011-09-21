This project is intended to be a basic template of a portlet that dispatches to a JSP for the view. It is built off the Maven Archetype ID maven-archetype-portlet with Group ID org.apache.maven.archetypes.

My problem with the originating archetype project is that it includes stuff that prevents the project from immediately being built and deployed to a portal. Every time I create a new project based on this archetype I ended up needing to delete some directories and remove some information from the web.xml file. This project is a primary step in creating my own archetype.

You should be able to download the project files, put them into a new Eclipse project, convert that project to be a Maven project (so that you can take advantage of dependency management features as well as lifecycle functions). 

Hope you find this helpful.

