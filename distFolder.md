🚨 NOTE: I didn't mention in the video how to get the "dist" folder to appear when running the Live Sass extension! You will have to go into your VS Code Settings (Ctrl-Shift-P and type in "settings" then select "Preferences: Open Settings (JSON)" and in the settings.json file, inside the outer curly brackets "{" and "}" add the following:

"liveSassCompile.settings.formats": [
{
"format": "expanded",
"extensionName": ".css",
"savePath": "/dist",
"savePathSegmentKeys": null,
"savePathReplaceSegmentsWith": null
}
],
