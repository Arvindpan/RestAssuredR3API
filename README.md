# RestAssuredR3API
Assignment for R3
This is testing and validation of USD exchange rate API for diffrent currencies using Rest assured and JAVA
Framework component:
  JAVA, ECLIPSE, TESTNG, CUCUMBER,MAVEN,EXTENT REPORT.
  
Scanerios covered:
      API call is successful and returns valid price.
     Check the status code and status retuned by the API response.
        o API could return multiple statuses like SUCCESS, FAILURE etc. Make sure this
          is catered for.
    Fetch the USD price against the AED and make sure the prices are in range on 3.6 – 3.7.
    Make sure API response time is not less then 3 seconds then current time in second.
        o Timestamp is returned in the API response.
    Verify that 162 currency pairs are retuned by the API.
    Make sure API response matches the Json schema.
        o Generate a schema from the API response.
