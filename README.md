
# I have created Mavan project in JAVA with pom.xml file
Steps to execute the test case are below
 1. Download this repositary zip file and unzip it and open in JAVA eclips
 2. Navigate to below path
 deckofcards.zip\deckofcards\src\test\java\com\col\dof\presentation\deck.java
 3. Right click on the eclips tool and select option as run as "testNG" test
 
 Above test case will validate following test steps
 * Validated the creation of deck through GET API- https://deckofcardsapi.com/api/deck/new
 * Validated response of above API with status code is 200 
 * Validated the "deck_id" should not be null and "remaining" value should be 54(As we created new deck by addding parameters as "jokers_enabled=true"
 * Validated the drawing of cards through GET API https://deckofcardsapi.com/api/deck/<<deck_id>>/draw
 * Validated response of above API with status code is 200 and "remaining" value should be 53"
 
 
 
 
