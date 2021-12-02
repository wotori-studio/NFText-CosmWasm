# Archway Increment smart-contracts

`% archway deploy`

JSON encoded constructor arguments example:
```json
{
    "name": "ARCHWAY FUN COIN",
    "symbol": "ARF",
    "decimals": 6,
    "initial_balances":
    [
        {
            "address": "archway1gl8zm42ygtchts2elhn8vr5ps9txmxnc85j4ld",
            "amount": "1000000"
        }
    ],
    "mint":
    {
        "minter": "archway1gl8zm42ygtchts2elhn8vr5ps9txmxnc85j4ld",
        "cap": "99900000000"
    }
}
```
one line:
```json
{ "name": "ARCHWAY FUN COIN", "symbol": "ARF", "decimals": 6, "initial_balances": [ { "address": "archway1gl8zm42ygtchts2elhn8vr5ps9txmxnc85j4ld", "amount": "1000000" } ], "mint": { "minter": "archway1gl8zm42ygtchts2elhn8vr5ps9txmxnc85j4ld", "cap": "99900000000" } }```