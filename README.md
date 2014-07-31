iconic-iconset
==============

Iconic icons in Polymer (http://www.polymer-project.org/)

![screenshot](https://raw.githubusercontent.com/karlll/iconic-iconset/master/screenshot.png "Screenshot")


## Overview

This repo contains the custom element `<iconic-iconset>` for using Iconic icons in your Polymer projects.


## Installation

### Requirements

* bower
* Iconic (pro); unlimited or non-commercial version
  - Note: the open version of Iconic, Open Iconic (https://github.com/iconic/open-iconic) could easily be
    made to work as well, see `iconic-iconset.html`

### Preparation

* Download the pro version of the iconic icon-set from http://useiconic.com
* Unpack in project root dir, rename directory to `iconic-web`


### Install dependencies

~~~
  $ bower install
~~~

## Usage

Import the custom element definition, `<link rel="import" href="iconic-iconset.html">` and add an icon to your page,  `<iconic-iconset icon="thumb-up-md" />`

See `demo.html` for further examples. To view the demo page, your browser should allow local XHRs.


## Limitations

- `iconic.js`is not used, so a lot of the described features at http://useiconic.com does not work.

## License

- This project: MIT License

- Iconic resources: see [https://preview.useiconic.com/license/](https://preview.useiconic.com/license/) for information of the Iconic licensing terms.

## Author

Karl Larsaeus - <karl@ninjacontrol.com>
