# create-react-app-crx-issue

Minimal project created with `create-react-app` that uses `styled-components`. Including the `styled-components` causes Chrome to fail when loading the extension with this error message:

> Could not load file 'src/js/main.XXXXX.js' for content script. It isn't UTF-8 encoded.

I've hard-coded the proper values in the `public/manifest.json` to match the hash included in the filename generated by `npm run build`.