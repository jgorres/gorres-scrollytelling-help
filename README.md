# Gorres Scrollytelling – Online Help

Online help for the WordPress plugin **Gorres Scrollytelling**, packaged as a
[WordPress Playground](https://wordpress.github.io/wordpress-playground/)
blueprint. It opens a complete site in the browser: the help pages in English
and German, live examples of the blocks, and the editor to try them out.

**Open the help in the Playground:**

https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/jgorres/gorres-scrollytelling-help/main/blueprint.json&mode=seamless

## Contents

| File | Purpose |
| --- | --- |
| `blueprint.json` | Playground blueprint: installs the theme and the plugins, imports the content |
| `gorres-scrollytelling.zip` | The plugin, same build as the release |
| `content.json` | Pages, templates, navigation and media records of the help site |
| `uploads.zip` | Media files: photos, screenshots, banners and a short test video |
| `import.php` | Import script, run by WP-CLI inside the Playground |
| `export.php`, `build.sh` | Tools that create the bundle from the local help site; not used by the Playground |

## Running it locally

```
npx @wp-playground/cli@latest server --blueprint=. --blueprint-may-read-adjacent-files
```

Then open http://127.0.0.1:9400.

## License

GPL v2 or later, see `LICENSE`. The photos in `uploads.zip` come from the
[WordPress Photo Directory](https://wordpress.org/photos/) and are CC0; the
source of each photo is noted in its description in the media library.

Author: Jörn Gorres, https://joern.gorres.com
