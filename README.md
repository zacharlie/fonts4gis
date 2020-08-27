# fonts4gis

Process the SVG Icons for common FOSS webfont libraries for use with the QGIS Resource Sharing Plugin

Install the [QGIS resource sharing plugin](https://qgis-contribution.github.io/QGIS-ResourceSharing/) and add the URL ```https://github.com/zacharlie/fonts4gis.git``` as a repository. Once installed, you should have access to the various font libraries to use as SVG Symbols.

## Process

SVGs are added into a directory structure as required by the QGIS Resource Sharing Plugin and processed to insert additional parameters which allow QGIS to properl utilise the SVG (assigning fill/ stroke etc).

## Libraries

A list of currently included libraries (and their versions), in alphabetical order:

https://github.com/coreui/coreui-icons (2.0.0-beta.5)
https://github.com/astrit/css.gg (2.0.0)
https://gitlab.com/SUSE-UIUX/eos-icons (4.5.0)
https://github.com/feathericons/feather (4.28.0)
https://github.com/fontello/fontelico.font (latest - 2014)
https://github.com/ForkAwesome/Fork-Awesome/ (1.1.7)
https://github.com/tabler/tabler-icons (1.15.0)
https://github.com/Iconscout/unicons (2.1.11)

> **Note** that this does not include the Font Awesome library, which was provided it's own repository at https://github.com/zacharlie/fa4gis

This project was created to allow users familiar with other popular open source font libraries the ability to use those symbols.

A subset of Font Awesome symbols were cherry picked and isolated for cartographic purposes and readied for inclusion in QGIS Core as per [mailing list discussions](http://osgeo-org.1560.x6.nabble.com/Font-Awesome-symbols-in-QGIS-td5442745.html), which is also available as a separate repository:

https://github.com/zacharlie/fa4qgis

## License notes

The code and content of this repository is released under the unlicense, however each set of items included in the various nested components will be bound by the terms of the license agreement distributed with those components.
