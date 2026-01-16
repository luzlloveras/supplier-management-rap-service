## Application Details
|               |
| ------------- |
|**Generation Date and Time**<br>Mon Jul 10 2023 19:22:16 GMT+0000 (Coordinated Universal Time)|
|**App Generator**<br>@sap/generator-fiori-elements|
|**App Generator Version**<br>1.10.1|
|**Generation Platform**<br>SAP Business Application Studio|
|**Template Used**<br>List Report Page V2|
|**Service Type**<br>SAP System (ABAP On Premise)|
|**Service URL**<br>http://localhost:8080/sap/opu/odata/sap/ZMARA_SERVICE_BINDING
|**Module Name**<br>material_by_supplier|
|**Application Title**<br>Supplier Management|
|**Namespace**<br>|
|**UI5 Theme**<br>sap_horizon|
|**UI5 Version**<br>1.111.5|
|**Enable Code Assist Libraries**<br>False|
|**Enable TypeScript**<br>False|
|**Add Eslint configuration**<br>False|
|**Main Entity**<br>MatProv|
|**Navigation Entity**<br>None|

## material_by_supplier

A compact Fiori application for supplier lifecycle management.

## What this service demonstrates
- RAP BO modeling
- Status lifecycle with custom actions
- Minimal business validations

### Starting the generated app

-   This app runs locally with mock data by default. To launch it, run the following from the app root folder:

```
    npm start
```

- If you want the explicit mock command, run:
```
    npm run start-mock
```

Example action call (mock server):
```
    curl -X POST "http://localhost:8080/sap/opu/odata/sap/ZMARA_SERVICE_BINDING/Provedor('SUP-1000')/approveSupplier"
```

#### Pre-requisites:

1. Active NodeJS LTS (Long Term Support) version and associated supported NPM version.  (See https://nodejs.org)


