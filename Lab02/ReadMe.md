# Lab02-Work-with-Microsoft-Graph-lab-instructions

# Exercise 1: Using query parameters when querying Microsoft Graph via HTTP

## Task 1: Go to the Graph Explorer

![020101](evidenciasFotos/020101.PNG)

## Task 2: Use $select to retrieve only some object properties

![020102](evidenciasFotos/020102.PNG)

![020103](evidenciasFotos/020103.PNG)

![020104](evidenciasFotos/020104.PNG)

## Task 3: Use $orderby to sort results

![020105](evidenciasFotos/020105.PNG)

![020106](evidenciasFotos/020106.PNG)

## Task 4: Use $filter to retrieve a subset of data available

![020107](evidenciasFotos/020107.PNG)

![020108](evidenciasFotos/020108.PNG)

![020109](evidenciasFotos/020109.PNG)

![020110](evidenciasFotos/020110.PNG)

![020111](evidenciasFotos/020111.PNG)

## Task 5: Use $skip and $top for explicit pagination of results

![020112](evidenciasFotos/020112.PNG)

![020113](evidenciasFotos/020113.PNG)

![020114](evidenciasFotos/020114.PNG)

## Task 6: Expand and retrieve resources using $expand query parameter

![020115](evidenciasFotos/020115.PNG)

![020116](evidenciasFotos/020116.PNG)

![020117](evidenciasFotos/020117.PNG)

## Task 7: Use $count to discover the total number of matching resources

![020118](evidenciasFotos/020118.PNG)

![020119](evidenciasFotos/020119.PNG)

## Task 8: Use $search to discover the total number of matching resources

![020120](evidenciasFotos/020120.PNG)

![020121](evidenciasFotos/020121.PNG)

# Exercise 2: Retrieve and control information returned from Microsoft Graph

## Task 1: Create an Azure AD application

![020201](evidenciasFotos/020201.PNG)

![020202](evidenciasFotos/020202.PNG)

![020203](evidenciasFotos/020203.PNG)

![020204](evidenciasFotos/020204.PNG)

![020205](evidenciasFotos/020205.PNG)

![020206](evidenciasFotos/020206.PNG)

![020207](evidenciasFotos/020207.PNG)

![020208](evidenciasFotos/020208.PNG)

![020209](evidenciasFotos/020209.PNG)

## Task 2: Create .NET Core console application

![020210](evidenciasFotos/020210.PNG)

![020211](evidenciasFotos/020211.PNG)

![020212](evidenciasFotos/020212.PNG)

## Task 3: Update the console app to support Azure AD authentication

![020213](evidenciasFotos/020213.PNG)

## Task 4: Create helper classes

![020214](evidenciasFotos/020214.PNG)

![020215](evidenciasFotos/020215.PNG)

## Task 5: Incorporate Microsoft Graph into the console app

![020216](evidenciasFotos/020216.PNG)

![020217](evidenciasFotos/020217.PNG)

![020218](evidenciasFotos/020218.PNG)

![020219](evidenciasFotos/020219.PNG)

## Task 6: Build and test the application

![020220](evidenciasFotos/020220.PNG)

## Task 7: Edit the application to optimize the query

![020221](evidenciasFotos/020221.PNG)

![020222](evidenciasFotos/020222.PNG)

![020223](evidenciasFotos/020223.PNG)

![020224](evidenciasFotos/020224.PNG)

![020225](evidenciasFotos/020225.PNG)

![020226](evidenciasFotos/020226.PNG)

![020227](evidenciasFotos/020227.PNG)

# Exercise 3: Using change notifications and track changes with Microsoft Graph

## Task 1: Create a new Azure AD web application

![020301](evidenciasFotos/020301.PNG)

![020302](evidenciasFotos/020302.PNG)

![020303](evidenciasFotos/020303.PNG)

![020304](evidenciasFotos/020304.PNG)

![020305](evidenciasFotos/020305.PNG)

## Task 2: Create .NET Core App

![020306](evidenciasFotos/020306.PNG)

### Create .NET Core WebApi App

![020307](evidenciasFotos/020307.PNG)

![020308](evidenciasFotos/020308.PNG)

## Task 3: Code the HTTP API

### Add model classes

![020309](evidenciasFotos/020309.PNG)

![020310](evidenciasFotos/020310.PNG)

![020311](evidenciasFotos/020311.PNG)

![020312](evidenciasFotos/020312.PNG)

![020313](evidenciasFotos/020313.PNG)

### Add notification controller

![020314](evidenciasFotos/020314.PNG)

## Task 4: Run the application

![020315](evidenciasFotos/020315.PNG)



*****

****
***
***
***
***
***********************************************************

# Exercise 4: Reduce traffic with batched requests

## Task 1: Sign in to Microsoft Graph Explorer


![020401](evidenciasFotos/020401.PNG)


## Task 2: Submit three (3) GET requests in a single batch

![020402](evidenciasFotos/020402.PNG)


## Task 3: Combine POST and GET requests in a single batch request

![020403](evidenciasFotos/020403.PNG)



# Exercise 5: Understand throttling in Microsoft Graph

## Task 1: Create an Azure AD application

![020501](evidenciasFotos/020501.PNG)

![020502](evidenciasFotos/020502.PNG)

![020503](evidenciasFotos/020503.PNG)

## Task 2: Grant Azure AD application permissions to Microsoft Graph

![020504](evidenciasFotos/020504.PNG)

![020505](evidenciasFotos/020505.PNG)

## Task 3: Create .NET Core console application

![020506](evidenciasFotos/020506.PNG)

## Task 4: Update the console app to support Azure AD authentication


![020507](evidenciasFotos/020507.PNG)

## Task 5: Create authentication helper classes

![020508](evidenciasFotos/020508.PNG)

## Task 6: Incorporate Microsoft Graph into the console app

![020509](evidenciasFotos/020509.PNG)

![020510](evidenciasFotos/020510.PNG)

![020511](evidenciasFotos/020511.PNG)

![020512](evidenciasFotos/020512.PNG)

## Task 7: Build and test the application

![020513](evidenciasFotos/020513.PNG)

Add helper class to deserialize the message object returned in a REST request
Add method to implement delayed retry strategy when requests are throttled

![020514](evidenciasFotos/020514.PNG)

Update application to use retry strategy

![020515](evidenciasFotos/020515.PNG)




## Task 8: Implement Microsoft Graph SDK for throttling retry strategy

Update the GetAuthenticatedHttpClient method

Update the GetMessageDetail method to return


## Task 9: Build and test the updated application


![020516](evidenciasFotos/020516.PNG)


# Exercise 6: Querying user data from Microsoft Graph

## Task 1: Go to the Graph Explorer

## Task 2: Get the signed in user's profile

![020601](evidenciasFotos/020601.PNG)

## Task 3: Get a list of users in the organization


![020602](evidenciasFotos/020602.PNG)

## Task 4: Get the user object based on the user’s unique identifier


![020603](evidenciasFotos/020603.PNG)