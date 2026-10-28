# Third-party software

## @imgly/background-removal

`vendor/bg-removal.js` is a bundled build of [@imgly/background-removal](https://github.com/imgly/background-removal-js), used by "Find subject automatically" to separate the subject from the background. It runs entirely in the browser; photos are not uploaded. Its model files are downloaded from IMG.LY's CDN (`staticimgly.com`) the first time the feature is used, then cached for offline use.

Licence: GNU Affero General Public License v3.0 (AGPL-3.0). Source: https://github.com/imgly/background-removal-js
