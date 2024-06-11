This repository is an error reproduction for Issue in vscode ESLint

fixError.js is the file that I'm trying to fix.

My VSCode settings.json related configs to ESLint extension are:

"eslint.experimental.useFlatConfig": true,
"eslint.migration.2_x": "off",
"eslint.format.enable": true,
"eslint.options": {
    "fixTypes": ["layout"]
}

both ESLint class example in "fixExample.js" and "npx eslint .\fixError.js --fix --fix-type layout" work properly

Issue: using format with ESLint in vscode fix all the problems, not only the specified through eslint.options.fixTypes 
