To create a multi step proposal on-chain, in the aptos-core repo on main branch, run
```
aptos governance propose --is-multi-step \
  --metadata-url https://raw.githubusercontent.com/aptos-foundation/mainnet-proposals/main/metadata/v1.2/3/0.json \
  --pool-address $pool_address \
  --script-path /path/to/mainnet-proposals/sources/v1.2/3/0-move-stdlib.move \
  --framework-git-rev aptos-node-v1.2.0 \
  --profile mainnet-voter
```
