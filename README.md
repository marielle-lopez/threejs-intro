# Introduction to Three.js

## Changelog

- Installed Three.js and Vite
- Added [Vite's common commands](https://vitejs.dev/guide/#command-line-interface) into the 'scripts' list in `package.json`
- Created `.gitignore` to ignore `node_modules` directory
  - I contemplated whether `package-lock.json` is meant to be added to a version control repository, and as mentioned by [this Stack Overflow answer](https://stackoverflow.com/a/48524475), it should **not** be added to `.gitignore`
- Using `main.js`, I created a simple scene with an animated cube
  - Followed the ['Creating a scene' tutorial](https://threejs.org/docs/#manual/en/introduction/Creating-a-scene)

### Speedbumps

- While installing Three.js and Vite via `npm install --save three` and `npm install --save-dev vite`, both a `node_modules` directory and `package.json` file were not generated
  - According to [this Stack Overflow answer](https://stackoverflow.com/a/47642158), running `npm init` generates a `package.json` file which is needed to solve this speedbump
