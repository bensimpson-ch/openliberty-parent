# openliberty-parent
Parent pom for an open liberty project.  Open Liberty plugin is activated only in the Maven sub-module where a src/main/liberty/config/server.xml is present.  Otherwise, the plugin is deactivated.  This enables development of multiple-modules to encourage separation of concerns.
