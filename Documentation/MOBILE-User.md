# User Documentation

This is the section of the documentation that explains the current functionality of Puma Mobile, and how to use it.

## There are 3 main functions of the mobile app:

  1. Logging In
  2. Adding Assets to Portfolio
  3. Retrieving Results/Trade Recommendations
  
These functions can be navigated between the screens through the bottom bar

### 1. Logging In

Puma Mobile starts up with the login screen as the first screen. You must use the Accutech login credentials, 
either yours or some provided to you. Enter the username in the first field and the password in the second.
Once you have filled out the forms, hit the sign in button below both of the fields.

If you have entered your credentials correctly, the credentials are valid, and Puma Mobile is connected to a Puma backend server,
then after a short delay the application will automatically switch to the Asset Input screen.
If the login failed, then the and error will display above the sign in button and no transition will take place.\

**PLEASE NOTE**
You must login to be able to submit a portfolio. All other functionality can be completed without loggin in.

**ALSO**
A successful login will grant you 60 minutes of time before it expires, after which it is as if you have not logged in.
To refresh your access time, simply login in with the correct credentials again. 
You can navigate back to the login screen through the bottom bar to do this.

### 2. Adding Assets to the Protfolio

Puma Mobile also allows for the adding of assets though the Asset Input Screen. There are 5 fields, "Asset Code," "Symbol," "Issue," "Issuer,"
and "Units." Assets will need either an asset code and a symbol, or an issue and issuer, depending on the asset type. 
All entered assets will need a units values, aka the quantity of this asset.

As you fill out your portfolio, you can check on what you have added thus far by navigating to the Portfolio Screen through the bottom bar.
Here you will find a table containing all the assets you have added to the portfolio, and their constituent field values.

### 3. Retrieving Results/Trade Recommendations

Lastly, Puma Mobile allows for the retrieval of recommendations after you have completed your portfolio. Once you are done with making
your portfolio, you must then navigate to the results screen using the bottom bar and hit the submit portfolio button. If you are
connected to the Puma backend, your login session has not expired, and you have added at least one asset to your protfolio, the 
portfolio will be sent to the backend for review. 

After ~20 seconds the response will be received and will be displayed on the results page.
The response will take the form of 2 numbers, net worth increase and monthly income increase, and a table displaying the trades that the system recommends
take place in the portfolio.
