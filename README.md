# sass-livereload

http://prgssr.ru/development/vvedenie-v-paketnyj-menedzher-npm-dlya-nachinayushih.html
https://habrahabr.ru/post/133363/#npm_install_locally
https://blog.jayway.com/2014/03/28/running-scripts-with-npm/
https://sass-scss.ru/
https://www.npmjs.com/package/static-livereload

Install git, node.js, npm, sass, static-livereload. Clone repository, run "npm install". 
You can run server using the command "npm start".
The local server will be available at http://localhost:3000/static/

Examples for watching *.scss files:
	sass --watch input.scss output.css	 - watch input.scss, compile to output.css
	sass --watch .:./css				 - watch all *.scss files in current folder, compile them to /css folder
	
Examples for launching static-livereload server:
	static-livereload --path test		- starts static server for the /test folder
	static-livereload --path /			- starts static server for the current folder
