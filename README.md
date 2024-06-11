This repository is an error reproduction for Issue in vscode ESLint

<b>Issue:</b><br> 
using format with ESLint in vscode fix all the problems, not only the specified through eslint.options.fixTypes in settings.json<br>
<b>fixError.js</b> is the file that I'm trying to fix.<br>

<b>Setup:</b><br>
vscode extension ESLint v2.4.4<br>
eslint v9.4.0<br>

<b>VSCode settings.json</b> (related to ESLint extension)<br>
"eslint.experimental.useFlatConfig": true,<br>
"eslint.migration.2_x": "off",<br>
"eslint.format.enable": true,<br>
"eslint.options": {<br>
    "fixTypes": ["layout"]<br>
}<br>

both ESLint class example in "fixExample.js" and "npx eslint .\fixError.js --fix --fix-type layout" work properly


