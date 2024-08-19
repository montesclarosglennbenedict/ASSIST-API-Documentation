# Institutions

Institution list for the ASSIST.org website.

## Example Institutions Object

```js
[
  {
    "id": 1,
    "names": [
      {
        "name": "California Maritime Academy",
        "hasDepartments": true,
        "hideInList": false
      },
      {
        "name": "California State University, Maritime Academy",
        "fromYear": 2015,
        "hasDepartments": true,
        "hideInList": false
      }
    ],
    "code": "CSUMA   ",
    "prefers2016LegacyReport": false,
    "isCommunityCollege": false,
    "category": 0,
    "termType": 0,
    "beginId": 31,
    "termTypeAcademicYears": [
      {
        "termType": 0,
        "fromYear": 2015
      },
      {
        "termType": 0,
        "fromYear": 1980
      }
    ]
  },
  {
    "id": 2,
    "names": [
      {
        "name": "Evergreen Valley College",
        "hasDepartments": true,
        "hideInList": false
      }
    ],
    "code": "EVERGRN ",
    "prefers2016LegacyReport": false,
    "isCommunityCollege": true,
    "category": 2,
    "termType": 0,
    "beginId": 31,
    "termTypeAcademicYears": [
      {
        "termType": 0,
        "fromYear": 2016
      },
      {
        "termType": 0,
        "fromYear": 1980
      }
    ]
  }
]```

> **GET** api/institutions