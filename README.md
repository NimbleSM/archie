# Archie Build Environment for [NimbleSM](https://github.com/NimbleSM/NimbleSM)

First time use:

```bash
git clone git@github.com:NimbleSM/NimbleSM.git
cd archie
echo "make_threads=8" >> archie_config # Or look in archie_config 
./archie update
```

Pulling all new changes into existing copy:

```bash
./archie pull all
```

Developing a package:
```bash
./archie changed src/nimblesm
```
