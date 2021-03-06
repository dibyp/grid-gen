Grid Generator - Chrome Extension
=============================

Grid Generator is an extension for [Google Chrome](https://www.google.com/chrome) allowing you to
draw a grid or grids on the webpage you are seeing to know which grid system it uses.

### [Install the addon here from the Chrome Web Store](#)

Please use the [issue tracker](https://github.com/dibyp/grid-gen/issues) to report any bugs or make suggestions

## Contribute

All contributions are welcome. The project uses [Grunt](http://gruntjs.com/) for automated builds and [Sass](http://sass-lang.com/) for CSS.

### Quickstart

Install [node.js](http://nodejs.org/). Once installed run the following commands to install grunt, less and generate a build.

```bash
npm install -g grunt-cli
npm install -g sass
cd /path/to/gridgen
npm install
grunt
```

Source code is located in the `src` directory. Grunt will monitor any changes to the files in this folder and automatically compile
and generate a new builds in the `build` directory. Set `/path/to/gridgen/build` as the location of your unpacked extension and
you can now makes changes and see the results in your browser.

### Translating

If you would like to contribute a translation please either:

1. fork the repository, add them in `src/_locales` using the guildelines specified in the
[Chrome extension internationalization guide](http://developer.chrome.com/extensions/i18n.html) and submit a pull request.
2. download the English master version at [src/_locales/en/messages.json](#)
and create a new ticket in the [project issue tracker](https://github.com/dibyp/grid-gen/issues) attaching your translated version.
Please prefix the issue title with '[translation]' and remember to say what language it is for!

All translations should be based on the master English version located at `src/_locales/en/messages.json`

### Credit
If you would like to be credited for your contribution on the upgrade page please also include a name and link (personal site, twitter etc)
with your submission
