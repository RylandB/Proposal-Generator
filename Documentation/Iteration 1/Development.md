Development

Puma is a Web application using: 
	Javascript(es6) and React framework (16.12.0) for the frontend.
	C# asp.net core (2.1) for the backend.
	Locally hosted

As with asp.net core we are using an MVC architecture.

To replicate our development envvironment you'll need:
NPM: https://www.npmjs.com/
OR Yarn: https://yarnpkg.com/lang/en/
Jetbrains Rider 2019.2.2: https://www.jetbrains.com/rider/

Folder Structure:
In the project folder There are 4 main folders: Client App, Controllers, DataStructure, and Model.

ClientApp contains all of the code for the view layer of the application. This includes miscellanea such as icons and other visual resources.
As well as the main React App and its composite compoenents in their own separate folder. Front end Jest tests are also included alongside the components they test.
Lastly ClientApp Contains the package.json file, containing all of the javascript dependencies required to be installed in order for the project to run correctly.

Controllers Contains the simple Web API that interfaces between the view and the model, Using PumaController.cs

DataStructure Contains all of the requisite class that the model and the controller need to bind and maipulate data both from Cheetah and the View.
These include the all of the personal details of the client, as well as the format for various types of assets and the data that composes them.

Lastly, the Model contains all code actually interacting directly with the Cheetah software. This includes making the http request to and from the Cheetah software, and sending that data back to the Controller.