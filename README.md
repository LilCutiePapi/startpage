# startpage

A simple, customisable startpage/homepage.

![example screenshot](/img/screenshots/2016-08-19-open.png?raw=true)

## Installation

Clone the repository or
[download](https://github.com/fuyuneko/startpage/archive/master.zip) the zip.

##### Firefox
In older versions of Firefox you could change the newtab page in about:config
by changing the value of 'browser.newtab.url'.
If you're using a newer version, you will probably need an add-on to change
the newtab and home pages.
Just add the path to ```index.html``` as the URL, preceding it
with ```file:///``` if it's a local file.
E.g.: ```file:///home/yuki/startpage/index.html```

##### Chromium/Chrome
To use the startpage in Chromium and Chrome you'll have to use it as an extension.
Just download the ```.crx file``` from the [latest release](https://github.com/fuyuneko/startpage/releases/latest)
and open it with Chrome.<br>
If a ```.crx``` file for a release isn't available or you want to use the latest version on github you
will have to [download](https://github.com/fuyuneko/startpage/blob/chromium-patch/manifest.json)
the manifest.json for the startpage and save it in the same directory as the startpage.
Go to Chrome's extension menu, enable _developer mode_, click on _"load unpacked
extension"_ and select the folder you saved the startage in.


## Configuration
The startpage can be configured by using a configuration file or by using a built-in menu.<br>
If you're using some sort of private/incognito mode in your browser the configuration will not be saved and
has to be loaded from ```config.json``` every time the page is reloaded. To prevent the configuration menu
from appearing every time you load the page you will have to set ```privateMode``` to ```true``` in ```config.json```.

When first opening the startpage you can choose to load the configuration from the ```config.json``` file
or configure the page by using the configuration menu. Choose whatever you like, you will be able to change this
later.<br>


Warning: Because of the way the configuration menu saves data, moving the startpage's directory to a different location
will result in it not being able to load the config. Moving it back should fix it. You can export the configuration as a
JSON file in the menu, then move the directory and load the file.

##### config.json
This is the file used for configuration.


## Contact
If you're having problems or have an improvement you can create an issue [here](https://github.com/fuyuneko/startpage/issues).

