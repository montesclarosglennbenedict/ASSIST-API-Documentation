# Agreements

Agreement articulation list from an institution to an institution. Format differs for Next Gen/Legacy and MOD articulation agreements.

## Example Agreements Object (MOD)

```js
{
  "reports": [
    {
      "label": "European Languages and Transcultural Studies with German/B.A.",
      "key": "74/140/to/117/Major/11f80810-575c-4100-8fdf-4ae93667636b",
      "ownerInstitutionId": 117
    },
    {
      "label": "Linguistics and Computer Science/B.A.",
      "key": "74/140/to/117/Major/d1a0f785-6aa5-4b20-8551-461045892ec4",
      "ownerInstitutionId": 117
    }
  ]
}
```

## Example Agreements Object (Next Gen, Legacy)

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