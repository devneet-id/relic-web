# Vessel

**Every library of this website lives here.**

The vessel is a folder of libraries, carried by the runite into the page. `php cast build` takes it per folder: every `.html`, `.css`, `.js` and `.php` here joins `dist/index.php`, no need to list it in `cast`.

| File | Goes into |
| ---- | --------- |
| `*.head.html` | `<head>` |
| `*.html` | `<body>`, after `src/index.html` |
| `*.css` | `<style>`, after `src/index.css` |
| `*.js` | `<script>`, after `src/index.js` |
| `*.php` | on top, after `src/index.php` |

Name each file after its library, side by side, no subfolder: `exura.css`, `exura.js`, `exura.php`.

Other files (images, this README) stay out of the bundle, but still travel with the relic as shards.
