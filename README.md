## ubb-owl-date-widget

This is a Protege 3.5 OWL slot widget plugin for date creation. The plugin is a clone of <code>OWLDateWidget</code> from the Protege 3.5 OWL-plugin with some custom modifications.
This slot widget plugin automatically copies the current date into the specified slot when the instance is created thereby marking a "creation date". 
The plugin also contains a date picker such that the date can be manually modified.

 You would need <code> Java JDK6</code> or newer to run this plugin.

### How to install the plugin

- Download the plugin JAR file from https://github.com/ubbdst/ubb-date-widget/releases.

- Go to your Protege installation directory and put the JAR file into <code>plugins/edu.stanford.smi.protegex.owl</code>. 
Note that this plugin is an owl-plugin hence it belongs (and must be put) to the Protege owl-plugin directory otherwise it will not work.

- Restart the Protege and go to the form editor to select the plugin. You should see <code>UBBOWLDateWidget</code>
as one of the optional plugins displayed. It is a wise to note that if you are using Protege client-server mode, you must install the plugin to the server and to all of the clients.





