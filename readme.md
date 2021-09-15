Setting for vscode

.vscode/settings.json

{
"liveServer.settings.port": 3000,
"liveSassCompile.settings.formats": [
{
"format": "compressed",
"extensionName": ".min.css",
"savePath": "/dist/css"
}
],
"liveSassCompile.settings.includeItems": ["/scss/*.scss", "/scss/_*.scss"],
"liveSassCompile.settings.excludeList": ["**/node_modules/**", ".vscode/**"],
"liveSassCompile.settings.autoprefix": ["> 1%", "last 2 versions"],
"liveSassCompile.settings.generateMap": false,
"liveSassCompile.settings.showOutputWindow": false
}
