Standalone [code-server] client.
(notes: disabled CommandOrControl+W shortcut to disable closing and it allows to set up close tab shortcut in vsc code-server)

Requires Node.JS and Electron installed to Build release.

~ requires electron-forge

~ use `electron-forge publish` to build standalone application.

INSTALLATION
0) change url to your http code-server (src/index.js)
1) `npm i`
2) `electron-forge publish`
3) use build from 'out' directory


= only MacOS tested.
