# JSonAPITest
This test is for  Json API that have a get method. With the following Criteria:
API = https://api.tmsandbox.co.nz/v1/Categories/6327/Details.json?catalogue=false

Acceptance Criteria:

Name = "Carbon credits"
CanRelist = true
The Promotions element with Name = "Gallery" has a Description that contains the text "2x larger image"

Created 12 test just testing the Acceptance criteria provided.
Technology used:
C# , Visual studio 2015 using the following reference: Restsharp,Shouldly,Nunit etc.
I just put it in a single project but in reality it should be separated.
I created a base where every code needed for base and support file is located.
I separate the test file and only test file are present for clean code.
I also created a property files as container for the API Json call items and Test item for clean
and single call of the expected and actual data.
I put it in a list collection for single call for the test.
I didnt put all the item in the jSon data in the property cause not all of them are used in the test criteria.
I just added a few just to show that it can be added and in future use and validation.
