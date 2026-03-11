# DPR (Daily Price Range)

---

## DPR Request — Single Token

```
http://ip:port/dpr/<exchange-segment>/<instrument-token-id>
```

## DPR Response — Single Token

```json
{
  "DPR": [
    {
      "token": <instrument-token-id>,
      "dprHigh": <dpr-high>, /*In paisa*/
      "dprLow": <dpr-low>, /*In paisa*/
      "ts": <timestamp>
    }
  ]
}
```

**Exchange Segments:** `NSEFO`, `NSECM`, `BSEFO`, etc.