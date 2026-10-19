# TCS Demo

Browser build of the LEGO Star Wars: The Complete Saga decompilation
(based on opensagadev/saga) with the game's original touch controls.

This repository contains only the compiled page. It includes no game data:
you pick your own `main.1060.com.wb.lego.tcs.obb` from your device when the
page opens. `coi-serviceworker.js` (MIT) enables the cross-origin isolation
the threaded WebAssembly build needs on GitHub Pages.
