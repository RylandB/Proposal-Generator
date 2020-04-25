# Deployment

## **Prerequisites**
- [Node.js](https://nodejs.org/en/download/)
  - make sure to use LTS, and to download the 64 bit windows msi file
  
- [.NET Core version 3.0](https://dotnet.microsoft.com/download)
  - make sure to download the SDK as it comes with a built in runtime, this makes it easier on you to install

- [Python 2.7+](https://www.python.org/)
    
 Once these are downloaded and installed you can head over to our source code reposity and grab our [latest release](https://github.com/japperales/CS495-Capstone-Puma/releases)

 
 ## **Running our software**
 
1. You will recieve a .zip archive that you need to extract inside will have our puma version 5
 
2. After this there will need to be an update run on one of the JSON files. By default the configuration file should have the Cheetah QA address set. In order to get an API key you will need to reach out to one of the group members for it as it is private. There is further contact information on the User.md file.

3. run CS495-Capstone-Puma.exe

4. run PythonMiddleman.py

5. Upon Running these for the first time you may encounter the Windows 10 untrusted publisher screen, click on more info and run anyway to get around this

6. Once running properly you'll have a command prompt telling you which port the project is running on, select and copy the port like this 'https://localhost:5001' paste it into your browser and run, at this point the browser may warn you of a security risk, click on advanced, and go anyway. 
