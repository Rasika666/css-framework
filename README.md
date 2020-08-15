# CSS framework
---

make sure to add following snippets to settings.json in vs code
```javascript
{
    "liveSassCompile.settings.formats":[
        //dev
        {
            "format": "expanded", 
            "extensionName": ".css",
            "savePath": "~/../css"
        },
        //prod
        // {
        //     "format": "compressed",
        //     "extensionName": ".min.css",
        //     "savePath": "~/../css/"
        // }
    ]
}
```