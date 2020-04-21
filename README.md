# course-upto-4-sass-starter
# code pen link https://codepen.io/anon/pen/eGZKyY?editors=1100
cmd
cd
cd..
exit
cls clear
e:
dir
mkdir folderName createstype folder
cd folderName

create file
type nul> index.js 

E:\GitProjects\CSS_Ex\starter\js>copy index.js ..
 1 file(s) copied. copied form js to starter folder one level above(..).
E:\GitProjects\CSS_Ex\starter\js>move script.js ..
        1 file(s) moved. moved form js to starter folder onle level above(..).
E:\GitProjects\CSS_Ex\starter\js>del index.js
E:\GitProjects\CSS_Ex\starter>rmdir /s js
js, Are you sure (Y/N)? y
E:\GitProjects\CSS_Ex\starter\img>start hero.jpg // to watch the images

E:\GitProjects\newTry\starter> npm init
to create a package.json file

npm i node-sass --save-dev
to download node-sass as a developer dependancy

In package .json file add scripts for compile sass 
like that 
 "scripts": {
    "compile:sass" : "node-sass sass/main.scss css/style.css -w"
  },

here node-sass is a package 

and sass/main.scss is a input scss file to converted to css

and css/style.css is output pure css flle
and -w is a watch flag to listening current changes .

npm run compile:sass 
for compile sass code 

to add live server on globally
npm i live-server -g
E:\GitProjects\newTry\starter>npm run compile:sass
E:\GitProjects\CSS_Ex\starter>live-server
