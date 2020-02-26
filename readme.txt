To run Application in your system, please make sure you have node js & git has been installed.

Follow the steps belows,

1. Download all code from git repo in your system.
2. Install npm & gulp.js in your local system which is required for running application.
3. Copy "src" folder including gulpfile.js,package.json & package-lock.json in your local directory(not in src folder). 
4. 'src' folder contain all files i.e. css,js,images,fonts,scss,includes,index.html. etc. so copy and paste 'src' folder in your project directory.
4. To run gulp you need to install 'gulp-imagemin','gulp-sass','browser-sync' and 'gulp-notify' plugins in project environment. 
5. Once you successfully install all plugins then open project in code editior (vs code) or just open command prompt and run it.
6. Type 'gulp' command in command prompt and hit enter to  run the application.

Resources:

1. Used slick slider to run image slider in model popup.
2. used foundation for responsive & UI development.
3. used jquery for some custom changes to meet the requirements.
4. used SCSS (all code available in SCSS folder) for styling the page and compile it by using gulp.js into 
   normal css(in style.css file)
5. Also used W3.JS to separate common templates i.e. footer/header.html and import in index.html with help of w3.js.

Run application :

1) To Run application you must have npm and gulp install in your system(which is given in git repo) and 'node_modules' folder is available in project   
   directory.
2) You must have gulpfile.js, package.json, package-lock.json file with 'src' folder in your project directory.
3) 'src' folder contain all the files and folder provided in git repo.
4) Open command prompt in project folder and type command 'gulp' it will open application in browser.


Instructions for  to test the application :

After successfully configuration and running the application, you need to test it with following steps,

1) Open index.HTML in browser and click on more button to show more content. once you click the more button then text of 'more' button will change to 'Read Less' and if we click on the same button the it will collapse the content to 2 lines.

2)'Shwo gallery' button is disbled till we get response from json file and once data loaded show gallery button will enable then click 'Show gallery' button, it will open popup with slick image slider which contain image and author name at bottom of slider image. Slider has navigation button from left and right side to navigate to next or previous slide.

3) You can check application in mobile or Ipad view.



