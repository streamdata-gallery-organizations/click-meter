{
  "info": {
    "name": "Click Meter Retrieve a top report",
    "_postman_id": "e072b101-11d3-46f4-8572-d2fb4218d1f6",
    "description": "Retrieve a top report.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Conversions",
      "item": [
        {
          "id": "75983f32-d686-4d8f-8722-d20c7b4f2863",
          "name": "getConversionsConversionReports",
          "request": {
            "url": {
              "protocol": "http",
              "host": "apiv2.clickmeter.com",
              "path": [
                "conversions/:conversionId/reports"
              ],
              "query": [
                {
                  "key": "fromDay",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "hittype",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "timeframe",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "toDay",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "conversionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a top report connected to this conversion."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c1c1e46-92be-49c1-8199-88066fbbfa1b"
            }
          ]
        }
      ]
    },
    {
      "name": "Datapoints",
      "item": [
        {
          "id": "90f70149-dbfd-4e85-8c25-25f8246d7b47",
          "name": "getDatapointsReports",
          "request": {
            "url": {
              "protocol": "http",
              "host": "apiv2.clickmeter.com",
              "path": [
                "datapoints/:id/reports"
              ],
              "query": [
                {
                  "key": "fromDay",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "timeframe",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "toDay",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a top report connected to this datapoint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03c00571-8623-4196-89b8-2ee9335a2891"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "9b7592ea-9701-49c5-9771-56930c1bfd86",
          "name": "getGroupsReports",
          "request": {
            "url": {
              "protocol": "http",
              "host": "apiv2.clickmeter.com",
              "path": [
                "groups/:id/reports"
              ],
              "query": [
                {
                  "key": "fromDay",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "hittype",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "timeframe",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "toDay",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a top report connected to this group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2cfca08f-5e2a-46ca-be2a-74c6b94640e3"
            }
          ]
        }
      ]
    },
    {
      "name": "Reports",
      "item": [
        {
          "id": "76791560-8865-44ff-a7f5-99d02090af59",
          "name": "getReports",
          "request": {
            "url": "http://apiv2.clickmeter.com:80/reports?conversion=%7B%7D&datapoint=%7B%7D&fromDay=%7B%7D&group=%7B%7D&hittype=%7B%7D&timeframe=%7B%7D&toDay=%7B%7D&type=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a top report."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92b7f2c6-c488-4658-a089-11b94c5aa43b"
            }
          ]
        }
      ]
    }
  ]
}