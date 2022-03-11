# Chainlink External Adapter for Vibe Volatility

Version: 0.0.1

### Input Params

| Required? |  Name  |          Aliases          |             Description             |  Type  | Options | Default | Depends On | Not Valid With |
| :-------: | :----: | :-----------------------: | :---------------------------------: | :----: | :-----: | :-----: | :--------: | :------------: |
|    ✅     | currency |  `c`   | The symbol of the currency to query | string |         |         |            |                |

### Example

Request:

```json
{
  "id": "1",
  "data": {
    "currency": "BTC"
  }
}
```

Response:

```json
{
    "jobRunID": 0,
    "data": {
        "jsonrpc": "2.0",
        "result": 82.3281384946442,
        "usIn": 1646920966422338,
        "usOut": 1646920966422460,
        "usDiff": 122,
        "testnet": false
    },
    "result": 82.3281384946442,
    "statusCode": 200
}
```

---
