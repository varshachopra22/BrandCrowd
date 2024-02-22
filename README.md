# BrandCrowd
BrandCrowd Tech challenge

BrandCrowd Automation Framework consists of Page Object Model framework. 
The Pages 'CreateNewDesignPage.java' and 'Home.java' are pages that have been automated. 
'CreateNewDesignPage.java' has all the locators and WebElements. 
That way they just need to be declared once and can be reused in different classes that inherit them. 
Also it makes it more manageable if there happens to be be any new locators to be added or any changes 
there just needs to be updated in this place.

'Home.java' is the login page that has been automated. It contains the username and password in readable 
form which is a security breach. However that can be stored as xml or in json form at a later stage of development. 

'SmokeTest' package can have many other Smoke tests for different Web pages of the website brandcrowd.com. 
I have just automated and checked a couple of elements of CreateNewDesignSmokeTest for this task as an example.

The 'Tests' package can have the critical functionality tests automated. I have automated the Search functionality 
of 'Create New Design page'. I have automated the happy path for now but other form of texts can be included if 
the webpage is developed for any error conditions.

For Test reporting I have chosen TestNG as the results can also be viewed in HTML format in this location 
- BrandCrowd\test-output\index.html
