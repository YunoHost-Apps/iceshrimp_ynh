## Customising assets and locale

* To add custom CSS for all users, edit `__INSTALL_DIR__/custom/assets/instance.css`.
* To add static assets (such as images for the splash screen), place them in the `__INSTALL_DIR__/custom/assets/` directory. They'll then be available on <https://__DOMAIN__/static-assets/filename.ext>.
* To add custom locales, place them in the `__INSTALL_DIR__/custom/locales/` directory. If you name your custom locale the same as an existing locale, it will overwrite it. If you give it a unique name, it will be added to the list. Also make sure that the first part of the filename matches the locale you're basing it on. (Example: en-FOO.yml)
* To add custom error images, place them in the `__INSTALL_DIR__/custom/assets/badges` directory, replacing the files already there.
* To add custom sounds, place only mp3 files in the `__INSTALL_DIR__/custom/assets/sounds` directory.
* To update custom assets without rebuilding, just run `yarn run gulp`.
  * If a `gulp not found` error is received, run `yarn global add gulp-cli` then `yarn install` in `__INSTALL_DIR__` and try `yarn run gulp` again.
