# Agreements/Categories

Information on the availability of different categories of articulation agreements.

## Example Agreements/Categories Object

```js
{
  "listType": 0,
  "institutionName": "College of the Canyons",
  "academicYear": {
    "id": 74,
    "description": "2023-2024",
    "code": "2023-2024",
    "beginDate": "2023-10-01T00:00:00",
    "endDate": "2024-10-01T00:00:00",
    "isOpenForMaintenance": true,
    "isOpenForPublic": true,
    "isOpenForReporting": true
  },
  "courseInformationList": [
    {
      "footnoteParentIds": [],
      "prefixParentId": 1319,
      "prefixCode": "ECON",
      "prefixDescription": "Economics",
      "departmentName": "Economics",
      "courseIdentifierParentId": 204907,
      "courseNumber": "170",
      "courseTitle": "Economic History of the U.S.",
      "courseParentId": 142096,
      "isCsuTransferable": true,
      "minUnits": {
        "value": "3.00n",
        "type": "Big Number"
      },
      "maxUnits": {
        "value": "3.00n",
        "type": "Big Number"
      },
      "beginDate": "1995-10-01T00:00:00",
      "beginTermCode": "F1995",
      "endDate": "2070-10-01T00:00:00",
      "endTermCode": "",
      "transferAreas": [
        {
          "areaType": 4,
          "areaParentId": 0,
          "code": "C2",
          "codeDescription": " Humanities: (Literature, Philosophy, Languages Other than English)",
          "courseIdentifierParentId": 204907,
          "beginDate": "1991-10-01T00:00:00",
          "beginTermCode": "F1991",
          "endDate": "2070-10-01T00:00:00",
          "endTermCode": "",
          "name": "CSU GE"
        },
        {
          "areaType": 4,
          "areaParentId": 0,
          "code": "D6",
          "codeDescription": " History",
          "courseIdentifierParentId": 204907,
          "beginDate": "1950-10-01T00:00:00",
          "beginTermCode": "",
          "endDate": "2070-10-01T00:00:00",
          "endTermCode": "",
          "name": "CSU GE"
        },
        {
          "areaType": 3,
          "areaParentId": 0,
          "code": "3B",
          "codeDescription": " Humanities",
          "courseIdentifierParentId": 204907,
          "beginDate": "1991-10-01T00:00:00",
          "beginTermCode": "F1991",
          "endDate": "2070-10-01T00:00:00",
          "endTermCode": "",
          "name": "IGETC"
        },
        {
          "areaType": 3,
          "areaParentId": 0,
          "code": "4F",
          "codeDescription": " History",
          "courseIdentifierParentId": 204907,
          "beginDate": "1991-10-01T00:00:00",
          "beginTermCode": "F1991",
          "endDate": "2070-10-01T00:00:00",
          "endTermCode": "",
          "name": "IGETC"
        }
      ],
      "isRepeatable": false,
      "identifier": "ECON 170",
      "notations": [
        {
          "displayText": "IGETC: 3B, 4F; CSU GE: C2, D6",
          "eventDate": "0001-01-01T00:00:00",
          "eventTerm": "W1",
          "positionNumber": 0
        }
      ]
    }
  ]
}
```

> **GET** /api/transferability/courses

## Request Parameters

| Parameter | Type | Description |
| ----------- | ----------- | ----------- |
| institutionId | integer | The value of the sending (from) institution ID. |
| academicYearId | integer | The value of the academic year ID. |
| listType | string | The type of the transferability list (all caps). |