# Archway Increment smart-contracts

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
the same in one line:
```json
{"name":"NFText","symbol":"nftext","decimals":6,"initial_balances":[{"address":"archway1a8dq0wced6q29rppdug7yvk8ek0dsrqwe3hxcz","amount":"1000000000000000"}],"mint":{"minter":"archway1q0hurmerww8emklmtp2qfvrxcsdsc7e33w8ttu8vehfggvgd63tqa0m3c6","cap":"100000000000000000000000000"}}
```

### Execute
archway tx --args '{"upload_logo":{"url":"https://i.ibb.co/CBrDgrf/noun-Book-4419630.png"}}'

### Query
```bash
archway query contract-state smart --args '{"token_info":{}}'
archway query contract-state smart --args '{"minter":{}}'
```