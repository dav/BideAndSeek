## BideAndSeek

This is intended to be a tool that can be configured to accept text input, parse out a recognizable identifier within it (e.g. a GUID) and then find the data that the identifier represents and make it accessible to the user. In exchange for some upfront work (installation, configuration of desktop right click menu, configuration of data access, configuration of identifier pattern matching) it should save time throughout the work day by providing quick access to data entities.

To paint a clearer picture: you select some text with an identifier in it, e.g. from an error log line. Next you right click for a context menu and select the option to Seek. The Seek utility has been configured to be able to access your development, staging and production databases. Quickly in the background it attempts to find a typical entity (User, Order, etc) with that guid in each environment. When it gets a match, it opens the correct URL to view that entity. 
