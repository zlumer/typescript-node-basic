# typescript-node-basic
Project structure for a simple Node.js + TypeScript app

Press `Ctrl+Shift+B` to build the project. You will see compiler output in the output window (`Ctrl+Shift+U`).

The compiler will compile files automatically when saved.

To stop the compilation, press `Ctrl+P` → `> Tasks: Terminate Running Task`.

JS source maps are excluded from git to reduce clutter, you can re-enable them in `.gitignore`.

Press `F5` to run application.

`src/app.ts` ← code goes here  
`test/test.ts` ← tests go here

Source code
-----------
Put your code under `src/*.ts`

Run app using `node js/src/app.js`

Tests
-----
Put your tests under `test/*.ts`

Run tests using `mocha "js/test/**/*.js"`