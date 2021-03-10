Emrip Server Review & AJAX Intro
===

Stage 1: setup
---

- git init
- npm init -y
- npm install express
- add .gitignore
- set up folders( server, server/public, etc...)
- mover over jQuery (server/public/vendors)
- create html (server/public)
- create client.js (server/public/scripts)
- create server.js (server)

Stage 2: spin up server
---

edit server.js

- require express
- create app
- app.use express.static on server/public
- spin up server on port 5000