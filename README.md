# Svelte-Kanban-CRDT

- This is a fork of [V-Py/Svelte-Kanban](https://github.com/V-Py/svelte-kanban) with multiuser functionality provided by [Yjs](https://github.com/yjs/yjs) documents
  - [This PR](https://github.com/V-Py/svelte-kanban/pull/84) refactored V-Py/Svelte-Kanban to use Yjs documents via [SvelteSyncedStore](https://syncedstore.org/docs/svelte/)
  - [This PR](https://github.com/agle-dev/svelte-kanban-crdt/pulls/1) added CRDT functionality to it
- Here's a [movie](https://github-production-user-asset-6210df.s3.amazonaws.com/12297328/263563652-e4c8b0ee-6128-4c9c-b3f6-6f439610da1a.mp4) demonstrating multiple browsers
- The interface is currently the same as V-Py/Svelte-Kanban. It will be changed to also accept a Yjs document.

This component should not be used until props can specify the Yjs document.

## Dev Mode

The easiest way to try this component is to run it in dev mode.

```sh
git clone https://github.com/agle-dev/svelte-kanban-crdt.git
cd svelte-kanban
npm install
npm run dev
```

Open http://localhost:5173 in two tabs in the same browser.

To use two different web browsers (eg Chrome and Safari), first run:

```sh
PORT=4444 npx y-webrtc server.js
```
