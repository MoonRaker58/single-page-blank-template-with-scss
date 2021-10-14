This is a blank html project that uses scss for styling. There is an index page and then 2 example form pages.

This is based on following [this YouTube playlist](https://www.youtube.com/playlist?list=PLillGF-Rfqba3xeEvDzIcUCxwMlGiewfV) by Traversy Media

You need to have a SASS compiler. I'm using [Live Sass vscode extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass) for mine. I also have the following settings set in vscode.

```
"liveSassCompile.settings.formats": [
    {
        "format": "compressed",
        "extensionName": ".min.css",
        "savePath": "/dist/css"
    }
],
"liveSassCompile.settings.generateMap": false
```js