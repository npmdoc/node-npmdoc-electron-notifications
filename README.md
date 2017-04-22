# npmdoc-electron-notifications

#### api documentation for  electron-notifications (v1.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-electron-notifications.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-electron-notifications) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-electron-notifications.svg)](https://travis-ci.org/npmdoc/node-npmdoc-electron-notifications)

#### A node module for sending notifications in electron applications

[![NPM](https://nodei.co/npm/electron-notifications.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-notifications)

- [https://npmdoc.github.io/node-npmdoc-electron-notifications/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-notifications/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-notifications/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-notifications/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-electron-notifications/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-electron-notifications/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "electron-notifications",
    "version": "1.0.0",
    "description": "A node module for sending notifications in electron applications",
    "main": "index.js",
    "scripts": {
        "start": "npm run playbook",
        "playbook": "electron playbook/main.js",
        "lint": "standard"
    },
    "keywords": [
        "electron",
        "notification",
        "notification center",
        "toaster",
        "growl",
        "notify-send",
        "terminal-notifier",
        "notify"
    ],
    "repository": "git@github.com:blainesch/electron-notifications.git",
    "author": "Blaine Schmeisser",
    "license": "MIT",
    "standard": {
        "globals": [
            "CodeMirror"
        ],
        "ignore": [
            "playbook/assets/vendor"
        ]
    },
    "devDependencies": {
        "electron": "^1.3.4",
        "standard": "^8.0.0"
    },
    "dependencies": {
        "electron-is": "^2.3.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
