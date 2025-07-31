<img width="200" height="37" src="images/Gematik_Logo_Flag_With_Background.png" alt="Gematik Logo"/> <br/>

# Release notes epa-fdv testdriver api

## Release 3.1.3 api Version 4.2.0
- corrects retrieveDocuments (repositoryUniqueId added)
- removes deprecated endpoints
- added endpoint to support fulltext and metadata based search of documents (MHD document references)
- added endpoint to retrieve documents referenced inside a document reference (MHD document references)

## Release 3.0.5 api Version 4.1.0
- adds I_Test_Device_Farm_Management.yaml (new API for device farm management)
- no changes in I_Test_Driver_FdV.yaml

## Release 3.0.5 api Version 4.0.3
- fixes "required: - object" error (breaking error)

## Release candidate 3.0.5 api Version 4.0.2
- bugfix: ensures unique operationIds
- contains merge published epa3.1 VZD updates
- contains merge published epa3.1 endpoints for EU access

## Release candidate 3.0.5 api Version 4.0.1
- adds /epa/testdriver/api/v1/UserSpecificMedicationDenyList

## Release candidate 3.0.5 api Version 4.0.0
- new endpoint for retrieve document list 
- new endpoint for delete document metadata (compare ANFPSE-2834)
- operations to trigger document service with technical object selectors only