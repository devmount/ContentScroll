ContentScroll
=============

A Plugin for moziloCMS 2.0

Makes content that is wider than containter width horizontal scrollable.

## Installation
#### With moziloCMS installer
To add (or update) a plugin in moziloCMS, go to the backend tab *Plugins* and click the item *Manage Plugins*. Here you can choose the plugin archive file (note that it has to be a ZIP file with exactly the same name the plugin has) and click *Install*. Now the ContentScroll plugin is listed below and can be activated.

#### Manually
Installing a plugin manually requires FTP Access.
- Upload unpacked plugin folder into moziloCMS plugin directory: ```/<moziloroot>/plugins/```
- Set default permissions (chmod 777 for folders and 666 for files)
- Go to the backend tab *Plugins* and activate the now listed new ContentScroll plugin

## Syntax
```{ContentScroll|<height>|<content>}```
Inserts the scrollalble content.

1. Parameter ```<height>```: Height of content slider in px
2. Parameter ```<content>```: Content, that should be horizontal scrollable, e.g. thumbnails of an image gallery

## License
This Plugin is distributed under *GNU General Public License, Version 3* (see LICENSE) or, at your choice, any further version.

## Documentation
A detailed documentation and demo can be found on DEVMOUNT's website:
http://devmount.de/Develop/moziloCMS/Plugins/ContentScroll.html
