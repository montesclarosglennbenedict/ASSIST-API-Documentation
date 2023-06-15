# Agreements

Agreement articulation list from an institution to an institution.

## Example Agreements Object

```js
{
  "reports": [
    {
      "label": "Anthropology B.A, Archaeology Concentration",
      "key": 26638929,
      "ownerInstitutionId": 0
    },
    {
      "label": "Anthropology B.A, General Concentration",
      "key": 26638930,
      "ownerInstitutionId": 0
    }
  ]
}
```

> **GET** /api/agreements

## Request Parameters

| Parameter | Type | Description |
| ----------- | ----------- | ----------- |
| receivingInstitutionId | integer | The value of the receiving (to) institution ID. |
| sendingInstitutionId | integer | The value of the sending (from) institution ID. |
| academicYearId | integer | The value of the academic year ID. |
| categoryCode | string | The category that the data is being organized by. | 