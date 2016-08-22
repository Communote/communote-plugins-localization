# About
The Communote localization plugins add additional langauges to [Communote](https://github.com/Communote/communote-server) and provide 
translations of the web frontend in these languages. The available languages are:

* Spanish (see communote-localization-spanish)
* French (see communote-localization-french)
* Italian (see communote-localization-italian)
* Russian (communote-localization-russian - this translation is only a stub)

The translations which are not 100% complete are focussed on the main web frontend. The administration section is typically not translated. 
Untranslated messages will be shown in English.

# Compatibility
The plugin can be used with a Communote standalone installation and the Communote SaaS platform.

The following table shows which Communote server versions are supported by a specific version of the plugins. A server version which is not 
listed cannot be uses with the plugin.

| Plugin Version  | Supported Server Version |
| ------------- | ------------- |
| 3.4  | 3.2, 3.4  |

# Installation and Usage
To install one of the localization plugins get a release from the [Releases](https://github.com/Communote/communote-plugins-localization/releases) 
section and deploy it to your Communote installation as described in the [Installation Documentation](http://communote.github.io/doc/install_extensions.html). 
Afterwards the new language will be selectable in the user profile.

# Building
To build the plugins you have to clone or download the source and setup your development environment as described in our 
[Developer Documentation](http://communote.github.io/doc/dev_preparation.html). When the preparations are done you can just run 
```mvn``` in the checkout directory. The JAR file of a plugin will be created in its target subdirectory.

# License
The localization plugins are licensed under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).
