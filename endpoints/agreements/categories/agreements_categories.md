# Agreements/Categories

Information on the availability of different categories of articulation agreements.

## Example Agreements/Categories Object

```js
[
  {
    "label": "Major",
    "code": "major",
    "reportType": 3,
    "reportCategoryType": 0,
    "courseTransferItemType": 0,
    "hasReports": true
  },
  {
    "label": "Department",
    "code": "dept",
    "reportType": 2,
    "reportCategoryType": 0,
    "courseTransferItemType": 0,
    "hasReports": true
  },
  {
    "label": "Prefix",
    "code": "prefix",
    "reportType": 10,
    "reportCategoryType": 0,
    "courseTransferItemType": 0,
    "hasReports": true
  },
  {
    "label": "General Education / Breadth",
    "code": "breadth",
    "reportType": 1,
    "reportCategoryType": 0,
    "courseTransferItemType": 0,
    "hasReports": false
  }
]
```

> **GET** /api/agreements/categories

## Request Parameters

| Parameter | Type | Description |
| ----------- | ----------- | ----------- |
| receivingInstitutionId | integer | The value of the receiving (to) institution ID. |
| sendingInstitutionId | integer | The value of the sending (from) institution ID. |
| academicYearId | integer | The value of the academic year ID. |