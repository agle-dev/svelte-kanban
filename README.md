# Svelte-Kanban-CRDT

This is a fork of [V-Py/Svelte-Kanban](https://github.com/V-Py/svelte-kanban) and adds multiuser functionality via Y-Js.

The interface is currently the same. If you would like to try out the functionality, run this project in dev mode.

## Dev Mode

```sh
git clone https://github.com/agle-dev/svelte-kanban-crdt.git
cd svelte-kanban
npm install
npm run dev
```

Open http://localhost:5173 in two tabs in the same browser. If you would like to use two different web browsers (eg Chrome and Safari), first run:

```sh
PORT=4444 npx y-webrtc server.js
```
