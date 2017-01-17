В корне проекта выполнить эти команды

1) npm install -g gulp

2) npm install --save-dev gulp gulp-sass browser-sync gulp-concat gulp-uglifyjs gulp-cssnano gulp-rename del gulp-imagemin imagemin-pngquant gulp-cache gulp-autoprefixer


// ПОСМОТРЕТЬ ЧТО ДЕЛАЮТ
gulp-useref
gulp-if
gulp-minify-css
gulp-imagemin
run-sequence
gulp-csso
gulp-concat
gulp-notify
gulp-css-url-adjuster
streamqueue
gulp-plumber


gulp.src - выборка исходных файлов проекта для обработки плагином;
.pipe(plugin()) - вызов Gulp плагина для обработки файла;
.pipe(gulp.dest('folder')) - вывод результирующего файла в папку назначения (dest - пункт назначения).