## provider-services query staking unbonding-delegation

Query an unbonding-delegation record based on delegator and validator address

### Synopsis

Query unbonding delegations for an individual delegator on an individual validator.

Example:
$ <appd> query staking unbonding-delegation akash1gghjut3ccd8ay0zduzj64hwre2fxs9ld75ru9p akashvaloper1gghjut3ccd8ay0zduzj64hwre2fxs9ldmqhffj

```
provider-services query staking unbonding-delegation [delegator-addr] [validator-addr] [flags]
```

### Options

```
      --height int      Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help            help for unbonding-delegation
  -o, --output string   Output format (text|json) (default "text")
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID
      --node string       The node address (default "http://localhost:26657")
```

### SEE ALSO

* [provider-services query staking](provider-services_query_staking.md)	 - Querying commands for the staking module

###### Auto generated by spf13/cobra on 5-Dec-2022