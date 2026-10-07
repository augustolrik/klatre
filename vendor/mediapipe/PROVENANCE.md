# MediaPipe Hands runtime provenance

The files in this directory are the pinned `@mediapipe/hands` JavaScript
solution and model/WASM assets at version `0.4.1675469240`. They are used
locally by `src/ui/hand-tracking.ts` after the user explicitly starts the
camera. The package metadata declares Apache-2.0; the accompanying
`LICENSE.txt` is retained with the vendored distribution.

Source package: [google-ai-edge/mediapipe](https://github.com/google-ai-edge/mediapipe)

The asset set was copied from the read-only local package at
`C:/Git/hand-math-game/node_modules/@mediapipe/hands` and its matching local
`vendor/mediapipe` runtime. No runtime code in that project was modified.

The loader uses `hands.js` with `locateFile` pointed at this directory. No
CDN or remote model request is used. Camera frames remain in the browser; the
game does not send them to a server.

The main desktop game received this unchanged, licensed asset set from the
completed local `sites/matematikvaerkstedet/public/vendor/mediapipe` copy on
6 October 2026. That copy remains untouched.
