# Bitcorn

Having fun with blockchain/cryptocurrency technology

# Examples

```
$ ./bitcorn createwallet
Your new address: <ADDRESS 1>
```

```
$ ./bitcorn createwallet
Your new address: <ADDRESS 2>
```

```
$ ./bitcorn createwallet
Your new address: <ADDRESS 3>
```

```
$ ./bitcorn createblockchain -address <ADDRESS 1>
00004f6bbfc0d363aed361e6aad809d785bc9341255ca4ddd6c7ae7e55e32b5b

Done!
```

```
$ ./bitcorn getbalance -address <ADDRESS 1>
Balance of '<ADDRESS 1>': 10
```

```
$ ./bitcorn send -from <ADDRESS 2> -to <ADDRESS 1> -amount 5
2017/09/27 13:08:56 ERROR: Not enough funds
```

```
$ ./bitcorn send -from <ADDRESS 1> -to <ADDRESS 2> -amount 6
0000426391a6f880c05e40a7190e3c9912c5f857cf9fda2956569ad9eac714ff

Success!
```

```
$ ./bitcorn getbalance -address <ADDRESS 1>
Balance of '<ADDRESS 1>': 4
```

```
$ ./bitcorn getbalance -address <ADDRESS 2>
Balance of '<ADDRESS 2>': 6
```

```
$ ./bitcorn getbalance -address <ADDRESS 3>
Balance of '<ADDRESS 3>': 0
```