Following tests are part of API certification:
- Valid URL test
- Configuration test (includes; API Key, Search term, API Url)
- Test for API returned data (is it a valid JSON) - testValidJson 
- Tests returned count per configured / expected count
- Tests unique ids from response

APIs use:
- TestNG
- HttpClientApi
- Maven
- GSON 


---------------------------------
Instruction:
- Using eclipse
This is a mavenized project just open Eclipse

Test Results: 

testCount (10) 
  
testFeedHasData (true) 
testFeedUrl 
  
testResultCount (10) 
  
testSearchConfiguration 
testUniqueId 
 testValidJson 