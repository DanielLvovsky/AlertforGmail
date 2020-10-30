## [Alert for Gmail](https://alertforgmail.netlify.app/)

### Description
[Alert for Gmail](https://chrome.google.com/webstore/detail/alert/njaeaemciiokfpolomebdlppcafjchod) is a multi-account notifier for Gmail (without storing passwords)



### General information
To run Alert for Gmail you need to have these softwares and libraries available:

 * [nodejs](http://nodejs.org/)
 * [Gulp.JS](http://gulpjs.com/)

### Folders description
* compile: nodejs locale converter
* preview: screenshots
* src: Alert for Gmail source code

### How to compile Alert for Gmail
1. Open a new terminal in the root dir (directory contains src, preview, template, and compile folders)
2. Run `npm install` to acquire the necessary nodejs packages
3. Run  `gulp chrome` to compile Alert for Gmail in Chrome browsers
    * After running `gulp chrome`, project gets compiled for Chrome/Opera browser. Compiled files will be located on `builds/unpacked/chrome` folder. A zipped archive will be placed in `builds/packed/chrome.zip`
    * For `gulp chrome` to auto install the extension on your Chrome browser, you will need to modify [Line 65 of `gulp.js`]

### How to try the precompiled latest version on Chrome
1. Select the right branch
2. Browse the `builds/packed` directory
3. Download the *.zip file and extract it somewhere
4. Open a browser tab for `chrome://extensions` and turn on the developer mode
5. Point the browse button to the root directory
