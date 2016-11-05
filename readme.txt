1. create a module (npmdemo.rong) and publish to npm server
	(1) to see if your module name is avaliable 
		npm view npmdemo.rong
	(2) create a git repo and clone the empty project to local
	(3) in your local, initiate npm package.json
		npm init
	(4) creaet you module code (module.exports) and test(require('./index.js'))
	(5) push to git repo

	(6) npm adduser
	(7) npm version 0.0.1
	(8) npm publish
	Done!

2. import the module and use it
	(1) in an other folder, import the npm module
		npm install npmdemo.rong
	(2) create a test js file in order to use the module
		var func = require('npmdemo.rong');
		func.add(1,4);
	Done!