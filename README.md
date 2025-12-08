curl -X POST <OTEL_ENDPOINT>/v1/metrics \
  -H "Content-Type: application/json" \
  -H "x-scope-orgid: FOO" \
  -d '{
    "resourceMetrics": [{
      "resource": {
        "attributes": [
          {"key": "cmdbReference", "value": {"stringValue": "AT59428"}},
          {"key": "opEnvironment", "value": {"stringValue": "DEV"}}
        ]
      },
      "scopeMetrics": [{
        "metrics": [{
          "name": "test_metric",
          "type": "GAUGE_INT64",
          "int64DataPoints": [{
            "asInt": "1",
            "timeUnixNano": "1733667900000000000"
          }]
        }]
      }]
    }]
  }'
