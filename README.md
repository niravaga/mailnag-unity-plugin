# mailnag-unity-plugin
Plugin that integrates [Mailnag](https://github.com/pulb/mailnag) in Ubuntu's messaging menu.

## Installation

### Ubuntu PPA
This plugin is available in the official [Ubuntu PPA](https://launchpad.net/~pulb/+archive/mailnag).  
Issue the following commands in a terminal to enable the PPA and install the plugin.  

    sudo add-apt-repository ppa:pulb/mailnag
    sudo apt-get update
    sudo apt-get install mailnag-unity-plugin

### Generic Tarballs
Sourcecode releases are available [here](https://github.com/pulb/mailnag-unity-plugin/releases).  
To install the plugin type `sudo ./setup.py install --prefix=/usr --install-layout=deb` in a terminal.
That's it. Now fire up `mailnag-config` and enable the plugin.  

###### Requirements
* mailnag >= 1.0.0
* gir1.2-messagingmenu-1.0

## Screenshots
![Screenshot](https://raw.github.com/pulb/mailnag-unity-plugin/docs/docs/screenshot.png)
