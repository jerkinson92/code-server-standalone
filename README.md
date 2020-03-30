Standalone [code-server] client. Download and run before (https://github.com/cdr/code-server)
(notes: disabled CommandOrControl+W shortcut to disable closing and it allows to set up close tab shortcut in vsc code-server)

Requires Node.JS and Electron installed to Build release.

~ requires electron-forge

~ use `electron-forge publish` to build standalone application.

INSTALLATION
1) change url to your http code-server (src/index.js)
2) `npm i`
3) `electron-forge publish`
4) use build from 'out' directory


= only MacOS tested.
