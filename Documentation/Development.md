# Development.md
## Tech Stack
Puma is a Web application using: 
* Javascript(es6) and React framework (16.12.0) frontend
* C# asp.net core (2.1 backend
* Local hosting
* MVC architecture (per asp.net core)

## Development Environment
* NPM: https://www.npmjs.com/ **OR** Yarn: https://yarnpkg.com/lang/en/
* Jetbrains Rider 2019.2.2: https://www.jetbrains.com/rider/

## Folder Structure
In the project folder, there are 4 main folders: 
* Client App 
	* Code for view layer of the application
	* Includes miscellanea such as icons and other visual resources
	* Main React App & composite components in separate folder
	* Jest tests are included alongside the associated components
	* Package.json file
		* Lists javascript dependencies required to be installed in order for the project to run correctly
* Controllers
	* Simple Web API PumaController.cs
		* Interfaces between the view and the model
* DataStructure
	* C# objects corresponding to relevant JSON structures
	* Folder Nesting represents Object nesting in JSON
* Model
	* Code for interfacing with Cheetah software
		* HttpRequests
		* Parsing Cheetah JSON Response
		
## Running the project within the development enviornment

1. The first thing you will notice is an installation for our dependancies. Please make sure to run the 'npm install' that will appear in the bottom right of the IDE.

2. Once the dependencies are installed you can begin to explore the folder structure on the left side of the project. Make sure to go into the CS495-Capstone-Puma C# project folder, inside of here you will find our front and backends. The front end is placed in the ClientApp folder and the back end occupies the other folders.

3. In order to run our project properly you will need to setup a launch settings file, start by adding a new directory to the root of the C# project and naming it "Properties". 
It should look like this 
![](Documentation/images/directory.png)
