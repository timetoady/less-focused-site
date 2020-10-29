# Site Design Using Less


## Test Basics

Click on "OUR TOP EXPERIENCE" to navigate to the second page. Other elements are dummy elements.

## Design based on: 
https://otaku-games.com/

## Requirements

* [style.less](https://github.com/timetoady/less-focused-site/blob/main/less/style.less) imports info from variables, markup, mixins, and product less files.
* [variables.less](https://github.com/timetoady/less-focused-site/blob/main/less/variables.less) maintains needed variables, including font style and size and color, as well as background and accent colors.
* [mixins.less](https://github.com/timetoady/less-focused-site/blob/main/less/mixins.less) maintains the many various mixins the site, probably more than was likely called for. This includes two different button mixins. #missingthepointofmixins
* [markup.less]() incorporates the various variables and mixins with specifics to basically mimic the HTML structure.
* Using media queries and escaped variables fount in [variables.less](https://github.com/timetoady/less-focused-site/blob/main/less/variables.less), various changes to grid, images, font-sizes are used for small and medium screens.