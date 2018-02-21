## Allocate ealry contributors tokens

```
# You want to allocate 100 STAR to 0xAAA and 200 STAR to 0xBBB.
# Your ethereum account for this operation is 0xCCC and it must be unlocked.
# An ethereum client must be synced and running with port 8545.

$ npm install
$ cat allocation-xxx.csv
0xAAA,100
0xBBB,200
$ node ./allocate-ec-tokens 0xCCC allocation-xxx.csv
```

WARNING: **Don't execute this script twice or more with the same file, or you would allocate extra tokens to them!**
