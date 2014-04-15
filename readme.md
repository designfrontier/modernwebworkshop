#MODERN WEB DEV WORKSHOP
##SETUP LINKS
* git: http://git-scm.com/downloads and https://help.github.com/articles/set-up-git
* node: http://nodejs.org/
* Heroku: http://heroku.com/
* Homebrew: http://brew.sh/
* Sublime: http://www.sublimetext.com/
* Google Chrome: https://www.google.com/intl/en/chrome/browser/

##SETUP ROUND 1
1. npm install -g express gulp supervisor
2. Create a directory for the project
3. Open a command line and type `git init`
4. `express -e .`
5. `npm install`
6. `npm start`
7. Open chrome up and head to http://localhost:3000
8. Create a `.gitignore` file in your project root
9. Add the following to your `.gitignore` file
	* .DS_Store
	* node_modules/
	* build/
10. `git add .`
11. `git commit -m "your message here"`

##SETUP ROUND 2
1. brew update
2. brew install mongodb
3. Open a command line and head to your project
4. Create a `data` directory
5. Inside the data directory create a `db` directory
6. add `data/db/` to your .gitignore file