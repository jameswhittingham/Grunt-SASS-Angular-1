Grunt SASS Angular 1 Boilerplate
=====================

Installation instructions
===============================

	1) Installing node
		a) Install Node from http://nodejs.org/
		b) Open Command Line and navigate to your projects directory
		c) Run the command "npm install" to install node at the projects level
	2) Installing bower
		a) Open Command Line and run the command "npm install -g bower"
	3) Installing grunt
		a) Open Command Line and run the command "npm install -g grunt-cli"
	4) Other installations that may be required
		a) Compass

Install Bower Packages
===============================

	1) Open Command Line and run the command "bower install" at your PROJECTs level
		a) Packages will be installed in teh directory specified in the .bowercc file
		b) Packages that will be installed can be viewed in the bower.json file

Grunt Tasks
===============================

	1) Run the following commands from Command Line at your PROJECTs level
		a) "grunt build" - will run the following tasks
			- Compile the .scss files into a main.css file
			- minifys the HTML
			- Copy the required files into a build folder for deployment
		b) "grunt" - will run the above tasks as well as the following
			- Runs a local server on port 9001 - navigate to http://localhost:9001 to view
			- Runs a watcher, to watch for changes in the .html and .scss files