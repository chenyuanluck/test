`
var gulp = require('gulp');
// 用来将HTML 文件中（或者templates/views）中没有优化的script 和stylesheets 替换为优化过的版本。
var usemin = require('gulp-usemin');
// javascript代码优化工具，可以解析，压缩和美化javascript。
var uglify = require('gulp-uglify');
// 合并压缩html
var minifyHtml = require('gulp-minify-html');
// 合并css
var minifyCss = require('gulp-minify-css');
// 加上哈希文件名
var rev = require('gulp-rev');
// 提示消息
var notify = require('gulp-notify');
// 清理目录
var clean = require('gulp-clean');
// JavaScript检查
var jshint = require('gulp-jshint');
// 文件引入
var fileInclude = require('gulp-file-include');
// 配置文件
var config = require('./gulpConfig.json');
// 文本替换
var replace = require('gulp-replace');
// 重命名
var rename = require('gulp-rename');
// 合并文件
var concat = require('gulp-concat');
// gulp-exec
var exec = require('gulp-exec');
`