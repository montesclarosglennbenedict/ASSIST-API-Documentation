# Transferability/Categories

## Example Transferability/Categories Object

```js
[
  {
    "label": "Department",
    "code": "dept",
    "reportType": 0,
    "reportCategoryType": 0,
    "courseTransferItemType": 0,
    "hasReports": true
  },
  {
    "label": "Prefix",
    "code": "prefix",
    "reportType": 0,
    "reportCategoryType": 0,
    "courseTransferItemType": 0,
    "hasReports": true
  },
  {
    "label": "IGETC Area",
    "code": "igetcArea",
    "reportType": 0,
    "reportCategoryType": 0,
    "courseTransferItemType": 0,
    "hasReports": true
  }
]
```

> **GET** /api/transferability/categories

## Request Parameters

| Parameter | Type | Description |
| ----------- | ----------- | ----------- |
| institutionId | integer | The value of the sending (from) institution ID. |
| academicYearId | integer | The value of the academic year ID. |
| listType | string | The type of the list