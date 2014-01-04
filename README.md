Public repo with Python plugins for Prismatik software
-------------

Prismatik software on [Lightpack project page] (http://code.google.com/p/lightpack/)

###Install:
* Push "Dowload ZIP" button at the bottom of the left menu of the [repo main page] (https://github.com/Atarity/Prismatik-plugins)
* Unzip downloaded archive locally
* Just copy plugins folders to the Prismatik profile dir, e.g. for Win `C:\Documents and Settings\Atarity\Prismatik\Plugins` or in OS X `/Users/Atarity/.Prismatik/Plugins`
* Push "Reload plugins" button in Prismatik
* Read "About" tab if plugin did not work properly

### To committers and contributors:
1. Do not commit third-party Python modules. Describe all dependancies in plugin readme.txt or directly in "About" section
2. Add all third-party Python modules you use in `<Prismatik profile>/Plugins/site-packages/` dir
3. Use "Fork" button if you plan to develop something "hardcore-experimental-not-for-all" feature

###Repo mapping tips and triks:
Use Linux-way linking in Windows to map specific plugin directly from repo to Prismatik profile dir. Use folder **symbol links** for it (Alt+F6 in Far Manager).
