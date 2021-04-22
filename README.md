# RemNote-Interactive-Code
Embed the Klipse (https://github.com/viebel/klipse) code editor into your
RemNote documents.

Add interactive code editor to your RemNote docs. Clojure(Script), JavaScript,
Python, and more are available.

<img src="demo.gif" alt="GIF Demo of Using the plugin" />

## Install
* In RemNote go to settings.
* Select plugins and insert the following:
    * **Plugin Name**: Can be anything, If the editor is for Python then I would do *py-code* etc.
    * **Plugin Description**: Optional
    * **Plugin URL**: `https://sirvan3tr.github.io/RemNote-Interactive-Code/?lang=python&code=print(%22hello%22)` See usage below for more info.
    * **CSS Height**: At least 150px
    * **CSS Width**: 100%
    * **Permission**: Leave on Read (This plugin doesn't do anything to your notes. So it is safe.)

## Usage
The plugin is controlled by the URL parameters.
* `lang=` is for the language that you can use.
    * `lang=js` for JavaScript
    * `lang=python` for Python
    * etc.
* `code=` You can initiate your plugin with a code snipper.
* **Example**: `https://sirvan3tr.github.io/RemNote-Interactive-Code/?lang=python&code=print(%22hello%22)`
    * This uses python and initiates the editor wit a print() statement.

## RemNote API
You can access the RemNote API (v0) through the editors.
Here is a demo of how to use it.

<img src="demo_api.gif" alt="API Access Demo" />