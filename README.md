iconic-iconset
==============

Iconic icons in Polymer (http://www.polymer-project.org/)

  ![screenshot](https://raw.githubusercontent.com/karlll/iconic-iconset/master/screenshot.png "Screenshot")

## Overview

This repo contains the custom element `<iconic-iconset>` for using Iconic icons in your Polymer projects.


## Installation

### Requirements

* bower
* Iconic (pro or open version)

### Preparation

* Download and extract in project root dir one (or both) of the Iconic versions below

#### Open Iconic

* Download https://github.com/iconic/open-iconic/archive/master.zip and extract to `open-iconic` in project directory

#### Iconic Pro

* Download from http://useiconic.com and extract to `iconic-web` in project directory


### Install dependencies

~~~
  $ bower install
~~~

## Usage

Import the custom element definition, `<link rel="import" href="iconic-iconset.html">` and add an icon to your page,  `<iconic-iconset icon="thumb" type="smart" class="iconic-md" />`

See `demo.html` for further examples. To view the demo page, your browser should allow local XHRs.

## Limitations

- Smart icon features such as data attributes and Javascrip API is not mapped from `iconic.js`

## License

- This project: MIT License

- Iconic resources: see [https://preview.useiconic.com/license/](https://preview.useiconic.com/license/) for information of the Iconic licensing terms.

## Author

Karl Larsaeus - <karl@ninjacontrol.com>
