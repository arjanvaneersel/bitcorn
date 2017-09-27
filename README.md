# Obichain

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
0000005420fbfdafa00c093f56e033903ba43599fa7cd9df40458e373eee724d

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
00000019afa909094193f64ca06e9039849709f5948fbac56cae7b1b8f0ff162

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