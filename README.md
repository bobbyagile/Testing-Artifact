# Testing-Artifact
API Testing - Template using BDD and combinations 

Scenario: Create a New Customer and validate the response  ( Positive test ) 
Given I onboard a customer 
When I create a customer 
Then I get a code response 200
Than I can see the customer Id and Validate the body



