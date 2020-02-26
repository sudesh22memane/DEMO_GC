Hello All,

I have given below instructions to setup and test the application on your local system.

Note: To run the Application, please make sure you have node js installed on your system.

Steps to Setup the Application:
1. Download all soucre code from git repository on your local system. example in d:/testassigment
2. Install npm & gulp.js in your local system which is required for running application.
3. Copy "src" folder including gulpfile.js,package.json & package-lock.json in your local directory(not in src folder). 
4. 'src' folder contain all files i.e. css,js,images,fonts,scss,includes,index.html. etc. so copy and paste 'src' folder in your project directory.
4. To run gulp you need to install 'gulp-imagemin','gulp-sass','browser-sync' and 'gulp-notify' plugins in project environment. 
5. Once you successfully install all plugins then open project in code editior (vs code) or just open command prompt and run it.
6. Type 'gulp' command in command prompt and hit enter to  run the application.


To Run application :
1) We must have npm and gulp installed on our system(which is given in git repo) and 'node_modules' folder is available in project directory.
2) We need gulpfile.js, package.json, package-lock.json file with 'src' folder in your project directory.
3) 'src' folder contain all the files and folder provided in git repo.
4) Open command prompt in project folder and type command 'gulp' it will open application in browser.

How to Test the application :
1) Open index.HTML in Chrome/FF Browser. 
2) Click More button to show More Content. More Button now will see as 'Read Less' and if we click on Read Less Button then it will collapse the Content to 2 lines.
3)'Show gallery' button is Disabled till we get josn response and once data get loaded,  Show Gallery button will get Enabled. 
4) On Click of 'Show gallery' button, popup will get open with slick image slider which contain image and author name at bottom of slider image. We can slide images with the help of Slider 
5) We can view application in mobile or Ipad view.


Resources Used:
1. Used slick slider to run image slider in model popup.
2. used foundation for responsive & UI development.
3. used jquery for some custom changes to meet the requirements.
4. used SCSS (all code available in SCSS folder) for styling the page and compile it by using gulp.js into 
   normal css(in style.css file)
5. Also used W3.JS to separate common templates i.e. footer/header.html and import in index.html with help of w3.js.


If you face any challenges while setup, please reachout to Sudesh.memane@clariontechnologies.co.in

Thank you
Sudesh M