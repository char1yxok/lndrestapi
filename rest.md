```
▶︎curl --insecure --header "Grpc-Metadata-macaroon: $(xxd -ps -u -c 1000  /Users/USER/Library/Application\ Support/Lnd/data/chain/bitcoin/testnet/admin.macaroon)" https://localhost:8080/v1/getinfo |jq .
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   491  100   491    0     0  31345      0 --:--:-- --:--:-- --:--:-- 32733
{
  "identity_pubkey": "02bad2d8bc05c4e67732ad9577ddfbbdd52c0635a638eddf8457d31a4c682aa910",
  "alias": "02bad2d8bc05c4e67732",
  "num_active_channels": 5,
  "num_peers": 2,
  "block_height": 1575287,
  "block_hash": "00000000000001b27d98199525abc991618982c029268ffd75abe78a0c9e0da0",
  "synced_to_chain": true,
  "testnet": true,
  "best_header_timestamp": "1566351956",
  "version": "0.7.1-beta commit=v0.7.1-beta-20-g8c9c4b52e869f1d083f4ba7b1302a0bb964bc6be",
  "chains": [
    {
      "chain": "bitcoin",
      "network": "testnet"
    }
  ],
  "color": "#3399ff"
}
```
