# Get job by dataset

```
curl  -X GET \
  'https://analytics.adobe.io/api/asctes9/classifications/job/byDataset/62e2ecdf813be76dff0020d9?page=0&size=10' \
  --header 'Accept: */*' \
  --header 'User-Agent: Thunder Client (https://www.thunderclient.com)' \
  --header 'x-api-key: b93e0c9c7d59494db4c7623c4469565e' \
  --header 'Authorization: Bearer <token>'
```


```
{
  "content": [
    {
      "datasetId": "62e2ecdf813be76dff0020d9",
      "history": [
        {
          "timestamp": "2024-04-04 21:15:14",
          "jobState": "created",
          "message": "Created import job via API"
        },
        {
          "timestamp": "2024-04-04 21:15:14",
          "jobState": "queued",
          "message": "Job queued and ready for processing."
        },
        {
          "timestamp": "2024-04-04 21:15:14",
          "jobState": "processing",
          "message": "Started processing"
        },
        {
          "timestamp": "2024-04-04 21:15:15",
          "jobState": "completed",
          "message": "Successfully imported 5/5 records."
        }
      ],
      "imsOrgId": "1BC13D035792A0A27F000101@AdobeOrg",
      "jobOptions": {
        "dataFormat": "tsv",
        "encoding": "utf8",
        "listDelimiter": ",",
        "keyOptions": {
          "byte_length": 255,
          "type": "string",
          "overwrite": true
        }
      },
      "jobId": "5cd1e9c9-de84-4cf4-8e67-6f5a6d2ec186",
      "jobSize": 384,
      "name": "SAINT Import for phpVUNxEV",
      "setName": "asctestor.sparta.1 evar11 classifications",
      "state": "completed",
      "totalLines": 5,
      "noeffectLines": 0,
      "type": "import"
    },
    {
      "datasetId": "62e2ecdf813be76dff0020d9",
      "history": [
        {
          "timestamp": "2024-04-04 21:14:56",
          "jobState": "created",
          "message": "Created import job via API"
        },
        {
          "timestamp": "2024-04-04 21:14:56",
          "jobState": "queued",
          "message": "Job queued and ready for processing."
        },
        {
          "timestamp": "2024-04-04 21:14:57",
          "jobState": "processing",
          "message": "Started processing"
        },
        {
          "timestamp": "2024-04-04 21:14:58",
          "jobState": "completed",
          "message": "Successfully imported 5/5 records."
        }
      ],
      "imsOrgId": "1BC13D035792A0A27F000101@AdobeOrg",
      "jobOptions": {
        "dataFormat": "tsv",
        "encoding": "utf8",
        "listDelimiter": ",",
        "keyOptions": {
          "byte_length": 255,
          "type": "string",
          "overwrite": true
        }
      },
      "jobId": "0f37093f-d2a0-46b6-b2b6-e58316970808",
      "jobSize": 383,
      "name": "SAINT Import for phpaahhNJ",
      "setName": "asctestor.sparta.1 evar11 classifications",
      "state": "completed",
      "totalLines": 5,
      "noeffectLines": 0,
      "type": "import"
    },
    {
      "datasetId": "62e2ecdf813be76dff0020d9",
      "history": [
        {
          "timestamp": "2024-04-04 21:13:41",
          "jobState": "created",
          "message": "Created export job via API"
        },
        {
          "timestamp": "2024-04-04 21:13:41",
          "jobState": "queued",
          "message": "Job queued and ready for processing."
        },
        {
          "timestamp": "2024-04-04 21:13:41",
          "jobState": "processing",
          "message": "Started processing"
        },
        {
          "timestamp": "2024-04-04 21:13:41",
          "jobState": "completed",
          "message": "Successfully exported 0/0 records."
        }
      ],
      "imsOrgId": "1BC13D035792A0A27F000101@AdobeOrg",
      "jobOptions": {
        "dataFormat": "tsv",
        "encoding": "utf8",
        "listDelimiter": ",",
        "rowLimit": 0,
        "offset": 0,
        "dateFilterStart": "2000-01-01T00:00:00Z",
        "dateFilterEnd": "2000-01-31T23:59:59Z"
      },
      "jobId": "0ede459b-9e30-4ccb-801a-57f47fa6fe6e",
      "jobSize": 231,
      "name": "SAINT Export ",
      "setName": "asctestor.sparta.1 evar11 classifications",
      "state": "completed",
      "totalLines": 0,
      "noeffectLines": null,
      "type": "export"
    }
  ],
  "page": 0,
  "size": 10,
  "totalPages": 1,
  "totalElements": 3,
  "numberOfElements": 3,
  "first": true,
  "last": true
}
```
