######   https://jsongrid.com/json-grid

`if present is starving, future is exhorted`
`if present is pastured, future is extravegant` 

```json
{
    "target": 60,
    "dictionary": {
        "b": "buy at instant",
        "bs": "buy stop",
        "s": "sell at instant",
        "ss": "sell stop",
        "bnr": "break and retest",
        "dtdb": "break and deep retest - double top/bottom",
        "cheese": "hold and deep retest - double top/bottom",
        "rev": "reversal" 
    },
    "watchlist": [
        {"date": "2021-11-5","product":["XAUUSD","USDCHF","EURJPY"]},
        {"date": "2021-11-4","product":["XAUUSD","USDCAD"]},
    ],
    "opportunity": [
        {
            "date": "2021-11-4", "product":"xauusd", "order":"ss",
            "entry":1793.056, "sl":6.553, "r":2, 
            "pattern":"dtdb", 
            "plan": "1 wick or 2 wick arounds previous LH at 1795.668"
        },
        {
            "date": "2021-11-4", "product":"usdcad", "order":"bs", 
            "entry":1.24245, "sl":13.9, "r":3, 
            "pattern":"bnr", 
            "plan": "1 wick arounds previous HH at 1.24178",
            "note": "close without entry because of entry was not in trading hour",
        },
    ],
    "record": [
        // bring opportunity down
        {
            "date": "2021-11-4", "product":"xauusd", "order":"ss",
            "log": "2021-11-5",
            "entry":1793.056, "sl":6.553, "r":2, 
            "pattern":"dtdb", 
            "plan": "1 wick or 2 wick arounds previous LH at 1795.668"
        },
    ]
}
```