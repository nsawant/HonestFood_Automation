# HonestFood_Automation
Project contains automation assignment


Project contains Manual test cases for Search functionality and Selenium automation scripts (Considering time Only some TCs are covered) 

Manual Test cases: Test cases are created for search operation (Not all) edge cases including Search with valid and invalid inputs. Search from pagination and from input textbox

Automation: 6 Test cases are automated which includes 
1. Search after login 
2. Search without login
3. Search with empty string
4. Search with 250+ chars
5. Search Delete button


In Order to execute the scripts please follow the below steps: (To run the project Eclipse is mandatory - along with eclipse TestNG the Selenium libraries should be imported in project also relevant verion of chromedirever and geckodriver should be downloaded (64 or 32 bit as per computer configuration)

    Import the attached project in Eclipse.
    Open the Project and go the the path com.utils(package) => BaseClass.java
    Open the BaseClass.java file and change the value of pathtoChromedirver and pathtoFirefoxdirver with path of chrome driver and gecko driver file location
    Right click on testNG.xml file and Select the option Run as TestNg Suite
    Check the results.

Repository contatins:

    Manaul Test cases
    Automation Scripts for below test cases: 1.DeleteSearchString, 2. SearchSuggetion, 3. LongString, 4. EmptySearch, 
    5. SearchWithoutLogin, 6. LoginAndSearch
    Executed Results (TestNG HTML format) and Execution Screenshots

NOTE:

    Reference of the manual test cases and Automation scripts is mentioned in Project only for one TestCase (DeleteSearchString)   (Screenshot for the same has been attached)

    Step level pre-requisite is only defined for first test cases (Create_Computer_Valid_01)

