# Directory index plugin for Vite

📂 Directory index plugin for the Vite dev server

<p align=center>
  <img src="https://i.imgur.com/vhzjfm3.png">
</p>

⚡ Works with [Vite] \
📂 Great for HTML files in subfolders like `test/app.test.html` \
🖥️ Rendered on the server only in development \
📦 Doesn't affect your build output

## Installation

![npm](https://img.shields.io/static/v1?style=for-the-badge&message=npm&color=CB3837&logo=npm&logoColor=FFFFFF&label=)
![Yarn](https://img.shields.io/static/v1?style=for-the-badge&message=Yarn&color=2C8EBB&logo=Yarn&logoColor=FFFFFF&label=)
![pnpm](https://img.shields.io/static/v1?style=for-the-badge&message=pnpm&color=222222&logo=pnpm&logoColor=F69220&label=)

You can install this package using npm or your favorite npm package manager like
[Yarn] or [pnpm].

```sh
npm install --save-dev vite-plugin-directory-index
```

## Usage

![Vite](https://img.shields.io/static/v1?style=for-the-badge&message=Vite&color=646CFF&logo=Vite&logoColor=FFFFFF&label=)

```js
// vite.config.js
import { defineConfig } from "vite";
import directoryIndex from "vite-plugin-directory-index";

// https://vitejs.dev/config/
export default defineConfig({
  plugins: [directoryIndex()],
});
```

### Options

This plugin **respects [the `server.fs` options]**. Other than that, there's no
available configuration. If you have need a config option, [open an Issue]!

<!-- prettier-ignore-start -->
[Vite]: https://vitejs.dev/
[the `server.fs` options]: https://vitejs.dev/config/server-options.html#server-fs-strict
[open an issue]: https://github.com/jcbhmr/vite-plugin-directory-index/issues
[yarn]: https://yarnpkg.com/
[pnpm]: https://pnpm.io/
<!-- prettier-ignore-end -->
