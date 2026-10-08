
Odata is open data protocol.
In stateless state, no information regarding response is saved on the server.

TCode: SEGW ( SAP Gateway Service Builder ) -> Create a Project
TCode: /n/IWFND/MAINT_SERVICE ( Activate and Maintain OData Service ) -> Work with OData

Create New Project 
![New Project Icon](assets/CreateNewProjectIcon.png)

Create New Project Details
![New Project Details](assets/CreateNewProjectDetailSection.png)

Create Entity Type
![Creating Entity Type In Data Model](assets/CreatingEntitySetinDataModel.png)

Create Entity Type with Default Entity Set
If the checkbox for "Create Default Entity Set" is checked then it automatically created a Entity Set with same structure
![Create Entity Type with Default Set](assets/CreatingEntityTypeWithCheckedSet.png)

Generate Runtime Artifact
![Generate Runtime Artifact](assets/GenerateRuntimeArtifact.png)
Generate Runtime Artifact in Transport
![Generate Runtime Artifact in Transport](assets/GenerateRuntimeArtifactTransport.png)
Runtime Artifact MPC and DPC Creation
![Generate Runtime Artifact with MPC and DPC Creation](assets/RuntimeArtifactMPC-DPCCreation.png)

Register and Activate Service In OData
![Add Service](assets/AddServiceofOData.png)
![Service Creation Fetch Service](assets/ServiceCreationFetchService.png)
![Service Creation Service Fetched](assets/ServiceCreationServiceFetched.png)
![Service Creation Add Selected Service](assets/ServiceAddSelectedService.png)
![Add Service Selection Package Add](assets/AddServicePackageSelection.png)
![The Service is present in IWFND/MAINT_SERVICE](assets/MaintainAndActivateServicecataloguePresence.png)
![Open SAP Gateway Client after Activating Service](assets/SAPGatewayClientAfterServiceActivation.png)
![SAP Client Gateway Screen to Test OData Service TCode: /n/IWFND/GW_CLIENT](assets/SAPClientGatewayScreen.png)

If status code is 5** then it is an error from server side
If staus code is 4** then it is an error from frontend side
We get Status code 2** then it is generally a success.

Implement Header Entity Type and Set ( More like Unmanaged Implementation)
We also do it in DPC Extension
![Inititate Implementation of Entity Set](assets/InitiateImplementationofEntitySet.png)
![Right Click and then Select ABAP workbench](assets/SecondSteptoInititateImplementation.png)
![Click the checkbox to Open Class Page for Implementation](assets/ImplementationABAPWOrkbenchCheckArrow.png)
![Redefine the method to start the implementation - We do this to fetch from superclass](assets/RedefineMethodToInitiateImplementation.png)
After Redefine Activate the class.
![Write the code in the method to fetch the record](assets/PostRedefineSampleCodetofetchRecord.png)
![The sample code to fetch the record and read it based on the key](assets/ReadTableImplementationSample.png)
![Use the filter option to fetch the records](assets/FIlterOptionToPreviewFields.png)
![Sample to update a record](assets/UpdateSampleCode.png)
![Do this when you are adding new Entity Sets](assets/LoadMetadata.png)
![Do this when you want to update the record](assets/Tofetchdataforthepayload.png)
![We can also update the records with Json Format](assets/JSONPayloadUpdate.png)

TCode: /N/IWBEP/REG_SERVICE to register, maintain, and activate OData services in the backend system for the SAP NetWeaver Gateway  
TCode: /IWBEP/CACHE_CLEANUP: Clears the backend OData cache. Run this if you changed your Data Provider Class (DPC) or Model Provider Class (MPC). -> For Backend
TCode: /IWFND/CACHE_CLEANUP: Clears the Gateway Hub cache. Essential after updating system aliases or service registrations. -> For Frontend

![Sample Code to show error error in Gateway](assets/SampleCodeForError.png)
We can't POST data without CRSF token. Execute GET will retrieve it for us.

![Mapping Data Source to get entity](assets/MappingDataSourceToReadEntity.png)
![Use these Tcodes to check the performance at Frontend and Backend Level](assets/ToAnalyseOdataPerformance.png)
![To Implement Function Import Operation](assets/FunctionImportOperation.png)
![Mappings for Media Content require MPC changes](assets/MappingForMediaContent.png)

After Get Header Set in post there should be always two spaces.

For CDS based Odata, we use SEGL

![Error Handling could be done using this interface](assets/ErrorHandling.png)