# Gulp Starter

[**Gulp Starter**](https://github.com/ummahusla/Gulp-Starter) is a project template which uses [**Gulp**](http://gulpjs.com/) to compile CSS to SASS, minimise CSS and JS files, optimising images, [**Browsersync**](https://browsersync.io/) for time-saving while development and much more!

___

### Installing

1. `git clone https://github.com/ummahusla/Gulp-Starter.git folder-name`
2. `cd /folder-name && npm install`
3. `gulp`

You should see very similar output in console

```
[10:53:52] Using gulpfile /folder-name/gulpfile.js
[10:53:52] Starting 'default'...
[10:53:52] Starting 'sass'...
[10:53:52] Starting 'browser-sync'...
[10:53:52] Finished 'browser-sync' after 12 ms
[BS] Access URLs:
 ---------------------------------------
       Local: http://localhost:3000
    External: http://192.168.15.166:3000
 ---------------------------------------
          UI: http://localhost:3001
 UI External: http://192.168.15.166:3001
 ---------------------------------------
[BS] Serving files from: app
[BS] 1 file changed (styles.css)
[10:53:52] Finished 'sass' after 146 ms
[10:53:52] Starting 'watch'...
[10:53:52] Finished 'watch' after 18 ms
[10:53:52] Finished 'default' after 167 ms
```

___

### Dependencies

* `browser-sync`
* `del`
* `gulp`
* `gulp-cache`
* `gulp-cssnano`
* `gulp-if`
* `gulp-imagemin`
* `gulp-sass`
* `gulp-uglify`
* `gulp-useref`
* `gulp-autoprefixer`
* `run-sequence`

___

### Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

___

### License

MIT License
