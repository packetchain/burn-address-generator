# Burn Address Generator
Simple script to generate burn addresses for any cryptocurrency

# Requirements
You need `pip` if you don't have it:

```
sudo apt install python-pip
```
Then install the `base58` python package if you don't have it:
```
sudo pip install base58
```
# Running
To use the scrip just start it and indicate what is the prefix you want, including the first character of the coin's address:
```
./burn SXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```
as a result we get a valid burn address for PacketChain ( PTCL ):
```
PXXXXXXXXXXXXXXXXXXXXXXXXXXXXHbf2d
```
# Credits
A great thank you to [CoinWhisperer](https://gist.github.com/CoinWhisperer/6d673f1f3d13da1611cd) and James C. Stroud
