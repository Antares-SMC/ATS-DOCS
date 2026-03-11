# LPP

---

## LPP Request — Single Token

```
http://ip:port/lpp/<exchange-segment>/<instrument-token-id>
```

## LPP Response — Single Token

```json
{
  "LPP": [
    {
      "token": <instrument-token-id>,
      "lppHigh": <lpp-high>, /*In paisa*/
      "lppLow": <lpp-low>, /*In paisa*/
      "ts": <timestamp>
    }
  ]
}
```

**Exchange Segments:** `NSEFO`, `NSECM`, `BSEFO`, etc.