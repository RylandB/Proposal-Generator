## Testing Requirements
Most functionality of Puma is reliant on having valid Cheetah login credentials. As such, testing is only possible in a limited capacity.
Certain tests can be run by downloading the source code and opening it in a C# IDE. Our development environment uses Jetbrains Rider.

##### All backend tests are contained within the CS495-Capstone-Puma.UnitTests Project

## Logic Testing
To run tests, open the IDE's Test Explorer. The tests currently existing in the code are as follows:
- TestLoadConfig 
  - Tests the proper initialization of Handler class
- TestPostAccessToken 
  - Tests Request formatting & response handling
- TestPostBadAccessToken 
  - Tests Request formatting & error handling

## Elevated Permissions Communication Testing
These tests can only be performed by someone with valid Cheetah Credentials. 
Without these credentials, the system will error.
Login and Password should be placed within the "login.json" file in the CS495-Capstone-Puma.UnitTests project.

- ElevatedTestPostAccessToken
  - Posts login credentials to Cheetah
  - Receives realtime response
- ElevatedTestPostAssets
  - Posts an asset to a Cheetah Account
  - Checks for success response
- ElevatedTestBadPostAssets
  - Attempts to post an empty list of assets
  - Checks for failure response
