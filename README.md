# FHIRFacade
FHIR Façade architecture in IRIS
1. Create a foundation namespace and activate it (Health-> Installer Wizard (at the top of the page)).
2. Import the FHIRFacade.xml file into the namespace and compile all the classes in it.
3. Create a FHIR endpoint (Health->FHIR Configuration->Server Configuration) and select the 'FHIRFacade.InteractionsStrategy' as your Interactions strategy class.
4. Start the production 'FHIRFacade.PROD.FoundationProduction'.
5. Use the postman collection to send various FHIR requests to the FHIR endpoint - make sure that the base URL points to the endpoint you have created.
