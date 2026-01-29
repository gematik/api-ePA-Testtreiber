<img width="200" height="37" src="images/Gematik_Logo_Flag_With_Background.png" alt="Gematik Logo"/> <br/>

# Release notes epa-fdv testdriver api
## Release 3.1.3 Phase 1 includes Test Driver API version 4.2.5 and Farm Management API version 4.1.1
- Test Driver API version 4.2.5
  - fixed wrong content type

## Release 3.1.3 Phase 1 includes Test Driver API version 4.2.4 and Farm Management API version 4.1.1
- Test Driver API version 4.2.4
  - added deviceRegistrationStatus to LoginResponseDTO
  - corrected PostRegisterDeviceResponseDTO (missing required generell ResponseDTO)

## Release 3.1.3 Phase 1 includes Test Driver API version 4.2.3 and Farm Management API version 4.1.1
- Test Driver API version 4.2.3
  - marks endpoints '/epa/testdriver/api/v1/mhd*' as to be implemented first with 3.1.3 Phase 2
  - added repositoryUniqueId to the DocumentMetadata
- Farm Management API version 4.1.1
  - removes Kvnr from Device structure

## Release 3.1.3 includes Test Driver API version 4.2.2 and Farm Management API version 4.1.0
- corrects DocumentIdents structure (retrieveDocuments)

## Release 3.1.3 includes Test Driver API version 4.2.1 and Farm Management API version 4.1.0
- added endpoint for research data purposes ('researchdatapurposes')
- added data-submission to FunctionIdType
- added new query type 'FindDocumentsByComment'
- added new endpoint ('/epa/testdriver/api/v1/medication/render/eml/fhir') to trigger retrieval of eML as FHIR search bundle

## Release 3.1.3 includes Test Driver API version 4.2.0 and Farm Management API version 4.1.0
- corrects retrieveDocuments (repositoryUniqueId added)
- removes deprecated endpoints
- added endpoint to support fulltext and metadata based search of documents (MHD document references)
- added endpoint to retrieve documents referenced inside a document reference (MHD document references)

## Release 3.0.5 api Version 4.1.0 (no changes) Farm Management Version 1.1.1 (modified)
- adds property environment to device endpoint

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