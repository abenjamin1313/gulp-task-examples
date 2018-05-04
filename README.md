"# gulp-task-examples" 

# Gulp Example/Starter App

Example gulp application to show how to use plugins and run tasks
Moving/Copying Files
Concatenate JavaScript Files
Minify / Uglify JavaScript Files
Compile Sass/scss Files
Optimize Images with Imagemin

### Version
1.0.0

##Dependencies  
gulp-imagemin [gulp-imagemin](https://github.com/sindresorhus/gulp-imagemin "gulp-imagemin")
compress's GIF, JPEG, PNG, and SVG images  
gulp-concat [gulp-concat](https://www.npmjs.com/package/gulp-concat "gulp-concat") concat files by your operating systems newLine.  
gulp-uglify [gulp-uglify](https://www.npmjs.com/package/gulp-uglify "gulp-uglify") Minification of JavaScript   
gulp-sass [gulp-sass](https://www.npmjs.com/package/gulp-sass "gulp-sass") Compile SASS files  

## Install Dependencies
```bash
npm install --save-dev gulp-imagemin
npm install --save-dev gulp-concat
npm install --save-dev gulp-uglify
npm install --gulp-sass --save-dev
```

## Run all tasks
```bash
gulp
```

## Watch all tasks/files
```bash
gulp watch
```