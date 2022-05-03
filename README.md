# Fractal loader plugin for Craft CMS 4.x

Allows you to include [Fractal](https://fractal.build/) generated partials in your Craft CMS templates. 

## Requirements

This plugin requires Craft CMS 4.0.0-RC-2 or later.

## Installation

To install the plugin, follow these instructions.

1. Open your terminal and go to your Craft project:

   cd /path/to/project

2. Then tell Composer to load the plugin:

   composer require madebyraygun/fractal

3. In the Control Panel, go to Settings → Plugins and click the “Install” button for Fractal Loader.

## Fractal Overview

Make use of the Fractal library in Craft 4 by exporting a `components-map.json` file to your base `craft/templates` directory. Then include in your templates like

```
{% include '@button' with {
  text: 'Click here',
  url: 'https://google.com'
} %}
```

## Credits & Special Thanks

Credit [ournameismud](https://github.com/ournameismud/fractal) for the Craft 3 version.
Credit [allmarkedup](https://github.com/allmarkedup) for original [Fractal component loader plugin for Craft cms](https://gist.github.com/allmarkedup/72afed8e97c9b2e8c61c36b798ae1870)

