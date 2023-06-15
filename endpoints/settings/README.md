# Settings

Settings for the ASSIST.org website.

## Example Settings Object

```js
{
  //The highest fall year that one can access for articulation agreements in ASSIST.org
  "maxAcademicFallYear": 2022,
  //The highest fall year that one can access under the "Search below for transferable courses" tab in ASSIST.org
  "maxTransferableAcademicFallYear": 2023,
  //The default fall year listed under the "Search below for transferable courses" tab in ASSIST.org
  "defaultTransferableAcademicFallYear": 2023,
  //The minimum fall year that one can access for articulation agreements in ASSIST.org
  "minAcademicFallYear": 1985,
  //The default fall year that one can access for articulation agreements in ASSIST.org
  "defaultAcademicFallYear": 2022,
  //The feedback URL to provide feedback for ASSIST.org
  "feedbackUrl": "https://ucop.questionpro.com/t/AU89IZuBip",
  //The version of the web application
  "appVersion": "assistng-public v1.46.6.0",
  //The minimum academic year value to be able to access the modernized articulation agreements
  "modernizationMinAcademicYearId": 121
}
```

> **GET** api/appsettings
