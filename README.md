# proto-by-solidity

Prototype apps by using solidity

## version

```bash
$ truffle version
Truffle v5.0.0 (core: 5.0.0)
Solidity v0.5.0 (solc-js)
Node v10.9.0
```

## test

```bash
$ truffle test
Compiling ./contracts/ConvertLib.sol...
Compiling ./contracts/MetaCoin.sol...
Compiling ./contracts/Migrations.sol...
Compiling ./test/TestMetacoin.sol...


  TestMetacoin
    ✓ testInitialBalanceUsingDeployedContract (89ms)
    ✓ testInitialBalanceWithNewMetaCoin (88ms)

  Contract: MetaCoin
    ✓ should put 10000 MetaCoin in the first account
    ✓ should call a function that depends on a linked library (47ms)
    ✓ should send coin correctly (141ms)


  5 passing (9s)
```
